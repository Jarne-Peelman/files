# 24. AD Lateral Movement — Entry 3

## Categorie

WMIC

## Commando

```
$options = New-CimSessionOption -Protocol DCOM
$session = New-Cimsession -ComputerName 192.168.50.73 -Credential $credential -SessionOption $Options 
$command = 'calc';
```

## Omschrijving

Creating a new CimSession

## Voorbeeld

_(empty)_

## Opmerkingen

_(empty)_

