# Còpies de seguretat

Una **còpia de seguretat**, també anomenada *backup*, és una còpia de les dades que es guarda en un altre lloc per poder recuperar-les en cas de pèrdua o dany.

Les còpies de seguretat permeten protegir documents, fotografies, projectes i altres dades importants.

---

## Per què són importants?

Les dades es poden perdre per diferents motius:

- Fallada del disc dur.
- Virus o ransomware.
- Esborrat accidental.
- Dany físic del dispositiu.
- Problemes elèctrics.
- Error humà.
- Robatori o pèrdua del dispositiu.

Una còpia de seguretat permet **recuperar les dades** després d'un incident.

```text
Dades originals
      |
      v
+----------------+
|     BACKUP     |
+-------+--------+
        |
        v
Emmagatzematge segur
```
## On podem guardar una còpia?

Les còpies de seguretat es poden guardar en diferents llocs:

| Mètode | Exemple | Característica |
|---|---|---|
| **Disc extern** | HDD o SSD | Còpia local |
| **Núvol** | Servei d'emmagatzematge | Accés per Internet |
| **Servidor** | Servidor de l'empresa | Centralització |
| **NAS** | Emmagatzematge de xarxa | Permet compartir i guardar dades |

És recomanable **no guardar totes les còpies al mateix dispositiu**.

## Tipus de còpies

Hi ha diferents tipus de còpies de seguretat.

### Còpia completa

Copia totes les dades seleccionades.

```text
Dilluns    → Còpia completa
Dimarts    → Còpia completa
Dimecres   → Còpia completa
```
És fàcil de restaurar, però necessita més espai d'emmagatzematge.

### Còpia incremental

Només copia les dades que han canviat des de l'última còpia.

```text
Dilluns    → Completa
Dimarts    → Canvis
Dimecres   → Canvis
Dijous     → Canvis
```
Ocupa menys espai, però la restauració pot requerir diverses còpies.

### Còpia diferencial

Copia les dades que han canviat des de l'última còpia completa.

```text
Dilluns    → Completa
Dimarts    → Canvis des de dilluns
Dimecres   → Canvis des de dilluns
Dijous     → Canvis des de dilluns
```

## Regla 3-2-1

Una estratègia habitual per protegir les dades és la **regla 3-2-1**:

- Tenir **3 còpies** de les dades.
- Guardar-les en **2 tipus de suport diferents**.
- Tenir **1 còpia en una ubicació diferent**.

### Exemple

```text
Dades originals
      |
      +----> Disc extern
      |
      +----> Servidor
      |
      +----> Núvol
```
Això redueix el risc de perdre totes les còpies al mateix temps.

## Automatitzar les còpies

És recomanable automatitzar els backups perquè no depenguin de fer-los manualment.

Per exemple:

```text
Cada dia a les 22:00
        |
        v
Backup automàtic
        |
        v
Emmagatzematge
```
L'automatització permet fer còpies de manera regular i reduir els errors humans.

## Provar les còpies

Fer una còpia no és suficient. També hem de comprovar que es pot restaurar correctament.

El procés pot ser:

```text
Crear backup
     |
     v
Comprovar backup
     |
     v
Provar restauració
     |
     v
Dades recuperades
```
Si una còpia està danyada o incompleta, podria no servir quan realment la necessitem.

## Quines dades hauríem de copiar?

Depèn de les necessitats de cada sistema, però alguns exemples són:

- Documents importants.
- Bases de dades.
- Configuracions dels servidors.
- Fotografies.
- Projectes.
- Fitxers de treball.
- Informació dels usuaris.

No sempre és necessari copiar tots els fitxers del sistema.

## Bones pràctiques

Per tenir un sistema de còpies de seguretat fiable:

- Fes còpies de manera regular.
- Automatitza els backups quan sigui possible.
- Utilitza més d'un suport.
- Guarda almenys una còpia en una ubicació diferent.
- Protegeix les còpies contra accessos no autoritzats.
- Comprova periòdicament que es poden restaurar.
- Defineix quines dades són importants.
- Mantén documentat el sistema de còpies.