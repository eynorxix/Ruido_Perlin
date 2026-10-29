U N I V E R SI D A D PR I V A D A F R A N Z
TAMAYO

FA C U L T A D D E I N G E N I E R Í A
C A R R E R A D E I N G E N I E R Í A D E SI ST E M A S

PROYECTO

CASO: “EDUCACION HAMBIENTAL”

“VIDEOJUEGO CON INTELIGENCIA ARTIFICIAL QUE PERMITA REPRESENTAR LA
CONSECUENCIA DE LAS DECISIONES DEL USUARIO SOBRE EL ENTORNO VIRTUAL
CON LA FINALIDAD DE EDUCACION AMBIENTAL”
POSTULANTE:
BRAYAN QUISPE MAMANI
TUTOR:
I NG. MARISOL ARGUEDAS BALLADARES
REVISOR:

I NG. MARISOL ARGUEDAS BALLADARES
E L A L T O – BO L I V I A
2025

1
CONTENIDO DE COMPONENTES

CAPITULO I. MARCO TEORICO
1. Introduccion.

1.2 Antecedentes:

1.1.1 Antecedentes internacionales:
1.1.2 Antecedentes nacionales:

1.2. Planteamiento del problema
1.2.1. Problema Principal:

1.2.2. Formulacion del problema:
1.2.3 Problemas Especificos:

1.3.1 Objetivos.

1.3.2 Objetivos generales:

1.3.3 Objetivos Especificos:

1.4.1 Justificaciones y limitaciones:
1.4.2 Justificacion Tecnica
1.4.3 Justificacion Social

1
1

2

2

3

4

4

4

5

5

5

6

7

7

7

1.4.3 Justificacion Economica

8

1.5.2 Enfoque.

8

1.5.1 Metodologia.

1.5.3 Tipo de diseño.

8

8

1.5.4 Motodologia de desarrollo de software.

9

1.6.2 Godot Engine.

9

1.6.4 Sistema operativo Arch linux.

10

1.7.2 Alcance Tematico.

10

1.6.1 Herramientas.
1.6.3 Blender.
1.7.1 Alcances.

1.7.3 Alcances Geograficos.
1.7.4 Alcance Temporal.

1.8.1 Limites.

1.8.2 Alcance de conexion a una red.

1.8.4 Restricciones en distribucion del juego.

1.8.5 funcionamiento en linea.

9
9

10

11

12

13

14

14

15

2

CAPITULO II. MARCO TEORICO
2. Introduccion

2.1 Juego tipo Sandbox.

2.1.2 Termino Sandbox.

16
17

17

17

2.1.3 Caracteristicas de un juego tipo Sandbox.

18

2.2.1 GDScript.

20

2.2.4 Ecenas.

20

2.2 Motor de Videojuegos.
2.2.3 Nodos.

19
20

2.3.1 Funcionalidad de la IA reactiva

21

2.4.1 Como funciona Scrum.

22

2.3.2 Funcionalidad en diversos campos
2.4.2 Product Backlog

21

23

2.5.1 Diagrama de Casos de Uso.

24

2.5.3 Diagrama de clases.

25

2.5.2 Diagrama de secuencia.

25

2.5.3.1 Relaciones.

25

3. Introduccion

28

CAPITULO III MARCO PRACTICO.
3.1. Diseño y desarrollo de software.

27

28

3.1.1. Analisi y Requeqerimientos.

28

3.1.2. Definición y diseño

30

3.3 Situacion actual.

33

Diagrama de contexto propuesto.

36

Tabla 1.
Tabla 2.

3.4 Problema.

3.5.1 Requerimientos funcionales.

3.5.2 Requerimientos no funcionales.
3.5.4 Requerimientos de Seguridad.

ANEXOS:

29
31

34

37

39

40

42

3

CAPÍTULO I
MARCO
INTRODUCTORIO

4
1. Introduccion.
En es presente capitulo presenta como el usuario con el presente proyecto es mostrar
al usuario quien va estar interactuandio con el juego fomentar de manera directa y creativa de
como un videojuego como este puede explorar como tambien reusar los componentes del
mismo mundo del juego en la cual estara interactuando con ello en la cual estara presente
como cada decision que el vaya a tomar podra ver los cambios en el mismo mundo, ver como
cambia el hambiente y los mismos agentes en la cual interactuaran segun su entorno como el
usuario decida como coperar con el mundo del mismo juego.
En las unidades educativas se ha llevado por varios años de como deben de cuidar el
medio ambiente en la cual hacen trabajos escolares como: resiclar las partes de basura en la
cual transforman algo distinto, reusar como objetos con un segundo uso, restar es dejar de
generar mas desperdicios. En este videojuego busca lo mismo pero con el punto de tener un
ambiente mas amplio en la cual el usuario podra visualizar como los decisiones que el a
tomado afecta a su entorno ambiental dentro del mismo juego.
Para convertir el juego en realidad se utilizara Metodologia de investigacion de “CUD”
en la cual esta diseñada en recolectar datos de los usuarios y usar esos mismos datos para la
mejora del videojuego, en la cual tambien se usara la metodologia de desarrollo el “SCRUM”
en la cual junto con el “UCD” y “SCRUM” combina en recoletar datos de usuarios y trabajar en
el juego con la metodologia de desarrollo,ambos como UCD y SCRUM se trabajara de manera
par uno con el otro claro sin olvidar los diagramas UML que es fundamental para ver el
proyecto de manera grafica y ordenada.
1.2 Antecedentes.
En continuacion se presenta repositorios describen sistemas en la que involucran
juegos educativos, y inteligencia artfiacial para el mismo.

5
1.1.1 Antecedentes internacionales.
Se menciona herramientas como desafios de desarrollo de juegos inde referentes al
presente proyecto.
⮚ (Esquivel, 2014, p.44)Uno de los problemas que enfrentan nuevos juegos es el
gameplay (mecanicas del juegos) sin olvidar los graficos de los mismos en la actualidad
se le aplica el realismo tanto como texturas como la iluminacion en la que buscan que
el juego sea visual atractivamente olvidando de que sea entretenido, lo deficil para el
usuario es enganchar al juego que se ha desarrollado para el y es complicado si el
usuario no ha formado vinculos con el juego mismo, en la cual el concepto centarl de
discuciones sobre video juegos. Marianne Krawczyk Jeannie Novak trata que el juego
debe de ser narativamente bueno como tambien visualmente .
⮚ (Akemi, 2025, p .11) La adoptacion de integrar inteligencia artificial en los juegos se
destaca en la automatizacion de desarrollo en las areas repetidas como la generacion
de terrenos, con el fin de reducir el trabajo humano y el mismo en el esfuerzo en la que
contienen inteligencia artificial en los motores como Unity como Unreal como tambien
Godot para ayudar con el desarrollo de mecanicas dentro del juego que se desarrolla
⮚ (Bustramante, 2019, p.44) Debido a la variedad que se encuentra en el mercado es
complicado sobresalir en la cual esta la idea inicial con la que sedesea desarrolalr uno
mismo, ademas lo que se busca mas son los graficos en los cuales generan mas ventas
lo tipico en juegos con gran grafico, como tambien estan los microtransacciones para
los juegos libres en la cual es una forma de concegir ganancias.

