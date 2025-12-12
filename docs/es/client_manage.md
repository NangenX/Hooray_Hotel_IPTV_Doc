# Configuración de Gestión de Clientes

>Introducción

![Menú de Cliente](_images/client/client_1.png)

En `Client Menu`, el administrador necesita configurar la información de equipo correspondiente en `Room Category`, `Client Information` y `Client Status` y operar el check-in y check-out de visitantes.

## Categoría de Sala

>Introducción

![Categoría de Sala](_images/client/client_2.png)

En `Room Category`, el administrador necesita establecer el nombre de clasificación lógica. En la clasificación lógica de Hooray Hotel IPTV se utiliza para distinguir equipos pertenecientes a diferentes pisos o diferentes usos. Por ejemplo, si hay más de una pieza de equipo colocada en el 1er piso, entonces establezca el nombre de clasificación como L1, y así sucesivamente.

Presione el botón `Add` para crear la `Room Category`

![Categoría de Sala - Agregar](_images/client/client_3.png)

1. <font color="red">**Group Name**</font>: En `Group Name`, el administrador establece el nombre de categoría lógica.

## Información de Cliente

>Introducción

![Información de Cliente](_images/client/client_4.png)

En `Client information`, esta página muestra todos los dispositivos actualmente en línea y fuera de línea. El administrador puede administrar el nombre del dispositivo y el estado del `WIFI hotspot status` (abandonado) a través de esta página. En la lista de dispositivos, puede ver la clasificación a la que pertenece el dispositivo, el número de habitación correspondiente y otra información de dispositivo, etc.

Presione el botón `Add` para crear la `Client information`

![Información de Cliente - Agregar](_images/client/client_5.png ':size=40%') ![Información de Cliente - Editar](_images/client/client_6.png ':size=40%')

<font color="red">**MAC Address**</font>: En `Mac Address`, si el dispositivo no está en Información de Cliente, entonces se puede agregar manualmente ingresando la dirección MAC. Si el dispositivo ha sido descubierto por el servidor IPTV del hotel, la dirección MAC solo se puede ver.

<font color="red">**IP**</font>: En `IP`, se muestra información sobre la dirección IP de la última vez que el dispositivo estuvo en línea.

<font color="red">**Room Name**</font>: En `Room Name`, ingrese el nombre de la sala a la que pertenece el dispositivo.

<font color="red">**Room Category**</font>: En `Room Category`, seleccione la categoría de sala a la que pertenece el dispositivo.

<font color="red">**WiFi**</font>: En `WiFi`, el administrador puede ENCENDER y APAGAR la función de punto de acceso del dispositivo, y puede establecer el nombre y contraseña del WiFi de la función de punto de acceso. Debido a la protección de Google para Android, esta función ya no se puede habilitar.


## Estado de Cliente

>Introducción

![Estado de Cliente](_images/client/client_7.png)

En la página Estado de Cliente, el administrador puede operar el check-in y check-out del equipo correspondiente. En el equipo sin check-in, puede ver la información de los clientes que realizaron check-in anteriormente y sus registros de consumo. En los dispositivos con check-in, puede operar pedidos en línea, registros de consumo, editar información de huéspedes, ver registros de check-in anteriores y operaciones de check-out.

![Estado de Cliente - Estado de Check-In](_images/client/client_8.png)

<font color="red">**Request**</font>: Haga clic en el botón `Request`, se abrirá la página actual de operación de reserva del huésped. En la página, el administrador puede ver la reserva de la sala del huésped. El administrador puede confirmar o eliminar el pedido a través del botón de operación. Después de la operación correspondiente, el resultado se devolverá al huésped y se mostrará el estado en la aplicación del hotel.

<font color="red">**Consume**</font>: Haga clic en el botón `Consume`, se le redirigirá a la página de registro de consumo actual del huésped, que muestra el pedido completado actual del huésped desde la aplicación.

<font color="red">**Edit**</font>: Haga clic en el botón `Edit`, el administrador puede restablecer el nombre del huésped que realizó check-in y el mensaje de bienvenida.

<font color="red">**Records**</font>: Haga clic en el botón `Record`, el administrador puede ver el registro de check-in del dispositivo, incluyendo el nombre del ocupante, hora de check-in, hora de check-out y registro de consumo.

<font color="red">**Check-Out**</font>: Después de hacer clic en el botón `Check-Out`, el dispositivo entra automáticamente en estado de Check-Out, en el cual todos los servicios no están disponibles.

![Estado de Cliente - Estado de Check-In](_images/client/client_9.png)

<font color="red">**Check-In**</font>: Haga clic en el botón `Check-In`, el administrador necesita rellenar el nombre del cliente que realiza check-in y el mensaje de bienvenida que se muestra en la pantalla grande.
