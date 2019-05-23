# Regional XMLs

{% tabs %}
{% tab title="British" %}
{% code-tabs %}
{% code-tabs-item title="British.xml" %}
```markup
<gs:GlobalizationServices xmlns:gs="urn:longhornGlobalizationUnattend"> 
<!--User List-->
<gs:UserList>
    <gs:User UserID="Current" CopySettingsToDefaultUserAcct="true" CopySettingsToSystemAcct="true"/> 
</gs:UserList>
<!-- user locale -->
<gs:UserLocale> 
    <gs:Locale Name="en-GB" SetAsCurrent="true"/> 
</gs:UserLocale>
<!-- system locale -->
<gs:SystemLocale Name="en-GB"/>
<!-- GeoID -->
<gs:LocationPreferences> 
    <gs:GeoID Value="242"/> 
</gs:LocationPreferences>
<gs:MUILanguagePreferences>
	<gs:MUILanguage Value="en-GB"/>
	<gs:MUIFallback Value="en-US"/>
</gs:MUILanguagePreferences>
<!-- input preferences -->
<gs:InputPreferences>
    <!--en-GB-->
    <gs:InputLanguageID Action="add" ID="0809:00000809" Default="true"/> 
</gs:InputPreferences>
</gs:GlobalizationServices>

```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="French" %}
{% code-tabs %}
{% code-tabs-item title="French.xml" %}
```markup
<gs:GlobalizationServices xmlns:gs="urn:longhornGlobalizationUnattend"> 
<!--User List-->
<gs:UserList>
    <gs:User UserID="Current" CopySettingsToDefaultUserAcct="true" CopySettingsToSystemAcct="true"/> 
</gs:UserList>
<!-- user locale -->
<gs:UserLocale> 
    <gs:Locale Name="fr-FR" SetAsCurrent="true"/> 
</gs:UserLocale>
<!-- system locale -->
<gs:SystemLocale Name="fr-FR"/>
<!-- GeoID -->
<gs:LocationPreferences> 
    <gs:GeoID Value="84"/> 
</gs:LocationPreferences>
<gs:MUILanguagePreferences>
	<gs:MUILanguage Value="fr-FR"/>
</gs:MUILanguagePreferences>
<!-- input preferences -->
<gs:InputPreferences>
    <!--fr-FR-->
	<!--Based on https://docs.microsoft.com/en-us/windows-hardware/manufacture/desktop/default-input-locales-for-windows-language-packs -->
    <gs:InputLanguageID Action="add" ID="040c:0000040c" Default="true"/>
	<!--en-US-->
	<!--Based on https://docs.microsoft.com/en-us/windows-hardware/manufacture/desktop/default-input-locales-for-windows-language-packs -->
	<gs:InputLanguageID Action="add" ID="0409:00000409" />
</gs:InputPreferences>
</gs:GlobalizationServices>

```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="German" %}
{% code-tabs %}
{% code-tabs-item title="German.xml" %}
```markup
<gs:GlobalizationServices xmlns:gs="urn:longhornGlobalizationUnattend"> 
<!--User List-->
<gs:UserList>
    <gs:User UserID="Current" CopySettingsToDefaultUserAcct="true" CopySettingsToSystemAcct="true"/> 
</gs:UserList>
<!-- user locale -->
<gs:UserLocale> 
    <gs:Locale Name="de-DE" SetAsCurrent="true"/> 
</gs:UserLocale>
<!-- system locale -->
<gs:SystemLocale Name="de-DE"/>
<!-- GeoID -->
<gs:LocationPreferences> 
    <gs:GeoID Value="94"/> 
</gs:LocationPreferences>
<gs:MUILanguagePreferences>
	<gs:MUILanguage Value="de-DE"/>
	<gs:MUIFallback Value="en-US"/>
</gs:MUILanguagePreferences>
<!-- input preferences -->
<gs:InputPreferences>
    <!--de-DE-->
	<!--Based on https://docs.microsoft.com/en-us/windows-hardware/manufacture/desktop/default-input-locales-for-windows-language-packs -->
    <gs:InputLanguageID Action="add" ID="0407:00000407" Default="true"/>
	<!--en-US-->
	<!--Based on https://docs.microsoft.com/en-us/windows-hardware/manufacture/desktop/default-input-locales-for-windows-language-packs -->
	<gs:InputLanguageID Action="add" ID="0409:00000409" />
</gs:InputPreferences>
</gs:GlobalizationServices>


```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="Greek" %}
{% code-tabs %}
{% code-tabs-item title="Greek.xml" %}
```markup
<gs:GlobalizationServices xmlns:gs="urn:longhornGlobalizationUnattend"> 
<!--User List-->
<gs:UserList>
    <gs:User UserID="Current" CopySettingsToDefaultUserAcct="true" CopySettingsToSystemAcct="true"/> 
</gs:UserList>
<!-- user locale -->
<gs:UserLocale> 
    <gs:Locale Name="el-GR" SetAsCurrent="true"/> 
</gs:UserLocale>
<!-- system locale -->
<gs:SystemLocale Name="el-GR"/>
<!-- GeoID -->
<gs:LocationPreferences> 
    <gs:GeoID Value="98"/> 
</gs:LocationPreferences>
<gs:MUILanguagePreferences>
	<gs:MUILanguage Value="el-GR"/>
</gs:MUILanguagePreferences>
<!-- input preferences -->
<gs:InputPreferences>
    <!--el-GR-->
	<!--Based on https://docs.microsoft.com/en-us/windows-hardware/manufacture/desktop/default-input-locales-for-windows-language-packs -->
    <gs:InputLanguageID Action="add" ID="0408:00000408" Default="true"/>
	<!--en-US-->
	<!--Based on https://docs.microsoft.com/en-us/windows-hardware/manufacture/desktop/default-input-locales-for-windows-language-packs -->
	<gs:InputLanguageID Action="add" ID="0409:00000409" />
</gs:InputPreferences>
</gs:GlobalizationServices>

```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="Italian" %}
{% code-tabs %}
{% code-tabs-item title="Italian.xml" %}
```markup
<gs:GlobalizationServices xmlns:gs="urn:longhornGlobalizationUnattend"> 
<!--User List-->
<gs:UserList>
    <gs:User UserID="Current" CopySettingsToDefaultUserAcct="true" CopySettingsToSystemAcct="true"/> 
</gs:UserList>
<!-- user locale -->
<gs:UserLocale> 
    <gs:Locale Name="it-IT" SetAsCurrent="true"/> 
</gs:UserLocale>
<!-- system locale -->
<gs:SystemLocale Name="it-IT"/>
<!-- GeoID -->
<gs:LocationPreferences> 
    <gs:GeoID Value="118"/> 
</gs:LocationPreferences>
<gs:MUILanguagePreferences>
	<gs:MUILanguage Value="it-IT"/>
</gs:MUILanguagePreferences>
<!-- input preferences -->
<gs:InputPreferences>
    <!--it-IT-->
	<!--Based on https://docs.microsoft.com/en-us/windows-hardware/manufacture/desktop/default-input-locales-for-windows-language-packs -->
    <gs:InputLanguageID Action="add" ID="0410:00000410" Default="true"/>
	<!--en-US-->
	<!--Based on https://docs.microsoft.com/en-us/windows-hardware/manufacture/desktop/default-input-locales-for-windows-language-packs -->
	<gs:InputLanguageID Action="add" ID="0409:00000409" />
</gs:InputPreferences>
</gs:GlobalizationServices>

```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="Irish" %}
{% code-tabs %}
{% code-tabs-item title="Irish.xml" %}
```markup
<gs:GlobalizationServices xmlns:gs="urn:longhornGlobalizationUnattend"> 

<!--User List-->
<gs:UserList>
    <gs:User UserID="Current" CopySettingsToDefaultUserAcct="true" CopySettingsToSystemAcct="true"/> 
</gs:UserList>
<!-- user locale -->
<gs:UserLocale> 
    <gs:Locale Name="en-IE" SetAsCurrent="true"/> 
</gs:UserLocale>
<!-- system locale -->
<gs:SystemLocale Name="en-IE"/>
<!-- GeoID -->
<gs:LocationPreferences> 
    <gs:GeoID Value="68"/> 
</gs:LocationPreferences>
<gs:MUILanguagePreferences>
	<gs:MUILanguage Value="en-GB"/>
</gs:MUILanguagePreferences>
<!-- input preferences -->
<gs:InputPreferences>
    <!--en-GB-->
	<!--Based on https://docs.microsoft.com/en-us/windows-hardware/manufacture/desktop/default-input-locales-for-windows-language-packs -->
    <gs:InputLanguageID Action="add" ID="0809:00000809" Default="true"/>
	<!--en-US-->
	<!--Based on https://docs.microsoft.com/en-us/windows-hardware/manufacture/desktop/default-input-locales-for-windows-language-packs -->
	<gs:InputLanguageID Action="add" ID="0409:00000409" />
</gs:InputPreferences>
</gs:GlobalizationServices>
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="South African" %}
{% code-tabs %}
{% code-tabs-item title="SouthAfrican.xml" %}
```markup
<gs:GlobalizationServices xmlns:gs="urn:longhornGlobalizationUnattend"> 
<!--User List-->
<gs:UserList>
    <gs:User UserID="Current" CopySettingsToDefaultUserAcct="true" CopySettingsToSystemAcct="true"/> 