6
1.1.2 Antecedentes nacionales.
En los siguientes antecedentes muestra las metodologias que se usa para el desarrollo
de los videojuegos.
⮚ (Mamani, 2015, p.25) Enfatisa que una de las metodologias para el desarrollo de
juegos es usar la “cascada espiral” o usar el “metodo po nivel” con lo que se vea
conveniente lo siguiente trata de forma clara para hacer un desarrollo de juegos en 3D
es tener primero diseñar el esqueleto, lo denomina el nivel cero donde tenemos el
primer prototipo del juego en la cual se encarga de ordenar nuestras ideas, usando las
parcticas basadas en niveles.
⮚ (Canaviri, 2015, p.26) Enfatisa igual el uso de desarrollo de juegos es usando la
metodologia SUM en la que se destaca en lo siguiente adapta la metodologia Scrum
Team, SUM se basa en sub-roles en la que trata a integrantes de un equipo enfocarce
en su trabajo como: audio-visual es enfoca en su rol como lo mismo de los diseñadores
graficos, es perfecto para los que no son jugadores frecuentes pero muestra los
mismos resultados al igual que Scrum.
1.2. Planteamiento del problema.
1.2.1. Problema Principal.
El usuario tiene dificultad en la primera comprensión del fin que tiene el entorno virtual
en la cual no tiene presente la causa de las acciones a su entorno, el efecto en que las
acciones del usuario sobre el entorno en como afecta al ambiente del juego y como estos los
agentes como la flora y fauna interactuán sobre el mismo ambiente, en la cual el usuario haga
con ese entorno es la decisión del mismo usuario.

7
1.2.2. Formulacion del problema.
¿Como se se podria influenciar al usuario evitar que la falta de mecanicas no sea
adecuado a seguir con el juego y a la vez vea las causas de sus acciones que represente sus
efectos de lo mismo?
1.2.3 Problemas Especificos.
⮚ Establecer como las decisiones del usuario afecta el entorno del juego en tiempo ral
inculyendo: cambio visual, cambio en agentes, sonido, en lo que provoca un estimulo nuevo
al jugador.
⮚ Diseñar agentes con un sistema adapadativo con inteligencia artificial reactiva con cada
accion del usuario, en la cual ocaciona el jugador experimente el efecrto distinto en los
agentes.
⮚ Implementar indicadores en la cual los acciones del usuario realiza en el juego en la cual
fomentar lo que ocaciona con sus actos en el mismo juego, con el uso de fomentar las
acciones que ocaciona en como afecta el ambiente.
⮚ Diseñar estructuras en la cual los agentes y los cambio de cada accion del usuario no afecte
el rendimiento del juego, esto es afecta que el usuario no persiva fallos al jugar el juego.
1.3.1 Objetivos.
1.3.2 Objetivos generales.
Desarrollar un Sitema de un videojuego con inteligencia artificial reactiva para fomentar
la conciencia ambiental con los acciones del usuario a sus agentes y entorno dentro del mismo
juego.

8
1.3.3 Objetivos Especificos.
Analizar como se va ha realizar la interacion del usuario con el mismo juego en ello
debe no pierda de informacion con la interaccion y ser intuitivo las mecanicas.
Diseñar los modulos en como va ser la interaccion del usuario con el juego en la cual
debe de ser comprensible interactivo evitando demaciada redundancia y desinteres de los
mismo usuarios.
Implementar Agentes con inteligencia artificial en la cual actuaran segun el cambio con
su entorno en la cual el usuario debe de hacer la tomoa de decisiones con cada objeto
mecanico del juego.
Crear entornos tridimensionales inmersivos que representen un bosque afectado por
la contaminación y su proceso de recuperación tomada por las desiciones del mismo usuario.
1.4.1 Justificaciones y limitaciones.
1.4.2 Justificacion Tecnica.
En las unidades educativas que en la que me enfoco no tienen hosting o servidores
en la cual se puede ser muy limitado que contienen tienen uso de unidades de computo de
media gama en la cual se usan para trabajos escolares de un nivel de escritorio.
Debido que las unidades educativas los usuarios comun mente usan unidades de
computo de media gama en la cual usan recursos muy limitados como el mismo software
como usar un sistema operativo minimo de windows 10, cpu de core i5, ram de 8GB.
1.4.3 Justificacion Social.
El sistema del juego esta enfocada que la informacion del usuario tendra un sistema
de evaluacion para fomentar las desiciones que tomadas y como afecta al hambiente.

9
El sistema tendra modulos como registro de usuarios en la cual podra intercalar entre
cuentas de usuario para tener diversos mundos con entornos distintos en la cual podra realizar
en cada uno acciones distintas.
La estructura de los agentes del juego podran mostrar los acciones que fueron
involucrados por el usuario que esta en su mismo mundo y esto podra ser evaluado con el
sistema de evaluacion del mismo juego.
El sistema del juego otorgara logros en las cuales fueron evaluadas en el mismo juego
y podran obtener diferentes tipos de agentes.
1.4.3 Justificacion Economica.
El sistema del juego sera es libre en la cual no esta enfocada ha ser de uso comercial
en la cual las unidad educativa podra experimentar el sistema del juego sin tener limitaciones
con el mismo el juego puede remplazar actividades fisicas como compra de suministros
como:(papel, plastico, metales) reducion los costos de manera anual tambien el mismo juego
no necesita servidores o computo potente para que puedan experimetar el sistema del juego.
1.5.1 Metodologia.
1.5.2 Enfoque.
En el enfoque de la recoleccion de datos sera cuantitativo, por la razon que los datos
se usaran para la evaluacion de interes de los mismos usarios en la cual los datos se utilizaran
paa el desarrollo en donde cada dato recolectado sera para prueba y error.
1.5.3 Tipo de diseño.
El diseño de la investigación es de tipo observacional y experimental, fundamentado
en la metodología de “playtesting”. Este método se centra en la recopilación de datos directa
y en el análisis del comportamiento de los usuarios mientras interactúan con el juego.El

