# Grid

En este proyecto se trabajó el uso de HTML + CSS, más específicamente del uso de grid y sus diversas funcionalidades, de manera que se creó una organización de videos e imágenes en formato de grilla, aplicando variados conocimientos en propiedades grid, además de medidas relativas (generando un sitio web responsivo, es decir, adaptable a diferentes dispositivos).

|Tabla de contenidos|
|--|
|[¿Cómo ejecutar este archivo?](#Ejecucion)|
|[Funcionamiento del programa](#Funcionamiento)|

<a name="Ejecucion"></a>

## ¿Cómo ejecutar este archivo?

Para poder observar la página web creada en este proyecto se puede realizar de dos maneras diferentes:

1. Accediendo directamente a través de este link: https://dante-sal.github.io/HTML_S1_SalamancaDante/Dia_11/
2. Clonando el repositorio desde una terminal linux a través del comando `git clone https://github.com/Dante-Sal/HTML_S1_SalamancaDante`, accediendo a la ruta HTML_S1_SalamancaDante/Dia_11/ y abriendo el archivo index.html con el navegador web de su preferencia.

<a name="Funcionamiento"></a>

## Funcionamiento del programa

En esencia, el funcionamiento de este programa se basa en la aplicación de la propiedad CSS display: grid; así como de sus derivados (grid-template-columns para definir la cantidad de columnas deseadas o grid-row-start para definir en qué fila debería iniciar una división específica, entre otros). Se hizo uso de etiquetas div anidadas y nombradas siguiendo los parámetros de la metodología BEM, facilitando la estructuración de la página, además de un flujo de trabajo organizado y secuencial.

En primer lugar, se introdujo en el sitio el material multimedia precisado (imágenes y videos), a través de enlaces en etiquetas img e iframe respectivamente. Este material se dividió en dos secciones (cada aartado de color negro del sitio), que fueron nombradas section1 y section2 a través de clases para su posterior modificación. Cada imagen o video también recibió su correspondiente clase para permitir un mejor manejo de los tamaños (width / height) y, en el caso de aquellas celdas que necesitaban ocupa más de una fila o columna, una mejor aplicación de las propiedades grid-row-start, grid-row-end, grid-column-start y grid-column-end.

Para definir la cantidad de columnas y filas de cada sección se hizo uso de las propiedades grid-template-rows y grid-template-columns, conjuntamente con las fracciones de espacio disponible de contenedores de cuadrícula (fr), prefabricando el esqueleto base de la grilla; mientras que, como último apunte, se generaron estilos personalizados para esta última a través de propiedades como lo son border-radius, background-color, entre otras (así como una intrínseca de las configuraciones grid: gap).