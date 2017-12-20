# PRODUCTO: PROPUESTA DE DASHBOARD LABORATORIA
* Dashboard realizado con HTML, CSS Y JS.
* En este proyecto, se muestran maquetaciones y estructuras propuestos junto con la teoría que respaldan las decisiones de diseño para cada una de las secciones de contenido.
* Dicho dashboard, está diseñado y estructurado para las Training Managers (TM) de todas las sedes de Laboratoria.

Dashboard hecho por:
* Andrea I. Gutiérrez Rodríguez
* Lia Laguna Gamboa

- - - -

> ## El Usuario
Para la construcción de este dashboard, fue necesario delimitar y describir al usuario que interactuará con la interfaz y la información contenida allí.
 * __ ¿Quién es el usuario? __
    * _Training Managers_ de Laboratoria, puesto que requiere manejar mucha data tanto de las alumnas de Laboratoria como del staff que conforma en cada sede.

 * __Nivel de conocimientos de manejo de interfaces por parte del usuario: __
    * _Conocimiento básico-intermedio. _ Puede ejecutar pasos básicos y rápidos dentro de la interfaz para manejo, edición y comprensión de información en general.

 * __Objetivo del Usuario: __
    * Visualizar, filtrar, editar y manipular una gran cantidad de data continuamente actualizada en un sólo lugar sin tener que cambiar a diferentes páginas o perder el tiempo buscando la información en diferentes ubicaciones y con la que, a partir de la misma, pueda tomar decisiones y planeaciones a corto y largo plazo.

 * __Objetivo de la propuesta de dashboard__:
    * Lograr resolver las necesidades de control y edición de data por parte del usuario, siendo capaz no solo de mostrar la data, sino que la soporte visualmente por medio de gráficas y métricas que ayuden a que comprenda y visualice mejor la información mostrada.

> ## La arquitectura de la información ##
Es importante definir y comprender el tipo de información que estamos manejando y el objetivo que se busque con la misma. Es por eso, que, estudiando la base de datos proporcionada, se establece lo siguiente:
 * La granularidad de la información que se maneja para es de __nivel agregado__.
    * En este nivel, el usuario debe ser capaz de manipular y modificar la data mostrada en la base de datos y que sea capaz de almacenarla, por lo que __el diseño del dashboard debe responder a esa necesidad de interacción. __

> ## Los colores y tipografías
* __Colores__: Se usaron los colores institucionales de Laboratoria, blanco, gris #2b2b2b y amarillo #ffc107.
En las gráficas se usó el amarillo para marcar números positivos y el rojo para números negativos.
El color amarillo no sólo nos ayuda a respetar el diseño institucional de Laboratoria, si no que también nos transmite luminosidad y visibilidad, nos ayuda a captar la atención ya que es el único que sobresale ante los demás, crea felicidad y genera calidez. No sólo se uso en pequeñas dosis por cuestiones de minimalismo, si no que al abusar de él puede ser molesto a la vista y causar fatiga ocular.
* __Tipografías__: En todo el proyecto se utilizó la tipografía Montserrat, porque su diseño tipográfico es funcional y contemporáneo. La tipografía Montserrat es un tipo de estilo geométrico que tiene ajustes ópticos sutiles. Además ésta nos funciona en el mundo editorial como en el corporativo.

---

> ## El tipo de navegación y mapa de sitio
* La navegación y estructuración del dashboard se planeó para ser sencilla y clara, para que el usuario no tenga problemas en identificar las partes donde debe ingresar datos, buscarlos, y comprenderlos;
* Utilización de iconos y elementos conocidos por el usuario para una rápida identificación de secciones, menús e información.
* Utilización de menú global donde se encontraran todas las sedes.
* Utilización de menús locales por sede para separación y organización de la data entre alumnos y profesores.
* Longitud de casa view no mayor a 2 scrolls para mejor navegación del usuario entre la información mostrada.

 <img src=assets/images/maquetados/mapa.png>
(Imagen de mapa de sitio)

> ## Sketching y maquetación ##
La presentación y organización visual de la información es importante, siendo esta esencial desde la primera impresión del usuario y la interacción que vaya a tener con ella.
Es por eso, que tener una maquetación correcta con medidas y ubicación espacial general de la información nos facilitará la tarea de pasar dicho diseño a HTML y CSS. Las medidas propuestas para cada view son:
#### Login
 <img src=assets/images/maquetados/login-maquetacion.jpg>

#### Overview / teachers / alumnas
<img src=assets/images/maquetados/overview-detalles.jpg>
<img src=assets/images/maquetados/students-detalles.jpg>



> ## Descripción de secciones de Dashboard
### __Login__ ###
Al ser una herramienta diseñada y pensada para las TM de Laboratoria y manejo de data de alumnas y profesores, se propone agregar un Login para poder asegurar que únicamente las TM puedan accesar a dicha información.

#### Diseño
El diseño es simple y sencillo a la vista del usuario, permitiendo que se comprenda de forma rápida por medio del logo y los colores en botones y fondo.
<img src=assets/images/maquetados/login-coment.png>

### __Overview__ ###
#### Diseño
<img src=assets/images/maquetados/overview-coment.png>


### __Students-Teachers__ ###
<img src=assets/images/maquetados/students-detalles.jpg>

> ## Diseño final ##

### __Overview__ ###
<img src=assets/images/maquetados/overview.jpg>

### __Students__ ###
<img src=assets/images/maquetados/students.jpg>

### __Teachers__ ###
<img src=assets/images/maquetados/teachers.jpg>