10
objetivo principal es comprender la experiencia real del jugador para identificar áreas de
mejora. El playtesting se basa en tres principios clave como:
⮚ Observación del comportamiento (Descriptivo): Se observa y registra de manera
cómo interactúan los jugadores con el juego incluy: reacciones como desiciones que
toman,como que el usuario ve el interfaz y lo entienda sin un manual, el objetivo es
obtener una descripción que ayude al diseño y desarrollo del mismo.
⮚ Análisis de la experiencia (Cualitativo): El objetivo es ver al usuario el jugador en si
interactuar con el sistema del juego, la idea es simple ver comoreacciona con el juego
ver si los resultados son como uno espera que es entretener al usuario con el juego
que se a desarrollado.
⮚ Análisis de la utilidad (Utilitario): La información recopilada se utiliza de manera
práctica para validar y mejorar el diseño.Es utilizar al usuario para recolectar datos en
las cuales son: reconocer errores en el juego o partes especificas del diseño que no le
agradaron, esto ayuda a ver desde un punto de vista distinto para corregir sea diseño
o errores del mismo. Esto garantiza que las decisiones de diseño se basen en
evidencia real de la experiencia del usuario (Strong National Museum of Play, 2020).
Mediante se use esta metodologia de investigacion se debe de tener encuenta
que el desarrollador no debe de intervenir durante las sesiones de prueba para obtener
una perspectiva del usuario. El playtesting permite a los desarrolladores recolectar
información, aplicar cambios y volver a probar asegurando que sea entretenido para
el publico como los usuarios de prueba.

11
1.5.4 Motodologia de desarrollo de software.
La metodologia del desarrollo se utilizara es el “Scrum” donde encaja a la perfeccion
con “playtesting”. Recolectas datos de manera experimental con “playtesting”para construir el
juego con la metodologia de desarrollo “Scrum” en punto sencillo “dato nuevo desarrollo
nuevo” obtener datos para desarrollar ambos de manera simultanea en la cual “Scrum” es
escalable cada que se necesite implementar un nuevo modulo o requerimiento seran
proporcionados por los mismos datos recolectados del usuario usando “playtesting” en la cual
se podra hacer cambios de manera escalable implimentando las aplicaciones necesarias
como tambien usar diagramas UML en la cual muestra de manera grafica y escalable de cada
desarrollo.
1.6.1 Herramientas.
1.6.2 Godot Engine.
Es un motor de videojuegos libre en la cual esta hecha para desarrollo de
juegos multiplataforma, ademas los juegos que se pueden realizar en el mismo son los mas
usados en el mercado 2d y 3d ademas que cuenta con una gran comunidad de juegos indi.
El motor de Godot usa lenguajes de programacion como C# o JsdScrip para el
desarrollo de juegos dentro del motor en la cual se puede usar cualquiera de las 2 para un
desarrollo indi la diferencia con otro motor este no contiene un creador de modelos 2d o 3d
por lo cual se debe de tener los modelos y exportarlos dentro del motor.
1.6.3 Blender.
El software de Blender es un software libre ademas que es usado comunmente para
la creacion de diseños 3d y 2d como son los: avatares, agentes, paisajes etc. Blender es ideal
para los desarrolladores indi que se dedican en esta area de desarrollar juegos en 3d.

12
El software es compatible con diferentes sistemas operativos como son los: Windows,
Mac, Linux. Blender esta disponible en cualquiera de las plataforma lo que se puede realizar
con el mismo es: modelado 3d, animacion, pruebas fisicas, creacion de esculturas digitales,
creacion de juegos con motores externo. Los archivos en la que se exporta por nativo de
blender es el .blend para juegos y usarlos en motores es el .fbx tambien esta el mezclar
elementos como 2d y 3d.
1.6.4 Sistema operativo Arch linux.
El sistema operativo de linux es ligera en la cual consume un menor recurso en la cual
es ideal para desarrolladores que necesiten tener los recursos optimizados al usar
herramientas o software pesados para desarrollo de sistemas de informacion en la cual una
distribucion como Arch es ideal para el desarrollo.
Arch linux usa el modelo rolling realse lo que significa que siempre esta actualizado a
comparacion con otra distribucion linux esta no necesita reinstalar una version cada vez que
lo necesite, usa el gestor de paquetes pacman ademas que cuenta con una gran cantidad de
usar un software en el ecosistema de Arch como:AUR, Faltpak, Snap, Wine para el software
de Windows. En la cual no es un problema encontrar software ademas cuenta con una gran
comunidad activa.
1.7.1 Alcances.
1.7.2 Alcance Tematico.
El proyecto tiene como alcance por el momento cuenta con cuatro midulos en las
cuales puede segir ampliandoce a medida del desarrollo ahora estan los modulos de las
funciones basicas de un video juego como: Usuario en la cual es la creacion de una cuante
una o varias, Inicio este modulo esta el inicio del juego en la cual el usuario dispone de

13
configuraciones del sistema he intercambio de cuentas, Comienza del juego en este modulo
el usuario interactua con el mismo juego como tambientiene la disposicion de configuracion
basica del sistema, Guardado en este modulo cuenta con el guardado de la misma partida
como tambien el guardado de las evaluaciones del mismo.
1.7.3 Alcances Geograficos.
El sistema del juego esta siendo desarrollada para las unidades educativas en la cual
los usarios de la edad desde los 13 años para adelante en la cual podran los usuarios
interactuar con el sistema del juego.
1.7.4 Alcance Temporal.
El proyecto esta enfocada para un perido de 2 años en la cual esta se basa en
desarrollo del mismo en la cual son: analisis de diseño, desarrollo implementacion, pruebas,
tambien se tendra presente las reuniones para las funciones del sistema del juego con los
usuarios.
1.8.1 Limites.
El desarrollo y despliegue del videojuego educativo para fomentar la conciencia
ambiental presenta las siguientes limitaciones incluyendo alcances como tambien la parte del
desarrollo del mismo juego:
1.8.2 Alcance de conexion a una red.
El sistema del juego no estara conectada ha internet he servidores.
El mismo juego no estara conectada ainternet en si no existen cuentas en un servidor
fisico.
El juego no podra mandar actualizaciones por la red en la cual debe de hacerce manual

14
1.8.4 Restricciones en distribucion del juego.
Al no tener servidores o conexion a internet para la descarga del juego debe de realizar
de manera fisica con pendrivers. Imposibilidad de enviar actualizaciones automaticas en la
cual las universidades deben de realizarlo de manera manual.
1.8.5 funcionamiento en linea.
El juego no puede incluir el modo multijugador como tambien no incluira una tabla de
calificacion global incluyendo la interaccion entre los mismos usuarios en diferentes
ciomputadoras.
No sera posible la sincronizacion de progreso en la cual los usuarios tendran
limitaciones de solo usar una maquina por usuario.

