# Permisos

Els permisos de Linux permeten controlar l'accés als fitxers i directoris.

## Tipus de permisos

Els principals permisos són:

| Permís | Significat |
| ------ | ---------- |
| `r`    | Lectura    |
| `w`    | Escriptura |
| `x`    | Execució   |

## Consultar permisos

Podem utilitzar:

```bash
ls -l
```

Exemple:

```text
-rwxr-xr--
```

Els permisos es divideixen entre:

* propietari
* grup
* altres usuaris

## Modificar permisos

Podem utilitzar `chmod`.

Per exemple:

```bash
chmod 755 script.sh
```

Això permet al propietari llegir, escriure i executar, mentre que el grup i els altres poden llegir i executar.

## Canviar el propietari

Podem utilitzar:

```bash
sudo chown usuari:grup fitxer
```

Els permisos són importants perquè permeten protegir la informació i limitar les accions dels usuaris.
