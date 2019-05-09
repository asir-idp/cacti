# CACTI

**Cacti** es una herramienta que permite monitorizar y visualizar gráficas y estadísticas de dispositivos conectados a una red y que tengan habilitado el protocolo **SNMP**.

Con **Cacti** podremos monitorizar cualquier equipo de red que soporte el protocolo SNMP, ya sea un switch, un router o un servidor *Linux*. 

## Instalacion LAMP

Primero **Actualizamos** nuestro sistema y nos aseguramos de tener los paquetes mas recientes.

Los podemos actualizar escribiendo los siguientes comandos:

```bash
sudo apt-get update
sudo apt-get upgrade
```
##

Ahora instala Apache2.
```bash
sudo apt-get install apache2
```
Ahora es el momento de instalar **MySQL**, que es un sistema de gestion de base de datos. Se encarga de organizar y facilitar el acceso a las bases de datos. 

Para ello ejecutamos el siguiente comando.
```bash
sudo apt-get install mysql-server
```
PHP ejecuta tu aplicacion. Instalar PHP y modulos adicionales con el siguiente comando.
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