# Usuaris i grups

Linux és un sistema multiusuari. Això significa que diferents usuaris poden utilitzar el mateix sistema amb permisos diferents.

## Crear un usuari

Per crear un usuari podem utilitzar:

```bash
sudo adduser nomusuari
```

El sistema ens demanarà una contrasenya i algunes dades de l'usuari.

## Crear un grup

Podem crear un grup amb:

```bash
sudo groupadd informatica
```

## Afegir un usuari a un grup

Per afegir un usuari al grup:

```bash
sudo usermod -aG informatica nomusuari
```

## Consultar els grups

Podem comprovar els grups d'un usuari amb:

```bash
groups nomusuari
```

## Per què és important?

Els usuaris i grups permeten controlar qui pot accedir als recursos del sistema i quines accions pot realitzar.
