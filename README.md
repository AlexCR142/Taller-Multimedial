# Taller-Multimedial

#### Exploracion creativa de arte y medios digitales onyeractivos.

#### Cultura web y arte digital

file:///Users/alumno/Desktop/alex%20correa/Taller-Multimedial-main/w/index.html

###Ejercicio 1 Semana 1:

```
<!DOCTYPE html>
<!-- Indica al navegador que este documento usa HTML5 -->

<html>
<!-- Inicio del documento HTML -->

<head>
<!-- Sección donde van metadatos, título y estilos -->

<meta charset="UTF-8">
<!-- Define la codificación de caracteres para que se vean bien tildes y símbolos -->

<title>Multimedial</title>
<!-- Título de la página que aparece en la pestaña del navegador -->

<style>
/* Aquí comienza la sección de estilos CSS que define la apariencia visual */

body{
/* "body" se refiere a todo el contenido visible de la página */

  background-color: cyan;
  /* Define que el fondo de toda la página sea blanco */

  color: purple;
  /* Define que el color del texto sea negro */

  margin: 0;
  /* Elimina los márgenes que los navegadores agregan por defecto */

  height: 100vh;
  /* Hace que el alto del cuerpo sea igual al 100% de la altura de la pantalla */

  display: flex;
  /* Activa el sistema Flexbox para organizar y centrar elementos */

  justify-content: center;
  /* Centra el contenido horizontalmente */

  align-items: center;
  /* Centra el contenido verticalmente */

  font-family: Arial, sans-serif;
  /* Define la tipografía del texto */

  font-size: 60px;
  /* Define el tamaño grande del texto */

}
/* Fin de las reglas de estilo del body */

</style>
<!-- Fin de la sección de estilos -->

</head>
<!-- Fin de la sección head -->

<body>
<!-- Inicio del contenido visible de la página -->

Taller Multimedial
<!-- Texto que aparece en el centro de la pantalla -->

</body>
<!-- Fin del contenido visible -->

</html>
<!-- Fin del documento HTML -->

```
### Semana 2

Visual Studio Codigo 

```
<!DOCTYPE html>
<!-- Indica al navegador que este documento usa HTML5 -->

<html>
<!-- Inicio del documento HTML -->

<head>
<!-- Sección donde van metadatos, título y estilos -->

<meta charset="UTF-8">
<!-- Define la codificación de caracteres para que se vean bien tildes y símbolos -->

<title>Multimedial</title>
<!-- Título de la página que aparece en la pestaña del navegador -->

<style>
/* Aquí comienza la sección de estilos CSS que define la apariencia visual */

body{
/* "body" se refiere a todo el contenido visible de la página */

  background-color: #743AF0;
  /* Define que el fondo de toda la página sea blanco */

  color: #5EF2E6;
  /* Define que el color del texto sea negro */

  margin: 0;
  /* Elimina los márgenes que los navegadores agregan por defecto */

  height: 100vh;
  /* Hace que el alto del cuerpo sea igual al 100% de la altura de la pantalla */

  display: flex;
  /* Activa el sistema Flexbox para organizar y centrar elementos */

  justify-content: center;
  /* Centra el contenido horizontalmente */

  align-items: center;
  /* Centra el contenido verticalmente */

  font-family: Arial, sans-serif;
  /* Define la tipografía del texto */

  font-size: 60px;
  /* Define el tamaño grande del texto */

}
/* Fin de las reglas de estilo del body */

</style>
<!-- Fin de la sección de estilos -->

</head>
<!-- Fin de la sección head -->

<body>
<!-- Inicio del contenido visible de la página -->

 Taller Multimedial
<!-- Texto que aparece en el centro de la pantalla -->

</body>
<!-- Fin del contenido visible -->

</html>
<!-- Fin del documento HTML -->

```

Pagina 1

```
<!DOCTYPE html>
<html lang="es">
<head>
 <meta charset="UTF-8">
<title>Mi sitio</title>
</head>

<body>

<h1>Página principal</h1>

<a href="pagina2.html">Ir a la segunda página</a>

</body>
</html>

```

Pagina 2

```
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Página 2</title>
</head>

<body>

<h1>Esta es la segunda página</h1>

<a href="index.html">Volver a la página principal</a>
<!--<a href="index.html" target="_blank">Volver a la página principal</a> -->

<!--<a href="https://www.wikipedia.org" target="_blank">Ir a Wikipedia</a> -->

</body>
</html>

```

### Semana 3

Llamar imagen desde archivo

