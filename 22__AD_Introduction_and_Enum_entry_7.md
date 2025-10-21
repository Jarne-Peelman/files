# 22. AD Introduction and Enum — Entry 7

## Categorie

ADSI

## Commando

```
foreach ($group in $(LDAPSearch -LDAPQuery "(objectCategory=group)")) { $group.properties | select {$_.cn}, {$_.member} }
```

## Omschrijving

List every group

## Voorbeeld

_(empty)_

## Opmerkingen

_(empty)_

