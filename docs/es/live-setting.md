# Configuración de Transmisión en Vivo

>Introducción

![Menú de Programa](_images/program/program_1.png)

El menú de programas permite a los administradores crear, modificar y eliminar configuraciones de `Live` y `VOD`.

## Paquetes en Vivo

>Introducción

![Paquete en Vivo](_images/program/program_2.png)

En la función de Paquetes en Vivo, los administradores pueden crear, modificar y eliminar categorías para las fuentes de canales en vivo. Al crear categorías, se facilita la organización y asociación de las fuentes con sus categorías correspondientes, permitiendo a los suscriptores buscar y clasificar los canales en vivo que desean ver.

Los administradores pueden crear nuevas categorías en vivo haciendo clic en el botón `Add`. Cada categoría debe asociarse a una fuente de canal en vivo; cada categoría puede subir un póster distintivo.

![Live Package-Add](_images/program/program_3.png)

1. <font color="red">**ID**</font>: El `ID` se genera automáticamente por el sistema; cuanto menor sea el `ID`, más arriba se mostrará la categoría en la lista. Puede ajustar el `ID` en la página de edición para ordenar las categorías.

2. <font color="red">**Name**</font>: El `Name` distingue entre los distintos nombres de categoría.

3. <font color="red">**Price**</font>: El administrador puede configurar el `price` de la categoría en vivo; cuando el precio es 0, la categoría es gratuita; si no es 0, al acceder se solicitará cobro.

4. <font color="red">**Image**</font>: Subiendo la `image` correspondiente a la categoría, ésta se mostrará en el menú de categorías en el decodificador.

!>  **Warning: Live Package upload image size should 300x210**

5. <font color="red">**Live Program Select**</font>: Para `select` el programa en vivo correspondiente a la categoría, el administrador debe seleccionar los programas que se mostrarán bajo esa categoría en el menú del terminal.

6. <font color="red">**STB Select**</font>: El administrador selecciona los dispositivos en la lista; solo los dispositivos seleccionados podrán mostrar esta categoría en vivo.

## Programa en Vivo

>Introducción

![Programa en Vivo](_images/program/program_4.png)

En la sección "Live Program", los administradores pueden añadir manualmente o en lote programas en vivo. Tras añadirlos, pueden editar y eliminar programas específicos. Se admiten protocolos comunes: UDP(unicast)/RTP(unicast)/HTTP-TS/HTTP-FLV/RTMP/RTMPS/HLS/DASH, entre otros.

Los administradores pueden crear un nuevo canal en vivo haciendo clic en el botón `Add`.

![Live Channel Add Detail](_images/program/program_5.png)

1. <font color="red">**ID**</font>: Este `ID` se genera automáticamente por el sistema y puede editarse manualmente. Al editar manualmente no debe entrar en conflicto con otros `ID`. Este `ID` es el número de orden del canal; cuanto menor sea, antes se mostrará en el decodificador.

2. <font color="red">**Name**</font>: El `Name` se usa para mostrar el nombre del canal en el decodificador. El texto ingresado se muestra completo como nombre del canal.

3. <font color="red">**URL**</font>: Rellene la `URL` con la dirección que debe reproducirse en el terminal.

4. <font color="red">**Image**</font>: Al subir el `program logo` correspondiente, éste se mostrará en la lista de canales y en el detalle del canal en el decodificador.

