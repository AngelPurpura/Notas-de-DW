# Conceptos báscios de css

## Reglas, selectores, declaraciones, propiedades y valores de css

Las reglas es la sintaxys con la que css modifica los estilos, estos estilos solo son aplicados al que el selector dicta. Los cambios estan escritos en una declaración, que esta conformada por una propiedad y el valor de esta propiedad.

Ejemplo de código de css:

```CSS
selector {
    propiedad: valor;
}
```
Existen varios tipos de selectores, el del ejemplo anterior se le llama selector de etiqueta, modifica a todos los objetos que el selector dicta. Los selectores desendentes afectan a los hijos de los selectores padres, por ejemplo, el selector *body header* afectara a *header* siempre y cuando este sea hijo de *body*. Por ultimo están los selectores de id y clase, estos selectores afectaran a todos las etiquetas de html cuyo id o clase corresponda, el selector de id comienza con *#*, y el de clase con *.* .

## Estilos del navegador

Por defecto el navegador le proporciona unos ciertos estilos a algunas etiquetas. Esto podria parecer sin importancia, pero el problema viene cuando cada navegador tiene sus propios estilos, en consecuencia, si no indicas todos los estilos que quieres en todas tus etiquetas, provocas que algún estilo de algún elemento se escoja a juicio del navegador. Si la experiencia de tu pagina web depende del navegador donde esta corra, entonces no tenemos control sobre la misma, y se pueden dar casos absurdos. Imaginemos que nuestra web tiene una mejor experiencia, en consecuencia de lo anterior dicho, en el navegador X, y una peor en el navegador Y. Supongamos que el navegador Y es más popular que el X, entonces, estariamos perdiendo visitas o ventas, o cual sea la intención de la web solo por qué el navegador Y lo ha 'decidido' así. La solución más simple es establecer unos estilos por defecto que se apliquen a todas las etiquetas, antes de que nosotros establescamos nuestros propios estilos. Utilzar normalize.css o reset.css soluciona el problema.

## Unidades de medida y colores
Una completa *y mejor* documentación del manejo de colores en css puede ser contrada en este link: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value. Para insertar colores en css existen 3 formas. La primera es usando alguna palabra reservada en css que ya indique algún color como "red, blue, transparent". Otra forma es usando hexadecimales como #FFFFFF o funciones como rgb(), rgba() y la ultima es usando valores de matrices, saturación y luminosidad con hls() hlsa().

La unidad de medida más extendia en el mundo digital es el píxel, se abrevia px. Sin embargo en css existen muchos más, por ejemplo em, rem, pt, fr, vw, vh.

## Propiedades para los textos

|Propiedad| Modifica|
|:---|:---|
|font-family|  el tipo de fuente|
|line-height | el alto de linea|
|font-size | el tamaño de la fuente|
|font-weight | el tipo de fuente|
|font-style | el estilo de la fuente|
|letter-spacing | el espacio entre letras|
|text-transform | Cambia a (mayusculas, minuculas, etc)|
|text-decoration |la decoración de la fuente|