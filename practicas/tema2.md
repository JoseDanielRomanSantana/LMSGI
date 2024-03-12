# Ejercicios

# Ejercicio 1.

**Instala tres de las alternativas expuestas anteriormente, luego revisa tu configuración de VSCode con los plugins. Una vez hecho, realiza una comparativa a nivel de funcionalidades disponibles y da tu opinión sobre cuál de los tres entornos prefieres para crear tus XML.**

# Ejercicio 2.

**Realiza un XML para estructurar la información de la tabla siguiente:**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE bibioteca>
<biblioteca>
    <libro>
        <titulo>Git y Github desde cero</titulo>  
        <autor>Brais Moure</autor>
        <añoPublicacion fecha="2023"></añoPublicacion>
        <editorial>Publicación independiente</editorial>
        <paginas numeroPaginas="321"></paginas>
        <isbn>979-8391200475</isbn>
    </libro>
    <libro>
        <titulo>Código Limpio</titulo>  
        <autor>Robert C. Martin</autor>
        <añoPublicacion fecha="2012"></añoPublicacion>
        <editorial>Anaya Multimedia</editorial>
        <paginas numeroPaginas="463"></paginas>
        <isbn>978-8441532106</isbn>
    </libro>
    <libro>
        <titulo>Aprendiendo JavaScript</titulo>  
        <autor>Carlos Azaustre</autor>
        <añoPublicacion fecha="2023"></añoPublicacion>
        <editorial>Publicación independiente</editorial>
        <paginas numeroPaginas="286"></paginas>
        <isbn>979-8852737427</isbn>
    </libro>
    <libro>
        <titulo>El programador prágmatico</titulo>  
        <autor>David Thomas y Andrew Hunt</autor>
        <añoPublicacion fecha="2022"></añoPublicacion>
        <editorial>Anaya Multimedia</editorial>
        <paginas numeroPaginas="339"></paginas>
        <isbn>978-8441545878</isbn>
    </libro>
</biblioteca>
```

# Ejercicio 3.

**Escribir un documento XML que almacene la siguiente información:**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE ciudades>
<ciudades>
    <ciudad husoHorario="UTC+1">
        <nombre>Ceuta</nombre>
        <pais continente="África">España</pais>
        <elevacion medidaAltitud="metros">10m</elevacion> 
    </ciudad>
    <ciudad husoHorario="UTC+2">
        <nombre>Santorini</nombre>
        <pais continente="Europa">Grecia</pais>
        <elevacion medidaAltitud="metros">260m</elevacion> 
    </ciudad>
    <ciudad husoHorario="UTC+8">
        <nombre>Hong Kong</nombre>
        <pais continente="Asia">China</pais>
        <elevacion medidaAltitud="metros">957m</elevacion> 
    </ciudad>
    <ciudad husoHorario="UTC-6">
        <nombre>Guadalajara</nombre>
        <pais continente="América">México</pais>
        <elevacion medidaAltitud="metros">1566m</elevacion> 
    </ciudad>
    <ciudad husoHorario="UTC+1">
        <nombre>Casablanca</nombre>
        <pais continente="África">Marruecos</pais>
        <elevacion medidaAltitud="metros">27m</elevacion> 
    </ciudad>
</ciudades>
```

# Ejercicio 4.

**Escribir un documento XML que almacene la siguiente información:**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE hechosHistoricos>
<hechosHistoricos>
    <hechosHistorico descripcion="IBM da a conocer el PC">
        <fecha>
            <dia>12</dia>
            <mes>Agosto</mes>
            <año>1981</año>
        </fecha>
    </hechosHistorico>
    <hechosHistorico descripcion="Tim Berners-Lee escribe la primera web">
        <fecha>
            <dia>20</dia>
            <mes>Diciembre</mes>
            <año>1990</año>
        </fecha>
    </hechosHistorico>
    <hechosHistorico descripcion="Se funda Google">
        <fecha>
            <dia>4</dia>
            <mes>Septiembre</mes>
            <año>1998</año>
        </fecha>
    </hechosHistorico>
    <hechosHistorico descripcion="Se funda Facebook">
        <fecha>
            <dia>4</dia>
            <mes>Febrero</mes>
            <año>2004</año>
        </fecha>
    </hechosHistorico>
    <hechosHistorico descripcion="Steve Jobs presenta el iPhone">
        <fecha>
            <dia>29</dia>
            <mes>Junio</mes>
            <año>2007</año>
        </fecha>
    </hechosHistorico>