15

CAPÍTULO II
MARCO TEORICO

16
2. Introduccion
En esta sección de herramientas tecnologicas y el desarrollo personal a la area
de la tecnologia se mostrara en este capitulo un recorrido de heramientas y metodos para lel
desarollo de videojuegos en la como lo este mismo en la cual lo siguiente es listar una lista de
elementos de desarollo y analisis para los sitemas de videojuegos.
2.1 Juego tipo Sandbox.
No hace muchos años la aventura de un videojuego era algo lineal, para ir del punto
A al C tenías que pasar por B si o sí. Eso cambió con la aparición de los juegos tipo Sandbox,
seguro que te suenan Minecraft o Grand Theft Auto, juegos con mundos abiertos en los que
puedes hacer prácticamente lo que te dé la gana. Bien, pues vamos a saber un poco más
sobre el término sandbox. Quédate a leer.
2.1.2 Termino Sandbox.
Un juego sandbox, también conocido como juego de caja de arena, es un videojuego
que se caracteriza por ofrecer al jugador un alto grado de libertad para explorar y experimentar
dentro de un mundo virtual. A diferencia de los juegos lineales, donde la progresión del
jugador está guiada por una historia o una serie de objetivos específicos, los juegos sandbox
no tienen un camino predefinido (U-tad, 2024, párr. 2).
En un sentido más literal, el término «sandbox» también se refiere al área física dentro
del juego donde el jugador tiene esta libertad de exploración y experimentación. Esta área
suele ser un espacio abierto y sin restricciones, donde el jugador puede construir, crear,
destruir y manipular objetos del juego a su antojo (Cazarrez,2010,p70).

17
En este tipo de juegos, el jugador es libre de crear sus propias metas, interactuar con
el entorno a su manera y descubrir las posibilidades que ofrece el juego a su propio ritmo.
Esto fomenta la creatividad, la experimentación y la resolución de problemas de forma abierta.

La idea de la «caja de arena» se origina en los espacios de juego infantiles donde los
niños pueden jugar libremente con arena, moldeándola y creando sus propias estructuras sin
seguir reglas o instrucciones específicas. De ahí la analogía con los videojuegos que ofrecen
este tipo de experiencia abierta y creativa.
En resumen, el término «sandbox» en los videojuegos representa tanto un estilo de
juego como el espacio virtual donde se desarrolla este tipo de experiencia.
2.1.3 Caracteristicas de un juego tipo Sandbox.
Son videojuegos que dan al jugador una gran libertad para explorar e interactuar con
un mundo virtual. A diferencia de los juegos lineales, no hay un camino predefinido a seguir.
En un juego sandbox, el jugador es libre de:
⮚ Crear sus propios objetivos: No hay una historia principal que dicte la progresión del
jugador.
⮚ Explorar a su propio ritmo: El mundo del juego está abierto para ser descubierto sin
restricciones en la cual el jugado puede explorar el mismo mundo sin la necesidad de
tener una historia extricta de como tiene que avanzar.
⮚ Experimentar con diferentes mecánicas: El juego ofrece herramientas y objetos
para interactuar de forma creativa.

18
⮚ Resolver problemas de forma abierta: No hay una única forma correcta de superar
los desafíos en la cual el mismo juego puede tener diferentes caminos pero el juego
conduce a un unico final, en la cual no importa de que lado de la mapa del juego
comience es libre pero el final del juego conduce a un unico camino.
2.2 Motor de Videojuegos.
Un motor de juegos, o game engine, como está llamado en inglés, es un conjunto de
herramientas de software o API creadas para optimizar el desarrollo de un videojuego. Esto
normalmente incluirá un bucle de juego (Blender,2025,p1).
Como mínimo, un game engine debería tener un motor de renderizado. Esto puede
parecer redundante, pero el motor de renderizado maneja la gestión de la memoria y el
almacenamiento en búfer de las imágenes y los objetos 3D,(ComunityBlender,2025,p12).
Algunos de los motores más avanzados, como Unity, incluirán muchos otros componentes
como:
⮚ Bucle de juego integrado
⮚ Motores de animación
⮚ Motores de audio
⮚ Multijugador y herramientas de red
⮚ Herramientas de realidad virtual
⮚ Iluminación, sombreadores, sombras, materiales de objetos y otros componentes
visuales

19
⮚ Inteligencia Artificial (IA)
2.2 Godot engine.
Godot fue desarrollado inicialmente por un estudio de juegos argentino. Su desarrollo
comenzó en 2001, y el motor se reescribió y mejoró enormemente desde su lanzamiento de
código abierto en 2014.
2.2.1 GDScript.
En Godot, es posible escribir código utilizando los lenguajes de programación GDScript
y C#. Aunque GDScript es un lenguaje específico de Godot, las técnicas que aprenderás con
él se aplicarán a otros lenguajes de programación(Calden,2019,p5).
Ten en cuenta que es completamente normal que un programador aprenda y utilice
varios lenguajes. Los lenguajes de programación tienen más similitudes que diferencias, así
que una vez que domines uno, puedes aprender otro mucho más rápido.
2.2.3 Nodos.
Todos los motores de videjuegos giran alrededor de abstracciones que usas para
hacer sus aplicaciones. En Godot, un juego es un árbol de nodos que se agrupan juntos en
escenas. Puedes enlazar estos nodos para que pueden comunicarse por medio de señales
en la cual es ecencial utilizar una estructura con una buen alogica (Cortez,2021,p21).
2.2.4 Ecenas.
En Godot, puedes dividir tu juego en escenas reutilizables. Una escena puede ser un
personaje, un arma, un menú en la interfaz de usuario, una sola casa, un nivel entero, o
cualquier cosa que se le ocurra. Las escenas de Godot son flexibles; cumplen tanto la función
de prefabs como de escenas en otros motores de juego en la cual es tener varias ecenas en

20
la cual es conveniente si el juego se basa en capitulos o en modulos los cuales es facil de
mantener al momento de modificar una area del juego(Valinez,2021,p23).
El motor de juegos Godot Engine es uno de varios motores que oersisten en la
actualidad la diferencia de las demas es que el motor de Godot engine es de uso libre sin la
necesidad de adquerir un alicencia o adquerir algun paquete Premium, la forma en la que
adquiere recursos Godot es por la comunidad ellos lo mantienen como tambien tienen
fiananciamiento de empresas ademas que es posible donar a Godot con el fin de mantenerlo
(Vazques,2020,p32).
2.3 Inteligencia Reactiva
La IA reactiva, un subconjunto de la inteligencia artificial, se centra en tomar decisiones
en tiempo real basadas en la entrada sensorial. A diferencia de otros modelos de IA que se
basan en reglas predefinidas o

