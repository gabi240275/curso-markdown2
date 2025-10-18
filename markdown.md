# Mardown
Hola mundo esto es un curso de Markdown

en Mardown para dar salto de linea debemos hacer 2 Enter

<!-- Títulos -->
## Título2
### Título3
#### Título4
##### Título5
###### Título6
<!-- Texto negrita - Strong -->

Para escribir **negrita** usamos doble * al inicializar y al finalizar la palabra

También para __negrita__ podemos usar _ dos guiones bajos

<!-- Texto Italic -->

Para escribir *texto en Italic* usamos un * al comienzo y al final del texto

También podemos usar _para escribir en Italic_ un _ guion bajo al inicio y al final del texto

<!-- Texto negrita y curvada a la vez -->

Para hacer ***texto negrita y curvado a la vez*** usamos tanto al inicio como al final *** tres asteriscos

<!-- Texto tachado -->

Para ~~tachar texto~~ usamos tanto al inicio como al final del texto ~~ doble Tilde

<!-- Cita -->
Para usar una cita antes de la cita ponemos >

>A la vista de suficientes ojos, todos los errores resultan evidentes --Linus Torvalds

<!-- Para usar código --->

Para usar una línea de código empezamos y finalizamos con: 

`
console.log("Hola mundo");
`

También podemos usar tres ~

~~~
print ("Hello word");
~~~

También para un bloque de código usamos:

```xml
<key>NSHealthShareUsageDescription</key>
<string>La app necesita acceso a tus pasos para mostrar la actividad.</string>
<key>NSLocationWhenInUseUsageDescription</key>
<string>Se usa para registrar tus recorridos.</string>
<key>NSLocationAlwaysUsageDescription</key>
<string>Se usa para registrar el recorrido incluso en segundo plano.</string>
<key>UIBackgroundModes</key>
<array>
    <string>location</string>
    <string>audio</string>
</array>
```

<!-- Lista desordenada -->
Para las listas desordenadas podemos usar tanto el - guion como el asterisco *

- Manzana
- Pera
* Pantalones
* Camisas

También se puede usar el símbolo de +

+ Azucar
+ Aceite
+ Vinagre

Para añadir sublistas hacemos una tabulación

* Desayuno
    * Zumo naranja
    * Huevos
    * Fruta
* Comida
    * Pasta
    * Pescado
    * Fruta
* Cena
    * Sopa
        * de marisco
        * de pollo

<!-- Listas ordenadas -->

### Asignaturas
1. Programación
2. Base de datos
3. Sistemas
    1. cmd
    2. linux
    3. redes
        * practica
        * teoria

<!-- Creación de Links -->