</gs:UserList>
<!-- user locale -->
<gs:UserLocale> 
    <gs:Locale Name="en-ZA" SetAsCurrent="true"/> 
</gs:UserLocale>
<!-- system locale -->
<gs:SystemLocale Name="en-ZA"/>
<!-- GeoID -->
<gs:LocationPreferences> 
    <gs:GeoID Value="209"/> 
</gs:LocationPreferences>
<gs:MUILanguagePreferences>
	<gs:MUILanguage Value="en-ZA"/>
	<gs:MUIFallback Value="en-US"/>
</gs:MUILanguagePreferences>
<!-- input preferences -->
<gs:InputPreferences>
	<!--en-US-->
	<!--Based on https://docs.microsoft.com/en-us/windows-hardware/manufacture/desktop/default-input-locales-for-windows-language-packs -->
	<gs:InputLanguageID Action="add" ID="0409:00000409" Default="true"/>
</gs:InputPreferences>
</gs:GlobalizationServices>
```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}

{% tab title="Spanish" %}
{% code-tabs %}
{% code-tabs-item title="Spanish.xml" %}
```markup
<gs:GlobalizationServices xmlns:gs="urn:longhornGlobalizationUnattend"> 
<!--User List-->
<gs:UserList>
    <gs:User UserID="Current" CopySettingsToDefaultUserAcct="true" CopySettingsToSystemAcct="true"/> 
