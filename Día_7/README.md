# Metrolínea

En este proyecto se trabajó el uso de HTML + CSS, más específicamente del uso de los selectores en CSS, de manera que se creó una organización de una simulación de página de tarjetas digitales de metrolínea (de carácter meramente estético, sin ninguna funcionalidad o interactividad con el usuario, exceptuando una conexión con otra página HTML modularizada) a partir de un conjunto de archivos preestablecidos.

|Tabla de contenidos|
|--|
|[¿Cómo ejecutar este archivo?](#Ejecucion)|
|[Funcionamiento del programa](#Funcionamiento)|

<a name="Ejecucion"></a>

## ¿Cómo ejecutar este archivo?

Para poder observar la página web creada en este proyecto se puede realizar de dos maneras diferentes:

1. Accediendo directamente a través de este link: https://dante-sal.github.io/HTML_S1_SalamancaDante/D%C3%ADa_7/
2. Clonando el repositorio desde una terminal linux a través del comando `git clone https://github.com/Dante-Sal/HTML_S1_SalamancaDante`, accediendo a la ruta HTML_S1_SalamancaDante/Día_7/ y abriendo el archivo index.html con el navegador web de su preferencia.

<a name="Funcionamiento"></a>

## Funcionamiento del programa

En esencia, el funcionamiento de este programa se basa en la modificación de atributos de diferentes elementos a través del uso de selectores CSS como clases, elementos o IDs (no aplicados en este ejercicio). Simultáneamente, se hizo uso constante de divisiones anidadas siguiendo la metodología BEM para la asignación de nombres de clases, así como el acceso a estas divisiones mediante una ruta de selectores precisa.

Los primeros pasos de la generación del código HTML siguieron la siguiente lógica: en primer lugar se tiene un elemento div que abarca todo el ancho y alto del sitio web, permitiendo el centrado del div que hará las veces de fondo para la interfaz (división con gradiente). Una vez creada esta estructura, se pudo generar el div que se muestra en color blanco en el resultado final, ubicando en su interior la barra lateral y los demás elementos que hacen parte de los requerimientos solicitados.

A través de atributos como position, margin y display, se pudo hacer un uso eficiente del posicionamiento de cada objeto, otorgando la posibilidad de organizar el sitio adecuadamente (se siguen las medidas exactas especificadas). Finalmente, una vez terminado el sitio principal, se pasó a efectuarle ciertas modificaciones para que funcionara como sitio secundario (al hacer clic en el enlace "Ver Saldo"), conectándolo, como última medida, a través de una etiqueta a con el atributo href direccionado al archivo checkbalance.html.