```
<!DOCTYPE html>
<!-- Indica al navegador que este documento usa HTML5 -->

<html>
<!-- Inicio del documento HTML -->

<head>
<!-- Sección donde van metadatos, título y estilos -->

<meta charset="UTF-8">
<!-- Define la codificación de caracteres para que se vean bien tildes y símbolos -->

<title>Multimedial</title>
<!-- Título de la página que aparece en la pestaña del navegador -->

<style>
/* Aquí comienza la sección de estilos CSS que define la apariencia visual */

body{
/* "body" se refiere a todo el contenido visible de la página */

  background-color: #743AF0;
  /* Define que el fondo de toda la página sea blanco */

  color: #5EF2E6;
  /* Define que el color del texto sea negro */

  margin: 0;
  /* Elimina los márgenes que los navegadores agregan por defecto */

  height: 100vh;
  /* Hace que el alto del cuerpo sea igual al 100% de la altura de la pantalla */

  display: flex;
  /* Activa el sistema Flexbox para organizar y centrar elementos */

  justify-content: center;
  /* Centra el contenido horizontalmente */

  align-items: center;
  /* Centra el contenido verticalmente */

  font-family: Arial, sans-serif;
  /* Define la tipografía del texto */

  font-size: 60px;
  /* Define el tamaño grande del texto */

}
/* Fin de las reglas de estilo del body */

</style>
<!-- Fin de la sección de estilos -->

</head>
<!-- Fin de la sección head -->

<body>
<!-- Inicio del contenido visible de la página -->

 Taller Multimedial
<!-- Texto que aparece en el centro de la pantalla -->

<img src="img/img1.jpeg" alt="descripción" width="300">

</body>
<!-- Fin del contenido visible -->

</html>
<!-- Fin del documento HTML -->
```
### Semana 4

Bloques

Index:

```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Index</title>

    <style>
        /* Estilo general del cuerpo */
        body {
            font-family: Arial, sans-serif;
            background-color: #484b7c;
            margin: 0;
        }

        /* Contenedor principal */
        .contenedor {
            width: 80%;
            margin: auto;
        }

        /* Sección o bloque */
        .bloque {
            background-color: rgb(215, 225, 255);
            margin: 20px 0;
            padding: 20px;
            border-radius: 10px;
        }

        /* Imagen */
        .bloque img {
            width: 100%;
            height: auto;
        }

        /* Encabezado */
        .bloque h2 {
            margin-top: 10px;
            
        }

        /* Texto */
        .bloque p {
            line-height: 1.5;
        }
    </style>
</head>

<body>

    <!-- Contenedor principal -->
    <div class="contenedor">

        <!-- BLOQUE 1 -->
        <div class="bloque">
            <h1>Alex CorRami</h2>

<img src="img/img1.jpeg" alt="Tortuga">



            
            
        </div>

        <!-- BLOQUE 2 -->
        <div class="bloque">
            
          <a href="obra.html">Obra</a><br> 
            
        </div>

        <!-- BLOQUE 2 -->
        <div class="bloque">
            
         <a href="contacto.html">Contacto</a>  
            
        </div>
        </div>

</body>
</html>
```

Obras

```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Obras</title>

    <style>
        /* Estilo general del cuerpo */
        body {
            font-family: Arial, sans-serif;
            background-color: #484b7c;
            margin: 0;
        }

        /* Contenedor principal */
        .contenedor {
            width: 80%;
            margin: auto;
        }

        /* Sección o bloque */
        .bloque {
            background-color: rgb(215, 225, 255);
            margin: 20px 0;
            padding: 20px;
            border-radius: 10px;
        }

        /* Imagen */
        .bloque img {
            width: 100%;
            height: auto;
        }

        /* Encabezado */
        .bloque h2 {
            margin-top: 10px;
        }

        /* Texto */
        .bloque p {
            line-height: 1.5;
        }
    </style>
</head>

<body>

    <!-- Contenedor principal -->
    <div class="contenedor">

        <!-- BLOQUE 1 -->
        <div class="bloque">
            <h1>Mi obra</h1>



<a href="index.html">Inicio</a><br>
<a href="contacto.html">Contacto</a>

            
            </p>
        </div>

        <!-- BLOQUE 2 -->
        <div class="bloque">
            <img src="img/img1.jpeg" alt="Grabado Mantis">
            <h2>Título 1</h2>
            <p>
                Este es un texto de ejemplo. Aquí puedes escribir contenido descriptivo,
                reflexivo o informativo sobre la imagen.
            </p>
        </div>

        <!-- BLOQUE 3 -->
        <div class="bloque">
            <img src="img/img2.jpeg" alt="Mantis">
            <h2>Título 2</h2>
            <p>
                Otro texto que acompaña la imagen. Puedes trabajar narrativa,
                análisis visual o cualquier tipo de contenido.
            </p>
        </div>

        <!-- BLOQUE 4 -->
        <div class="bloque">
            <img src="img/img4.jpeg" alt="espejos">
            <h2>Título 3</h2>
            <p>
                Este es un tercer bloque. Puedes repetir esta estructura
                tantas veces como quieras.
            </p>
        </div>
         

    </div>

</body>
</html>

```


