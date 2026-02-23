# Unidad1_-Graficación
**Temario:**
Unidad I. Introducción a la graficación por
computadora.  
1.1. Historia y evolución de la graficación por    computadora.

1.2. Áreas de aplicación.

1.3. Aspectos matemáticos de la graficación.

1.4. Modelos del color: RBG, CMY, HSV y HSL.

1.5. Representación y trazo de líneas y polígonos.

  1.5.1 Formatos de imagen.
(En este apartado vas a colocar las prácticas de dibujo de un polígono y la flor de la vida, como ejercicio práctico)

1.6. Procesamiento de mapas de bits.  

# Introducción 
La graficación por computadora es la disciplina que estudia cómo crear, representar, manipular y mostrar imágenes digitales mediante algoritmos y dispositivos electrónicos. No se trata únicamente de dibujar figuras en pantalla, sino de transformar información matemática en representaciones visuales que puedan ser interpretadas fácilmente por el usuario.

1. Permite comunicar información compleja de forma visual.

2. Convierte datos numéricos en imágenes comprensibles.

3. Es fundamental en casi todos los sistemas informáticos modernos.

4. Combina programación, matemáticas, física y diseño.

En términos simples: la computadora calcula números y esos números se convierten en píxeles que forman imágenes.

# 1.1. Historia y evolución de la graficación por computadora.
La graficación por computadora es una de las áreas más importantes de las Ciencias de la Computación, cuyo objetivo es desarrollar principios, técnicas y algoritmos para generar y manipular imágenes digitales mediante una computadora. Estas imágenes pueden variar desde representaciones simples en dos dimensiones hasta modelos tridimensionales complejos con apariencia realista.

Esta disciplina permite establecer una interacción visual directa entre el usuario y la computadora, facilitando la comunicación de información, ya que las imágenes suelen ser más claras y comprensibles que el texto. Por ello, se considera vigente la idea de que una imagen vale más que mil palabras.

Con el avance de la tecnología y de los dispositivos electrónicos, la capacidad de generar gráficos ha evolucionado notablemente. Hoy en día, prácticamente cualquier computadora cuenta con capacidades gráficas, lo que ha convertido a la graficación en una herramienta rápida, económica y accesible.

**Línea del Tiempo de la Historia de la Graficación por Computadora.**

<br> **1950.**</br>
<br>La graficación por computadora tuvo sus inicios con el surgimiento de lascomputadoras digitales. Una computadora digital como la Whirlwhin de la Mit fueuna de las primeras en utilizar una pantalla capaz de representar gráficos.</br>
<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/49e85e1e-1477-4aff-a9ac-0ff723ea5dba" />


<br> **1955.** </br>
<br> El primer sistema gráfico SAGE (SemiAuutomaticGroundEnviorement) de la Fuerzas aéreas norteamericanas (US Air Force’s), es  desarrollado en el Lincoln Laboratory del MIT (Massachusetts Institute of Technology).El sistema SAGE procesaba datos de radar y otras informaciones de localizaciones de objetos mostrándolos a través de una pantalla CTR. </br>
<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/4e814098-459a-4d1a-9fe1-c3db39d52786" />


<br> **1959.** </br>
<br> Surgió el primer sistema de dibujo por computadora, la DAC-1(Design Augmentedby Computers) Fue creado por General Motors e IBM. LaDAC-1 permitía al usuario describir un automóvil en 3D con la capacidad de rotar y cambiar el ángulo de la imagen. </br>
<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/b110554f-e6be-4ead-84b5-c1c78783fa9b" />


<br> **1960 - 1970.** </br>
<br>Ivan Suterland (Estudiante de MIT), creó un programa que llamó Sketchpad,mediante el cual podía realizar trazos en la pantalla de la computadoraauxiliándose de una pluma de luz: </br>
<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/338b39b3-553d-40c2-83f7-e2e47c5063dd" />


<br> **1961.** </br>
<br> Otro estudiante del MIT, Steve Rusell creó el primer juego de video, llamado“ Spacewar ” o guerra espacial en español. Escrito para la DEC PDP-1, la guerraespacial fue un éxito inmediato.1963 E. E. Zajac un científico de la Bell Telephone Laboratory (BTL), creo unapelícula llamada "Simulation of a two-giro gravity attitude control system. </br>
<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/cbb30b96-54ab-4216-9376-14011b29911f" />

