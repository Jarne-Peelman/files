# 24. AD Lateral Movement — Entry 12

## Categorie

PowerShell Remoting - PSSession

## Commando

```
$username = 'jen';
$password = 'Nexus123!'
$SecureString = ConvertTo-SecureString $password -AsPlaintext -Force;
$credential = New-Object System.Management.Automation.PSCredential $username, $secureString;
New-PSSession -ComputerName 192.168.175.73 -Credential $credential
```

## Omschrijving

```
Establishing a PowerShell Remote Session via WinRM
```

## Voorbeeld

_(empty)_

## Opmerkingen

_(empty)_

