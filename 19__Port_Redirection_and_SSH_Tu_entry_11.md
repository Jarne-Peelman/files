# 19. Port Redirection and SSH Tu — Entry 11

## Categorie

```
SSH Local port Forwarding - finding hosts
```

## Commando

```
for i in $(seq 1 254); do nc -zv -w 1 172.16.50.$i 445; done
```

## Omschrijving

```
Making a connection to every ip in the range to check which one is up
```

## Voorbeeld

_(empty)_

## Opmerkingen

_(empty)_

