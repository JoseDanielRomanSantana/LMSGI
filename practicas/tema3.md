# Ejercicios

# Ejercicio 1.

**El elemento HTML sobre el que se aplica un estilo se especifica:**
**A) En etiquetas, es decir, entre < y >.
B) Entre paréntesis.
C) Entre llaves.
D) No va encerrado entre signos.**

# Ejercicio 2.

**Vamos a crear un fichero llamado primercss.html y en el head declaramos una estructura como la siguiente:**
<style type=“text/css”>
#alinear {
text-align: center;
}
</style>
Una vez declarada, en el body, realizamos un HTML o copiamos el del ejercicio anterior.
Por último, le aplicamos a nuestro elementos los estilos de la siguiente forma:
<div id="alinear"> ... </div>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>primercss.html</title>
    <style type=“text/css”>
        #alinear {
        text-align: center;
        }
    </style>
</head>
<body>
    <head>
        <title>Ejemplo de estilos CSS en los elementos</title>
    </head>
    <h3 style="color: green;">
        Ejemplo del uso de estilos CSS en los elementos
    </h3>
    <div id="alinear">
        <p style="color: orange; font-family: Verdana;">En esta ocasión el
        párrafo de texto aparece de color naranja y el encabezado h3 aparece en
        verde, mientras que en los ejemplos vistos hasta ahora el color de la letra            era negro.</p>
    </div>
</body>
</html>
```

# Ejercicio 3.

**Prueba los ejemplos sobre las distintas formas de aplicar estilos, copiándolos tal cual aparecen.**

```html
<!DOCTYPE html>
<html>
	<head>
		<title>Ejemplo de estilos CSS en fichero externo</title>
		<link rel=“stylesheet” type=“text/css” href=“formatos.css” />
	</head>
<body>
	<h3>Ejemplo del uso de estilos CSS en fichero externo</h3>
	<p>En esta ocasión el párrafo de texto aparece de color
		 naranja y el encabezado h3 aparece en verde, mientras que en los ejemplos
		 vistos hasta ahora el color de la letra era negro. </p>
</body>
</html>
```

```css
h3 {
	color: green;
}
p { 
	color:orange; 
	font-family: Verdana; 
}
```

# Ejercicio 4.

**El mejor modo de aplicar formatos a una página web es:**
**A) Definiendo los formatos directamente a través de los atributos de los
elementos HTML.
B) Incluyendo el formato CSS en los elementos de HTML.
C) Definiendo los estilos en la cabecera del documento HTML.
D) Definiendo un fichero CSS externo.**

# Ejercicio 5.

**Busca cuales fueron los primeros navegadores mutilizados en masa y porque a día de hoy ya no existen.**

1. **WorldWideWeb (Nexus):** Lanzado por Tim Berners-Lee en 1990, este fue el primer navegador web.
2. **Mosaic:** Lanzado en 1993, Mosaic fue uno de los primeros navegadores gráficos ampliamente utilizados.
3. **Netscape Navigator:** Lanzado en 1994, fue uno de los primeros navegadores comerciales. 

# Ejercicio 6.

**Indaga en internet la historia de alguno de los navegadores presentes en la gráfica siguiente.**

Google Chrome es un navegador web desarrollado por Google.

1. **Lanzamiento Inicial (2008):** Google Chrome fue presentado como un navegador web rápido y ligero, diseñado para proporcionar una experiencia de navegación más eficiente. Introdujo una interfaz de usuario minimalista con pestañas independientes y un motor de renderizado llamado Blink.
2. **Rápida Adopción:** Gracias a su velocidad y diseño, Google Chrome ganó rápidamente popularidad y superando a otros navegadores como Internet Explorer y Mozilla Firefox.
3. **Extensiones y Aplicaciones:** Google Chrome introdujo el soporte para extensiones en 2010, permitiendo a los desarrolladores crear complementos que mejoraran la funcionalidad del navegador. 
4. **Actualizaciones Constantes:** Google ha mantenido un ciclo de actualizaciones frecuentes para Chrome, introduciendo nuevas funciones y mejorando la seguridad y el rendimiento de manera regular.
5. **Domina el Mercado:** A lo largo de los años, Google Chrome ha llegado a dominar el mercado de navegadores, siendo el navegador más utilizado a nivel mundial.

# Ejercicio 7.

**Realiza una comparación entre los motores de los principales navegadores web actuales, vistos en la tabla anterior.**

# Ejercicio 8.

**Busca en Can I use las siguientes propiedades y su soporte en los principales navegadores:**

- **CSS Masks**

![Untitled](Ejercicios%20285544e8ac7a4daa9c362b691f25ad93/Untitled.png)

- **CSS zoom**

![Untitled](Ejercicios%20285544e8ac7a4daa9c362b691f25ad93/Untitled%201.png)

- **CSS resize property**

![Untitled](Ejercicios%20285544e8ac7a4daa9c362b691f25ad93/Untitled%202.png)

# Ejercicio 9.

**Actualmente se está en proceso de abandonar los vendor prefixes en favor de los flags del navegador. Explica en qué consiste este cambio y su motivo.**

# Ejercicio 10.

**Reproduce y estila el siguiente HTML, para que el encabezado este alineado al centro y sea de color azul.**

```css
h1{
    color: blue;
    text-align: center;
}
```

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./estilo.css">
    <title>Ejercicio 10</title>
</head>
<body>
    <h1>Este es un encabezade de nivel 1.</h1>
    <hr>
    <h6>Pero este otro es de nivel 6</h6>
    <hr>
        <p>
            Ahora  voy a definir un párrafo. Dentro del que pondremos texto en <b>negrita</b>, <i>cursiva</i>,<u>subrayada</u> e incluso <b><u>negrita
            y subrayada</u></b> simultaneamente y <b><i><u>negrita, cursiva y subrayada,</u></i></b> mediante el anidamiento de etiquetas. Además
            vamos a mostrar el uso de <sub>subindices</sub> y de <sup>superindices</sup>, asi como <strong>texto resaltado, que no es negrita.</strong> 
        </p>
</body>
</html>
```