<br> **1970 – 1980.** </br>
<br> Los años 70 consideraron la introducción de los gráficos por computadora en elmundo de la televisión. Computer Image Corporation (CIC), desarrolló sistemascomplejos de la dotación física y de software tales como ANIMAC, SCANIMATE yCAESAR. </br>
<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/7795f8bb-f601-4839-98cd-83dee1ee11e9" />


<br> **1978.** </br>
<br> El laboratorio central deFísica Aplicada de la UniversidadJohn-Hopkins publica un trabajoque se convertiría en la obra "Matematicalelements for computer graphics" de DavidF. Rogers. Esta sucedió desde esemomento una de las disciplinas importantetanto para el trazado de línea como en larepresentación de objetos naturales. Lainformática gráfica se hizo presente en lagestión, la Medicina, la televisión, laindustria del espectáculo, los videojuegos,la industria fílmica, y así en todas lasdisciplinas científicas, Matemáticas, Aeronáuticas, Mecánicas y otras muchasesferas del conocimiento. </br>

<br> **1980 – 1990.** </br>
<br> Turner Whitted publicó un artículo en el año 80 sobre un nuevo método de representación para simular superficies altamente reflexivas. Conocido hoy como raytracing.1999 – 2000. En 1993, la película Jurassic Park revoluciona los efectos visuales, al crear dinosaurios como nunca antes se habían visto, con la ayuda de las computadoras. </br>
<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/866b95ba-5d66-4d2f-acd1-2092c65086e9" />


**1999.**
La empresa Autodesk tiene 1.000.000 usuarios de AutoCAD LT y 100.000 3D Studio.*2000: Autodesk inicia la venta por Internet de AutoCAD 2000.*2001: Presentación versión AutoCAD 2002. Destacan la función de asociación de funciones de las dimensiones en el dibujo, el editor gráfico de atributos. La definición de bloques y un conversor de capas asociado a la funcionalidad del gestor de normas. Orientación hacia Internet.
La disciplina originalmente se relacionó mucho a las técnicas de Tratamiento deImágenes .Su evolución no puede comprenderse sino con el análisis de suproducción digital, tanto dentro del tratamiento estático o dinámico dentro desus resultados.Esta define los gráficos, creados y generados por un ordenador, donde la gestiónse basa en una estación gráfica compuesta de elementos materiales como elProcesador y la Tarjeta gráfica, las herramientas de adquisición como eldigitalizador o la Cámara digital, las periféricos de interfaz de usuario como elratón o la Tablilla gráfica, de medios de almacenamiento como el Disco Duro olas memorias USB y de herramientas de reproducción como la impresora.

# 1.2. Áreas de aplicación.

<br> **DISEÑO INDUSTRIAL.** Es un tema del diseño que busca crear o modificar objetos o ideas para hacerlos útiles, estéticos, prácticos o atractivos visualmente, con la intención de crear necesidades del ser humano, adaptando los objetos e ideas no solo en su forma sino también las funciones de este. </br> 
 

<br> **DISEÑO ARQUITECTÓNICO.** Se define como diseño arquitectónico a la disciplina que tiene por objeto generar propuestas que tiene por objeto generar propuestas e ideas para la creación y realización de espacios físicos enmarcado dentro de la arquitectura. </br> 

<br> **DISEÑO URBANO.** El Diseño Urbano está orientado a interpretar la forma y el espacio público con criterios físico-estético-funcionales, buscando satisfacer las necesidades de las comunidades o sociedades urbanas, dentro de una consideración del beneficio  colectivo en un área urbana existente o futura, hasta llegar a la conclusión de una estructura urbana a seguir. </br> 

<br>  **DISEÑO Y FOTOGRAFÍA.** Maximiza tu creatividad, consigue toda la magia en tus imágenes y contenidos gráficos un sofisticado conjunto de herramientas para la creación y edición de ilustraciones. Transforma todo aquella que puedas imaginas y preséntalo de maneras impactantes. </br> 

<br> **AUDIO Y VIDEO.** Aplicaciones para la edición de video con opciones inteligentes y automatizadas que te permiten mejorar tus películas con efectos de calidad profesional, y compartir en casi cualquier pantalla. </br> 

<br> **DISEÑO WEB.** Es una actividad que consiste en la planificación, diseño e implementación de sitios web. No es simplemente una aplicación de diseño convencional, ya que requiere tener en cuenta la navegabilidad, interactividad, usabilidad, arquitectura de la información y la interacción de medios como el audio, texto, imagen, enlaces y video. </br> 

