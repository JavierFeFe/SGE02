# Tarea para SGE02.

## Enunciado.
En esta unidad has aprendido determinados aspectos de los sistemas de planificación empresarial, y los tipos de licencias que tienen, para seguidamente realizar la instalación y configuración de dos ERPs de software libre. También has aprendido a instalar y configurar herramientas de asistencia técnica remota, para dar soporte técnico a equipos situados físicamente alejados. Finalmente, has conocido algunas herramientas de programación que te pueden ser de utilidad.

Pues bien, mediante esta tarea vamos a poner en práctica estos conocimientos aprendidos en la unidad. Para ello vamos a realizar la instalación completa de Odoo 11, así como una primera prueba de uso.

PRIMERA PARTE (INSTALACIÓN)

Vamos a utilizar la máquina virtual de Ubuntu server creada en la unidad 1.

Visualiza los pasos de instalación de los ERP mencionados en la unidad. Utiliza para ello los tutoriales oficiales de Odoo para la versión 11. Realizaremos la instalación de paquetes en Linux de Odoo versión 11. (documentación)
Sigue los pasos para la instalación y configuración de la base de datos.
Nombre de usuario para la base de datos: tucorreo
Nombre de la base de datos: demoSXE
Contrasela para administrador de la base de datos: abc123..
Crea la base de datos con información de demostración.
![image](https://user-images.githubusercontent.com/44543081/69916996-ed123c80-1461-11ea-9f9a-7dd2e007db77.png)  
![image](https://user-images.githubusercontent.com/44543081/69917021-2ea2e780-1462-11ea-91a2-b71b2aaa6223.png)  
En este punto con el fin de facilitar la copia y pega de los manuales de instalación preferí conectarme por ssh desde el equipo cliente al servidor.
![image](https://user-images.githubusercontent.com/44543081/69917085-ab35c600-1462-11ea-951a-f2552ae13875.png)  
![image](https://user-images.githubusercontent.com/44543081/69917117-e7692680-1462-11ea-81d8-f09191aa3e94.png)  
![image](https://user-images.githubusercontent.com/44543081/69917135-12537a80-1463-11ea-9945-9a6e2bc83639.png)  
![image](https://user-images.githubusercontent.com/44543081/69917151-3020df80-1463-11ea-8724-f9a3822bec56.png)  
En este punto escribí mal mi correo, por lo que lo corrigo en el siguiente paso desde la configuración.




Si fuera necesario, realiza otras configuraciones de servicios, red y base de datos.
SEGUNDA PARTE (PRUEBA)

Comprueba el correcto funcionamiento de las aplicaciones. Utiliza para ello los tipos de acceso que permita la aplicación.
Accede a la aplicación desde la máquina virtual de Ubuntu de Escritorio, haciendo uso de la ip asignada al servidor.
![image](https://user-images.githubusercontent.com/44543081/69917160-4b8bea80-1463-11ea-8253-54adde356a87.png)  

Visualiza los módulos instalados en la aplicación.
![image](https://user-images.githubusercontent.com/44543081/69917177-8857e180-1463-11ea-9a18-6b0e8d89634d.png)
TERCERA PARTE (SSH)

Comprueba si están instalados el cliente y el servidor los servicios de SSH. Instala si fuera necesario el paquete openssh-server (para el servidor) y openssh-client (para el cliente).

Como se puede apreciar en los apartados anteriores ya tenía configurado openssh tanto en el cliente como en el servidor.
Conéctate desde el cliente, mediante terminal, al servidor y comprueba que efectivamente puedes realizar acciones y cambios en el servidor.
![image](https://user-images.githubusercontent.com/44543081/69917283-94906e80-1464-11ea-9b74-332b033a2d7e.png)  
![image](https://user-images.githubusercontent.com/44543081/69917299-ad008900-1464-11ea-8b06-f1a27ec02278.png)  
![image](https://user-images.githubusercontent.com/44543081/69917312-c43f7680-1464-11ea-91d7-d6f1cab5d4af.png)  