</gs:UserList>
<!-- user locale -->
<gs:UserLocale> 
    <gs:Locale Name="es-ES" SetAsCurrent="true"/> 
</gs:UserLocale>
<!-- system locale -->
<gs:SystemLocale Name="es-ES"/>
<!-- GeoID -->
<gs:LocationPreferences> 
    <gs:GeoID Value="217"/> 
</gs:LocationPreferences>
<gs:MUILanguagePreferences>
	<gs:MUILanguage Value="es-ES"/>
	<gs:MUIFallback Value="en-US"/>
</gs:MUILanguagePreferences>
<!-- input preferences -->
<gs:InputPreferences>
    <!--es-ES-->
	<!--Based on https://docs.microsoft.com/en-us/windows-hardware/manufacture/desktop/default-input-locales-for-windows-language-packs -->
    <gs:InputLanguageID Action="add" ID="0c0a:0000040a" Default="true"/>
	<!--en-US-->
	<!--Based on https://docs.microsoft.com/en-us/windows-hardware/manufacture/desktop/default-input-locales-for-windows-language-packs -->
	<gs:InputLanguageID Action="add" ID="0409:00000409" />
</gs:InputPreferences>
</gs:GlobalizationServices>

```
{% endcode-tabs-item %}
{% endcode-tabs %}
{% endtab %}
{% endtabs %}