<br> **DISEÑO DE VIDEOJUEGOS.** El desarrollo de videojuegos es el proceso de creación de un videojuego, desde el concepto inicial hasta el videojuego en su versión final. Es una actividad multidisciplinaria, que involucra profesionales de la programación, el diseño gráfico, la animación, el sonido, la música, la actuación, etcétera.
DISEÑO DE PELÍCULAS. Es la técnica que consiste en crear imágenes en movimiento mediante el uso de ordenadores o computadoras. Cada vez más los gráficos creados son en 3D, aunque los gráficos en 2D todavía se siguen usando amplia mente para conexiones lentas y aplicaciones en tiempo real que necesitan rende rizar rápido. Algunas veces el objetivo de la animación es la computación en sí misma, otras puede ser otro medio, como una película. Los diseños se elaboran con la ayuda de programas de diseño, modelado y por último rende rizado. </br> 

<br> **DISEÑO DE PELÍCULAS.** Es la técnica que consiste en crear imágenes en movimiento mediante el uso de ordenadores o computadoras. Cada vez más los gráficos creados son en 3D, aunque los gráficos en 2D todavía se siguen usando amplia mente para conexiones lentas y aplicaciones en tiempo real que necesitan rende rizar rápido. Algunas veces el objetivo de la animación es la computación en sí misma, otras puede ser otro medio, como una película. Los diseños se elaboran con la ayuda de programas de diseño, modelado y por último rende rizado.  </br> 

<br> __VISUALIZACIÓN:__ Científicos, ingenieros, personal médico, analistas y otros necesitan con frecuencia analizar grandes cantidades de información o estudiar el comportamiento de ciertos procesos. La visualización es una técnica de proyección de imágenes agradables con el fin de que esas proyecciones puedan convertirse en una realidad. </br> 

<br>  __PROCESAMIENTO DE IMAGENES:__ A pesar de que los métodos empleados en las gráficas por computadora y en el procesamiento de imágenes se traslapan, las dos áreas realizan, en forma fundamental, operaciones distintas. En las gráficas por computadora se utiliza una computadora para crear una imagen; en el procesamiento de imágenes se aplican técnicas para modificar o interpretar imágenes existentes, como fotografías y rastreos de televisión. </br> 

<br>  __FORMATOS GRÁFICOS DE ALMACENAMIENTO:__ El almacenamiento de datos que componen una imagen digital en un archivo puede realizarse utilizando diferentes formatos gráficos, cada uno de los cuáles ofrece diferentes posibilidades con respecto a la resolución de la imagen, la gama de colores, la compatibilidad, la rapidéz de carga, etc. </br> 

<br> __INTERFACES GRÁFICAS DE USUARIO:__ un componente importante de una interfáz gráfica es un administrador de ventanas que hace posible que un usuario despliegue con ventanas múltiples.</br> 
<br> PELICULAS: Se puede utilizar la animación, edición y efectos especiales, siendo estos los que más llaman la atención entre los consumidores. En películas o series de televisión es común que se combinen objetos animados y objetos con actores reales.</br>
<br> -Animación por computadora. La animación pertenece al ámbito del cine y a la televisión; aunque la relación que existe entre estos dos es directa a las artes visuales clásicas, dibujo, pintura y escultura, así como la fotografía.
Para la animación se requieren ciertas técnicas. </br>
<br> -Arte digital. Los métodos de graficas por computadora se utilizan en forma general tanto en aplicaciones de bellas artes como en aplicaciones de arte comercial. </br>

# 1.3. Aspectos matemáticos de la graficación.
La graficación por computadora está completamente fundamentada en las matemáticas, ya que una computadora no percibe imágenes como lo hace el ser humano. Mientras nosotros vemos colores, formas y movimiento, la computadora únicamente procesa números, ecuaciones y operaciones algebraicas.

Cada elemento visual que aparece en pantalla ya sea una línea, una figura geométrica, un botón de una interfaz o un modelo tridimensional complejo se obtiene a partir de cálculos matemáticos que determinan posición, tamaño, orientación, color e iluminación.

Por esta razón, la graficación utiliza áreas como:

<br> -Geometría analítica (puntos, rectas, planos) </br>
<br> -Álgebra lineal (vectores y matrices) </br>
<br> -Trigonometría (ángulos y rotaciones) </br>
<br> -Cálculo numérico (aproximaciones y suavizado)</br>

<br> Sistemas de coordenadas </br>

