# System Setting

>Introducción

![System](_images/setting/setting_1.png) 

En `System`, el administrador puede modificar la información del sistema IPTV, incluyendo la importación de información de autorización, la copia de seguridad de la base de datos y la configuración de seguridad de la interfaz API externa.

## Setting

>Introducción

![Setting - Setting ](_images/setting/setting_2.png) 

En `Setting`, el administrador configura la información básica que debe sincronizarse con el terminal, la imagen de fondo de cada página jerárquica, el formato de hora y algunos otros parámetros detallados.

<font color="red">**Monetary Unit**</font>: En `Monetary Unit`, el administrador ingresa el equivalente local del símbolo del dólar, que se utiliza para mostrar el símbolo del dólar local en `Shopping`.

<font color="red">**Paid Days**</font>: En `Paid Days`, cuando el huésped hace clic para comprar un paquete de transmisión en vivo o una película, es el tiempo de vencimiento establecido.

<font color="red">**Consumption Mode**</font>: En `Consumption Mode`, el administrador selecciona el método de pago del huésped. En `Prepaid consumption`, cuando el huésped consume, primero necesita recargar el monto en la cuenta. Solo cuando hay suficiente monto en la cuenta pueden consumir. Si el monto es insuficiente, no pueden consumir. En `Advance Consumption`, los huéspedes pueden consumir sin recargar, y el consumo se registra en el monto de la habitación en forma de cuentas por cobrar.

<font color="red">**Home Page Show**</font>: En `Home Page Show`, el administrador selecciona la forma en que se muestra el fondo de la página de inicio en la lista desplegable. Cuando se selecciona `Image`, se muestra la imagen de fondo cargada. Cuando se selecciona `Video`, se muestra el archivo de video cargado.

<font color="red">**Time Format**</font>: En `Time Format`, el administrador establece manualmente el formato de hora que se muestra en el front-end.

<font color="red">**Favorite Operation**</font>: En `Favorite Operation`, los administradores configuran si se debe borrar la lista de favoritos guardada por el huésped al hacer el check-out.

<font color="red">**Request ring**</font>: En `Request ring`, el administrador carga el tono de alerta de pedido correspondiente. Actualmente está obsoleto debido a factores técnicos del navegador.

<font color="red">**Welcome Background**</font>: En `Welcome Background`, el administrador necesita cargar la imagen de fondo de bienvenida que se sincronizará con el lado del TV.

<font color="red">**Home Background**</font>: En `Home Background`, el administrador necesita cargar la imagen de fondo de inicio que se sincronizará con el lado del TV.

<font color="red">**Secondary Menu Background**</font>: En `Secondary Menu Background`, el administrador necesita cargar la imagen de fondo del menú secundario que se sincronizará con el lado del TV.

<font color="red">**LOGO**</font>: En `LOGO`, el administrador necesita cargar la imagen del logo que se sincronizará con el lado del TV y móvil.

<font color="red">**Live Player Watermark**</font>: Esta función está actualmente obsoleta.

<font color="red">**Vod Player Watermark**</font>: Esta función está actualmente obsoleta.

<font color="red">**City**</font>: En `City`, el administrador ingresa el nombre de la ciudad correspondiente, y el servidor IPTV obtendrá la información del clima y la reenviará a diferentes terminales.

<font color="red">**Enable Remote Assistance**</font>: Esta función está actualmente obsoleta.

<font color="red">**Protocolo**</font>: En `Protocolo`, seleccione el protocolo de transmisión en vivo utilizado por los dispositivos terminales (p. ej. `http`, `udp`, `rtsp`).

<font color="red">**Número de operador**</font>: En `Número de operador`, introduzca el número de operador único necesario para el mantenimiento del sistema y el soporte técnico. **Una vez rellenado, no se puede modificar.**

<font color="red">**PMS**</font>: En `PMS`, seleccione el modo de integración del PMS (Sistema de Gestión de Propiedades):
- `Ninguno`: la integración con el PMS está desactivada.
- Cuando se selecciona un tipo de PMS, rellene la `Información del servidor PMS` (la dirección del servidor PMS). El sistema IPTV se integrará con el PMS (p. ej. para la entrada/salida automática de huéspedes y la sincronización de facturas). El conmutador, la dirección y el puerto del PMS los configura el administrador.

## Version

>Introducción

![APK Version Management](_images/setting/setting_3.png) 

En `APK Version Management`, los administradores pueden configurar políticas de actualización para diferentes terminales, admitiendo métodos de actualización tanto obligatorios como no obligatorios.

Presione el botón `APK Upgrade` para cargar el apk. Después de hacer clic en el botón `APK upgrade`, aparecerá una página de carga. Después de seleccionar el archivo APK que se va a actualizar, el sistema procesará automáticamente la información de la versión del archivo y la mostrará en la lista de actualización. El administrador necesita verificar si es correcta.

## Configuración de medios de transmisión

> Introducción

![Configuración de medios de transmisión](_images/setting/streaming_1.png ':size=80%')

<!-- 📷 Captura pendiente: página de configuración de medios de transmisión -->

En `Configuración de medios de transmisión`, el administrador configura las direcciones del servidor de medios de transmisión y del servidor de time-shift (TV en diferido), que utilizan los dispositivos terminales para reproducir transmisiones en vivo y programas en diferido.

<font color="red">**IP de medios de transmisión**</font>: En `IP de medios de transmisión`, introduzca la dirección IP del servidor de medios de transmisión.

<font color="red">**Puerto de medios de transmisión**</font>: En `Puerto de medios de transmisión`, introduzca el puerto del servidor de medios de transmisión.

<font color="red">**IP del servidor Time-shift**</font>: En `IP del servidor Time-shift`, introduzca la dirección IP del servidor de time-shift.

<font color="red">**Puerto del servidor Time-shift**</font>: En `Puerto del servidor Time-shift`, introduzca el puerto del servidor de time-shift.

<font color="red">**Horas de Time-shift**</font>: En `Horas de Time-shift`, establezca cuántas horas de programas conserva el servidor de time-shift, lo que permite a los huéspedes ver programas anteriores dentro de esta ventana.

## Gráficos de datos

> Introducción

![Gráficos de datos](_images/setting/charts_1.png ':size=80%')

<!-- 📷 Captura pendiente: página de estadísticas de datos -->

En `Gráficos de datos`, los administradores pueden ver las estadísticas de funcionamiento del sistema IPTV, incluyendo:

- **Estadísticas de facturación**: las estadísticas totales de ingresos del negocio.
- **Estadísticas de VOD**: estadísticas de las reproducciones de video bajo demanda.
- **Tipo de consumo**: estadísticas agrupadas por tipo de consumo.
- Gráficos de barras mensuales y gráficos circulares, filtrables por año.
