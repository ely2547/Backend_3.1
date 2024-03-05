# Servidor Express para Envío de Correos

Este repositorio contiene un servidor Express simple que permite a una aplicación enviar correos electrónicos a través de Gmail utilizando MongoDB para almacenar información relacionada con el envío de correos.

## Requisitos

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

## Configuración

1. Clona este repositorio:
   ```bash
   git clone https://github.com/ely2547/Backend_3.1.git

  

 Instala las dependencias:
 
npm install

Crea un archivo .env en la raíz del proyecto y agrega las siguientes variables de entorno:

MONGODB_URI=tu_uri_de_mongodb
GMAIL_USER=tu_correo@gmail.com
GMAIL_PASS=tu_contraseña

Asegúrate de reemplazar tu_uri_de_mongodb, tu_correo@gmail.com y tu_contraseña con la información correspondiente.

## Ejecución

Para iniciar el servidor, ejecuta el siguiente comando:

node index



Este README proporciona una estructura básica y descripción de un servidor Express. Asegúrate de personalizar la información y agregar más detalles según las necesidades específicas de tu proyecto. Además, ten en cuenta que almacenar contraseñas y credenciales en un archivo `.env` es sensible. Se recomienda utilizar un sistema seguro para gestionar las credenciales en entornos de producción.