</hechosHistoricos>
```

# Ejercicio 5.

**Sin utilizar atributos, crear un documento XML bien formado que describa una lista de marcadores de páginas web, sabiendo que se desea que la información de cada página sea el nombre, una descripción breve y su URL. Los datos de los marcadores son los descritos en la siguiente tabla:**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE marcadores>
<marcadores>
    <marcador>
        <nombre>MDN Web Docs</nombre>
        <descripcion>Resources for Developers, by Developers</descripcion>
        <url>https://developer.mozilla.org/es/</url>
    </marcador>
    <marcador>
        <nombre>Lenguaje JavaScript</nombre>
        <descripcion>JavaScript en Español</descripcion>
        <url>https://lenguajejs.com/</url>
    </marcador>
    <marcador>
        <nombre>W3Schools</nombre>
        <descripcion>Learn to code</descripcion>
        <url>https://www.w3schools.com</url>
    </marcador>
    <marcador>
        <nombre>Wikipedia</nombre>
        <descripcion>La enciclopedia libre</descripcion>
        <url>https://es.wikipedia.org/</url>
    </marcador>
</marcadores>
```

# Ejercicio 6.

**Escribir un documento XML bien formado que guarde información de dos equipos de fútbol (nombre, estadio, ciudad y entrenador) con tres jugadores (nombre, apellidos, numero, posición y nacionalidad) cada uno. La posición (portero, defensa, medio o delantero) deberá representarse mediante un atributo del jugador. Utilizar datos reales para los equipos y jugadores. No obstante, no deberá indicarse el nombre del entrenador.**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE equipos>
<equipos>
    <equipo>
        <nombre>Real Madrid</nombre>
        <estadio>Santiago Bernabeu</estadio>
        <ciudad>Madrid</ciudad>
        <entrenador>Ancelotti</entrenador>
        <jugador posicion="defensa" nacionalidad="Español" numero="6">
            <nombre>Nacho</nombre>
            <apellidos>
                <primerApellido>Fernandez</primerApellido>
                <segundoApellido>Iglesias</segundoApellido>
            </apellidos>
        </jugador>
        <jugador posicion="delantero" nacionalidad="Español" numero="12">
            <nombre>Joselu</nombre>
            <apellidos>
                <primerApellido>Moreno</primerApellido>
                <segundoApellido>Mata</segundoApellido>
            </apellidos>
        </jugador>
        <jugador posicion="defensa" nacionalidad="Español" numero="2">
            <nombre>Daniel</nombre>
            <apellidos>
                <primerApellido>Carvajal</primerApellido>
                <segundoApellido>Ramos</segundoApellido>
            </apellidos>
        </jugador>
    </equipo>
    <equipo>
        <nombre>FC Barcelona</nombre>
        <estadio>Camp Nou</estadio>
        <ciudad>Barcelona</ciudad>
        <entrenador>Xavi</entrenador>
        <jugador posicion="defensa" nacionalidad="Francés" numero="23">
            <nombre>Jules</nombre>
            <apellidos>
                <primerApellido>Oliver</primerApellido>
                <segundoApellido>Koundé</segundoApellido>
            </apellidos>
        </jugador>
        <jugador posicion="Medio" nacionalidad="Español" numero="8">
            <nombre>Pedri</nombre>
            <apellidos>
                <primerApellido>Fernandez</primerApellido>
                <segundoApellido>Iglesias</segundoApellido>
            </apellidos>
        </jugador>
        <jugador posicion="Medio" nacionalidad="Español" numero="6">
            <nombre>Pablo</nombre>
            <apellidos>
                <primerApellido>Páez</primerApellido>
                <segundoApellido>Gavira</segundoApellido>
            </apellidos>
        </jugador>
    </equipo>
