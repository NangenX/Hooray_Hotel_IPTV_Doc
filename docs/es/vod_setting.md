## Configuración de Video On Demand (VOD)

>Introducción

![Video On Demand Menu](_images/program/program_6.png)

El menú de "Video On Demand" permite a los administradores crear, modificar y eliminar las configuraciones de `VOD Category`, `VOD Program` y `VOD Upload`.

## VOD Category

>Introducción

![Video On Demand Menu](_images/program/program_7.png)

En la función `VOD Category`, los administradores pueden crear, modificar y eliminar categorías para las películas. Al crear categorías de VOD, los administradores organizan mejor y asocian las películas correspondientes con sus categorías. Esto permite a los suscriptores buscar y filtrar las películas que desean ver de forma más cómoda.

Los administradores pueden crear una nueva `VOD category` haciendo clic en el botón `Add`.

![VOD Category Detail](_images/program/program_8.png)

1. <font color="red">**ID**</font>: Este `ID` se genera automáticamente por el sistema y puede editarse manualmente. Al editar manualmente, no debe entrar en conflicto con otros ID. Este `ID` es el número de secuencia de la categoría VOD; cuanto menor sea el número, antes se mostrará la categoría VOD en el decodificador (set-top box).

2. <font color="red">**Name**</font>: El `Name` se utiliza principalmente para mostrar el nombre de la categoría VOD en el decodificador.

## VOD Program

>Introducción

![VOD Program](_images/program/program_9.png)

En el menú `VOD Program`, el administrador puede agregar, editar y eliminar información de películas, y vincular archivos de película a las entradas correspondientes. Después de agregar la información de una película, el administrador podrá ver la nueva carátula (poster) y la información correspondiente en el menú `VOD Program`, así como la cantidad de veces que la película ha sido reproducida bajo demanda.

![VOD Program-add](_images/program/program_10.png)

Los administradores pueden crear una nueva `movie` haciendo clic en el botón `Add`.

1. <font color="red">**Poster**</font>: El administrador sube la `Poster` correspondiente a través de la página; el `poster` aparecerá en el terminal para identificar la película y atraer a los suscriptores a hacer clic para reproducirla.

2. <font color="red">**Name**</font>: El `Name` se usa para mostrar el título de la película en el decodificador.

3. <font color="red">**Price**</font>: El administrador puede establecer el `price` de la película; cuando el precio es 0, la película es gratuita; si el precio no es 0, al acceder el usuario se le solicitará el cobro.

4. <font color="red">**Director**</font>: El `Director` se muestra en los detalles de la película; los suscriptores pueden ver esta información al entrar en los detalles de la película.

5. <font color="red">**Actors**</font>: Los `Actors` se muestran en los detalles de la película; los suscriptores pueden ver esta información al entrar en los detalles de la película.

6. <font color="red">**Area**</font>: El `Area` indica la región de estreno en los detalles de la película; los suscriptores pueden verlo al entrar en los detalles.

7. <font color="red">**Language**</font>: El `Language` muestra el idioma de audio predeterminado de la película; los suscriptores pueden verlo en los detalles.

8. <font color="red">**Screen Time**</font>: La `Screen Time` (duración) se muestra en los detalles de la película; los suscriptores pueden consultarla al entrar en los detalles.

9. <font color="red">**VOD Type**</font>: `VOD Type` selecciona la categoría a la que pertenece la película; las categorías permiten a los suscriptores encontrar rápidamente películas al filtrar por tipo.

10. <font color="red">**Tag**</font>: La `Tag` indica si la película pertenece a "Hot Movies"; si está marcada como película popular, la película aparecerá en la categoría "Hot" y se mostrará en la parte superior de la página VOD.

11. <font color="red">**Off Sale**</font>: La opción `Off Sale` configura que la película esté fuera de venta en la aplicación.

12. <font color="red">**Introduction**</font>: La `Introduction` se utiliza para describir los detalles de la película.

## VOD Upload

>Introducción

![Vod Upload](_images/program/program_11.png)

En la página VOD Upload, el administrador puede subir y eliminar archivos de película; el formato del archivo debe cumplir el estándar de Hooray VOD. El formato de vídeo admite codificación `HEVC/H.264/AV1`; el audio admite `AAC/MP3/AC-3/E-AC-3/FLAC/DTS`. El formato de archivo subido <font color="red">MUST BE</font> `.MP4`.

!> :warning: **Advertencia: Los nombres de archivo subidos `DEBEN` estar libres de símbolos especiales y espacios.**

Al hacer clic en `Choose File` se abrirá la ventana de selección; seleccione el archivo de película a subir. Cuando el archivo haya terminado de subirse, la página de carga se actualizará automáticamente y mostrará el archivo en la lista de subidos.

!> Después de subir el archivo de la película, haga clic en `VOD Program` para ir a la lista de información de películas, seleccione la película correspondiente y haga clic en el icono para vincular la película con el archivo subido.

![Vod Upload](_images/program/program_12.png)

Haga clic en el botón `Add` para ir a la página de Añadir.

![Vod Upload](_images/program/program_13.png)

1. <font color="red">**ID**</font>: El `ID` se genera automáticamente por el sistema IPTV; el número generado se utiliza para el orden de visualización de los archivos; cuanto menor sea el número, más adelante se mostrará el archivo en la APP.

2. <font color="red">**Source**</font>: El desplegable `Source` permite seleccionar la ubicación de almacenamiento del archivo de película: `URL` o `Local File`. Si el archivo se ha subido a través del sistema IPTV, seleccionar `Local File`; si está almacenado de otra forma, seleccionar `URL`.

3. <font color="red">**URL**</font>: Cuando se selecciona `URL` en `Source`, rellenar la caja de entrada con la URL correspondiente del servidor remoto.

