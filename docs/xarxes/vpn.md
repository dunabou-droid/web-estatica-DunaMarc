# VPN

Una **VPN (Virtual Private Network)** és una tecnologia que permet crear una connexió segura entre un dispositiu i una xarxa a través d'Internet.

La informació que viatja per la VPN es transmet de manera **xifrada**, dificultant que terceres persones puguin veure-la.

---

## Per a què serveix una VPN?

Una VPN es pot utilitzar per:

- Protegir la connexió en xarxes públiques.
- Connectar-se de forma segura a una xarxa d'una empresa.
- Accedir a recursos interns des de fora de l'organització.
- Protegir les dades que es transmeten per Internet.
- Crear connexions segures entre diferents xarxes.

---

## Com funciona?

Quan utilitzem una VPN, el dispositiu crea un **túnel xifrat** amb el servidor VPN.

```text
┌──────────────┐
│   Ordinador  │
└──────┬───────┘
       │
       │ Connexió xifrada
       ▼
   ╔══════════════╗
   ║  TÚNEL VPN   ║
   ╚══════════════╝
       │
       ▼
┌──────────────┐
│ Servidor VPN │
└──────┬───────┘
       │
       ▼
    Internet
```
La VPN protegeix la comunicació entre el dispositiu i el servidor VPN.

## Avantatges

| Avantatge | Descripció |
|---|---|
|  **Xifratge** | Protegeix les dades durant la transmissió |
|  **Accés remot** | Permet connectar-se a una xarxa des de fora |
|  **Treball remot** | Facilita l'accés als recursos de l'empresa |
|  **Xarxes públiques** | Afegeix protecció quan s'utilitza una xarxa pública |

## Limitacions

Una VPN no protegeix de totes les amenaces.

Per exemple:

- No substitueix un antivirus o altres mesures de seguretat.
- No evita que l'usuari caigui en un atac de phishing.
- No fa que una contrasenya insegura sigui segura.
- La velocitat de connexió pot disminuir.
- La seguretat depèn també de la configuració i del proveïdor VPN.

Per això, una VPN s'ha de combinar amb **altres mesures de seguretat**.

## Protocols VPN

Les VPN poden utilitzar diferents protocols.

Alguns exemples són:

| Protocol | Característica |
|---|---|
| **WireGuard** | Protocol modern i senzill |
| **OpenVPN** | Molt utilitzat i configurable |
| **IPsec** | Conjunt de protocols per protegir comunicacions IP |
| **IKEv2** | Utilitzat habitualment amb IPsec |

El protocol utilitzat depèn del **sistema i de la configuració de la VPN**.

## Exemple de connexió VPN

Un exemple senzill seria:

```text
1. L'usuari inicia la VPN
          │
          ▼
2. Es connecta al servidor VPN
          │
          ▼
3. Es crea el túnel xifrat
          │
          ▼
4. L'usuari accedeix als recursos
          │
          ▼
5. Es transmet la informació
```

## Bones pràctiques

Quan utilitzem una VPN:

- Utilitza un servei VPN de confiança.
- Mantén actualitzat el client VPN.
- Utilitza contrasenyes segures.
- Activa 2FA quan estigui disponible.
- Comprova que la connexió VPN estigui activa quan sigui necessària.
- No confiïs en una VPN com a única mesura de seguretat.
- Evita instal·lar aplicacions VPN de fonts desconegudes.