</equipos>
```

# Ejercicio 7.

**Corregir los errores que hay en el siguiente documento XML ("frutas.xml") para que
esté bien formado. Para ello, puede ser necesario crear nuevas etiquetas o atributos.**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE frutas>
<frutas>
    <fruta>
        <nombre>cereza</nombre>
    </fruta>
    <fruta>
        <nombre>naranja</nombre>
    </fruta>
</frutas>
```

# Ejercicio 8.

**Corregir los errores que hay en el siguiente documento XML ("vehiculos.xml") para que esté bien formado. Para ello, puede ser necesario crear nuevas etiquetas o atributos.**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE vehiculos>
<vehiculos>
    <vehiculo tipo="terrestre">
        <nombre></nombre>
        <nombre></nombre>
        <nombre></nombre>
    </vehiculo>
    <vehiculo tipo="terrestre">
        <nombre></nombre>
    </vehiculo>
    <vehiculo tipo="terrestre">
        <nombre></nombre>
        <nombre></nombre>
    </vehiculo>
</vehiculos>
```

# Ejercicio 9.

**Corregir los errores que hay en el siguiente documento XML ("figuras.xml") para que
esté bien formado. Para ello, puede ser necesario crear nuevas etiquetas o atributos.**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE figuras>
<figuras>
    <figura tipo="plana">
        <nombre numeroLados="4">cuadrado</nombre>
        <nombre numeroLados="3">triángulo</nombre>
    </figura>
    <figura tipo="tridimensional">
        <nombre numeroAristas="12" numeroCaras="6"></nombre>
    </figura>
</figuras>
```

# Ejercicio 10.

**Realiza un documento XML en la que añadáis una sección CDATA con el código HTML de
una página web.**

```xml
<?xml version="1.0" encoding="UTF-8"?>

<![CDATA[ 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
]]>
```

# Ejercicio 11.

**Una tienda de muebles, necesita organizar sus productos (mesas y sillas) para guardar la siguiente información: nombre, ancho, alto, profundidad y material. A partir del enunciado y el ejemplo anterior, realiza un XML con dos espacios de nombres.**

```xml

```

# Ejercicio 12.

**Realiza un documento XML con DTD para la siguiente información:** 

