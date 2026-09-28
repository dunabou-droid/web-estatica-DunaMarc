# Firewall

Un **firewall** o tallafocs és un sistema que controla el trànsit de xarxa entre dispositius.

La seva funció principal és **permetre o bloquejar connexions** segons unes regles de seguretat.

---

## Per a què serveix?

Un firewall ajuda a:

- Bloquejar connexions no autoritzades.
- Permetre serveis necessaris.
- Controlar el trànsit de xarxa.
- Protegir dispositius i servidors.
- Reduir el risc d'accessos no autoritzats.

```text
Internet
   │
   ▼
┌──────────────┐
│   FIREWALL   │
└──────┬───────┘
       │
       ▼
 Xarxa interna
```

## Com funciona?

El firewall analitza les connexions i les compara amb les regles configurades.

```text
Connexió
   │
   ▼
Firewall
   │
   ├── Regla permet →  Accés
   │
   └── Regla bloqueja →  Accés denegat
```
Les regles poden tenir en compte diferents elements:

- **Adreça IP d'origen.**
- **Adreça IP de destinació.**
- **Port.**
- **Protocol.**
- **Direcció del trànsit.**

## Ports i protocols

Els ports permeten identificar diferents serveis de xarxa.

| Port | Protocol | Servei |
|---:|---|---|
| 22 | TCP | SSH |
| 53 | UDP/TCP | DNS |
| 80 | TCP | HTTP |
| 443 | TCP | HTTPS |
| 3389 | TCP | RDP |

Per exemple, una regla podria permetre el trànsit HTTPS:

```text
Protocol: TCP
Port: 443
Acció: PERMETRE
```

## Exemple de regles

Un firewall pot tenir regles com aquestes:

| Origen | Destinació | Port | Acció |
|---|---|---:|---|
| Xarxa interna | Servidor web | 443 | Permetre |
| Xarxa interna | Servidor SSH | 22 | Permetre |
| Internet | Servidor | 22 | Bloquejar |
| Internet | Servidor web | 443 | Permetre |

Les regles s'han de configurar segons les **necessitats de la xarxa**.

## Bones pràctiques

Per configurar correctament un firewall:

- Permet només els serveis necessaris.
- Bloqueja els ports que no s'utilitzen.
- Revisa periòdicament les regles.
- ⬆Mantén el sistema actualitzat.
- Evita exposar serveis innecessaris a Internet.
- Utilitza HTTPS per als serveis web.
- Limita l'accés administratiu quan sigui possible.