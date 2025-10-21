# 20 Tunneling DPI — Entry 13

## Categorie

Chisel

## Commando

```
ssh -o ProxyCommand='ncat --proxy-type socks5 --proxy 127.0.0.1:1080 %h %p' database_admin@10.4.50.215
```

## Omschrijving

```
Using ncat to ProxyCommand. The command we constructs tells Ncat to use the socks5 protocol at 127.0.0.1:1080 the %h and %p tokens represent the SSH command host port values, which SSH will fill in before running the command.
```

## Voorbeeld

_(empty)_

## Opmerkingen

_(empty)_