Curso que estamos siguiendo [curso](https://tutorialmarkdown.com/markdown "Tutorial Markdown")

<pepolink@gmail.com>

También podemos usar <> para url aunque no es recomendable

<https://tutorialmarkdown.com/markdown>

También los links los podemos poner en negrita abriendo y cerrando con doble *

Visita la web de **[apple](https://www.apple.com/es/ "Web de apple")**

Con 3 * tenemos combinación de inclinado y negrita

Visita la web de ***[apple](https://www.apple.com/es/ "Web de apple")***

Para hacer una referencia:

Esto es una referencia [1]

[1]: https://www.apple.com/es/ 

<!-- Imágenes y Badges -->

Esta es la sintaxis para crear agregar una imagen en el lenguaje de marcas Markdown

![imagen Markdown](https://d33wubrfki0l68.cloudfront.net/59f29676ef5e4d74685e14f801bbc10c2dbd3cef/c0688/lesson-images/markdown-1-markup.png "Imagen Markdown de internet")


Tambien podemos mostrar imágenes que se encuentran en local en este caso en nuestra carpeta Curso-Markdown2

![imagen Markdown](imagen2.jpg "Imagen en local")

![pixelar](imagen3.jpg "Pixel")

Para adjuntar badges consigo las url de
<https://github.com/henriquesebastiao/badges?tab=readme-ov-file>

![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat&logo=markdown&logoColor=white "Markdown")

![Github](https://img.shields.io/badge/GitHub-100000?logo=github&logoColor=white "Github")

![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat&logo=gmail&logoColor=white "Gmail")

![Discord](https://img.shields.io/badge/Discord-5865F2?style=flat&logo=discord&logoColor=white "Discord")

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black "Linux")

![macOS](https://img.shields.io/badge/macOS-000000?style=flat&logo=apple&logoColor=white "macOS")

![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=flat&logo=youtube&logoColor=white "YouTube")

![Docker](https://img.shields.io/badge/Docker-2496ED.svg?style=for-the-badge&logo=Docker&logoColor=white "Dorker")

GitHub Profile Badges

<https://home.aveek.io/GitHub-Profile-Badges/>


Top 5 badges para GitHub

<https://www.makeuseof.com/badges-that-will-supercharge-your-github-repository/>

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=gabi240275)](https://github.com/anuraghazra/github-readme-stats)

![Profile Views](https://komarev.com/ghpvc/?username=gabi240275)

![](https://komarev.com/ghpvc/?username=gabi240275&color=dc143c)

<!-- Reglas y emojis -->

Para poner una regla o linea de separación podemos poner 3 *
***
Tambien se puede hacer con 3 guiones

---
Para poder ver los emojis instalamos en Visual Studio Code la extensión github markdown preview

<https://gist.github.com/rxaviers/7360908>

:heart: :smirk: :frog:

:dog: :tiger:

:pig:

<!-- Tablas -->

| Distribuciones | Disponible | Version |
|----------------|------------|---------|
| ArchLinux      | Yes        | 1.0.1   |
| KaliLinux      | **No**     | 2.5     |
| Ubuntu         | Yes        | 25.7    |

También podemos generar tablas desde esta web
<https://www.tablesgenerator.com/markdown_tables>

| Distros   | Disponible | Versión | Año de publicación |
|-----------|------------|---------|--------------------|
| ArchLinux |     Yes    |   1.1   |        2020        |
| KaliLinux |   **No**   |   12.5  |        2021        |
| Ubuntu    |     Yes    |   25.7  |        2025        |


<!-- Combinar Markdown y HTML -->

### Combinación Markdown y HTML

<h3>  Código html</h3>

![imagen](https://upload.wikimedia.org/wikipedia/commons/9/9a/Visual_Studio_Code_1.35_icon.svg)

En html podemos modificar el tamaño de la imagen

<img src="https://upload.wikimedia.org/wikipedia/commons/9/9a/Visual_Studio_Code_1.35_icon.svg" width=50px height=50px>

<img src="dolphin.jpg" width=200px height=200px>



<!-- Videos -->



[![Ver el video](https://img.youtube.com/vi/LE0VkWstzhQ/maxresdefault.jpg)](https://www.youtube.com/watch?v=LE0VkWstzhQ)


[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/8mKf9rjvjv8/0.jpg)](https://www.youtube.com/watch?v=8mKf9rjvjv8)

Para una resolucion máspequeña quitamos el maxresdefaut por hqdefault 

[![Ver el video](https://img.youtube.com/vi/LE0VkWstzhQ/hqdefault.jpg)](https://www.youtube.com/watch?v=LE0VkWstzhQ)


<!-- Hacks de Texto -->

Vamos usar html:

<ins> Texto subrayado </ins>

<center> Texto alineado al centro </center>



Podemos hacer una combinación de ambas

<center><ins>Texto alineado al centro y subrayado </ins></center>


<p style=color:red> Texto de color rojo </p>

<p style=color:blue><ins>Texto de color azul con subrayado</ins></p>

<p style=color:green> Texto de color verder </p>

<a href="https://github.com/jcqa24" target="_blank"> Perfil de Github </a>

<!-- Diagramas flujo  horizontal-->

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```


<!-- Diagramas flujo vertical -->



```mermaid
flowchart TB
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```

<!-- Diagrama flujo personalizado -->


```mermaid
flowchart TB
A[Inicio]
```

```mermaid
flowchart TB
A(Inicio)
```

```mermaid
flowchart TB
A((Inicio))
```
<!-- Ejemplo digrama flujo -->

```mermaid
flowchart TB
A((INICIO))
B[/ Escribe tu contraseña /]
C[\ pass \]
D{ pass = '1234' }
E[/ Felicidades loging correcto /]
F[/ intenta con otra contraseña /]
G((FIN))

A --> B --> C -->D
D --> |Verdadero| E
D --> |Falso| F
F --> B
E--> G
```

<!--Diagrama de clases -->

Ponemos la clase Animal y los atributos->  con el + hacemos que sea pública, un tipo de dato entero que se llame edad y otro de tipo String
Para los métodos indicamos de nuevo nuestra clase Animal ->el + para indicar que es público y usamos () -> si queremos dentro de los() añadimos un parámetro
También entre clases podemos hacer una relación de herencia entre la clase padre y las otras clases
También podemos representar dependencia entre clases
También podemos representar la composición

```mermaid
    classDiagram

    class Animal
    Animal : +int edad
    Animal : +String nombre
    Animal : +Caminar ()
    Animal : +Comida (cantidad)

    class Pato {
        +color
        +nadar()
    }

    class Ballena{
        +color
        +nadar()
    }

    class Oso{
        +color
        +cazar()
    }

    Animal <|-- Pato
    Animal ..> Ballena
    Animal ..* Oso

```

<!--Diagramas de secuencia -->

Vamos ahora a realizar un diagrama de secuencia
Las peticiones sincronas son líneas continuas
Las oeticiones asincronas (linea punteada)

```mermaid

    sequenceDiagram

    actor U as User
    participant F as Front End
    participant B as Back End
    participant DB as BBDD

    U ->> F: Envio de datos
    F ->> B: Validar datos
    B -->> DB: Verifique la existencia

    DB ->>B: Datos correctos

    F --> F: Error en la validación

```
<!-- Gráficas circulares -->

Creación de gráficas circulares

```mermaid
pie showData
title lenguajes utilizados en el proyecto
"Java" : 25
"Html" : 25
"CSS" : 30
"JavaScript" :20
```


<!-- Crear diagrama Entidad Relación -->

Creación diagrama Entidad Relación
Usuario únicamente existe uno y solo uno ||
Usuario realiza 0 compras (pedidos) o varias o{
En un pedido debe tener almenos 1 producto o muchos }| o{

```mermaid

    erDiagram
    PRODUCTO {
        string ID_producto
        string Nombre
        double Precio
    }

    USUARIO{
        string ID_usser
        string Nombre
        string Direccion

    }

    PEDIDO {
        string ID_pedido
        string ID_usser
        string ID_producto
    }

    USUARIO ||--o{PEDIDO : compra
    PRODUCTO }| --O{ PEDIDO : venta
```

<!-- Diagrama Journey -->

Creación Diagramas Journey

```mermaid
    journey
        title Compra
        section SELECCION PRODUCTO
            Navegar:  6 : usuario
            Agregar al carrito: 6: usuario
        section PAGO
            Realizar pago: 3 : usuario
            validar pago: 5: sistema

```
Vamos a Realizar un diagrama Git
<!-- Diagramas Git -->

```mermaid
    gitGraph
        commit
        branch dev
        commit
        commit
        checkout main
        commit
        merge dev
        commit id: "V.1.0.0"tag: "Release"
        checkout dev
        commit
        branch bug
        commit id: "Error 404"
        checkout dev
        commit
        checkout bug
        merge dev
        checkout main
        commit
        commit
        merge dev
        commit id: "V.2.0.0" tag: "Release"
```

Vamos a realizar un diagrama Gantt
<!-- Diagramas Gantt -->

```mermaid
    gantt
        dateFormat YYYY-MM-DD
        excludes weekends
        title Proyecto tienda online

        section Diseño
            Diseño BD :done, BD,2022-07-20,4d
            Diseño Fronted :active, F, 2022-07-20,2d

        section Desarrollo
            Conexion BD: CBD, after BD,2d
            Desarrollo Front:crit, DF,after F,2d

       
```
<!-- Diagramas de Requerimiento -->

Vamos a crear un diagrama de requerimiento

```mermaid
    requirementDiagram

    performanceRequirement TiempoDeCarga{
        id: 1
        Text: "Tiempode carga menos a 2 seg"
        Risk: Low
        verifymethod: Test
    }
    element Carga{
        type: user_experience
        docRef: github/test
    }

    Carga <- satisfies - TiempoDeCarga
```


<!-- Añadir ecuaciones -->

Vamos añadir ecuaciones usando Latex

$$ x^2 + y^2 = z^n $$

$$ \int_{0}^{10}\pi\frac{3}{4\beta} $$





