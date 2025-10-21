# 18. Linux Privilege Esc — Entry 22

## Categorie

Manual Enumeration

## Commando

```
find / -user root -perm -6000 -exec ls -ldb {} \; 2>/dev/null
```

## Omschrijving

```
Root files that can be executed as normal user
```

## Voorbeeld

_(empty)_

## Opmerkingen

_(empty)_

