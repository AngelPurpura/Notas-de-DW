# Conceptos básicos de DW

## DOM

El DOM modelo de documento que se carga en el navegador web y que representa el documento como un árbol de nodos.

#### insertar imagen del tree

## HTML

HTML tiene la sintaxys basada en etiquetas, de tal manera qué, en general se escribe

```markup
<nombre> contenido </nombre>
```

Aun qué no todas las etiquetas funcionan de la misma manera algunas etiquetas se cierran en sí misma. Y otras necesitan ciertos atributos para funcionar. De manera general:

```markup
<nombre atributo='valor del atributo' />
```

Cada etiqueta tiene un uso distinto, para consultar que etiqueta usar y en que ocasión podemos visitar la pag [http://html5doctor.com](http://html5doctor.com) o [https://allthetags.com](https://allthetags.com)

Las etiquetas más basicas serán descritas aquí

### HTML 5 standar

```markup
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>

</body>
</html>
```

### Para qué sirve cada etiqueta?

| Etiqueta | Uso |
| :--- | :--- |
| &lt; !DOCTYPE html &gt; | Indica al navegador que vamos a usar html 5 |
| &lt; html &gt; | Dentro de esta etiqueta ira todo el contenido html |
| &lt; head &gt; | Aqui van contenidos los metadatos y información que no sera visible en el cuerpo de la pag |
| &lt; meta atri=" " &gt; | Aqui especificamos los metadatos |
| &lt; title &gt; | Aqui ponemos el titulo que se vera en la pestaña del navegador |
| &lt; body &gt; | Aqui va todo el contenido que se vera dentro del navegador |

