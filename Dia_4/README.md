# Formulario

En este proyecto se trabajó el uso de HTML + CSS, más específicamente del uso de formularios y entradas de diferentes tipos, de manera que se creó un sistema de llenado de información que debe cumplir ciertos requeimientos para poder ser enviados (aclaración: este fomulario no es funcional, es meramente estético).

|Tabla de contenidos|
|--|
|[¿Cómo ejecutar este archivo?](#Ejecucion)|
|[Funcionamiento del programa](#Funcionamiento)|

<a name="Ejecucion"></a>

## ¿Cómo ejecutar este archivo?

Para poder observar la página web creada en este proyecto se puede realizar de dos maneras diferentes:

1. Accediendo directamente a través de este link: https://dante-sal.github.io/HTML_S1_SalamancaDante/Dia_4/
2. Clonando el repositorio desde una terminal linux a través del comando `git clone https://github.com/Dante-Sal/HTML_S1_SalamancaDante`, accediendo a la ruta HTML_S1_SalamancaDante/Dia_4/ y abriendo el archivo index.html con el navegador web de su preferencia.

<a name="Funcionamiento"></a>

## Funcionamiento del programa

En esencia, el funcionamiento de este programa se basa en la inicialización de un elemento de tipo form con diferentes inputs en su interior, dependiendo de los requerimientos precisados. Por un lado tenemos los elementos de tipo texto, que admiten cualquier entrada que el usuario ingrese (sumándole además una longitud máxima de 50 caracteres con el atributo maxlength para las casillas correspondientes para nombres y apellidos). En segundo lugar, se declararon dos inputs de tipo radio, asignados al mismo nombre (name), haciéndolos mutuamente excluyentes, además de sumarles un label que muestra los textos informativos sobre qué representa cada radio. Por otra parte, se crearon una entrada de tipo email (sólo admite emails), dos entradas de tipo checkbox (estando la primera checada automáticamente con el atributo checked) y una entrada de tipo submit que permitiría enviar los datos ingresados si se hubiera hecho funcional el formulario.

Finalmente, se agregó un elemento de tipo select (con varios objetos de tipo option que representan las cuatro poblaciones posibles y el texto predeterminado "Selecciona una población") y un elemento de tipo textarea con un alto y ancho definidos por los atributos rows y cols, respectivamente (textarea permite escribir textos multilínea). Como última medida se vinculó un archivo css y se centró el formulario, obteniendo el resultado final.