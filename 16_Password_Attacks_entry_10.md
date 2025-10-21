# 16.Password Attacks — Entry 10

## Categorie

Rule function

## Commando

```
hashcat -m 0 crackme.txt /usr/share/wordlists/rockyou.txt -r demo3.rule --force
```

## Omschrijving

```
Using a rule conform a password policy
```

## Voorbeeld

```
$1 c $!
$2 c $!
$1 $2 $3 c $!
```

## Opmerkingen

Example: Password123!

