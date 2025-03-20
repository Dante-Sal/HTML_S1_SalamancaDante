# Coffee Shop

En este proyecto se trabajó el uso de HTML + CSS, más específicamente del uso de los selectores en CSS y propiedades de posicionamiento, tamaño, color y fomrato tipográfico, de manera que se creó una organización de una simulación de página de cafetería (de carácter meramente estético, sin ninguna funcionalidad o interactividad con el usuario, exceptuando un menú de navegación que conecta con las distintas secciones del sitio) a partir de un conjunto de archivos preestablecidos y un video de muestra.

|Tabla de contenidos|
|--|
|[¿Cómo ejecutar este archivo?](#Ejecucion)|
|[Funcionamiento del programa](#Funcionamiento)|

<a name="Ejecucion"></a>

## ¿Cómo ejecutar este archivo?

Para poder observar la página web creada en este proyecto se puede realizar de dos maneras diferentes:

1. Accediendo directamente a través de este link: https://dante-sal.github.io/HTML_S1_SalamancaDante/Dia_8/
2. Clonando el repositorio desde una terminal linux a través del comando `git clone https://github.com/Dante-Sal/HTML_S1_SalamancaDante`, accediendo a la ruta HTML_S1_SalamancaDante/Dia_8/ y abriendo el archivo index.html con el navegador web de su preferencia.

<a name="Funcionamiento"></a>

## Funcionamiento del programa

En esencia, el funcionamiento de este programa se basa en la modificación de atributos de diferentes elementos a través del uso de selectores CSS como clases, elementos o IDs. Simultáneamente, se hizo uso constante de divisiones anidadas siguiendo la metodología BEM para la asignación de nombres de clases, así como el acceso a estas divisiones mediante una ruta de selectores precisa.

Los primeros pasos de la generación del código HTML siguieron la siguiente lógica: en primer lugar se generó un sistema de organización basado en la segmentación de la página web en partes bien diferenciadas como encabezado, secciones y pie de página. Acto seguido, se estableció una estructura basada en la etiqueta div, diferenciando las distintas partes individuales de la interfaz para su correcto manejo de ubicación o asignación de estilos.

Por ejemplo, en el caso específico del apartado de menú (sección 4), se tiene un bloque general que abarca lo que serían los tres productos disponibles en el sitio (permitiendo el centrado y correcta distribución o separación de las diferentes mercancías ofrecidas en la unidad), ramificando esta con una nueva división para cada uno de ellos (3 en total). Cada producto posee un título, unos contenidos y un botón; de forma de cada uno de estos elementos posee su propia etiqueta div aislada, propiciando un código limpio y ordenado que facilita el trabajo con hojas de estilo en cascada.

A través de atributos como position, margin y display, se pudo hacer un uso eficiente del posicionamiento de cada objeto, otorgando la posibilidad de organizar el sitio adecuadamente (se siguen las medidas exactas especificadas). Finalmente, se aplicaron diversas propiedades específicas de diferentes objetos HTML (como background-color o width para la barra de desplazamiento; o line-height o text-decoration y sus derivados para elementos de tipo texto como <p>, <a>, etc.), así como la importación de fuentes tipográficas al inicio del archivo .css, la fabricación de enlaces internos que llevan a distintos sitios dentro de la página web (mediante etiquetas <a> y href="#[id_del_elemento]") y el uso de pseudoclases como :hover (estado del elemento al posarse sobre el con el puntero).
