# Powershell Configuration

```text
#Temporarily changing the settings for the Local Administrator.
#Working as of Windows 10 v1803
# Sets culture for current user account
Set-Culture de-DE

#Sets the system locale for the current computer.
Set-WinSystemLocale -SystemLocale de-DE

# Sets a user-preferred display language for the current user account
Set-WinUILanguageOverride -Language de-DE

# Sets the current user language settings.
Set-WinUserLanguageList de-DE -Force

# Info provided by https://docs.microsoft.com/en-us/windows/desktop/Intl/table-of-geographical-locations
Set-WinHomeLocation -GeoId 94

# Set Locale, language etc. 
C:\Windows\System32\control.exe "intl.cpl,,/f:""C:\YourPath\DERegion.xml`""

# Set Timezone
# Info provided by https://docs.microsoft.com/en-us/windows-hardware/manufacture/desktop/default-time-zones
& tzutil /s "Central Europe Standard Time"

# Install Windows 1803 Features on Demand v2. Info provided by https://docs.microsoft.com/en-us/windows-hardware/manufacture/desktop/add-language-packs-to-windows 

#Basic provides Spell checking, text prediction, word breaking, and hyphenation.
DISM.exe /Online /Add-Package /packagepath:C:\YourPath\Microsoft-Windows-LanguageFeatures-Basic-de-de-Package~31bf3856ad364e35~amd64~~.cab

#OCR Recognizes and outputs text in an image
DISM.exe /Online /Add-Package /packagepath:C:\YourPath\Microsoft-Windows-LanguageFeatures-OCR-de-de-Package~31bf3856ad364e35~amd64~~.cab

#Recognizes voice input, used by Cortana and Windows Speech Recognition.
DISM.exe /Online /Add-Package /packagepath:C:\YourPath\Microsoft-Windows-LanguageFeatures-Speech-de-de-Package~31bf3856ad364e35~amd64~~.cab

#Enables text to speech, used by Cortana and Narrator
DISM.exe /Online /Add-Package /packagepath:C:\YourPath\Microsoft-Windows-LanguageFeatures-TextToSpeech-de-de-Package~31bf3856ad364e35~amd64~~.cab

#Enables handwriting recognition for devices with pen input.
DISM.exe /Online /Add-Package /packagepath:C:\YourPath\Microsoft-Windows-LanguageFeatures-Handwriting-de-de-Package~31bf3856ad364e35~amd64~~.cab

#Setting Local Admin back to English Language for Support Purposes
Set-Culture en-US
Set-WinSystemLocale -SystemLocale en-US
Set-WinUILanguageOverride -Language en-US
Set-WinUserLanguageList en-US -Force
```

