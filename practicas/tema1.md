# Ejercicios

# **Ejercicio 1.**

### **Queremos guardar la información de un vehículo (tipo, marca, modelo y color). Crea un archivo de texto y pon los datos de un coche, moto u otro vehículo.**

![Ejercicio1.png](Ejercicios%20b3d6f7476bc249c3ac803365bcd8a56c/Ejercicio1.png)

# Ejercicio 2.

### **Un pequeño restaurante requiere guardar una carta con los productos que tiene. Crea un archivo de texto y escribe la información de 5 platos.**

![Untitled](Ejercicios%20b3d6f7476bc249c3ac803365bcd8a56c/Untitled.png)

# Ejercicio 3.

### Necesitamos guardar en un archivo de texto un pequeño con formato (con un título, un subtítulo y una lista). Crea un archivo de texto plano que contenga la siguiente información:

## **Título principal**

### **Subtítulo**

- item 1
- item 2

# Ejercicio 4.

### ¿Crees que es fácil de procesar por un programa informático la información escrita en los ejercicios anteriores? Justifica tu respuesta.

Sí, son un conjunto de tablas sencillas además de un simple título, subtítulo y texto común.

# Ejercicio 5.

### Busca información y explica de qué se trata el W3C y cita empresas que formen parte.

El W3C es una organización internacional que se dedica a desarrollar estándares y recomendaciones técnicas para la World Wide Web (WWW) con el objetivo de garantizar su crecimiento a largo plazo y su accesibilidad universal. 

Algunas de las principales actividades y estándares desarrollados por el W3C incluyen:

1. **HTML** 
2. **CSS** 
3. **Web Accessibility Initiative (WAI)**
4. **Web Security**
5. **Web of Things (WoT**
6. **Web Payments**

Empresas que forman parte del W3C:

1. **Apple**
2. **Google**
3. **Microsoft**
4. **Mozilla**
5. **IBM**
6. **Facebook**

# Ejercicio 6.

### Busca en qué consisten la Web 1.0, 2.0, 3.0, 4.0 y 5.0. Pon un ejemplo para diferenciar cada una de ellas.

**Web 1.0**:

La Web 1.0 se refiere a los primeros días de la web, cuando la mayoría de los sitios web eran estáticos y de lectura única. Los usuarios podían acceder a información en línea, pero la interacción era limitada. Los sitios web eran principalmente informativos y no permitían la participación activa del usuario.

**Web 2.0**:

La Web 2.0 introdujo la interactividad y la participación de los usuarios. Los sitios web permitían a los usuarios generar y compartir contenido, como redes sociales, blogs, wikis y plataformas de colaboración. La Web 2.0 se caracteriza por la creación de comunidades en línea y la colaboración entre usuarios.

**Web 3.0**:

La Web 3.0, también conocida como "Web semántica", se centró en hacer que la web fuera más inteligente y significativa. En esta etapa, las máquinas comenzaron a comprender el contenido web y a ofrecer resultados más personalizados y contextuales. Se esperaba que los datos estuvieran más estructurados y se pudieran utilizar para crear experiencias web más inteligentes.

**Web 4.0**:

 La Web 4.0 es una idea que se ha discutido pero no se ha implementado completamente. Se relaciona con la integración más profunda de tecnologías como la inteligencia artificial, la realidad virtual y aumentada, y la Internet de las cosas en la web. Se espera que la web se convierta en un entorno altamente inmersivo y conectado.

**Web 5.0**:

 La Web 5.0 es una etiqueta aún más especulativa y futurista. Se relaciona con la posible simbiosis entre la tecnología y la biología, donde la web podría estar conectada a la mente humana de alguna manera. Esta etapa está más allá de las tendencias tecnológicas actuales y aún no se ha materializado.

# Ejercicio 7.

### Realiza archivos XML teniendo en cuenta el enunciado de los ejercicios 1 y 2.

```xml
<?xml version="1.0" encoding="UTF-8" standalone="no"?>
<vehiculos>
    <vehiculo>
        <tipo>Coche</tipo>
        <marca>SEAT</marca>
        <modelo>Aroma</modelo>
        <color>Gris</color>
    </vehiculo>
    <vehiculo>
        <tipo>Coche</tipo>
        <marca>SEAT</marca>
        <modelo>Exeo</modelo>
        <color>Rojo</color>
    </vehiculo>
</vehiculos>
```

```xml
<?xml version="1.0" encoding="UTF-8" standalone="no"?>
<menu>
    <plato>
        <nombre>Arroz picante</nombre>
        <precio>8,50€</precio>
    </plato>
    <plato>
        <nombre>Arroz con Kefta</nombre>
        <precio>9€</precio>
    </plato>
    <plato>
        <nombre>Pollo a lo marroqui</nombre>
        <precio>11€</precio>
    </plato>
    <plato>
        <nombre>Cuscus de pollo</nombre>
        <precio>13€</precio>
    </plato>
    <plato>
        <nombre>Chuleton de cordero</nombre>
        <precio>10€</precio>
    </plato>
</menu>
```

# Ejercicio 8.

### Visita una página web y visualiza su html pulsando click derecho y haciendo uso de la opción que diga “Ver código fuente” o similar (dependerá del navegador utilizado). Haz una captura del navegador cuando se muestre e intenta explicar el código que ves.

![Untitled](Ejercicios%20b3d6f7476bc249c3ac803365bcd8a56c/Untitled%201.png)

Muestra un código HTML con todas las etiquetas necesarias para que muestre la página tal y como es, además de un apartado de estilos css.

# Ejercicio 9.

### Copia el XML y el HTML de la diapositiva anterior para crear dos archivos libro.xml y libro.html. Abrelos en el navegador para ver el resultado y realiza una captura.

![Ejercicio9-2.png](Ejercicios%20b3d6f7476bc249c3ac803365bcd8a56c/Ejercicio9-2.png)

![Ejercicio9.png](Ejercicios%20b3d6f7476bc249c3ac803365bcd8a56c/Ejercicio9.png)

# Ejercicio 10.

### ¿Cuál de las siguientes líneas es la correcta?
Justifica tu respuesta

a) **<i>Texto en cursiva</i>**
b) <I>Texto en cursiva<I>
c) <i>Texto en cursiva
d) <i>Texto en cursiva<i>
e) Todas las anteriores

