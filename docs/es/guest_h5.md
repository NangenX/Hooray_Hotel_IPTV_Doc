# H5 del huésped (Autoservicio del huésped)

> Introducción

![H5 del huésped](_images/guest/guest_1.png ':size=80%')

<!-- 📷 Captura pendiente: entrada/página de inicio del H5 del huésped -->

`H5 del huésped` es una aplicación web móvil para los huéspedes del hotel. Los huéspedes abren la página con su teléfono (mediante código QR o enlace) y pueden usar los servicios IPTV del hotel sin tocar el mando de la TV: ver TV en vivo y VOD, pedir comida, ver la factura, solicitar servicios del hotel y consultar instalaciones y atracciones cercanas.

## Acceso y verificación

![H5 del huésped - Verificar](_images/guest/guest_2.png ':size=80%')

<!-- 📷 Captura pendiente: página de verificación del huésped -->

El huésped introduce el **número de habitación** y el **apellido del huésped registrado** en la página de verificación. El sistema comprueba la habitación y el apellido (coincidencia de prefijo, sin distinguir mayúsculas) y crea una sesión de huésped aislada. La sesión del huésped está completamente separada de la sesión del administrador.

> **Nota**: la sesión del huésped es por navegador y caduca después de un tiempo de espera. El huésped debe volver a verificar después de que caduque la sesión.

## TV en vivo

![H5 del huésped - TV en vivo](_images/guest/guest_3.png ':size=80%')

<!-- 📷 Captura pendiente: página de TV en vivo del H5 -->

El huésped puede navegar por la lista de canales en vivo y reproducirlos con el reproductor H5. Los paquetes de canales siguen las mismas reglas de filtrado que el decodificador: solo se muestran los canales incluidos en los paquetes comprados por la habitación. La compra se realiza en la TV o en la recepción; el H5 no proporciona una entrada de compra.

## Video bajo demanda

![H5 del huésped - VOD](_images/guest/guest_4.png ':size=80%')

<!-- 📷 Captura pendiente: página de VOD del H5 -->

El huésped puede navegar por las categorías y películas de VOD, ver los detalles (póster, introducción, año, región, índice de clics) y reproducir la película. Cuando una película tiene varios episodios/líneas, el huésped puede seleccionar el episodio a reproducir.

## Pedido de comida

![H5 del huésped - Comida](_images/guest/guest_5.png ':size=80%')

<!-- 📷 Captura pendiente: página de pedido de comida del H5 -->

El huésped puede navegar por las categorías de comida y los artículos (con imágenes, precios y descripciones), añadir artículos al carrito y enviar el pedido. El pedido se envía a la consola del administrador para su confirmación. El huésped también puede ver su historial de pedidos y su estado.

## Factura

![H5 del huésped - Factura](_images/guest/guest_6.png ':size=80%')

<!-- 📷 Captura pendiente: página de factura del H5 -->

El huésped puede ver la factura de consumo actual, incluidos los registros de consumo y el importe total, agrupados por fecha.

## Servicios del hotel

![H5 del huésped - Servicio](_images/guest/guest_7.png ':size=80%')

<!-- 📷 Captura pendiente: página de servicios del hotel del H5 -->

El huésped puede navegar por las categorías de servicios del hotel y los artículos de servicio, y enviar reservas de servicios (p. ej. limpieza de la habitación, lavandería, llamada de despertador).

## Instalaciones y alrededores

![H5 del huésped - Instalaciones](_images/guest/guest_8.png ':size=80%')

<!-- 📷 Captura pendiente: página de instalaciones/alrededores del H5 -->

El huésped puede consultar las instalaciones del hotel y las atracciones cercanas:

- **Instalaciones**: el contenido de las instalaciones (p. ej. piscina, gimnasio, restaurante) se muestra como páginas integradas.
- **Alrededores**: lugares de interés alrededor del hotel con imágenes e introducciones.

## Idioma

El H5 es bilingüe (chino e inglés). Los huéspedes pueden cambiar el idioma en la página.
