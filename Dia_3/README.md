# Hoja de Vida

En este proyecto se trabajó el uso de HTML + CSS, más específicamente del uso de tablas y sus diferentes funciones, de manera que se creó un sistema de columnas que permitieron almacenar diferentes tipos de datos como texto, listas o imágenes.

|Tabla de contenidos|
|--|
|[¿Cómo ejecutar este archivo?](#Ejecucion)|
|[Funcionamiento del programa](#Funcionamiento)|

<a name="Ejecucion"></a>

## ¿Cómo ejecutar este archivo?

Para poder observar la página web creada en este proyecto se puede realizar de dos maneras diferentes:

1. Accediendo directamente a través de este link: https://dante-sal.github.io/HTML_S1_SalamancaDante/D%C3%ADa_3/
2. Clonando el repositorio desde una terminal linux a través del comando `git clone https://github.com/Dante-Sal/HTML_S1_SalamancaDante`, accediendo a la ruta HTML_S1_SalamancaDante/Día_3/ y abriendo el archivo index.html con el navegador web de su preferencia.

<a name="Funcionamiento"></a>

## Funcionamiento del programa

En esencia, el funcionamiento de este programa se basa en la creación de tablas, filas, columnas y elementos dentro de estas. En un inicio se crearon 3 filas que contendrían diferentes cantidades de elementos, dependiendo de lo que la hoja de vida requiriera.

En el caso de la primera fila, se precisó de tres elementos que, dadas las características de la tabla, se dispusieron horizontalmente; siendo el segundo y tercer elementos, celdas que precisaron del uso del atributo rowspan para expandir su alcance a más filas (dado su amplio contenido).

En el caso de la segunda fila, se precisó de un único elemento con rowspan de 1, teniendo en cuenta que los espacios donde deberían estar las celdas 2 y 3 de esta fila se encuentran ocupados por el uso de rowspan en las celdas 2 y 3 de la fila 1.

Finalmente, en el caso de la tercera fila, se precisó de dos elementos (celdas 1 y 2), dada la propiedad rowspan de la celda 3 de la fila 1, que ocupó el espacio correspondiente en la fila 3.

Como última medida, se le asignaron propiedades de formato a las celdas e imágenes mediante el uso de un archivo .css que le permitió a la tabla adquirir las características específicas solicitadas (como el formato circular de la fotografía de la persona, las líneas que delimitan los diferentes elementos de la hoja de vida, entre otras).