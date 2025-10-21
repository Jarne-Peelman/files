# 22. AD Introduction and Enum — Entry 48

## Categorie

Object Permission - PowerView

## Commando

```
Get-ObjectAcl -Identity "Management Department" | ? {$_.ActiveDirectoryRights -eq "GenericAll"} | select SecurityIdentifier,ActiveDirectoryRights
```

## Omschrijving

```
Enumerating ACLs for the Management Group -> Searching for the highest access permissions
```

## Voorbeeld

_(empty)_

## Opmerkingen

_(empty)_

