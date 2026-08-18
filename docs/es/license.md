# Configuración de licencia

> Introducción

![Licencia](_images/license/license_1.png ':size=80%')

<!-- 📷 Captura pendiente: página de gestión de licencia -->

En `Licencia`, los administradores gestionan la licencia del sistema IPTV. La licencia controla el número de decodificadores que pueden conectarse al sistema y el período de validez. Cuando la licencia es inválida o ha caducado, los nuevos terminales no pueden registrarse en el sistema.

## Estado de la licencia

![Estado de la licencia](_images/license/license_2.png ':size=80%')

<!-- 📷 Captura pendiente: información del estado de la licencia -->

La página de licencia muestra la información actual de la licencia:

<font color="red">**Estado**</font>: El estado actual de la licencia (válida / inválida / caducada / no activada).

<font color="red">**Nombre del cliente**</font>: El nombre del cliente vinculado a la licencia.

<font color="red">**Conexiones máximas**</font>: El número máximo de decodificadores permitidos para conectarse al sistema.

<font color="red">**Fecha de caducidad**</font>: La fecha de caducidad de la licencia.

<font color="red">**Motivo del fallo**</font>: Si la licencia es inválida, aquí se muestra el motivo del fallo.

## Huella digital

![Huella digital](_images/license/license_3.png ':size=80%')

<!-- 📷 Captura pendiente: huella digital del dispositivo -->

Pulse el botón `Huella digital` para generar la huella digital del servidor actual. La huella digital es un identificador único del hardware del servidor; debe proporcionarse al emisor de la licencia para que pueda generarse una licencia vinculada a este servidor.

Pulse el botón `Descargar` para descargar el archivo de huella digital y enviarlo al emisor de la licencia.

## Cargar licencia

![Cargar licencia](_images/license/license_4.png ':size=80%')

<!-- 📷 Captura pendiente: cargar archivo de licencia -->

Después de obtener el archivo de licencia del emisor:

1. Haga clic en el botón `Cargar` en la página de licencia.
2. En el diálogo emergente, seleccione el archivo de licencia.
3. Pulse `Enviar`. El sistema verifica el archivo de licencia (firma, vinculación con el cliente, fecha de caducidad y defensa contra retroceso de tiempo). Si la verificación es correcta, la licencia se activa inmediatamente; de lo contrario, el motivo del fallo se muestra en la página.