Los sistemas de coordenadas son la base para ubicar cualquier elemento dentro de un espacio gráfico.
Permiten asignar una posición exacta a cada objeto, de modo que la computadora sepa dónde colocarlo.
Sin un sistema de referencia, no existiría forma de organizar la imagen ni saber dónde comienza o termina un objeto.

**Coordenadas en 2 Dimensiones (2D)**

Las coordenadas en 2D son el sistema más básico y fundamental para representar gráficos dentro de una computadora.
Se utilizan para ubicar cualquier elemento en una superficie plana, como la pantalla del monitor o la ventana de una aplicación.

Cuando trabajamos con imágenes digitales, interfaces gráficas o videojuegos 2D, todo lo que aparece en pantalla se construye a partir de puntos posicionados mediante números.

La computadora no “sabe” qué es un botón, una línea o una figura; únicamente sabe colocar píxeles en posiciones específicas.

**Representación matemática**

Se expresan como un par ordenado:

(x,y)

donde:

x → desplazamiento horizontal (izquierda–derecha)

y → desplazamiento vertical (arriba–abajo)

<br> Cada par de valores indica la ubicación exacta de un punto dentro del plano. </br> 
<img width="326" height="240" alt="image" src="https://github.com/user-attachments/assets/83fff6f4-1da3-49dc-b93c-3c210343f6be" />

<br> **Plano cartesiano digital** </br> 

Para poder representar imágenes dentro de una computadora es necesario contar con un sistema de referencia que permita ubicar cada punto con exactitud.
Ese sistema está basado en el plano cartesiano, desarrollado por el matemático y filósofo René Descartes, quien propuso un método para localizar puntos en el espacio mediante números.

Este sistema revolucionó las matemáticas porque permitió describir la geometría usando álgebra, es decir, convertir figuras en ecuaciones.
Gracias a esta idea, hoy es posible representar gráficamente objetos dentro de una computadora.
Plano cartesiano tradicional (matemático)
En matemáticas puras, el plano cartesiano funciona de la siguiente manera:
<br> El eje X es horizontal (izquierda–derecha) </br>
<br> El eje Y es vertical (abajo–arriba) </br>
Ambos ejes se cruzan en el centro llamado origen (0,0)
Esto divide el plano en cuatro cuadrantes.

<br> _Características:_ </br> 
<br>Los valores positivos de X van hacia la derecha</br>
<br>Los valores negativos de X van hacia la izquierda </br>
<br>Los valores positivos de Y van hacia arriba </br>
Los valores negativos de Y van hacia abajo
<br>Por ejemplo:</br>
<br>(3, 2) está arriba y a la derecha </br>
<br>(-2, -1) está abajo y a la izquierda </br>
Este sistema es muy útil para resolver problemas geométricos y algebraicos.
<br>En el contexto de la programación, el sistema de coordenadas más utilizado es el plano cartesiano, que consta de dos ejes: el eje x (horizontal) y el eje y (vertical). Sin embargo, a diferencia del típico plano cartesiano matemático, donde el origen (0,0) está en el centro, muchos entornos de programación (especialmente para gráficos 2D) sitúan el origen en la esquina superior izquierda de la pantalla. En estos sistemas:</br>
-x aumenta al desplazarse hacia la derecha.
-y aumenta al desplazarse hacia abajo.
<br>Este sistema permite a los programadores controlar la posición de los elementos en la pantalla, desde la simple colocación de texto hasta las formas complejas de los videojuegos. </br>
<br>Para la programación 3D (como en los motores de juegos o el software de modelado 3D), se añade un eje z, lo que proporciona una nueva dimensión de profundidad y permite navegar y renderizar objetos en un espacio 3D.</br>

**Vectores**

En graficación por computadora, los vectores son una de las herramientas matemáticas más importantes, ya que permiten describir movimiento, dirección, orientación y cambios de posición dentro del espacio digital.
A diferencia de un número simple (escalar), que solo indica una cantidad, un vector describe cómo y hacia dónde ocurre un desplazamiento. Por eso, los vectores resultan ideales para modelar fenómenos dinámicos como el movimiento de un objeto, la dirección de una luz o la rotación de una figura.
De manera conceptual, un vector puede imaginarse como una flecha que parte de un punto y apunta hacia otro. Esa flecha contiene dos elementos fundamentales:
<br> Magnitud → cuánto mide o qué tan grande es el desplazamiento </br>
<br> Dirección → hacia dónde apunta ese desplazamiento </br>
<br> Gracias a estas dos características, un vector no solo indica “cuánto”, sino también “hacia dónde”. </br> 
<img width="278" height="181" alt="image" src="https://github.com/user-attachments/assets/e473f043-2d62-4be9-8bd5-ad841946e2e0" />

