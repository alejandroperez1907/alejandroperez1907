# Alejandro Pérez

Hola, soy Alejandro y estoy cursando actualmente 2º de ASIR (Administración de Sistemas Informáticos en Red) en el instituto Esteve Terradas i Illa de Cornellà de Llobregat.

## Con qué he trabajado

### Sistemas
- **Linux** (Debian y Ubuntu Desktop / Server): instalación, gestión de usuarios, grupos y permisos, y configuración de servicios.
- **Windows** (Windows 10/11 y Windows Server 2019/2022): gestión de usuarios y grupos, permisos NTFS y configuración de servicios.
- **Dominios**: creación de un dominio con **Active Directory**, unión de equipos cliente (Windows / Windows y Linux) y aplicación de **directivas de grupo (GPO)**.
- **Recursos compartidos en red**: carpetas compartidas con permisos y cuotas de disco con Samba y NFS en Linux.
- **Monitorización y auditoría**: revisión de registros y rendimiento del sistema (visor de eventos, monitor de rendimiento y journalctl) y auditorías de seguridad (inicios de sesión y acceso a archivos).
- **Administración remota**: SSH, Escritorio remoto (RDP) y VNC.
- **Proxmox VE**: creación y gestión de máquinas virtuales y contenedores.
- **LXC y Docker**: despliegue de servicios como Nginx, Nextcloud, Pi-hole...

### Redes
- **Conmutación**: VLAN, STP y agregación de enlaces con EtherChannel.
- **Enrutamiento**: OSPF, NAT y configuración básica de BGP.
- **Redundancia de puerta de enlace**: HSRP y GLBP.
- **Cisco**: todo lo anterior practicado con Cisco Packet Tracer.
- **MikroTik RouterOS**: configuración con Winbox de DHCP, reglas de firewall y VLAN.
- **DNS**: servidor DNS con BIND9 y Pi-hole.
- **VPN**: WireGuard y Tailscale (que funciona sobre WireGuard) para acceder a mis servicios desde fuera de casa.
- **Wireshark**: captura y análisis de tráfico de red.

### Programación y scripts
- **Python**:
  - Tipos de datos, condicionales y bucles `while` y `for`.
  - Cadenas de texto, listas y diccionarios, incluidas estructuras anidadas (listas de diccionarios, diccionarios de listas...) y comprehensions.
  - Funciones, `*args` y `**kwargs`, y separación del código en módulos propios.
  - Control de errores con `try` / `except`.
  - Lectura y escritura de ficheros `.txt` y `.csv`.
- **Bash**:
  - Variables, parámetros (`$1`, `$#`, `$@`...), condicionales, bucles, arrays y funciones.
  - Menús interactivos con `read`, `case` y `select`, y validación de los datos que introduce el usuario.
  - Tratamiento de texto y archivos con `grep`, `awk`, `find`, `du` y `wc`.
  - Organización del código en varios archivos con `source`.
  - Automatización de tareas con `cron`.
- **SQL** (MySQL / MariaDB / PostgreSQL): diseño de tablas y consultas.

### Desarrollo web:
- **HTML y CSS**: diseño de páginas web.
- **JavaScript**: interactividad, manipulación del DOM, eventos y validación de formularios en el navegador.
- **Node.js con Express**: servidor web con varias rutas, archivos estáticos, recepción de datos de formularios (POST) y respuestas en JSON.

## Mi proyecto principal

Mi proyecto más completo es mi **[Homelab casero](https://github.com/alejandroperez1907/homelab)**, un servidor que tengo en casa con Proxmox VE y cinco servicios en contenedores (Pi-hole con Unbound, Vaultwarden, Tailscale, Uptime Kuma y Jellyfin), y lo tengo todo documentado paso a paso

## Otros proyectos

También he subido algunos proyectos de clase:

- **[Papelera de reciclaje en Bash](https://github.com/alejandroperez1907/papelera-reciclaje-bash)**: una papelera para la terminal. En vez de borrar los archivos directamente, los manda a una papelera desde donde se pueden restaurar, uno a uno o por extensión, y cada acción queda registrada en logs y la papelera se vacía sola cada mes con `cron`.
- **[Gestor de Streamers](https://github.com/alejandroperez1907/gestor-streamers-python)**: una aplicación de consola en Python de unas 550 líneas, con un menú para añadir, modificar, eliminar y buscar streamers con filtros, ordenarlos y sacar estadísticas.

## Contacto

Me puedes encontrar en [LinkedIn](https://www.linkedin.com/in/alejandro-pérez-del-olmo)
