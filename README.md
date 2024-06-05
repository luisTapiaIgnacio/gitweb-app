Una aplicación PHP

Un sitio multilingüe construido en PHP. La solución es un sitio simple que tiene 2 idiomas, ING/DK. La idea era mostrar una aplicación PHP con un diseño eficiente y receptivo y tener un cambiador de idiomas.
Cómo ejecutarlo

Estas son las instrucciones sobre cómo ejecutar la solución en tu máquina:

Clona el repositorio en tu carpeta www o donde prefieras git clone https://github.com/luisTapiaIgnacio

Este proyecto fue construido en PHP/MySQL y necesita ser ejecutado bajo una aplicación como MAMP/WAMP/XAMP

Si usas una de las aplicaciones anteriores, ten en cuenta de clonar el repositorio bajo tu carpeta htdocs para tener acceso a través del localhost o configura tu virtualhost y el archivo hosts según tus necesidades.

Configura el archivo connection.php con tu información de la base de datos.

Asegúrate de crear una base de datos vacía ya que la aplicación creará una tabla para ti.
Qué se utilizó

    PHP
    MySQL
    Materialize un framework CSS Enlace
    jQuery
    HTML

La aplicación

Sitio Multilingüe, Contiene dos idiomas, inglés y danés.
Estoy manejando varios idiomas desde jQuery. He creado language.js para este propósito. La función onclick se llama cuando el usuario cambia el idioma y luego usando jQuery simplemente reemplazo el texto.

Formulario. Todas las validaciones se realizan en el lado del cliente.
Después de enviar un formulario, los datos van a la base de datos y también se envían por correo electrónico a la dirección de correo electrónico predefinida.

Receptividad. Para un sitio web receptivo, utilicé el nuevo framework MaterilizeCss que es de Google.