# Manual básico de Linux
Este repositorio contiene documentación básica
sobre administración de sistemas Linux.
## Contenidos
- Gestión de usuarios
- Permisos
Afondamento · 2.º ASIR Página 2
- Redes
- Servicios
## Comandos útiles
Para consultar la configuración de red:
```bash
ip addr
```
Para comprobar la conectividad:
```bash
ping 8.8.8.8
```
## Gestión de servicios

Para comprobar el estado de un servicio o reiniciarlo en el sistema, utiliza los siguientes comandos:

```bash
systemctl status nombre-servicio
sudo systemctl restart nombre-servicio