<img width="248" height="203" alt="image" src="https://github.com/user-attachments/assets/bd7bed20-b723-4d81-96e6-22b9f1793bae" />

<br> • ¿Qué representa un vector en gráficos? </br> 
En el contexto de la graficación, un vector puede representar:
+ el movimiento de un personaje
+ la velocidad de un objeto
+ la dirección de una cámara
+ la orientación de una superficie
+ la dirección de la luz
+ fuerzas físicas como gravedad o viento
Es decir, cualquier situación donde intervenga cambio de posición u orientación.

<br> ¿Dónde se utilizan los gráficos vectoriales? </br>
 <br> 1. Logotipos: los gráficos vectoriales son ideales para crear logotipos porque son escalables y, por lo tanto, se pueden usar en diferentes tamaños y resoluciones sin perder calidad.
2. Ilustraciones: los gráficos vectoriales son excelentes para producir ilustraciones porque se pueden modificar fácilmente y es fácil agregar sombras y rellenos.
3. Cartografía: los gráficos vectoriales se utilizan a menudo para construir mapas.
4. Fuentes: los gráficos vectoriales son una buena opción para diseñar fuentes porque son escalables y fáciles de editar.
5. Diseño web: los gráficos vectoriales son perfectos para el uso web, ya que tienen un tamaño de archivo pequeño y se pueden escalar a cualquier resolución y tamaño. SVG es un formato particularmente adecuado para su uso en la web. </br>

<img width="224" height="224" alt="image" src="https://github.com/user-attachments/assets/2a310420-a6a5-461a-8918-a03622634f6e" />

<br> **Transformaciones geométricas** </br>

Las transformaciones geométricas son operaciones matemáticas que permiten modificar las características de un objeto dentro del espacio gráfico. En graficación por computadora, los objetos no se manipulan “a mano”, sino que se cambian recalculando las coordenadas numéricas de los puntos que los forman. Cuando se quiere mover, girar o cambiar el tamaño de una figura, lo que realmente se hace es aplicar fórmulas matemáticas a cada uno de sus vértices.
Estas transformaciones son fundamentales para crear animaciones, interfaces interactivas, videojuegos y simulaciones, ya que permiten que los elementos de la pantalla no permanezcan estáticos. Las tres transformaciones básicas son la traslación, la rotación y el escalamiento, y a partir de ellas se pueden generar movimientos más complejos.

br> **Traslación (mover)** </br>

 <br>La traslación es la transformación más simple y consiste en desplazar un objeto de una posición a otra dentro del plano o del espacio. Durante este proceso no cambian ni la forma, ni el tamaño, ni la orientación del objeto; únicamente se modifica su ubicación.
Desde el punto de vista matemático, trasladar un objeto significa sumar una cantidad fija a sus coordenadas. Si un punto se encuentra en una posición determinada y se le agrega un desplazamiento, el punto aparecerá en una nueva posición conservando la misma distancia relativa respecto a los demás puntos del objeto. Todos los vértices se mueven exactamente lo mismo, por lo que la figura no se deforma.
En la práctica, la traslación ocurre cuando se arrastra una ventana en la pantalla, cuando un personaje camina de un lugar a otro o cuando un automóvil avanza dentro de un videojuego. Es la base del movimiento lineal y suele aplicarse continuamente en cada fotograma para producir animaciones suaves.  </br>

<img width="567" height="430" alt="image" src="https://github.com/user-attachments/assets/dc951562-ea47-4e7b-86ca-284c678e2a15" />

<br> **Rotación (girar)** </br>

 <br>La rotación es la transformación que permite girar un objeto alrededor de un punto específico llamado centro o eje de rotación. A diferencia de la traslación, donde los puntos se desplazan en línea recta, en la rotación los puntos se mueven siguiendo trayectorias circulares alrededor del eje.
Durante el giro, el objeto mantiene su tamaño y su forma, pero cambia su orientación. Esto significa que puede apuntar hacia otra dirección sin alterar sus proporciones. Matemáticamente, la rotación se calcula utilizando ángulos y funciones trigonométricas, las cuales determinan la nueva posición de cada punto después del giro.
Este tipo de transformación se observa cuando una rueda da vueltas, cuando un personaje gira la cabeza, cuando una aguja de reloj rota o cuando la cámara cambia su ángulo de visión en una escena 3D. Gracias a la rotación, los movimientos se perciben más naturales y realistas. </br>

