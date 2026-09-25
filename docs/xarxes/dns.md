# DNS

El DNS, o Domain Name System, permet relacionar noms de domini amb adreces IP.

Per exemple:

```text
www.exemple.com
```

pot estar associat a una determinada adreça IP.

## Per què serveix?

Sense DNS, hauríem de recordar les adreces IP dels servidors als quals ens volem connectar.

## Consultar DNS

A Linux podem utilitzar:

```bash
nslookup google.com
```

També podem utilitzar:

```bash
dig google.com
```

## Funcionament simplificat

```text
Usuari
   ↓
Nom de domini
   ↓
Servidor DNS
   ↓
Adreça IP
   ↓
Servidor web
```
