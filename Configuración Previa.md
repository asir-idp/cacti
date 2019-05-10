# CACTI

***¿Que es LAMP?***

## Instalacion LAMP

Primero **Actualizamos** nuestro sistema y nos aseguramos de tener los paquetes mas recientes.

Los podemos actualizar escribiendo los siguientes comandos:

```bash
sudo apt-get update
sudo apt-get upgrade
```
##

**Apache** es un servicio de paginas web **HTTP** de código abierto que sirve para colocar varias plataformas como *Unix*, *BSD*, *GNU/Linux*, *Windows*, *Macintosh* entre otros que implementan el protocolo **HTTP**.

Lo instalaremos con este comando:
```bash
sudo apt-get install apache2
```
##

Ahora es el momento de instalar **MySQL**, que es un sistema de gestion de base de datos. Se encarga de organizar y facilitar el acceso a las bases de datos. 

Para ello ejecutamos el siguiente comando.
```bash
sudo apt-get install mysql-server
```
##

Es un lenguaje de programación diseñado para producir *sitios web dinámicos*. **PHP** es utilizado en aplicaciones del lado del servidor, aunque puede ser usado también desde una interfaz de *línea de comandos o como aplicación de escritorio*.

Para instalar PHP y sus modulos adicionales debemos ejecutar el siguiente comando:
```bash
sudo apt-get install php libapache2-mod-php php-mcrypt php-mysql
```


## Instalar RRDTOOLS

Su finalidad es el tratamiento de datos temporales y datos seriales como temperaturas, transferencias en redes, cargas del procesador, etc.

Y lo instalaremos con el siguiente comando:

```bash
sudo apt-get -y install rrdtool
```

## Instalar SNMP y SNMPD


Permite a los administradores supervisar el desempeño de la red, buscar y resolver sus problemas, y planear y crecimiento.

```bash
sudo apt-get -y install snmp snmpd
```

























Enlace a [Google](https://www.google.com).