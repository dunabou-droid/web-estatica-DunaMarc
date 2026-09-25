# SSH

SSH és un protocol que permet connectar-se de manera remota a un sistema.

## Connexió

Per connectar-nos a un servidor podem utilitzar:

```bash
ssh usuari@192.168.1.10
```

## Avantatges

SSH permet administrar un servidor remotament sense haver d'estar físicament davant de l'equip.

És molt utilitzat en administració de sistemes Linux.

## Comprovar el servei

En sistemes amb systemd:

```bash
sudo systemctl status ssh
```

Per iniciar-lo:

```bash
sudo systemctl start ssh
```
