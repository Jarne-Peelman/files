# 17. Windows Privilege Esc — Entry 31

## Categorie

Service binary hijacking

## Commando

```
Get-CimInstance -ClassName win32_service | Select Name, StartMode | Where-Object {$_.Name -like 'mysql'}
```

## Omschrijving

```
Check the startup mode of a process.
```

## Voorbeeld

_(empty)_

## Opmerkingen

_(empty)_

