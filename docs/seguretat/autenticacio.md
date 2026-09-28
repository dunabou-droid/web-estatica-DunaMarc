# Autenticació

L'**autenticació** és el procés que permet comprovar que una persona és realment qui diu ser abans de donar-li accés a un compte, aplicació o sistema.

És una part molt important de la **seguretat informàtica**, ja que ajuda a evitar accessos no autoritzats.

---

## Què és l'autenticació?

Quan iniciem sessió en un servei, el sistema necessita comprovar la nostra identitat.

Per exemple:

```text
Usuari
   │
   ▼
Contrasenya
   │
   ▼
Sistema d'autenticació
   │
   ▼
┌────────────────┐
│ Accés permès   │
└────────────────┘
```
Si les dades són correctes, el sistema permet l'accés.

Si les dades no són correctes, l'accés es denega.

## Identificació i autenticació

La identificació i l'autenticació són conceptes relacionats, però no són exactament el mateix.

### Identificació

La identificació consisteix a indicar al sistema **qui som**.

Per exemple:

```text
Usuari: exemple
```
### Autenticació

L'autenticació consisteix a demostrar que realment som aquest usuari.

Per exemple:

```text
Usuari: exemple
Contrasenya: ********
```
El sistema comprova les dades i decideix si permet l'accés.

## Factors d'autenticació

Els sistemes d'autenticació poden utilitzar diferents factors per comprovar la identitat d'una persona.

Els principals són:

| Factor | Descripció | Exemple |
|---|---|---|
| **Que saps** | Informació que coneixes | Contrasenya o PIN |
| **Que tens** | Un objecte o dispositiu que tens | Telèfon o clau de seguretat |
| **Que ets** | Una característica física | Empremta o reconeixement facial |

Utilitzar diferents factors permet afegir **capes de seguretat**.

## Autenticació amb contrasenya

La contrasenya és un dels sistemes d'autenticació més utilitzats.

L'usuari introdueix les seves dades i el sistema comprova si són correctes.

### Exemple

```text
┌─────────────────────────┐
│      INICI DE SESSIÓ    │
├─────────────────────────┤
│                         │
│ Usuari:                 │
│ [ exemple             ] │
│                         │
│ Contrasenya:            │
│ [ ********            ] │
│                         │
│       [ ENTRAR ]        │
│                         │
└─────────────────────────┘
```

Aquest sistema és fàcil d'utilitzar, però la seguretat depèn en gran part de la protecció de la contrasenya.

Per aquest motiu, és important utilitzar contrasenyes llargues, segures i diferents per als diferents comptes.

## Autenticació de dos factors

L'autenticació de dos factors, coneguda com a **2FA**, afegeix una segona comprovació després de la contrasenya.

Per exemple:

```text
1. Introduïm la contrasenya
              │
              ▼
2. Rebrem un codi al mòbil
              │
              ▼
3. Introduïm el codi
              │
              ▼
4. Accedim al compte
```
D'aquesta manera, encara que una persona aconsegueixi la nostra contrasenya, necessitaria superar també el segon factor.

## Exemples de 2FA

Alguns exemples de sistemes de doble autenticació són:

- **Codi enviat al telèfon.**
- **Codi generat per una aplicació d'autenticació.**
- **Clau de seguretat física.**
- **Confirmació d'inici de sessió al mòbil.**
- **Empremta digital**, segons el sistema utilitzat.

### Exemple de codi

**Codi de verificació:**

```text
583 214
```
> ⚠️ **Important:** Els codis de verificació són personals i no s'han de compartir amb altres persones.

## Autenticació biomètrica

La biometria utilitza alguna característica física o de comportament per comprovar la identitat d'una persona.

Alguns exemples són:

- **Empremta digital.**
- **Reconeixement facial.**
- **Reconeixement de l'iris.**
- **Reconeixement de veu** en alguns sistemes.

### Exemple

```text
Persona
   │
   ▼
Empremta digital
   │
   ▼
Sistema de verificació
   │
   ├── Correcta ──►  Accés
   │
   └── Incorrecta ─►  Accés denegat
```
La biometria pot facilitar l'accés perquè no cal memoritzar una contrasenya, però també és important protegir correctament el dispositiu i el compte.

## PIN

Un PIN és un codi numèric que es pot utilitzar per autenticar-se en alguns dispositius i serveis.

Per exemple:

```text
PIN: 4827
```
No és recomanable utilitzar combinacions fàcils d'endevinar com:

```text
1234
0000
1111
```
És millor utilitzar un PIN que no sigui fàcil de predir.

## Errors habituals

Hi ha alguns errors que poden reduir la seguretat de l'autenticació.

### Compartir contrasenyes

No hem de compartir les nostres contrasenyes amb altres persones.

### Compartir codis 2FA

Els codis de verificació també són personals.

No s'han de proporcionar a altres persones, encara que diguin ser personal d'un servei.

### Acceptar peticions desconegudes

Si rebem una notificació d'inici de sessió que no hem fet nosaltres, **no l'hem d'acceptar**.

### Utilitzar la mateixa contrasenya

No és recomanable utilitzar la mateixa contrasenya en molts serveis.

### Utilitzar codis fàcils

Evita PIN com:

```text
1234
0000
1111
```