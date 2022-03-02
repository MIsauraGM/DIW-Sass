# DIW-Sass

Instálate la extensión de Live Sass Compiler en tu entorno de Visual Studio Code y clónate este repositorio para poder realizar las siguientes cuestiones. Las soluciones estarán disponibles en la rama "solution".

## EJERCICIO 1

Desde la carpeta *ej1* desarrolla los siguientes puntos de modo que obtengas el resultado que se muestra en ej1-resultado.png:
* Incluye 2 archivos HTML llamados index.html e index_scss.html que incluyan un h1 y un listado con enlaces dentro.
* Incluye dos carpetas llamadas CSS y SCSS.
* Dentro de cada carpeta crearemos los archivos style.css y style_scss.scss, respectivamente.
* Añade los estilos que consideres necesarios a cada archivo correspondiente.
* Cuando guardemos datos en los archivos pre-procesados, comprobarás que se habrán creado archivos asociados en la carpeta correspondiente de CSS.
* Referencia a cada HTML su hoja de estilos CSS correspondiente.
* Comprueba el resultado de cada html en el navegador.

## EJERCICIO 2
Realiza la versión index_sass.html y style_sass.sass del ejercicio anterior.

## EJERCICIO 3
Utilizando como plantilla el código HTML propuesto en la carpeta ej3:

* Abre en el navegador la ruta del archivo index.html y comprueba que funciona correctamente.
* Crea las carpetas css e img.
* Decide si vas a utilizar Sass o SCSS.
* Crea, dentro del carpeta css, el fichero style.scss o style.sass. Parto de que se va a usar style.scss en adelante.
* Podrías modificar la configuración de tu IDE o los comandos en la consola para compilar automáticamente el fichero style.scss con el nombre y ubicación que desees, no obstante, vamos a dejar la configuración por defecto donde alojará el fichero style.css compilado en la misma carpeta css.
* Si quieres aprovechar bien el ejercicio, no debes escribir nada en el archivo style.css, todo el código de dicho archivo se compilará a partir del fichero style.scss. 
* Accede a Google Fonts e importa la fuente Nunito en sus variantes light 300, regular 400 y bold 700 dentro del archivo style.scss.
* Enlaza el archivo style.css en tu archivo index.html.
* Modifica tu hoja de estilos para que la página y las fuentes cumplan los siguientes requisitos (intenta utilizar todo lo aprendido hasta ahora para optimizar tu hoja de estilos):
** Ajusta la página a un ancho máximo de 1400px sin márgenes y céntrala en la ventana del navegador
** La fuente en toda la página será Nunito y la alternativa será sans-serif.
** La fuente del cuerpo de la página tendrá un peso de 400 con un tamaño de 1rem.
** La fuente de los titulares (h1 a h3) llevará un peso de 700 y su tamaño será mayor que el cuerpo en cada paso (un 50% más para h3, un 100% mas para h2, un 200% mas para h1)
** En este punto, al refrescar tu página deberías ver los cambios en las fuentes. Si no es así, revisa la configuración y los estilos antes de continuar.
* Modifica tu hoja de estilos para que el header cumpla los siguientes requisitos
** El logo de Sass (que puedes descargar de su página web en svg), debe ir alineado a la izquierda ocupando el 10% del ancho del header.
** El título de la página debe aparecer centrado en el espacio restante del header, y el subtítulo debajo y también centrado.
** Pinchando en la imagen o en el título la página se debe recargar, pero el título no debe parecer un enlace (de hecho, ningún enlace de la página debe parecerlo).
** Resetea los márgenes de los títulos del header.
** Añade al header un color de fondo y un pequeño padding a los cuatro lados.
* Modifica tu hoja de estilos para que el nav cumpla los siguientes requisitos:
** El nav ocupará todo el ancho disponible, tendrá el mismo color de fondo y estará levemente separado del header.
** Los ítems de menú deben estar en línea y centrados en pantalla, sin margin y con un mínimo padding entre ellos.
** Los ítems de menú estarán en mayúsculas, con un tamaño de letra del 110% respecto del cuerpo, un peso de 400 y uno de 700 on hover.
** El color de los ítems y los enlaces será negro, salvo en los enlaces on hover que será rojo.
** Aplica a la section una altura mínima de 20em para separarla y que se diferencie del footer. Ya trabajaremos con ella en el tercer bloque.
* Modifica tu hoja de estilos para que el footer cumpla los siguientes requisitos:
** Las dos secciones del footer (div y p) tendrán el mismo color de fondo y estarán separadas levemente.
** Descárgate los iconos de las redes sociales en svg de ESTA DIRECCIÓN.
** Asócialos con sus correspondientes enlaces en el html.
** Los iconos del footer tendrán un ancho de 3em, estarán centrados y en línea, con una cierta separación entre ellos.
** La letra del párrafo p será un 80% respecto de la del cuerpo.

##EJERCICIO 4:
Haz una copia del ejercicio, añádele Bootstrap 4 y crea un menú con sub-niveles y sus estilos necesarios.
