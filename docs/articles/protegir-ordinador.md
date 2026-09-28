# Com protegir un ordinador

**Data:** 28/09/2026  
**Autor:** Duna Bou Crespi I Marc Mons Muñoz

![Protecció d'un ordinador](https://images.unsplash.com/photo-1563013544-824ae1b704d3?auto=format&fit=crop&w=1200&q=80)

## Introducció

Un ordinador pot contenir informació personal, documents i credencials d'accés.

Per aquest motiu és important aplicar algunes mesures bàsiques de seguretat.

## 1. Mantenir el sistema actualitzat

El primer pas és mantenir actualitzat el sistema operatiu i les aplicacions.

En Linux podem consultar les actualitzacions amb:

```bash
sudo apt update
```

I instal·lar-les amb:
```bash
sudo apt upgrade
```

## 2. Utilitzar contrasenyes segures

Les contrasenyes han de ser prou llargues i no s'han de reutilitzar en tots els serveis.

## 3. Utilitzar un firewall

Un firewall permet controlar les connexions de xarxa.

Per exemple, en sistemes Linux podem consultar `ufw`:

```bash
sudo ufw status
```

## 4. Fer còpies de seguretat

Les còpies permeten recuperar els fitxers en cas de pèrdua d'informació.

## 5. Evitar fitxers sospitosos

No s'han d'obrir fitxers o enllaços sospitosos, especialment si provenen de remitents desconeguts.

## Esquema de protecció

```text
Actualitzacions
       +
Contrasenyes segures
       +
Firewall
       +
Còpies de seguretat
       +
Precaució de l'usuari
       |
       v
Millor protecció de l'ordinador
```

## Conclusió

La seguretat d'un ordinador depèn de diferents mesures. Aplicar diverses mesures al mateix temps permet reduir els riscos.