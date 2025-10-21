# 24. AD Lateral Movement — Entry 2

## Categorie

WMIC

## Commando

```
$username = 'jen';
$password = 'Nexus123!';
$secureString = ConvertTo-SecureString $password -AsPlaintext -Force;
$credential = New-Object System.Management.Automation.PSCredential $username, $secureString;
```

## Omschrijving

Creating the PSCredential object in PowerShell

## Voorbeeld

_(empty)_

## Opmerkingen

_(empty)_