**Empleado: Silvia Vázquez García**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE empleado [
    <!ELEMENT empleado (nombre, apellido+)>
    <!ELEMENT nombre (#PCDATA)>
    <!ELEMENT apellido (#PCDATA)>
]>
<empleado>
    <nombre>Silvia</nombre>  
    <apellido>Vázquez</apellido>
    <apellido>García</apellido>
</empleado>
```

# Ejercicio 13.

**Realiza un documento XML y luego una DTD que nos sirva para validarlo.**

**La información a almacenar es sobre un vehículo (marca, modelo, precio, numBastidor, matriculado). Debemos tener en cuenta que para indicar si está matriculado queremos utilizar una etiqueta vacía, el resto es todo texto.**

**Ejemplo: BMW Serie 1 118i, 30000€, WW221023W269546, matriculado**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE vehiculo [
    <!ELEMENT vehiculo (marca, modelo, precio, numBastidor, matriculado)>
    <!ELEMENT marca (#PCDATA)>
    <!ELEMENT modelo (#PCDATA)>
    <!ELEMENT precio (#PCDATA)>
    <!ELEMENT numBastidor (#PCDATA)>
    <!ELEMENT matriculado EMPTY>
]>
<vehiculo>
    <marca>BMW</marca>
    <modelo>Serie 1 118i,</modelo>
    <precio>30000€,</precio>
    <numBastidor>WW221023W269546</numBastidor>
    <matriculado />
</vehiculo>
```

# Ejercicio 14.

**Realiza una DTD que sirva para que se cumpla la estructura básica de una web HTML:**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE html [
    <!ELEMENT html (head, body)>
    <!ELEMENT head (title)>
    <!ELEMENT title (#PCDATA)>
    <!ELEMENT body (br, p)>
    <!ELEMENT br EMPTY>
    <!ELEMENT p (#PCDATA)>
]>
 <html>
        <head>
            <title>Título del HTML</title>
        </head>
        <body>
            <br />
            <p>Esto es un párrafo</p>
        </body>
 </html>
```

# Ejercicio 15.

**Realiza un documento XML cuyo DTD sirva para que se cumpla la estructura básica de un empleado.**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE empleado [
    <!ELEMENT empleado (nombre, apellidos, fechaNacimiento, direccion, puesto, salario)>
    <!ELEMENT nombre (#PCDATA)>
    <!ELEMENT apellidos (#PCDATA)>
    <!ELEMENT fechaNacimiento (dia, mes, anio)>
    <!ELEMENT dia (#PCDATA)>
    <!ELEMENT mes (#PCDATA)>
    <!ELEMENT anio (#PCDATA)>
    <!ELEMENT direccion (#PCDATA)>
    <!ELEMENT puesto (#PCDATA)>
    <!ELEMENT salario (#PCDATA)>
    
]>
<empleado>
    <nombre>Daniel</nombre>
    <apellidos>Román Santana</apellidos>
    <fechaNacimiento>
        <dia>01</dia>
        <mes>10</mes>
        <anio>2003</anio>
    </fechaNacimiento>
    <direccion>Mi casa</direccion>
    <puesto>Admin</puesto>
    <salario>1.000.000€</salario>
</empleado>
```

# Ejercicio 16.

**Realiza una DTD a partir del XML siguiente. Ten en cuenta que el elemento producto tiene que aparecer una o más veces.**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE cesta [
    <!ELEMENT cesta (producto+)>
    <!ELEMENT producto (#PCDATA)>
]>
<cesta>
    <producto>WD BLACK SN770 1TB SSD PCIe Gen4 NVMe</producto>
    <producto>Sony PlatStation 5</producto>
    <producto>Xiaomi Pet Fountain</producto>
</cesta>
```

# Ejercicio 17.

**Realiza una DTD a partir del XML siguiente. Ten en cuenta que el elemento “nombre” tiene que aparecer una única vez. Ahora bien, el elemento “ingrediente” puede aparecer cero o más veces.**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE recetaCocina [
    <!ELEMENT recetaCocina (nombre, ingrediente*)>
    <!ELEMENT nombre (#PCDATA)>
    <!ELEMENT ingrediente (#PCDATA)>
]>
<recetaCocina>
    <nombre>Dip cementerio</nombre>
    <ingrediente>Frijoles cocidos</ingrediente>
    <ingrediente>Crene Fraiche o crema fresca</ingrediente>
    <ingrediente>Sazonador para quesadillas, burritos o tacos</ingrediente>
    <ingrediente>Salsa Tabasco unas gota</ingrediente>
    <ingrediente>Aguacate maduro</ingrediente>
    <ingrediente>Tortilla de trigo</ingrediente>
    <ingrediente>Lechuga iceberg</ingrediente>
</recetaCocina>
```

# Ejercicio 18.

**Tomando como referencia el XML del Ejercicio 13, realiza una DTD de manera que el elemento matriculado sea opcional, es decir, que pueda no aparecer.**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE vehiculo [
    <!ELEMENT vehiculo (marca, modelo, precio, numBastidor, matriculado?)>
    <!ELEMENT marca (#PCDATA)>
    <!ELEMENT modelo (#PCDATA)>
    <!ELEMENT precio (#PCDATA)>
    <!ELEMENT numBastidor (#PCDATA)>
    <!ELEMENT matriculado EMPTY>
]>
<vehiculo>
    <marca>BMW</marca>
    <modelo>Serie 1 118i,</modelo>
    <precio>30000€,</precio>
    <numBastidor>WW221023W269546</numBastidor>
    <matriculado />
</vehiculo>
```

# Ejercicio 19.

**Realiza una DTD a partir del XML siguiente.**

**Ten en cuenta que el elemento “articulos” puede:
• Estar vacío.
• Contener un elemento “codigo”.
• Contener un elemento “id”.
• Contener un elemento “codigo” y un elemento “id”.
• Contener un elemento “codigo” y varios elementos “id”.
• Contener un elemento “id” y varios elementos “codigo”.
• Contener varios elementos “codigo” y varios elementos “id”.**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE articulos [
    <!ELEMENT articulos (codigo|id)*>
    <!ELEMENT codigo (#PCDATA)>
    <!ELEMENT id (#PCDATA)>
]>
<articulos>
    <codigo>AF-32</codigo>
    <id>3891</id>
    <codigo>AF-50</codigo>
    <codigo>AF-89</codigo>
</articulos>
```

# Ejercicio 20.

**Crea una DTD externo correspondiente a la siguiente estructura de datos de un documento XML:**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE alumno SYSTEM "ejercicio20.dtd">
<alumno edad="24">
    <nombre>Luis</nombre>
    <apellido>Pérez</apellido>
    <direccion>Calle canalejas</direccion>
</alumno>
```

```xml
<!ELEMENT alumno (nombre, apellido, direccion)>
<!ATTLIST alumno edad CDATA #REQUIRED>
<!ELEMENT nombre (#PCDATA)>
<!ELEMENT apellido (#PCDATA)>
<!ELEMENT direccion (#PCDATA)>
```

# Ejercicio 21.

**Crea un DTD correspondiente a la siguiente estructura de datos de un documento XML.**

**Ten en cuenta que también podemos tener deportistas de futbol, que los valores posibles del atributo pais son "ESP", "FRA", "ITA" y "ALE" y que su valor por defecto es "ESP".**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE deportistas [
    <!ELEMENT deportistas (f1|tenis|futbol)*>
    <!ELEMENT f1 (#PCDATA)>
    <!ATTLIST f1 pais (FRA|ITA|ALE|ESP) "ESP">
    <!ELEMENT tenis (#PCDATA)>
    <!ATTLIST tenis pais (FRA|ITA|ALE|ESP) "ESP">
    <!ELEMENT futbol (#PCDATA)>
    <!ATTLIST futbol pais (FRA|ITA|ALE|ESP) "ESP">
]>
<deportistas>
    <f1 pais="ALE">SEbastian Vettel</f1>
    <f1>Fernando Alonso</f1>
    <f1 pais="ESP">Carlos Sainz</f1>
    <tenis>Rafael Nadal</tenis>
</deportistas>
```

# Ejercicio 22.

**Modifica el anterior ejercicio para que los pilotos de F1 tengan un atributo “código” identificativo.**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE deportistas [
    <!ELEMENT deportistas (f1+,tenis,futbol*)>
    <!ELEMENT f1 (#PCDATA)>
    <!ATTLIST f1 pais (ESP|FRA|ITA|ALE) "ESP">
    <!ATTLIST f1 codigo ID #REQUIRED>
    <!ELEMENT tenis (#PCDATA)>
    <!ELEMENT futbol (#PCDATA)>
]>
<deportistas>
    <f1 codigo="VET" pais="ALE"></f1>
    <f1 codigo="ALO"></f1>
    <f1 codigo="SAI" pais="ESP"></f1>
    <tenis></tenis>
</deportistas>
```

# Ejercicio 23.

**Crea un DTD correspondiente a la siguiente estructura de datos de un documento XML:**

**Ten en cuenta que los elementos “pelicula” que se escriban, deben incluir el atributo direccion, cuyo valor estará asignado a un atributo ID de otro elemento del documento. En este caso, el valor estará asignado a un atributo coddir de un elemento “director”**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE cine [
    <!ELEMENT cine (directores, peliculas)>
    <!ELEMENT directores (director*)>
    <!ELEMENT director (#PCDATA)>
    <!ATTLIST director coddir ID #REQUIRED>
    <!ELEMENT peliculas (pelicula*)>
    <!ELEMENT pelicula (#PCDATA)>
    <!ATTLIST pelicula direccion IDREF #REQUIRED>
]>
<cine>
    <directores>
        <director coddir="CE">Client Eastwood</director>
        <director coddir="JC">James Cameron</director>
    </directores>
    <peliculas>
        <pelicula direccion="JC">Avatar</pelicula>
        <pelicula direccion="CE">Mystic River</pelicula>
        <pelicula direccion="JC">Titanic</pelicula>
    </peliculas>
</cine>
```

# Ejercicio 24.

**Crea un DTD correspondiente a la siguiente estructura de datos de un documento XML:**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE usuarios [
    <!ELEMENT usuarios (usuario)*>
    <!ELEMENT usuario (#PCDATA)>
    <!ATTLIST usuario clave NMTOKEN #REQUIRED>
]>
<usuarios>
    <usuario clave="123456789">Ana</usuario>
    <usuario clave="ab-c-d-fg">Iker</usuario>
    <usuario clave="A1_B2..C3">Elsa</usuario>
</usuarios>
```

# Ejercicio 25.

**Crea un DTD correspondiente a la siguiente estructura de datos de un documento XML.**

**Ten en cuenta que los elementos “animal” que se escriban, deben incluir opcionalmente el atributo tipo_de_imagen, cuyo valor será una notación (gif, jpg o png). Además, son declaraciones de los siguientes tipos MIME (Multipurpose Internet Mail Extensions): image/gif, image/jpeg e image/png.**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE animales [
    <!ELEMENT animales (animal+)>
    <!ELEMENT animal (nombre)>
        <!ATTLIST animal imagen CDATA #IMPLIDED>
        <!ATTLIST animal tipo_de_imagen NOTATION (gif|jpeg|png) #REQUIRED>
            <!NOTATION gif SYSTEM "image/gif">
            <!NOTATION jpeg SYSTEM "image/jpeg">
            <!NOTATION png SYSTEM "image/png">
    <!ELEMENT nombre (#PCDATA)>

]>
<animales>
    <animal imagen="ballena-azul.gif" tipo_de_imagen="gif">
        <nombre>Ballena</nombre>
    </animal>
    <animal image="leon-dormido.png" tipo_de_imagen="png">
        <nombre>Leon</nombre>
    </animal>
</animales>
```

# Ejercicio 26.

**Crea un DTD correspondiente a la siguiente estructura de datos de un documento XML.**

**Ten en cuenta:**

- **Que los valores (ballena, delfin, elefante, leon y oso) van a ser
cargados desde una URI (Uniform Resource Identifier). En este caso, se hace referencia a los archivos externos “ballena.gif”, “delfin.gif”, “elefante.gif”, “leon.gif” y “oso.gif”.**
- **Con NDATA (Notation Data) se ha asociado a las entidades ballena, delfin, elefante, leon y oso con la notación gif.**
- **La notación gif es una declaración del tipo MIME image/gif.**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE animales [
    <!ELEMENT animales (grupos)*>
        <!ELEMENT grupos EMPTY>
            <!ATTLIST grupos imagenes NOTATION gif #IMPLDIED>
                <!ENTITY ballena SYSTEM "ballena.gif" NDATA gif>
                <!ENTITY delfin  SYSTEM "delfin.gif" NDATA gif>
                <!ENTITY elefante SYSTEM "elefante.gif" NDATA gif>
                <!ENTITY leon SYSTEM "leon.gif" NDATA gif>
                <!ENTITY oso SYSTEM "oso.gif" NDATA gif>

                <!NOTATION gif SYSTEM "image/gif">

]>      
<animales>
    <grupos imagenes="ballena"></grupos>
    <grupos imagenes="ballena delfin"></grupos>
    <grupos imagenes="elefante leon oso"></grupos>
    <grupos imagenes="ballena elefante"></grupos>
</animales>
```

# Ejercicio 27.

**Realiza un documento XML y un XSD para la siguiente información:**

**Alumno: Manuel García Fernández**

```xml
<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema">
    <xs:element name="Alumno" type="xs:string"/>
   </xs:schema>
```

# Ejercicio 28.

**Para los siguientes elementos:**

**<ciudad>Milán</ciudad>**

**<fecha-de-nacimiento>1999-12-18</fecha-de-nacimiento>**

**<hora>10:15:45</hora>**

**<nota>8.75</nota>**

**<apto>true</apto>**

**Escribir sus definiciones de elementos simples correspondientes.**

```xml
<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema">
       <xs:element name="ciudad" type="xs:string"/>
       <xs:element name="fecha-de-nacimiento" type="xs:date"/>
       <xs:element name="hora" type="xs:time"/>
       <xs:element name="nota" type="xs:decimal"/>
       <xs:element name="apto" type="xs:boolean"/>
</xs:schema>
```

# Ejercicio 29.

**Definir un elemento llamado ventanaCerrada de tipo lógico, que por defecto tenga el valor false, y otroelemento llamado puertaAbierta también de tipo lógico, que tenga asignado el valor fijo true.**

```xml
<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema">
    <xs:element name="ventanaCerrada" type="xs:boolean" default="false"/>
    <xs:element name="puertaAbierta" type="xs:boolean" fixed="true"/>
</xs:schema>
```

# Ejercicio 30.

**Asocia el documento XML con su XSD, ambos realizados en el ejercicio anterior.**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<libro xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:noNamespaceSchemaLocation="ejercicio30.xsd">
    <titulo>XML Práctico</titulo>
    <autor>Sébastian Lecomte</autor>
    <autor>Andrew Watt</autor>
    <editorial>Ediciones ENI</editorial>
</libro>
<?xml version="1.0" encoding="UTF-8"?>
<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema">
    <xs:element name="libro" type="Tlibro"/>
    <xs:complexType name="Tlibro">
        <xs:sequence>
            <xs:element name="titulo" type="xs:string"/>
            <xs:element name="autor" type="xs:string"/>
            <xs:element name="autor" type="xs:string"/>
            <xs:element name="editorial" type="xs:string"/>
        </xs:sequence>
    </xs:complexType>
</xs:schema>
```

# Ejercicio 31.

**Crea el esquema correspondiente al siguiente documento XML alumnos.xml para estructurar la información personal sobre los alumnos de un centro educativo:**

```xml
<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema">
    <xs:element name="alumnos" type="Talumnos"/>
    <xs:complexType name="Talumnos">
        <xs:sequence>
            <xs:element name="Alumno" type="Talumno"/>
        </xs:sequence>
   </xs:complexType>
   <xs:complexType name="Talumno">
        <xs:sequence>
            <xs:element name="nombre" type="xs:string"/>
            <xs:element name="apellidos" type="xs:string"/>
            <xs:element name="direccion" type="Tdireccion"/>
            <xs:element name="contactar" type="Tcontactar"/>
        </xs:sequence>
   </xs:complexType>
   <xs:complexType name="Tdireccion">
        <xs:sequence>
            <xs:element name="domicilio" type="xs:string"/>
            <xs:element name="codigo_postal" type="xs:integer"/>
            <xs:element name="localidad" type="xs:string"/>
            <xs:element name="provincia" type="xs:string"/>
        </xs:sequence>
   </xs:complexType>
   <xs:complexType name="Tcontactar">
        <xs:sequence>
            <xs:element name="telf_casa" type="xs:integer"/>
            <xs:element name="telf_movil" type="xs:integer"/>
            <xs:element name="telf_trabajo" type="xs:integer"/>
            <xs:element name="email" type="xs:string"/>
        </xs:sequence>
   </xs:complexType>
</xs:schema>
```

# Ejercicio 32.

**Dado el documento XML Ejemplo.xml, genera el correspondiente documento XSD para validarlo con las siguientes condiciones:**

- **el elemento "nombre" debe admitir nombres compuestos que comiencen con mayúscula**

```xml
<?xml version="1.0" encoding="UTF-8"?>
<usuarios xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
 xsi:noNamespaceSchemaLocation="ejercicio32.xsd">
    <usuario>
        <nombre>Peter Green</nombre>
        <departamento>Finanzas</departamento>
        <puntuacion>5</puntuacion>
        <estado>conectado</estado>
    </usuario>
</usuarios>
<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema">
    <xs:element name="usuarios" type="Tusuarios"/>
    <xs:complexType name="Tusuarios">
        <xs:sequence>
            <xs:element name="usuario" type="Tusuario"/>
        </xs:sequence>
    </xs:complexType>
    <xs:complexType name="Tusuario">
        <xs:sequence>
            <xs:element name="nombre" type="Tnombre"/>
            <xs:element name="departamento" type="xs:string"/>
            <xs:element name="puntuacion" type="xs:integer"/>
            <xs:element name="estado" type="xs:string"/>
        </xs:sequence>
    </xs:complexType>
    <xs:simpleType name="Tnombre">
        <xs:restriction base="xs:string">
            <xs:pattern value="(([A-Z])+[\s])*"></xs:pattern>
        </xs:restriction>
    </xs:simpleType>
</xs:schema>
```

# Ejercicio 33.

**Dado el documento XML Ejemplo.xml, genera el correspondiente documento XSD para validarlo con las siguientes condiciones:**

- **el elemento "puntuación" debe ser un número entero comprendido entre 1 y 10, ambos inclusive.**

```xml
<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema">
    <xs:element name="usuarios" type="Tusuarios"/>
    <xs:complexType name="Tusuarios">
        <xs:sequence>
            <xs:element name="usuario" type="Tusuario"/>
        </xs:sequence>
    </xs:complexType>
    <xs:complexType name="Tusuario">
        <xs:sequence>
            <xs:element name="nombre" type="xs:string"/>
            <xs:element name="departamento" type="xs:string"/>
            <xs:element name="puntuacion" type="Tpuntuacion"/>
            <xs:element name="estado" type="xs:string"/>
        </xs:sequence>
    </xs:complexType>
    <xs:simpleType name="Tpuntuacion">
        <xs:restriction base="xs:integer">
            <xs:minInclusive value="2"/>
            <xs:maxInclusive value="100"/>
        </xs:restriction>
    </xs:simpleType>
</xs:schema>
```

# Ejercicio 34.

**Dado el documento XML siguiente, genera el correspondiente documento XSD para validarlo:**

```xml
<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema">
    <xs:element name="fichas" type="Tfichas"/>
        
    <xs:complexType name="Tfichas">
        <xs:sequence>
            <xs:element name="ficha" type="Tficha" minOccurs="1" maxOccurs="unbounded"/>
        </xs:sequence>
            <xs:attribute name="numero" type="xs:integer"/>
    </xs:complexType>
    <xs:complexType name="Tficha">
        <xs:sequence>
            <xs:element name="nombre" type="xs:string"/>
            <xs:element name="edad" type="xs:integer"/>
        </xs:sequence>
    </xs:complexType>
</xs:schema>
```

# Ejercicio 35.

**Dado el documento XML Ejemplo.xml, genera el correspondiente documento XSD con la documentación del esquema realizado.**

```xml
<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema">
    <xs:element name="usuarios" type="Tusuarios"/>
    <xs:complexType name="Tusuarios">
        <xs:sequence>
            <xs:element name="usuario" type="Tusuario"/>
        </xs:sequence>
    </xs:complexType>
    <xs:complexType name="Tusuario">
        <xs:sequence>
            <xs:element name="nombre" type="xs:string">
                <xs:annotation>
                    <xs:appinfo>
                        <texto_de_ayuda>Se debe introducir el nombre del usuario correspondiente</texto_de_ayuda>
                    </xs:appinfo>
                </xs:annotation>
            </xs:element>
            <xs:element name="departamento" type="xs:string">
            <xs:annotation>
                <xs:appinfo>
                    <texto_de_ayuda>Se debe introducir el nombre del departamento correspondiente</texto_de_ayuda>
                </xs:appinfo>
            </xs:annotation>
            </xs:element>
            <xs:element name="puntuacion" type="Tpuntuacion"/>
            <xs:element name="estado" type="xs:string"/>
        </xs:sequence>
    </xs:complexType>
    <xs:simpleType name="Tpuntuacion">
        <xs:restriction base="xs:integer">
            <xs:minInclusive value="2"/>
            <xs:maxInclusive value="100"/>
        </xs:restriction>
    </xs:simpleType>
</xs:schema>
```

# Ejercicio 36.

[ejercicio36.md](Ejercicios%208dac8e291bde432e8c813a73af941588/ejercicio36.md)