<img width="564" height="540" alt="image" src="https://github.com/user-attachments/assets/a0d620e8-d78e-405e-b2f6-f10356ec4257" />

<br> **Escalamiento (cambiar tamaño)** </br>
<br>El escalamiento es la transformación que modifica el tamaño de un objeto. Permite agrandarlo o reducirlo sin alterar necesariamente su forma. Para lograrlo, las coordenadas de los puntos se multiplican por un factor de escala.
Cuando el factor es mayor que uno, el objeto aumenta de tamaño; cuando es menor que uno, se reduce. Si el mismo factor se aplica a todos los ejes, la figura conserva sus proporciones originales. Sin embargo, si se utilizan factores distintos, el objeto puede estirarse o comprimirse, cambiando su forma.
En aplicaciones prácticas, el escalamiento se utiliza al hacer zoom en una imagen, ajustar el tamaño de un botón, redimensionar una ventana o simular que un objeto se acerca o se aleja del observador. También es común en modelado 3D para adaptar objetos a diferentes dimensiones dentro de una escena.</br>

<img width="248" height="203" alt="image" src="https://github.com/user-attachments/assets/ca007173-79f8-4386-b1a5-a527e2de1ad3" />

En conjunto, estas tres transformaciones permiten modificar completamente el comportamiento visual de cualquier elemento gráfico. Combinándolas es posible crear movimientos complejos, animaciones fluidas y entornos interactivos, lo que las convierte en la base matemática de la graficación por computadora.
# 1.4. Modelos del color: RBG, CMY, HSV y HSL.

**Modelos de color**

En la imagen digital, el color no se maneja de forma intuitiva como en la pintura tradicional, sino mediante representaciones matemáticas. Para que una computadora pueda capturar, almacenar, procesar y mostrar colores, es necesario definirlos numéricamente. Para ello se utilizan los llamados modelos de color, que son sistemas que describen cómo se forman y combinan los colores a partir de un conjunto reducido de colores primarios.
El estudio de los modelos de color se basa en la radiación electromagnética y en el espectro visible, es decir, la parte de la luz que el ojo humano puede percibir. Cada color corresponde a una longitud de onda específica o a una combinación de varias. Cuando la luz llega a nuestros ojos, el cerebro interpreta esas combinaciones como diferentes colores.

 <br> **¿Qué es un modelo de color?**  </br>

Un modelo de color es una representación matemática que define un conjunto de colores primarios a partir de los cuales se pueden generar muchos otros mediante mezclas. Gracias a estas combinaciones es posible reproducir prácticamente todo el espectro visible, además de tonos como blanco, negro y grises.
En términos digitales, cada color se expresa mediante valores numéricos. Por ejemplo, un color puede describirse como una combinación de tres o cuatro componentes. Al modificar esos valores, cambia el color mostrado.
Es importante notar que algunos colores, como el marrón o el magenta, no existen como una única longitud de onda en la naturaleza. En realidad, son interpretaciones del cerebro que surgen al mezclar distintas intensidades de luz. Esto demuestra que el color es, en parte, una percepción visual y no solo un fenómeno físico.

 <br> **Importancia de los modelos de color en la computación**  </br>
 
 <br> Los modelos de color son fundamentales porque permiten que los dispositivos digitales trabajen con imágenes de forma precisa. Sin ellos, no sería posible mostrar fotografías en un monitor, imprimir imágenes en papel o editar colores en programas de diseño.
Cada dispositivo utiliza un modelo distinto según su funcionamiento físico. Por ejemplo, las pantallas emiten luz, mientras que las impresoras trabajan con tintas que absorben luz. Por esta razón, no todos los modelos funcionan igual ni producen los mismos resultados.
Elegir el modelo correcto garantiza que los colores se reproduzcan de manera adecuada en cada medio. </br>

 <br>**Modelo RGB** </br>
 
 <br> El modelo RGB se basa en la mezcla aditiva de luz. Sus siglas provienen de los colores primarios Red (rojo), Green (verde) y Blue (azul).
