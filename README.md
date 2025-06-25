# Trabajo práctico integrador

Computación Aplicada

Grupo 7

## Integrantes

* CASCARDO, EZEQUIEL
* FERNANDEZ GALARCE, FLORENCIA
* FERNANDEZ LACORT, GASTÓN
* GUIÑAZÚ SALVO, FACUNDO
* PELIGANGA, ANTONIO NATANIEL

## Configuración de red

iface enp0s3 inet static

 address 192.168.1.50
 
 netmask 255.255.255.0
 
 gateway 192.168.1.1

## Configuración de la Base Datos

servername = "localhost"

port = "3306"

username = "lcars"

password = "NCC1701D"

dbname = "ingenieria"

## Configuración del Servidor Web

DocumentRoot = /www_dir

Url = http://192.168.1.50/

## Configuración de Backups

Backpup Foder = /backup_dir

Backpup Script = /backup_dir#/backup_dir

Backup /www_dir = Lunes, miércoles y viernes a las 23:00

Backup /var/log = Diario a las 00:00
