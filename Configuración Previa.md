# CACTI

***¿Que es LAMP?***

Es un grupo de software de código libre que es instala normalmente en conjunto para habilitar un servidor para alojar sitios y aplicaciones web.


***¿Cual es el acrónimo de LAMP?***

Es describir un sistema de infraestructura de internet que usa las siguientes herramientas:

***Linux***, *el sistema operativo; En algunos casos también se refiere a LDAP*.

***Apache***, *el servidor web*.

***MySQL***, *el gestor de bases de datos*.

***PHP o Python***, *los lenguajes de programación*.

# Instalacion LAMP

Primero **Actualizamos** nuestro sistema y nos aseguramos de tener los paquetes mas recientes.

Los podemos actualizar escribiendo los siguientes comandos:

```bash
sudo apt-get update
sudo apt-get upgrade
```
## Apache 

**Apache** es un servicio de paginas web **HTTP** de código abierto que sirve para colocar varias plataformas como ***Unix, BSD, GNU/Linux, Windows, Macintosh*** entre otros que implementan el protocolo **HTTP**.

Lo instalaremos con este comando:
```bash
sudo apt-get install apache2
```
## MySQL

Ahora es el momento de instalar **MySQL**, que es un sistema de gestion de base de datos. Se encarga de organizar y facilitar el acceso a las bases de datos. 

Para ello ejecutamos el siguiente comando.
```bash
sudo apt-get install mysql-server
```
## PHP

Es un lenguaje de programación diseñado para producir *sitios web dinámicos*. **PHP** es utilizado en aplicaciones del lado del servidor, aunque puede ser usado también desde una interfaz de *línea de comandos o como aplicación de escritorio*.

Para instalar **PHP** y sus modulos adicionales debemos ejecutar el siguiente comando:
```bash
sudo apt-get install php libapache2-mod-php php-mcrypt php-mysql
```


# Instalar RRDTOOLS

Su finalidad es el tratamiento de datos temporales y datos seriales como *temperaturas, transferencias en redes, cargas del procesador, etc*.

Y lo instalaremos con el siguiente comando:

```bash
sudo apt-get -y install rrdtool
```

# Instalar SNMP y SNMPD

Simple Network Management Protocol) es un protocolo de la capa de aplicación que facilita el intercambio de información de administración entre dispositivos de red. Los dispositivos que normalmente soportan SNMP incluyen routers, switches, servidores, estaciones de trabajo, impresoras, bastidores de módem y muchos más.

Permite a los administradores supervisar el desempeño de la red, buscar y resolver sus problemas, y planear y crecimiento.

```bash
sudo apt-get -y install snmp snmpd
```