Toda etiqueta que se abre debe cerrarse.

# Ejercicio 11.

### Realiza archivos JSON teniendo en cuenta el enunciado de los ejercicios 1 y 2. Como guía puedes utilizar la imagen de la diapositiva anterior

```json
{ "vehiculos" :
    {
        "vehiculo" : [
            {
                "tipo" : "Coche",
                "marca" : "SEAT",
                "modelo" : "Aroma",
                "color" : "Gris"
            },
            {
                "tipo" : "Coche",
                "marca" : "SEAT",
                "modelo" : "Exeo",
                "color" : "Rojo"
            }
        ]
    }

}
```

```json
{ "menu" :
    {
        "plato" : [
            {
                "nombre" : "Arroz picante",
                "precio" : "8,50€"
            },
            {
                "nombre" : "Arroz con Kefta",
                "precio" : "9€"
            },
            {
                "nombre" : "Pollo a lo marroqui",
                "precio" : "11€"
            },
            {
                "nombre" : "Cuscus de pollo",
                "precio" : "13€"
            },
            {
                "nombre" : "Chuleton de cordero",
                "precio" : "10€"
            }
        ]
    }

}
```

# Ejercicio 12.

### Realiza un archivo Markdown teniendo en cuenta el enunciado del ejercicio 3. Para ello utilizaremos la web [https://stackedit.io/](https://stackedit.io/)

![Ejercicio12.png](Ejercicios%20b3d6f7476bc249c3ac803365bcd8a56c/Ejercicio12.png)

# Ejercicio 13.

### Teniendo en cuenta tu respuesta inicial a los ejercicios 1, 2 y 3, así como las posteriores versiones en distintos lenguajes de marcas. Reflexiona acerca de la importancia de utilizar lenguajes de marcas para representar la información.

Los lenguajes de marcas son una herramienta que nos  facilitan la representación, transmisión y presentación de datos , lo que es fundamental para la comunicación, la colaboración y el procesamiento de información, desde la web hasta la gestión de datos de empresa.

# Ejercicio 14.

### Para crear un documento HTML es necesario:

a) Software especializado para la tecnología HTML.
b) Herramientas de validación.
**c) Un block de notas y un navegador.**
d) Al menos, un editor HTML.

# Ejercicio 15.

### Realiza un búsqueda sobre los editores de código más utilizados para escribir en cada uno de los lenguajes de marcas vistos. Crea un documento en Markdown donde describas al menos 5.

```markdown
## HTML
- Visual Studio Code (VS Code)
- Sublime Text
- Atom

## XML
- Notepad+
- Oxygen XML Editor

## Markdown

- Typora
- Visual Studio Code (VS Code)
- StackEdit
```