bases de datos extensas de experiencias pasadas, los

algoritmos de IA reactiva están diseñados para reaccionar de inmediato a estímulos sin
conocimientos previos o datos. Imagina un robot que puede adaptarse y

responder

rápidamente a su entorno sin depender de información preexistente. Eso es la IA reactiva en
pocas palabras (Loeness,2018,p21).
2.3.1 Funcionalidad de la IA reactiva
La IA reactiva se centra en un agente que recibe información sensorial de su entorno,
la procesa a gran velocidad y Toma acciones que optimizan sus posibilidades de éxito. Este
agente puede ser un programa de IA o un robot. A diferencia de los sistemas basados en
reglas tradicionales o los modelos de aprendizaje automático, la IA reactiva no requiere
conjuntos de datos extensos o entrenamientos prolongados. En cambio, responde a
situaciones en tiempo real y se adapta sobre la marcha, lo que la hace perfecta para
aplicaciones que requieren toma de decisiones rápidas y precisas (Guisbert,2022,p34).

21
2.3.2 Funcionalidad en diversos campos
La IA reactiva es una tecnología versátil capaz de lograr proezas notables en diversas
aplicaciones. Por ejemplo, un agente como un cachoro en la cual debe de buscar agua y
comida para segur vivo y lo busca hasta encontrarlo en sentesis prueba y error. Este es un
ejemplo de IA reactiva en acción, aprendiendo y mejorando su rendimiento sin instrucciones
explícitas o datos de entrenamiento en la cual esta comun mente en la mayoria de los juegos
en lo cual los agentes deben de aprender du su entorno para seguir su funcionamineto
principal (Montes,2023,p56).
2.4 Metodologia de desarollo Scrum.
Scrum es un marco de trabajo ágil a través del cual las personas pueden
abordar problemas complejos adaptativos a la vez que se entregan productos de forma
eficiente y creativa con el máximo valor. Así, Scrum es una metodología que ayuda a los
equipos a colaborar y realizar un trabajo de alto impacto. La metodología Scrum proporciona
un plan de valores, roles y pautas para ayudar a tu equipo a concentrarse en la iteración y la
mejora continua en proyectos complejos. Por otra parte, deberás saber que en Scrum se
trabaja con equipos pequeños multidisciplinares en ciclos iterativos centrados en el cliente y
se crea un producto de forma incremental(Villca,2023,p32).
2.4.1 Como funciona Scrum.
Entonces, ¿qué es Scrum exactamente? ¿Qué hará tu equipo si usas Scrum? Así es
como se desarrolla el proceso Scrum:
⮚ Organiza tu trabajo pendiente: Para comenzar un sprint de Scrum, el líder del equipo
(también conocido como Scrum Master) identificará qué trabajo extraer de la lista de
tareas pendientes, es decir, el trabajo que debe realizarse. Para llevar a cabo el mejor
sprint de Scrum posible, asegúrate de que el trabajo pendiente para el producto esté

22
claramente documentado en un solo lugar. Considera usar una herramienta de gestión
de proyectos para recopilar toda esta información.
⮚ Sprint Planning: Realiza una sesión de planificación del sprint. Antes de que puedas
comenzar el sprint de Scrum, necesitas saber en qué te enfocarás. Durante tu sesión
de planificación del sprint, evaluarás en qué parte del trabajo pendiente se centrará tu
equipo durante este sprint de Scrum específico. Para comenzar, prueba nuestra
plantilla gratuita para planificación de sprints.
⮚ Comienza tu sprint de Scrum: Por lo general, un sprint dura dos semanas, aunque
puedes tener sprints más cortos o más largos dependiendo de lo que funcione mejor
para tu equipo. Durante tu sprint, tu equipo trabajará en las tareas pendientes que has
establecido durante la sesión de planificación del sprint.
2.4.2 Product Backlog
El Product Backlog es el artefacto Scrum que recoge la lista del trabajo que debe
realizarse. El encargado del Product Backlog o pila de producto es el product owner que
deberá clasificar los elementos de esta lista. Ten en cuenta que el hecho de que haya
elementos en la lista de trabajo pendiente del producto no significa que tu equipo trabajará
en ellos; más bien, los elementos de la lista del Product Backlog son opciones en las que tu
equipo puede trabajar durante un sprint de Scrum. Los encargados del proyecto deben
reordenar y actualizar con frecuencia el trabajo pendiente del producto, en función de la
nueva información y la lista de requisitos que obtengan de los clientes, del mercado o del
equipo del proyecto.

23
2.5 Diagrama unificado UML.
UML , abreviatura de Lenguaje de Modelado Unificado, es un lenguaje de modelado
estandarizado que consiste en un conjunto integrado de diagramas, desarrollado para ayudar
a los desarrolladores de sistemas y software a especificar, visualizar, construir y documentar
los artefactos de los sistemas de software, así como para el modelado de negocios y otros
sistemas no software.
El UML utiliza principalmente notaciones gráficas para expresar el diseño de proyectos
de software. El uso de UML ayuda a los equipos de proyecto a comunicarse, explorar diseños
potenciales y validar el diseño arquitectónico del software. En este artículo, le brindaremos
ideas detalladas sobre qué es UML, la historia de UML y una descripción de cada tipo de
diagrama UML, junto con ejemplos de UML.

2.5.1 Diagrama de Casos de Uso.
Un modelo de casos de uso describe los requisitos funcionales de un sistema en
términos de casos de uso. Es un modelo de la funcionalidad prevista del sistema (casos de
uso) y su entorno (actores). Los casos de uso permiten relacionar las necesidades de un
sistema con la forma en que este satisface dichas necesidades.

Piense en un modelo de caso de uso como un menú, similar al de un restaurante. Al
consultarlo, sabe qué hay disponible, los platos individuales y sus precios. También sabe qué
tipo de cocina sirve el restaurante: italiana, mexicana, china, etc. Al consultarlo, se forma una
idea general de la experiencia gastronómica que le espera. El menú, en efecto, "modela" el
comportamiento del restaurante.

24
Figura 1.
Diagrama de caso de uso