# Ejercicio 11.

**Utilizando los id, estila el tercer encabezado con un color de fondo amarillo y letra roja**.

```css
#encabezadoEditado{
    background-color: yellow;
    color: red;
}
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./estilo.css">
    <title>Ejercicio 11</title>
</head>
<body>
    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejercicio 12</title>
</head>
<body>
    <h2>Ejemplo de lista desordenada: Módulos de 1º de DAW</h2>
        <ul>
            <li>Lenguaje de Marcas</li> 
            <li>Base de Datos</li>
        </ul> 
    <h2>Ejemplo de lista ordenada: Módulos de 1º de DAW</h2>
        <ol>
            <li>Lenguaje de Marcas</li> 
            <li>Base de Datos</li> 
        </ol>
    <h2 id="encabezadoEditado">Ejemplo de lista definición: Módulos de 1º de DAW</h2>
        <dt>Lenguaje de Marcas</dt>
            <dd>HTML, CSS, XML, etc.</dd>
        <dt>Base de datos</dt>
            <dd>Diseño y uso de bases de datos relacionales</dd>
</body>
</html>
```

# Ejercicio 12.

**Estila de color verde todas las listas con la clase "letra" y de gris todas las de la clase "numero"**

```css
.letra{
    color: green;
}
.numero{
    color: gray;
}
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./estilo.css">
    <title>Ejrecicio 12</title>
</head>
<body>
    <ol class="numero">
        <li>DAW</li>
        <li>DAM</li>
        <li>ASIR</li>
    </ol>
    <ol class="numero" start="100">
        <li>DAW</li>
        <li>DAM</li>
        <li>ASIR</li>
    </ol>
    <ol class="letra" type="A">
        <li>DAW</li>
        <li>DAM</li>
        <li>ASIR</li>
    </ol>
    <ol class="letra" type="a">
        <li>DAW</li>
        <li>DAM</li>
        <li>ASIR</li>
    </ol>
    <ol class="numero" type="I">
        <li>DAW</li>
        <li>DAM</li>
        <li>ASIR</li>
    </ol>
    <ol class="numero" type="i">
        <li>DAW</li>
        <li>DAM</li>
        <li>ASIR</li>
    </ol>
    <ul>
        <li type="square">DAW</li>
        <li type="circle">DAM</li>
        <li type="square">ASIR</li>
    </ul>
</body>
</html>
```

# Ejercicio 13.

**Cambia el color y la fuente del siguiente HTML para todo el documento**.

```css
body{
    color: cadetblue;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./estilo.css">
    <title>Ejercicio 13</title>
</head>
<body>
    <h1>Los encabezado son elementos de bloque.</h1>
    <p>Y los párrafos también</p>
    <p><a href="">Los enlaces son elementos de línea</a></p>
    <p>Incluso si esta definido dento de un párrafo, <b>un texto en negrita</b> sigue siendo un elemento en línea.</p>
</body>
</html>
```

# Ejercicio 14.

**Pinta del color que prefieras el de fondo de los encabezados y el pie de la tabla.**

