# 17. Windows Privilege Esc — Entry 26

## Categorie

Service binary hijacking

## Commando

```
Get-CimInstance -ClassName win32_service | Select Name,State,PathName | Where-Object {$_.State -like 'Running'}
```

## Omschrijving

```
Toon alle processen die momenteel runnende zijn
```

## Voorbeeld

_(empty)_

## Opmerkingen

_(empty)_

