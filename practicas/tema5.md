# Ejercicios

# Ejercicio 1.

**Realiza un JSON para estructurar la información de la tabla siguiente:**

```json
{
    "libros":[
        {
     
            "Titulo" : "El programador pragmatico",
            "Autor" : "David Thomas y Andrew Hunt",
            "Año de publicacion" : "2022",
            "Editorial" : "Anaya Multimedia",
            "Paginas" : "339"
            
        },
        {
    
            "Titulo" : "Código Limpio",
            "Autor" : "Robert C. Martin",
            "Año de publicacion" : "2012",
            "Editorial" : "Anaya Multimedia",              
            "Paginas" : "463"
        
        },
        {
        
            "Titulo" : "Aprendiendo JavaScript",
            "Autor" : "Carlos Azaustre",                
            "Año de publicacion" : "2016",
            "Editorial" : "Publicacion independiente",
            "Paginas" : "99"
            
        }
    ]
}
```

# Ejercicio 2.

**Escribir un documento JSON que almacene la siguiente información:**

```json
{
    "ciudades":[
        {
            "Nombre" : "Ceuta",
            "Pais" : "España",
            "Continente" : "África",
            "Elevacion" : 10
            
        },
        {
            "Nombre" : "Mykonos",
            "Pais" : "Grecia",
            "Continente" : "Europa",
            "Elevacion" : null
            
        },
        {
            "Nombre" : "Pekin",
            "Pais" : "China",
            "Continente" : "Asia",
            "Elevacion" : 44
            
        },
        {
            "Nombre" : "Ciudad de Mexico",
            "Pais" : "Mexico",
            "Continente" : "America",
            "Elevacion" : 2240
            
        }
    ]
}
```

# Ejercicio 3.

**Escribir un documento JSON que almacene la siguiente información:**

```json
{ "hechos historicos":[
    {"Descripcion":"IBM da a conocel el PC", "fecha":{"dia":12, "mes":8, "año":1981}},
    {"Descripcion":"Se funda google", "fecha":{"dia":4, "mes":9, "año":1998}},
    {"Descripcion":"Se funda Facebook", "fecha":{"dia":4, "mes":2, "año":2004}},
    {"Descripcion":"Steve Jobs presenta el iPhone", "fecha":{"dia":29, "mes":6, "año":2007}}
]}
```

# Ejercicio 4.

**Crear un documento JSON que describauna lista de marcadores de páginas web, sabiendo que se desea que la información de cada página sea el nombre, una descripción breve y su URL. Los datos de los marcadores son los descritos en la siguiente tabla:**

```json
{ "marcadores":[
    {"Nombre":"MDN Web Docs", "Descripcion":"Resources for Developers, by Developers", "URL":"https://developer.mozilla.org/es/"},
    {"Nombre":"W3Schools", "Descripcion":"Learn to code", "URL":"https://www.w3schools.com"},
    {"Nombre":"Wikipedia", "Descripcion":"La enciclopedia libre", "URL":"https://es.wikipedia.org/"}
]}
```

# Ejercicio 5.

**Escribir un documento JSON que guarde información de dos equipos de fútbol (nombre, ciudad y entrenador) con dos jugadores (nombre, posición y nacionalidad) cada uno. Las posiciones posibles son (portero, defensa, medio, delantero). Utilizar datos reales para los equipos y jugadores. No obstante, no deberá indicarse el nombre del entrenador.**

```json
{ "equiposFutbol":[
        {
            "nombre":"Real Madrid CF", 
            "ciudad": "Madrid", 
            "entrenador":"Carlo Ancelotti", 
            "jugadores": [
                {
                "nombre": "Vinicius JR", 
                "nacionalidad":"Brasileño", 
                "posicion": "Delantero"
                },
                {
                "nombre": "Luka Modric", 
                "nacionalidad":"Croata", 
                "posicion": "Medio"
                }
            ]
        },
        {
            "nombre":"FC Barcelona", 
            "ciudad": "Barcelona", 
            "entrenador":"Jardinero Hernández", 
            "jugadores": [
                {
                "nombre": "Pedri", 
                "nacionalidad":"Español", 
                "posicion": "Medio"
                },
                {
                "nombre": "Gavi", 
                "nacionalidad":"Español", 
                "posicion": "Medio"
                }
            ]
        }
    ]}
```

