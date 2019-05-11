#   DOM

El DOM modelo de documento que se carga en el navegador web y que representa el documento como un árbol de nodos.

### insertar imagen del tree

# HTML

HTML tiene la sintaxys basada en etiquetas, de tal manera qué, en general se escribe

```html
<nombre> contenido </nombre>
```
Aun qué no todas las etiquetas funcionan de la misma manera algunas etiquetas se cierran en sí misma. Y otras necesitan ciertos atributos para funcionar. De manera general:

```html
<nombre atributo='valor del atributo' />
```

Cada etiqueta tiene un uso distinto, para consultar que etiqueta usar y en que ocasión podemos visitar la pag http://html5doctor.com o https://allthetags.com

Las etiquetas más basicas serán descritas aquí

## HTML 5 standar

```html

<!DOCTYPE html>
<html lang="en">
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

## Para qué sirve cada etiqueta?

| Etiqueta | Uso |
|:---|:---|
| <!DOCTYPE html>  | Indica al navegador que vamos a usar html 5   |
| <html> | Dentro de esta etiqueta ira todo el contenido html |
| <head> | Aqui van contenidos los metadatos y información que no sera visible en el cuerpo de la pag |
| <meta atri="valor"> | Aqui especificamos los metadatos |
| <title> | Aqui ponemos el titulo que se vera en la pestaña del navegador |
| <body> | Aqui va todo el contenido que se vera dentro del navegador |