```css
td.primerEncabezado{
    background-color: aquamarine;
}
td.segundoEncabezado{
    background-color: rgb(97, 97, 247);
}
td.encabezadoNacionales{
    background-color: rgb(8, 223, 8);
}
td.encabezadoImportados{
    background-color: yellow;
}
.cuerpo{
    background-color: bisque;
}
.piePagina{
    background-color: cadetblue;
}
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="./estilo.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejercicio 14</title>
</head>
<body>
    <table border="!">
     <thead>
        <tr>
            <td colspan="1" rowspan="3"></td>
            <td colspan="6" class="primerEncabezado">Ventas coches</td>
        </tr>
        
        <tr>
            <td colspan="2" class="segundoEncabezado">1 trimestre</td>
            <td colspan="2" class="segundoEncabezado">2 trimestre</td>
            <td colspan="2" class="segundoEncabezado">3 trimestre</td>
        </tr>
        <tr>
            <td class="encabezadoNacionales">Nacionales</td>
            <td class="encabezadoImportados">Importados</td>
            <td class="encabezadoNacionales">Nacionales</td>
            <td class="encabezadoImportados">Importados</td>
            <td class="encabezadoNacionales">Nacionales</td>
            <td class="encabezadoImportados">Importados</td>
        </tr>
    </thead>
    <tbody class="cuerpo">
        <tr>
            <td>Año 2020</td>
            <td>341</td>
            <td>561</td>
            <td>234</td>
            <td>129</td>
            <td>340</td>
            <td>261</td>
        </tr>
        <tr>
            <td>Año 2021</td>
            <td>341</td>
            <td>561</td>
            <td>234</td>
            <td>129</td>
            <td>340</td>
            <td>261</td>
        </tr>
        <tr>
            <td>Año 2022</td>
            <td>341</td>
            <td>561</td>
            <td>234</td>
            <td>129</td>
            <td>340</td>
            <td>261</td>
        </tr>
        <tr>
            <td>Año 2023</td>
            <td>741</td>
            <td>263</td>
            <td>721</td>
            <td>841</td>
            <td>590</td>
            <td>251</td>
        </tr>
    </tbody>
    <tfoot class="piePagina">
        <tr>
            <td>Total</td>
            <td>1082</td>
            <td>824</td>
            <td>955</td>
            <td>970</td>
            <td>930</td>
            <td>512</td>
        </tr>
    </tfoot>
    </table>
</body>
</html>
```

# Ejercicio 15.

**Realiza un HTML y CSS cuyo resultado sea lo más parecido posible al siguiente:**

```css
p{
    border-width: 4px;
    border-style: solid;
    border-color: red;
    padding: 25px;
    margin-left: 30%;
    margin-right: 30%;
    text-align: center;
}

#primerParrafo{
    background-color: lightgreen;
}
#segundoParrafo{
    background-color: #ddaefa;
}
#tercerParrafo{
    background-color: rgb(155, 55, 128);
    color: white;
}
#cuartoParrafo{
    background-color: hsl(60, 22%, 50%);
    color: white;
    
}
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./estilo.css">
    <title>Ejercicio 15</title>
</head>
<body>
    <p id="primerParrafo">background-color: lightgreen;</p>
    <p id="segundoParrafo">background-color: #ddaefa;</p>
    <p id="tercerParrafo">background-color: rgb(155, 55, 128);</p>
    <p id="cuartoParrafo">background-color: hsl(60, 22%, 50%);</p>
</body>
</html>
```

# Ejercicio 16.

**Realiza pruebas en HTML y CSS con una imagen cuadrada para obtener resultados parecidos a los siguientes:**

```css
body{
    background-image: url(./img/ejercicio16.jpeg);
    background-repeat: no-repeat;
    background-position: left top;
}
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./estilo-sinRepeticiones.css">
    <title>Ejercicio 16</title>
</head>
<body>
    <h2>Sin repeticiones</h2>
</body>
</html>
```

```css
body{
    background-image: url(./img/ejercicio16.jpeg);
    background-repeat:repeat-y;
    background-position: left top;
}
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./estilo-repeticionesVerticales.css">
    <title>Ejercicio 16</title>
</head>
<body>
    <h2>Repeticiones Verticales</h2>
</body>
```

```css
body{
    background-image: url(./img/ejercicio16.jpeg);
    background-repeat:repeat-y;
    background-position: left top;
}
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./estilo-todasRepeticiones.css">
    <title>Ejercicio 16</title>
</head>
<body>
    <h2>Todas repeticiones</h2>
</body>
</html>
```

# Ejercicio 17.

**Realiza un HTML y CSS cuyo resultado sea lo más parecido posible al siguiente:**