Este modelo funciona sumando luz de diferentes intensidades. Cuando se combinan los tres colores al máximo se obtiene blanco, y cuando no hay luz se obtiene negro. Esto se debe a que las pantallas generan color emitiendo luz directamente hacia el ojo.
Cada color se representa mediante tres valores numéricos que indican la cantidad de rojo, verde y azul presentes. Por ejemplo, un rojo puro tendría mucho valor en rojo y casi nada en verde y azul.
El modelo RGB se utiliza principalmente en monitores, televisores, cámaras digitales, teléfonos móviles y cualquier dispositivo que trabaje con luz directa.  </br>

<img width="275" height="183" alt="image" src="https://github.com/user-attachments/assets/ad47c66c-ed3e-4cda-aff6-f7d20e3c171c" />

**Modelo CMYK**
El modelo CMYK se basa en la mezcla sustractiva de color. Sus siglas corresponden a Cyan, Magenta, Yellow y Key (negro).
A diferencia del modelo RGB, aquí no se emite luz, sino que se usan tintas o pigmentos que absorben ciertas longitudes de onda y reflejan otras. Cuanta más tinta se añade, menos luz se refleja, por lo que el resultado es más oscuro.
La combinación de cian, magenta y amarillo produce colores variados, pero no logra un negro profundo, por lo que se añade tinta negra adicional para mejorar contraste y definición.
Este modelo se utiliza en impresoras, imprentas, revistas, carteles y cualquier medio físico de impresión.
<img width="275" height="183" alt="image" src="https://github.com/user-attachments/assets/10563169-00fe-4bae-bdee-a2cd5ee3072b" />

**Modelo HSL / HSV**
<br>El modelo HSL (Hue, Saturation, Lightness) y su variante HSV (Hue, Saturation, Value) organizan el color de una forma más cercana a la percepción humana. En lugar de basarse únicamente en mezclas de primarios, describen el color según cómo lo interpretamos visualmente.
El tono (Hue) representa el tipo de color, como rojo, azul o verde, y suele representarse como un ángulo dentro de una rueda cromática. La saturación indica la intensidad o pureza del color; cuanto menor es, más grisáceo se ve. La luminosidad o valor controla qué tan claro u oscuro es el color.
Este modelo es muy útil en edición de imágenes, fotografía y diseño gráfico, porque permite ajustar colores de manera más intuitiva. Por ejemplo, es más sencillo aumentar la luminosidad o disminuir la saturación que modificar directamente componentes RGB.</br>
<img width="322" height="157" alt="image" src="https://github.com/user-attachments/assets/8817eeea-153d-4efd-9492-5e64dc9c4afe" />

# 1.5. Representación y trazo de líneas y polígonos.

 <br>**Representación y trazo de líneas y polígonos en Blender**  </br>
 
En la graficación por computadora, cualquier objeto tridimensional, por complejo que parezca, está construido a partir de elementos geométricos muy simples. La computadora no “ve” superficies curvas ni formas orgánicas como lo hace el ojo humano; en realidad, todo se representa mediante puntos conectados por líneas que forman superficies planas llamadas polígonos.
En Blender, esta estructura se conoce como malla o mesh. Una malla está compuesta por vértices, aristas y caras, y constituye la base de todo modelado 3D. Cada uno de estos elementos cumple una función específica en la construcción de la geometría.

 <br> **Líneas (aristas)**  </br>
Las líneas en Blender se denominan aristas. Se generan al unir dos vértices, que son puntos con coordenadas numéricas en el espacio tridimensional (x, y, z). Aunque las aristas no tienen grosor ni superficie visible durante el renderizado, son fundamentales porque delimitan la forma del objeto y conectan las caras.
Las aristas funcionan como el “esqueleto” del modelo. Permiten definir contornos, dividir superficies y controlar la estructura general. Cuando se modifica una arista, se altera directamente la silueta del objeto.

```python
v1 = bm.verts.new((0, 0, 0))
v2 = bm.verts.new((2, 0, 0))
bm.edges.new((v1, v2))
```
Aquí se crean dos vértices con coordenadas tridimensionales. El primer vértice está en el origen del espacio y el segundo se encuentra dos unidades a la derecha sobre el eje X. Estos puntos representan posiciones matemáticas en el espacio 3D.

Después, la instrucción bm.edges.new((v1, v2)) conecta ambos vértices. Esa conexión es la arista, es decir, la línea. Blender no dibuja la línea como un trazo visual, sino que registra que esos dos puntos están unidos geométricamente. Esa relación es lo que forma la línea digital.

 <br> **Polígonos (caras)**  </br>
 