2.5.2 Diagrama de secuencia.
El diagrama de secuencia modela la colaboración de objetos basándose en una
secuencia temporal. Muestra cómo interactúan los objetos entre sí en un escenario específico
de un caso de uso. Con la capacidad avanzada de modelado visual, puede crear diagramas
de secuencia complejos con solo unos clics. Además, algunas herramientas de modelado
como Visual Paradigm pueden generar diagramas de secuencia a partir del flujo de eventos
definido en la descripción del caso de uso.

25
Figura 2.
Diagrama de secuencia

2.5.3 Diagrama de clases.
Este diagrama describe los tipos de objetos del sistema y los diversos tipos de
relaciones estáticas que existen entre ellos.
2.5.3.1 Relaciones.
Hay tres tipos principales de relaciones que son importantes:
⮚ Asociación : representa relaciones entre instancias de tipos (una persona trabaja
para una empresa, una empresa tiene varias oficinas).
⮚ Herencia : la adición más obvia a los diagramas ER para su uso en programación
orientada a objetos. Tiene una correspondencia inmediata con la herencia en el diseño
orientado a objetos.

26
⮚ Agregación : Agregación, una forma de composición de objetos en el diseño orientado
a objetos.
Figura 3.
Diagrama de clases

27
2.6 Normas ISO Seguridad De La Información.

2.6.1 ISO/IEC 27001: Sistema de Gestión de Seguridad de la Información (SGSI)
Establece los requisitos esenciales y el marco de trabajo para establecer, implementar,
mantener y mejorar continuamente un Sistema de Gestión de Seguridad de la Información
(SGSI). Su enfoque principal es la gestión de riesgos para proteger la confidencialidad,
integridad y disponibilidad de los activos de información. (ISO, 2022, p. 5).
2.6.2 ISO/IEC 27002: Controles de Seguridad de la Información
Proporciona un conjunto de directrices y controles de seguridad de la información,
estructurados en categorías (organizacionales, de personas, físicos y tecnológicos). Esta
norma funciona como un código de prácticas para la selección e implementación de los
controles de seguridad mencionados en el Anexo A de la ISO 27001. (ISO, 2022, p. 11).
2.6.3 ISO/IEC 27005: Gestión del Riesgo de Seguridad de la Información
Ofrece directrices para la gestión sistemática del riesgo de seguridad de la información.
El estándar detalla el proceso para identificar, analizar, evaluar, tratar y aceptar riesgos dentro
del contexto de un SGSI, asegurando que las decisiones de gestión de riesgos son
consistentes y efectivas. (ISO, 2021, p. 15).
2.6.4 ISO/IEC 27701: Gestión de la Información de Privacidad (PIMS)
Es una extensión de las normas ISO 27001 y 27002 que proporciona un marco para
establecer, implementar, mantener y mejorar un Sistema de Gestión de la Información de
Privacidad (PIMS). Ayuda a las organizaciones a gestionar los requisitos de privacidad (como
el GDPR) al tratar la información de identificación personal (PII). (ISO, 2019, p. 7).

28
2.6.5 ISO/IEC 27017: Seguridad en Servicios en la Nube (Cloud Computing)
Proporciona controles de seguridad específicos y directrices de implementación para
la protección de la información cuando se utiliza la computación en la nube. Se dirige tanto a
los proveedores de servicios en la nube como a sus clientes, abordando la responsabilidad
compartida y otros riesgos únicos de los entornos cloud. (ISO, 2015, p. 4).
2.6.6 ISO/IEC 27018: Protección de PII en la Nube Pública
Es un código de prácticas enfocado en la protección de la Información de Identificación
Personal (PII) por parte de los procesadores de PII en la nube pública. Su principal objetivo es
asegurar que los proveedores de servicios en la nube actúen como procesadores de PII con
transparencia y ética, cumpliendo con las obligaciones contractuales y legales de sus clientes.
(ISO, 2019, p. 6).

29

CAPÍTULO III
MARCO PRACTICO

30
3. Introduccion
En este capítulo se detalla la situación actual del proyecto, en la que muestra el diseño
y desarrollo en graficas de como lo ve el usuario el sistema tambien de como funciona el mismo
de manera grafica y estructurada de la solución propuesta, utilizando el Lenguaje Unificado
de Modelado (UML) para documentar los componentes y la interacción entre ellos mostrando
la coneccion entre ellos.
Se describe las estrategis y desarrollo para del sistema propuestop ara complementar
la metodología de desarrollo que permitirá mostrar datos directos sobre la prespectiva del
usuario cómo interactúan con el juego.
3.1. Diseño y desarrollo de software.
La metodología Scrum proporciona un marco ágil que facilita el desarrollo del sistema,
al utilizar esta metodología, se pueden llevar a cabo análisis detallados y estructurados
en cada iteración y sprint, lo que permite un enfoque incremental y colaborativo.
3.1.1. Analisi y Requeqerimientos.
Las historias de Scrum nos ayuda ver el trabajo por hacer en la cual es conveniete si
se desea acelerar el trabajo en la cual las historias son los reuqerimientos en las cuales se
puieden destribuir en lo siguiente funcionales y no funcionales en las cuales es prioriadad
destingiralas.
los requerimientos funcionales son aquellos que hace que el sistema funcione en si es
el motor de un sistema entero y los no funcionales son requerimientos que deben de funcionar
cuales son inperseptibles como la carga de una pantalla no exeda cierto tiempo de limite en la
cual debed de ser analisado.

31
Tabla 1.
Historias de Usuarios.
ID
1

PRIORIDAD

RIESGO

TITULO

Muy alta

Alta

REGISTRO
USARIO

DESCRIPCION
DE El sistema debe de poder
crear

perfiles segun a la

preferencia del usuario
2

Muy alta

Media

SELECTOR
PERFIL

DE El sistema debe de poder
cambiar entre perfiles para
cambiar

las

partidas

existentes de cada perfil
3

Muy alta

Media

ELIMINAR PERFIL El sistema debe de poder
EXISTENTE

4

Muy alta

Alta

NAVEGAR
MENUS

eliminar perfiles existentes
POR El sistema debe de poder
conceder

ajustes del juego

como la gestion de perfiles y
actualizacion de estadisticas

32
ID
7

PRIORIDAD

RIESGO

TITULO

Muy alta

Alta

CONTROL POR
DEFECTO

DESCRIPCION
El sistema debe de
poder edentificar y ajustar el
teclado del equipo.

8

Muy alta

Media

MENSAJE DE
APAGADO

El sistema debe de
poder edentificar el cambio
de

encendido

a

apagado

cuando este en uso o no.
9

Muy alta

Media

GUARDADO DE
PARTIDA

El sistema debe de
poder edentificar la solicitud
de guardar el progreso de un
perfil del juego

