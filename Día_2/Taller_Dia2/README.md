# Hoja de Vida

En este proyecto se trabajó el uso de HTML + CSS, más específicamente de la etiqueta div y sus diferentes funciones, de esta manera se creó un sistema de columnas que permitieron almacenar diferentes tipos de datos como texto, listas o imágenes.

## ¿Cómo ejecutar este archivo?

Para poder observar la página web creada en este proyecto se puede realizar de dos maneras diferentes:

1. Accediendo directamente a través de este link: https://dante-sal.github.io/HTML_S1_SalamancaDante/D%C3%ADa_2/Taller_Dia2/
2. Clonando el repositorio desde una terminal linux a través del comando ´´´git clone https://github.com/Dante-Sal/HTML_S1_SalamancaDante´´´, accediendo a la ruta HTML_S1_SalamancaDante/Día2/Taller_Dia2 y abriendo el archivo index.html con el navegador web de su preferencia.

## Funcionamiento del programa

En esencia, el funcionamiento de este programa se basa en la creación de divs anidados que representarán las diferentes capas del documento. En primera instancia se encuentra el div más grande, que mediante la asignación de la propiedad flex del body, permite centrar el contenido de toda la hoja de vida. Dentro de este div se encuentra otro div (también con la propiedad flex), que permitirá organizar el documento en columnas. Dentro de este div se encontrarán tres div más que reprsentarán cada columna y se organizarán de acuerdo a la propiedad flex del div inmediatamente superior. Finalmente, se encuentra una subdivisión más dentro de cada columna, que serán cada sección dentro de las columnas y (dado que estas últimas no poseen la propiedad flex) y se organizarán una debajo de la otra.

Aunque esta descripción es muy superficial y no permite comprender el código HTML y CSS en su totalidad, dentro del archivo index.html y style.css (dentro del directorio style), podrá encontrar comentarios que explican cada parte del código.
