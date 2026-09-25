# Firewall

Un firewall és un sistema que controla el trànsit de xarxa segons unes regles de seguretat.

## Funció

Un firewall pot permetre o bloquejar determinades connexions.

Un exemple simplificat seria:

```text
Internet
   |
   v
Firewall
   |
   +---- Servidor web
   |
   +---- Xarxa interna
```

  ## Firewall en Linux

En alguns sistemes Linux podem utilitzar ufw per gestionar les regles del firewall.

Per consultar l'estat:
```text
sudo ufw status
```

Per activar-lo:
```text
sudo ufw enable
```

Per permetre connexions SSH:
```text
sudo ufw allow 22/tcp
```
## Regles

Les regles del firewall determinen quin trànsit es permet i quin es bloqueja.

Per exemple, una organització pot permetre connexions a un servidor web però bloquejar altres ports que no siguin necessaris.

## Importància

Un firewall ajuda a controlar les comunicacions i a reduir les connexions no autoritzades.

## Resum

La configuració d'un firewall és una mesura important dins de la protecció d'una xarxa.