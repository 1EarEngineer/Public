# Dell SupportAssist

Recently Dell's Support Assist tool took a hit for a security vulnerability. After checking our environment, [the following script](https://www.reddit.com/r/PowerShell/comments/2830wq/uninstall_software_wmic_alternatives/ci97m1d?utm_source=share&utm_medium=web2x) was used to remove the tool via PS script

```text
# Grab data from registry
$regQuery32 = Get-ChildItem -Path "HKLM:\SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall" | Where {$_.GetValue("DisplayName") -match "Dell SupportAssist"}
$regQuery64 = Get-ChildItem -Path "HKLM:\SOFTWARE\Wow6432Node\Microsoft\Windows\CurrentVersion\Uninstall" | Where {$_.GetValue("DisplayName") -match "Dell SupportAssist"}
 
# Create uninstall strings
$regQuery32 | ForEach-Object {
    $productCode = $($_.Name).Split("\")[$($_.Name).Split("\").Length - 1]

    $app = Start-Process "msiexec.exe" -ArgumentList "/x $productCode /quiet /norestart" -PassThru
    Wait-Process $app.Id
}
 
$regQuery64 | ForEach-Object {
    $productCode = $($_.Name).Split("\")[$($_.Name).Split("\").Length - 1]

    $app = Start-Process "msiexec.exe" -ArgumentList "/x $productCode /quiet /norestart" -PassThru
    Wait-Process $app.Id
}
```

\*\*\*\*

