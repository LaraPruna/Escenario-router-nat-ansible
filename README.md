# Escenario router-nat con ansible


1. Comprobacion que cliente tiene acceso a internet haciendo ping a un nombre de una página web. Asegurate que no está saliendo por eth0 (muestra las rutas).

2. Entrega una captura de pantalla accediendo por ssh a las dos máquinas. Configura el sistema para que podamos acceder acceder a las máquinas por ssh. Te doy algunas ideas:
- Puedes usar las claves privadas generadas para cada una de las máquinas, o puedes generar nuevas claves que introduces en las máquinas.
- A lo mejor te viene bien la opción -A de ssh.
- Estudia el fichero ~/.ssh/config. Configurando de forma adecuada el fichero de configuración de ssh en tu equipo hasta puedes hacer que se conecte directamente con cliente.
- Las conexiones ssh nuncan las tienes que realizar por eth0.

3. Estudia la forma de integrar la receta ansible en vagrant, de tal manera que una vez se cree el escenario se ejecuta la configuración. Enseñale el funcionamiento al profesor.