# Ejercicio 6.

**XPath es un lenguaje XML que permite:**

**A) Transformar el formato de los datos de un fichero XML.
B) Definir un vocabulario que ha de cumplir un documento XML.
C) Obtener los datos del fichero XML de una base de datos.
D) Acceder a los datos de un fichero XML.**

# Ejercicio 7.

**Indica cuáles de los siguientes elementos de un documento XML pueden ser nodos del mismo:
A) Atributos.
B) Comentarios.
C) Etiquetas.
D) Texto.**

# Ejercicio 8:

**Realiza una expresión de XPath para quedarte con el nombre de los alumnos**

![Untitled](Ejercicios%20ae87a85a12504edba1a20f71720d775e/Untitled.png)

# Ejercicio 9:

**Realiza una expresión de XPath para quedarte con todos los alumnos**

![Untitled](Ejercicios%20ae87a85a12504edba1a20f71720d775e/Untitled%201.png)

# Ejercicio 10:

 **Realiza una expresión de XPath para seleccionar el cuarto deportista.**

![Untitled](Ejercicios%20ae87a85a12504edba1a20f71720d775e/Untitled%202.png)

# Ejercicio 11:

**Realiza una expresión de XPath para seleccionar a Alonso.**

![Untitled](Ejercicios%20ae87a85a12504edba1a20f71720d775e/Untitled%203.png)

# Ejercicio 12.

**Relaciona los ejes siguientes con sus equivalentes:**

**A) child::
B) descendant::
C) attribute::
D) parent::**

1. **@**
2. **/**
3. **//**
4. **..**

# Ejercicio 13.

**Partiendo del xml visto en ejercicios anteriores, realiza una expresión con predicado que seleccione sólo los profesores que tengan un elemento <nombre> como hijo de <profesor>:**

![Untitled](Ejercicios%20ae87a85a12504edba1a20f71720d775e/Untitled%204.png)

# **Ejercicio 14.**

**Partiendo del xml visto en ejercicios anteriores, realiza una expresión con predicado para obtener los profesores que se llamen “Elena”:**

![Untitled](Ejercicios%20ae87a85a12504edba1a20f71720d775e/Untitled%205.png)

# Ejercicio 15.

**Partiendo del xml visto en ejercicios anteriores, realiza una expresión con predicado para obtener el apellido de la profesora que se llama “Elena"**

![Untitled](Ejercicios%20ae87a85a12504edba1a20f71720d775e/Untitled%206.png)

# Ejercicio 16.

**Partiendo del xml visto en ejercicios anteriores, realiza una expresión con predicado para obtener el profesor que tiene el atributo especialidad en "507" y que se llama "Elena":**

# Ejercicio 17.

**Partiendo del xml de las siguientes diapositiva, realiza las siguientes consultas:**

1. **Nombre del propietario de la agenda.** 
2. **Teléfono de casa del propietario.** 
3. **Nombres y apellidos de los contactos de la agenda.** 
4. **Nombre e identificador de cada contacto.** 
5. **Datos del contacto con identificador “p02".** 
6. **Identificadores de los contactos que tienen móvil.** 

![Untitled](Ejercicios%20ae87a85a12504edba1a20f71720d775e/Untitled%207.png)

![Untitled](Ejercicios%20ae87a85a12504edba1a20f71720d775e/Untitled%208.png)

![Untitled](Ejercicios%20ae87a85a12504edba1a20f71720d775e/Untitled%209.png)

![Untitled](Ejercicios%20ae87a85a12504edba1a20f71720d775e/Untitled%2010.png)

![Untitled](Ejercicios%20ae87a85a12504edba1a20f71720d775e/Untitled%2011.png)

![Untitled](Ejercicios%20ae87a85a12504edba1a20f71720d775e/Untitled%2012.png)

# Ejercicio 18.

**Partiendo de los xml vistos en ejercicios de XPath anteriores, pásalos a formato JSON y repite
la realización de consultas.**

**Instalar la siguiente extensión en VSCode:
[https://marketplace.visualstudio.com/items](https://marketplace.visualstudio.com/items)?
itemName=weijunyu.vscode-json-path**