3.1.2. Definición y diseño
Una herramienta fundamental en la metodología Scrum es el Product Backlog, que
gestiona y prioriza los requisitos del sistema en desarrollo dentro del proyecto. El Product
Backlog funcionará como una lista dinámica que contiene histórias de usuarios, tareas
técnicas y mejoras. Cada elemento se evaluará en función de su valor y urgencia, lo que
permitirá evaluar todas las funcionalidades que maximicen la eficiencia y satisfacción del
usuario.

33
Tabla 2.
Procutc backlog
MODULO

PRIORIDAD

BACKLOG

ELEMENTOS

DESCRIPCION

RESPONSABlE

BACKLOG
USUARIO

ALTA

1

2

REGISTAR

El sistema

ELIMINAR

debe de poder

UNO O

registrar Como

MULTIPLES

eliminar perfiles

PERFILES

existentes

INTERCAMBIA
R PERFILES

El sistema
debe de poder
intercambiar
perfiles por el
usuario y cada
perfil debe de
tener su propia
partida del juego

Brayan
Quispe

Brayan
Quispe

34
MODULO

PRIORIDAD

BACKLOG

ELEMENTOS

DESCRIPCION

DE BACKLOG
MENU DEL

ALTA

4

JUEGO

RESPONSABL
E

NAVEGAR

El sistema debe

Brayan

MENU

poder acceder al

Quispe

menu y poder
navegar en el
mismo
ALTA

5

INICIAR

El sistema debe

Brayan

PARTIDA

de poder dejar

Quispe

entrar a la partida
de un perfil
existente
6

AJUSTES

El usuario debe

Brayan

poder tener

Quispe

acceder a ajustes
de:video,audio,gu
ardar como salir.

PARTIDA

ALTA

ACTIVA

7

INICIO DE LA

El sistema debe

Brayan

PARTIDA

de poder mostrar

Quispe

en pantalla la
carga de la
partida

3.3 Situacion actual.

35
Este es un diagrama de flujo como va con el tema del punto de vista del usuario jugador
con el sistema del juego.

El contexto del juego es lo siguiente: el usuario es un automata dentro del juego
en la que se activa de su modo invernacion por lo que su bateria llego al 5% de energia como
al ser un automata debe de buscar una fuente de energia y para ello se encuentra en un mundo

36
colapsada no encuentra señales humanas y las plantas son anomalos en las cuales no existe
en su regiostro comun, el usuario debe de seguir los ordenes de un usb que contiene un audio
libro de un aventurero en la cual el automata cree ser ordenes humanas.
El contexto del juego es que el usuario es un automata y recore el nuevo
ambiente construyendo herramientas y fuentes de energia para seguir en funcionamiento por
las unicas ordenes seguidas por un usb que el jugadior sigue durante el juego hasta encontrar
requerimientos del juego donde cambian los ordenes hasta ese entonces el jugador debe de
seguir manteniendo al automata en el mundo libre.
El sistema del juego muestra como primero crear un nuejo jugador con un nombre que
el usuario le aisgan en la cual es la decision continuar con el juego con el usuario que creeo
con anterioridad en la cual puede seguir el juego del mundo abierto con solo un jugador creado.
El usuario dispone de la configuracion en la que puede salir del juego como los
ajustes iniciales lo que conlleva en un juego comunmente: volumen en donde aumenta y
reduce la salida del audio del juego, controles donde el usuario puede manipular y configurar
los controles a su comodidad como tambien ajustar los graficos seguna a la necesidad de la
unidad para un rendimiento fluido y sin perdida de la vision del juego.
3.4 Problema.
El problema actual se reducio por varias semanas para el diseño del juego en lo cual
debe de hacer lo siguiente encontrar una buena idea inicial de como va ser el juego como se
convertira un juego educativo y cuidado del medio ambiente en la cual lo principal no volver
aburrido el juego mismopara el usuario, en la cual se enfoco en buscar la manera de ser
entretenido y libre para que el jugador tenga mas tiempo para jugar.

37
Los problemas en las cuales se encontro con un tope de avance de desarrollo fue como
influir de manera discreta para influir al jugador en cumplir la idea de educar y ayudar al
ambiente en la cual se le agrego los modulos como: “ordenes de” usb en la cual al principio el
jugador tiene solo las ordenes de explorar y registar su entorno.
Uno de otros problemas hubo en tener dificultan en el juego para no ser aburrido en la
cual aprovechando la falta de humanos y dejaron atras varios de sus creaciones del tiempo
en la cual solo siguen ordenes de humanos que dejaron de existir mas las plantas anomalos
se le mete la dificultad de tener varios tipos de automatas en la cual cumplian funciones
simples como recoleccion de metal, limpieza de areas para construcicines que no necesitaran,
plantas como hongos en la que votan poros que confunden el sistema del automata.
Ahora el problema principal era meterle inteligencia artificial en la mayoria de los
agentes usara inteligencia artificial reactiva pero falta uno mas importante es la inteligencia
artificial en donde el jugador interactue con el mismo y pueda ver como lo enseña para ello
agregare a un compañero que encontrara a lo largo del camino en el que el jugador encuentra
para poder enseñarlo y lo denomine con el nombre de “HECO unidad 02” en la cual es un
automata que aprende y replica las acciones del jugador y tambien es un elemnto principal
por que junto con “Heco” llega al final del juego.
Uno de los problemas que he tenido fue en meter mi vision del juego no tenia pensado
en hacer un juego con un final que es derotar aun jefe o tener un final como si terminara un
capitulo en la cual es agregar un final donde el automata en si el jugador deja de seguir las
ordenes y tiene una nueva orden que es “crear nuevas ordenes” y es dodne termina el juego
sin final de deretar un jefe o un final de un heroe, es un final donde un automata es libre de
elegir su destino.

38
Diagrama de contexto propuesto.

En este digrama de “entrada proceso y salida” es una muestra de como actuara el
sistema para el usuario en la cual se puede observar como el uusario crea un nuevo jugador
en la cual pueda acceder al inicio del juego ademas de poder crear uno o mas jugadores para
comenzar de nuevo el juego o usar otra cuenta para una partida diferente.
En la parte del proceso muestra el sistema del juego hambiental donde muestra como
la “inteligencia artficial reactiva” estara presente dentro del ecosistema del juego despues
guiardar ese mismo progreso en una base de datos en donde estan los requerimientos del
mismo juego desde reproducir un usb hasta tomar la desicion de plantar una nueva planta.
En la figura de la diagrama con respecto a la salida es lo que el usuario aprecia en si
lo que ha logrado lo que ha vivido dentro del ecosistema del juego se mostrara los logros como

