# HTTP

HTTP és un protocol utilitzat per a la comunicació entre clients i servidors web.

## Funcionament

Quan un usuari entra en una pàgina web, el navegador envia una petició al servidor.

```text
Navegador
    ↓
Petició HTTP
    ↓
Servidor web
    ↓
Resposta HTTP
    ↓
Navegador
```

## Exemple

Podem comprovar una resposta HTTP amb:

```bash
curl https://example.com
```

## HTTPS

HTTPS és la versió d'HTTP protegida mitjançant xifratge TLS.

És la forma habitual d'accedir de manera segura als serveis web.