Los polígonos, llamados caras en Blender, son superficies planas delimitadas por aristas. Estas caras sí son visibles y son las que reciben materiales, colores, texturas y efectos de iluminación. Sin caras, el objeto no podría verse en el render.
Un polígono puede estar formado por tres o más vértices. En gráficos por computadora, los más comunes son los triángulos y los cuadriláteros. Los triángulos siempre son planos y son fáciles de procesar, por lo que el sistema los utiliza internamente para dibujar la imagen. Sin embargo, los cuadriláteros facilitan el modelado y producen deformaciones más suaves, por eso son preferidos por los diseñadores.

```python
v1 = bm.verts.new((0, 0, 0))
v2 = bm.verts.new((2, 0, 0))
v3 = bm.verts.new((1, 2, 0))

bm.faces.new((v1, v2, v3))
```

Primero se definen tres vértices, cada uno con su posición en el plano XY. Estos tres puntos forman los extremos del triángulo.
La instrucción bm.faces.new((v1, v2, v3)) crea una cara cerrando el espacio entre esos vértices. Blender automáticamente genera las aristas necesarias y rellena el interior, formando un polígono visible.
Lo importante aquí es entender que una cara aparece cuando se cierra un conjunto de puntos. Con tres vértices se forma el polígono más básico posible: el triángulo.

 <br> **Trazo y construcción de formas**  </br>
 
El trazo de líneas y polígonos en Blender consiste en crear y modificar estas mallas para construir objetos cada vez más detallados. El proceso de modelado suele comenzar con figuras básicas llamadas primitivas, como cubos, planos, cilindros o esferas, que luego se transforman.
Las herramientas de edición permiten agregar nueva geometría. Extrude crea nuevas caras a partir de una existente. Knife permite cortar la malla dibujando nuevas aristas. Bevel redondea bordes agregando más polígonos. Todas estas acciones implican el trazado de nuevas líneas y superficies.

La aplicación de estos conocimientos se llevo acabo en una practica en la que creamos un hexagono en blender, en el siguinte link se encuentra la expliccaión : 
https://github.com/24680190-ren/24680190_EjercicioGraficaci-n

  ## 1.5.1 Formatos de imagen.


# Bibliografias 
1. https://grafidepc.blogspot.com/p/blog-page.html
2. https://www.sutori.com/es/historia/historia-y-evolucion-de-la-graficacion-por-computadora--HWxiLPJRpHqkjwYoadxpmheZ
3. https://es.slideshare.net/slideshow/1-1-historia-y-evolucion-de-la-graficacion-por-computadora-pdf/282295680
4. https://es.slideshare.net/slideshow/1-2-areas-de-aplicacion-de-la-graficacion-por-computadora-pdf/282295469
5. https://es.scribd.com/document/595159409/Informe-1-2-Areas-de-aplicacion-de-la-graficacion
6. https://byjus.com/maths/two-dimensional-coordinate-geometry/
7. https://engineeringstatics.org/cartesian-coords-2d.html
8. https://medium.com/@sutar.trupti23/coordinate-geometry-in-programming-the-building-block-of-graphics-and-simulations-a1141a036aca
9. https://www.mr-beam.org/es/blogs/news/que-es-un-grafico-vectorial?srsltid=AfmBOorD349G9rrEpIpjhAysayWFk87nnqq7cOIqDVXeemZ15ewN-Rzf
10. https://view.genially.com/64164b88abcad40018c55d4b/interactive-content-software-para-diseno-grafico-de-vectores
11. https://flexbooks.ck12.org/cbook/ck-12-conceptos-de-matem%C3%A1ticas-de-la-escuela-secundaria-grado-8-en-espa%C3%B1ol/section/6.14/primary/lesson/reconocer-transformaciones-de-traslaci%C3%B3n/
12. https://www.bartolomecossio.com/MATEMATICAS/movimiento_en_el_plano_traslacin_rotacin_y_simetra.html
13. https://es.slideshare.net/slideshow/traslacion-del-plano-cartesiano-41631955/41631955
14. https://ahenav.wordpress.com/2014/04/09/modelos-de-color/
15. https://www.shutterstock.com/es/image-vector/hsb-hsv-hsl-alternative-representations-rgb-2175452279?dd_referrer=https%3A%2F%2Fwww.google.com%2F
16. https://www-hslpicker-com.translate.goog/?_x_tr_sl=en&_x_tr_tl=es&_x_tr_hl=es&_x_tr_pto=tc
17. https://iluminacionnatural.artesolar.com/colorimetria-iii-espacio-de-color-rgb-hsv-y-hsl/
18. 
