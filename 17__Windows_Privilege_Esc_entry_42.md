# 17. Windows Privilege Esc — Entry 42

## Categorie

Unquoted Service Paths

## Commando

```
Get-CimInstance -ClassName win32_service | Select Name,State,PathName
```

## Omschrijving

List of services with binary path

## Voorbeeld

_(empty)_

## Opmerkingen

_(empty)_