39
las acciones que ocaciono dentre de su ecosistema, podra ver la historia de su automata
mostrando como su automata lo ha pasado en el mundo que el usuario lo que ha estado
haciendo.
3.5 Ingenieria de requerimientos.
3.5.1 Requerimientos funcionales.
En esta seccion se encuentra los requerimientos funcionales del sistema como
tambien lso requerimientos funcionales para el desarrollo dentro del mismo juego.
REQUERIMIENTOS
GESTION DEL USUARIO.

SUB-REQUERIMIENTOS
REGISTRO

DESCRIPCION
El usuario debe de poder

USUARIO: registar un nuevo perfil de
jugador para poder ingresar
al

sistema

con

el

perfil

jugador para poder acceder
al

juego

partida .

y

guardar

la

40
REQUERIMIENTOS

SUB-REQUERIMIENTOS

DESCRIPCION

ELIMINAR El jugador debe de tener la
USUARIO: opcion de eliminar un perfil
existente

borrando

permanentemente todos los
datos del juego de ese perfil.

CARGAR PARTIDA: El usuario debe de póder
cargar la partidade un perfil
existenet

y

progreso

de

continuar
la

el

misma

partida.

NAVEGAR POR

el usuario debe de poder

MENUS: navegar en el menu principal
y poder manipular ajustes,
perfiles,
progreso,
obtenidos.

ver

historial
ver

de

logros

41
REQUERIMIENTOS

SUB-REQUERIMIENTOS
DESBLOQUEAR

DESCRIPCION
El juego debe de poder

CONTENIDO: desbloquear requerimientos
del

mismo

juego

recursos,

como:

habilidades,

niveles.

CONTROL DEL JUEGO.

CONTROLAR El usuario como jugador
PERSONAJE: debe de poder controlar al
personaje principal usando
raton y teclados y poder
hacer

movimientos

como:

saltar,

correr,

recoger,

inspeccionar, abrir panel de
lectura de mensajes.
GESTIONAR EL El interfaz del juego debe de
INTERFAZ: poder mostrar la informacion
real del personaje que el
usuario

controla,

como

salud, recursos,ETC.

:

42
REQUERIMIENTOS
AUDIO Y VIDEO.

SUB-REQUERIMIENTOS

DESCRIPCION

AJUSTAR VIDEO: El usuario debe de poder
controlar el tamaño del video
del juego y modificarlo como:
(ventana/pantalla completa)
incluyendo
calidad

como

grafica

tambien
desde

el

menu de opciones antes de
iniciar o continuar el progreso
de la partida de un perfil.

AJUSTAR AUDIO: El jugador debe de poder
ajustar la salida del audio del
juego como poder controlar
de manera general del juego
como tambien individuales
como:
dialogos.

musica,

efectos,

43
REQUERIMIENTOS

SUB-REQUERIMIENTOS

DESCRIPCION

MOSTRAR Al terminar la historia del
CREDITOS: juego el sistema del mismo
debe

poder

mostrar

los

creditos de desarrollo del
juego.

3.5.2 Requerimientos no funcionales.

REQUERIMIENTOS
REQUERIMEINTO DE
USABILIDAD.

SUB-REQUERIMIENTOS

DESCRIPCION

Un jugador nuevo debe de
FACILIDAD DE
APRENDIZAJE: poder entender los controles
basicos como tambien de
poder enteder la mecanica
del juego dentro de los
primeros 5 minutos del juego
sin la necesidad de tener un
manual del juego.

44

REQUERIMIENTOS

SUB-REQUERIMIENTOS
CURVA DE DIFICULTAD:

DESCRIPCION
El juego debe de poder
aumentrar su dificultan con
el avance del juego en la
cual debe de ser progresiba
y justa despues de que el
usuario haya dominado las
mecanicas anteriores antes
de la dificultad

2.
REQUERIMIENT

El juego debe mantener una
TASA DE CUADROS
ESTABLES: tasa de cuadros estable y

OS DE

jugable como minimo de 30

RENDIMIENTO.

FPS ha 60 FPS en el
hardware incluso en esenas
con mas actividad.

45

REUERIMIENTOS

DESCRIPCION

SUB-REQUERIMIENTOS

El juego debe no debe de
CONSUMO DE
RECURSOS: consumir mas de el 80% de
RAM del hardaware en la
cual el objetivo es consumir
la

menor

cantidad

de

recursos de una unidad.

3.5.3 Requerimiento de fiabilidad.
REQUERIMIENTO

SUB-REQUERIMIENTO

DESCRIPCION

REQUERIMIENTO DE

TOLERANCIA:

El juego no debe de poder

FIABILIDAD.

cerrarse inesperadamente y
poder controlarla mostrarndo
mensajes de alerta en la que
le de tiempo suficiente al
usuario

de

entender

la

situación.
ESTABILIDAD

El juego debe de guardar y

DE PARTIDAS:

notificar.

46

REQUERIMIENTOS

SUB-

DESCRIPCION

REQUERIMIENTOS
REQUERIMIENTOS DE

PROTECCION

Los archivos como: progreso

SEGURIDAD.

DE DATOS:

de partida, itms. Deben de
estar

protegidos

modificaciones

faciles

ante
o

manidulacion de los mismos.

INSTALACION

El proceso de Instlacion y

HE

Desintalacion del juego debe

DESINTALACION de ser sencillo y limpio sin
:

dejar residuos del juego en
el sistema operativo.

47

ANEXOS

48
Diagrama de Las Normas Iso 27000.

49
Diagrama de caso de uso

50
Diagrama de caso de uso

51
Esquema de Funcionamineto dentro de la AI

52
Diagrama de actividad

53
Diagrama de secuencia

54

Diagrama de Clase

55
Tabla de base de datos relacional y no relacional

56
Tabla de frameworks para desarrollo de videojuegos

57
Tabla de arquitecturas de software y sus usos

58
Tabla de costos para desarrollar un juego en PC con Godot

59
Tabla de Database Multidimencional(Cubo)

Los cubos multidimensionales permiten analizar datos desde múltiples perspectivas
(por ejemplo: tiempo, usuario, nivel del juego).
Se usan para consultas rápidas y complejas, como “¿Qué niveles tienen mayor tasa
de abandono por edad del jugador?”.
Pueden

estar

basados

estructuras propias (MOLAP).

en

bases

de

datos relacionales

(ROLAP) o

en

60
ARBOL DE PROBLEMAS

61
Captura de imagenes Avance del Programa dentro de godot

62

Diseño de Blender

63
Captura de Diseno Layouts

64