```css
#punteado{
    border-style: dotted;
}
#guiones{
    border-style:dashed ;
}
#solido{
    border-style: solid;
}
#doble{
    border-style: double;
}
#interno{
    border-style: inset;
}
#externo{
    border-style: outset;
}
#sinBorde{
    border-style: none;
}
#escondido{
    border-style: hidden;
}
#mixto{
    border-style: dotted dashed solid double ;
}
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./estilo.css">
    <title>Ejercicio 17</title>
</head>
<body>
    <p id="punteado">Un vorde punteado.</p>
    <p id="guiones">Un borde con guiones.</p>
    <p id="solido">Un borde solido.</p>
    <p id="doble">Un borde doble.</p>
    <p id="interno">Un borde interno.</p>
    <p id="externo">Un borde externo.</p>
    <p id="sinBorde">Sin borde.</p>
    <p id="escondido">Un borde escondido.</p>
    <p id="mixto">Un borde mixto.</p>
</body>
</html>
```

# Ejercicio 18.

**Realiza un HTML y CSS cuyo resultado sea lo más parecido posible al siguiente:**

```css
.parrafoRojo{
    border-style: solid ;
    border-color: red;
}
.parrafoVerde{
    border-style: solid ; 
    border-color: green;
    border-width: 2px;
}
.parrafoAzul{
    border-style: dotted;
    border-color: blue;
    border-width: 4px;
}
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./estilo.css">
    <title>Ejercicio 18</title>
</head>
<body>
    <p class="parrafoRojo">Un borde solido rojo sin ancho</p>
    <p class="parrafoVerde">Un borde solido verde con 2px</p>
    <p class="parrafoAzul">Un borde punteada azul con 4px</p>
</body>
</html>
```

# Ejercicio 19.

**Redondea de la manera que prefieras los bordes implementados en el ejercicio anterior
(haz una copia).**

```css
.parrafoRojo{
    border-style: solid ;
    border-color: red;
    border-radius: 10px;
}
.parrafoVerde{
    border-style: solid ; 
    border-color: green;
    border-width: 2px;
    border-radius: 10px;
}
.parrafoAzul{
    border-style: dotted;
    border-color: blue;
    border-width: 4px;
    border-radius: 10px;
}
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./estilo.css">
    <title>Ejercicio 18</title>
</head>
<body>
    <p class="parrafoRojo">Un borde solido rojo sin ancho</p>
    <p class="parrafoVerde">Un borde solido verde con 2px</p>
    <p class="parrafoAzul">Un borde punteada azul con 4px</p>
</body>
</html>
```

# Ejercicio 20.

**Utiliza la forma abreviada de expresar los bordes sobre una copia del ejercicio 18.**

```css
.parrafoRojo{
    border-radius: 10px;
    border: solid red;
}
.parrafoVerde{
    border-radius: 10px;
    border: solid green 2px;
}
.parrafoAzul{
    border-radius: 10px;
    border: dotted blue 4px;
}
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./estilo.css">
    <title>Ejercicio 18</title>
</head>
<body>
    <p class="parrafoRojo">Un borde solido rojo sin ancho</p>
    <p class="parrafoVerde">Un borde solido verde con 2px</p>
    <p class="parrafoAzul">Un borde punteada azul con 4px</p>
</body>
</html>
```

# Ejercicio 21.

**Implementa un HTML y CSS para lograr un resultado lo más parecido posible al siguiente:**

```css
h1{
    text-decoration: overline red;
}
h2{
    text-decoration: line-through blue;
}
h3{
    text-decoration: underline green 2px;
}
h4{
    text-decoration: overline underline purple 2px;
}
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./estilo.css">
    <title>Ejercicio 21</title>
</head>
<body>
    <h1>Overline text decoration</h1>
    <h2>Line through text decoration</h2>
    <h3>Underline text decoration</h3>
    <h4>Overline and underline text decoration</h4>
</body>
</html>
```

# Ejercicio 22.

**Utiliza las propiedades de fuente vistas en una copia del ejercicio anterior.**

```css
*{
		font-style: italic;
    font-weight: bold;
    font-size: 16pt;
}

h1{
    text-decoration: overline red;
}
h2{
    text-decoration: line-through blue;
}
h3{
    text-decoration: underline green 2px;
}
h4{
    text-decoration: overline underline purple 2px;
}
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./estilo.css">
    <title>Ejercicio 21</title>
</head>
<body>
    <h1>Overline text decoration</h1>
    <h2>Line through text decoration</h2>
    <h3>Underline text decoration</h3>
    <h4>Overline and underline text decoration</h4>
</body>
</html>
```