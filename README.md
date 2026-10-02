# CyberSafe Docs

## 1. Nom del projecte

**CyberSafe Docs** és una web estàtica sobre ciberseguretat. Conté informació sobre contrasenyes, autenticació, tallafocs, VPN, còpies de seguretat i actualitzacions.

L'objectiu és organitzar la informació en diferents apartats perquè sigui fàcil de consultar.

## 2. Eines utilitzades i versions

Les eines utilitzades per crear i publicar el projecte són:

- **MkDocs:** generador de webs estàtiques escrit en Python.
- **Material for MkDocs:** tema utilitzat per al disseny visual.
- **Python:** llenguatge necessari per executar MkDocs.
- **Markdown:** format utilitzat per escriure el contingut.
- **CSS:** utilitzat per personalitzar l'aparença de la web.
- **Git:** eina per controlar els canvis dels fitxers.
- **GitHub:** plataforma per allotjar el repositori.
- **GitHub Pages:** servei per publicar la web.
- **GitHub Actions:** eina per automatitzar la generació i publicació.

  ## 3. Procés d'instal·lació

Per instal·lar les eines necessàries, cal tenir Python i Git instal·lats a l'ordinador.

### 1. Accedir a la carpeta del projecte

```powershell
cd "C:\Users\dunab\Desktop\web-estatica-DunaMarc"
```

### 2. Crear un entorn virtual

```powershell
python -m venv .venv
```

### 3. Activar l'entorn virtual

```powershell
.\.venv\Scripts\Activate.ps1
```

### 4. Instal·lar MkDocs Material

```powershell
pip install mkdocs-material
```

### 5. Comprovar la instal·lació

```powershell
mkdocs --version
```

## 4. Com executar la web localment

Executem el servidor local:

```powershell
mkdocs serve
```

Després obrim el navegador i accedim a:

[http://127.0.0.1:8000/](http://127.0.0.1:8000/)

Aquesta comanda permet visualitzar la web localment i veure els canvis quan modifiquem els fitxers.

Per aturar el servidor, premem `Ctrl + C` a PowerShell.


## 5. Com generar la web

Per generar la versió estàtica de la web, executem:

```powershell
mkdocs build
```

MkDocs llegeix els fitxers Markdown de la carpeta `docs/` i la configuració de `mkdocs.yml`. A continuació, genera els fitxers de la web dins de la carpeta `site/`.

Aquesta carpeta conté els fitxers preparats perquè el navegador pugui mostrar la web.

La carpeta `site/` està inclosa al fitxer `.gitignore`, juntament amb `.venv/` i `__pycache__/`, per evitar pujar fitxers generats o temporals innecessaris al repositori.

## 6. Com publicar la web

La web es publica amb GitHub Pages a partir del repositori de GitHub.

Per actualitzar el projecte, seguim aquests passos:

### 1. Comprovar els canvis

```powershell
git status
```

### 2. Afegir els fitxers modificats

```powershell
git add .
```

### 3. Crear un commit

```powershell
git commit -m "Actualitza la documentació"
```

### 4. Pujar els canvis a GitHub

```powershell
git push
```

## 7. Estructura del projecte

L'estructura principal del projecte és la següent:

```text
web-estatica-DunaMarc/
│
├── docs/
│   ├── index.md
│   ├── seguretat/
│   │   ├── contrasenyes.md
│   │   └── autenticacio.md
│   ├── xarxes/
│   │   ├── firewall.md
│   │   └── vpn.md
│   ├── proteccio/
│   │   ├── copies-de-seguretat.md
│   │   └── actualitzacio.md
│   ├── articles/
│   │   └── ...
│   └── stylesheets/
│       └── extra.css
│
├── .github/
│   └── workflows/
│       └── ...
│
├── .gitignore
├── mkdocs.yml
├── README.md
├── .venv/
└── site/
```

### Funció dels fitxers i les carpetes principals

- **`docs/`**: conté les pàgines de la web escrites en Markdown.
- **`docs/index.md`**: conté el contingut de la pàgina principal.
- **`docs/seguretat/`**: conté la informació sobre contrasenyes i autenticació.
- **`docs/xarxes/`**: conté els continguts sobre xarxes, tallafocs i VPN.
- **`docs/proteccio/`**: conté la informació sobre còpies de seguretat i actualitzacions.
- **`docs/articles/`**: agrupa els articles de la web.
- **`docs/stylesheets/extra.css`**: conté els estils CSS personalitzats.
- **`mkdocs.yml`**: configura el nom de la web, el tema, el menú de navegació i els estils.
- **`.gitignore`**: indica quins fitxers i carpetes no s'han de controlar amb Git.
- **`.github/workflows/`**: conté els fitxers de configuració dels processos automàtics de GitHub Actions.
- **`.venv/`**: conté l'entorn virtual de Python.
- **`site/`**: conté els fitxers generats per MkDocs després d'executar `mkdocs build`.

  
## 8. URL de la web publicada

La web està publicada amb GitHub Pages i es pot consultar a través del següent enllaç:

[https://dunabou-droid.github.io/web-estatica-DunaMarc/](https://dunabou-droid.github.io/web-estatica-DunaMarc/)
