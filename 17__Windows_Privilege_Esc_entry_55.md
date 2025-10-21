# 17. Windows Privilege Esc — Entry 55

## Categorie

Scheduled task

## Commando

```
schtasks /query /fo LIST /v | findstr /I ".exe .bat .ps1 cmd"
```

## Omschrijving

```
Showing only tasks running an exe, powershell, cmd or bat
```

## Voorbeeld

_(empty)_

## Opmerkingen

_(empty)_

