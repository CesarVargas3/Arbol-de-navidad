# **Arbol de navidad didactico (Versión 1.0)**

Hola!

En este repositorio encontrarás toda la información de funcionamiento, desarrollo, requerimientos, restricciones 
y todo lo relacionado al proyecto 1 del curso de electrónica analógica 3 del periodo 2023-1.

Antes que nada, nos gustaría que sepas quienes estamos detrás de esto:

  - Laura Nicolle García Villareal (20202192838)
  - Laura Sofía Polania Mendez (20211197481)
  - Juan Esteban Vargas Rivera (20202191289)
  - Cesar Diego Vargas Motta (20202191503)

Pertenecemos al programa de ingeniería electrónica de la universidad surcolombiana.

## **Información general**

Desarrollamos un kit de aprendizaje de electrónica analógica representado como un arbol navideño, siguiendo una 
serie de pautas dadas, llevando a cabo un proceso de diseño para poder conseguir de mejor manera todo lo requerido.

Este kit consta de pocas partes, todas son desmontables, además es muy intuitivo pues se desarrolló pensando en que
el usuario sea el encargado de montar la totalidad de la parte electrónica, para que este pueda entender de mejor 
manera el funcionamiento electrónico, nosotros creemos que no hay nada como el conocimeinto adquirido de manera empírica.

Como estudiantes encargados del desarrollo, seguimos un proceso de diseño, el cual nos puso en diferentes situaciones
poniendonos a prueba constantemente, debido a que teníamos que sortear las diferentes dificultades que se nos presentaban
en el camino.

# _**Proceso de desarrollo**_

El desarrollo de este proyecto está basado en un proceso de diseño, por lo que está seccionado por diferentes
etapas para obtener el producto requerido.

Es muy importante recalcar que todos los procesos que se tuvieron en el desarrollo fueron realizados en grupo,
todas las decisiones importantes fueron tomadas en consenso con todos los participes en el desarrollo, pero por 
razones de optimización de tiempo y de recursos en general, se empoderó a una persona de cada grupo para el desarrollo
de partes específicas del kit.

## **Planteamiento del problema**

Se nos propuso implementar un kit didáctico basado en un arbol de navidad, con el objetivo principal de 
enseñar conceptos básicos de electrónica analógica, para ello fue necesario identificar los diferentes 
requerimientos, pues estos fueron claves al momento de llevar a cabo las diferentes etapas de diseño,
debido a que es muy fácil dejar la objetividad a un lado y cumplir con lo que el usuario necesita.

Una vez conocido lo que se nos pedía desarrollar, fue de vital importancia encontrar los diferentes medios
que nos ayudarían en todo este proceso de desarrollo, en el camino nos fuimos encontrando diferntes herramientas
y metodologías para poder avanzar de mejor forma. En esta etapa inicial lo primero que vimos conveniente usar
fue una lista de chequeo o "Check List".

En un inicio nuestra Check List se veía a algo parecido a esto:

      □ Conocer lo requisitos exactos del cliente.
      □ Conocer las restricciones en el desarrollo.
      □ Plantear objetivos claros.
      □ Conceptos a enseñar.
      □ Acordar y aprovar con el cliente.
  
La Check List nunca fue la misma por mucho tiempo, una vez completabamos lo que se encontraba la lista se 
abrían nuevas tareas por cumplir, por lo que fue muy dinámico en ese sentido.

## **Indagación** 

Teniendo el planteamiento del problema, iniciamos el proceso indagatorio para identificar los requerimientos 
y las restricciones, siendo estas últimas de suma importancia en nuestro proceso, pues nos ajustamos a ellas,
presentando diferentes desafíos al momento de cumplir con los requerimientos sin violar las restricciones.

De nuestra indagación inicial, teniendo una discusión de equipo obtuvimos unos requerimientos y restricciones
que consideramos en su momento que serían las definitivas. El resultado de ello fue:

### Requerimientos:

* El kit debe de ser un medio didáctico para el aprendizaje de electrónica análoga.
* Conceptos a enseñar:
   1. Circuito integrado analógico.
   2. Temporización. 
   3. Oscilación.
   4. Síntesis de señales.
   5. Actuación (Sonido y luz).
* Debe de ser de fácil ensamble.
* Debe de ser transportable.
* Debe ser replicable.
* Debe contar con botón de encendido y apagado.

### Restricciones:

* Implementación no debe contar con PCB.
* El tamaño del kit.
* Costo de producción establecido (100.000 COP)
* Tiempo de desarrollo para el diseño.

## **Requerimientos finales**

En el desarrollo de nuestra indagación rápida de equipo nos percatamos de un error en el planteamiento, pues
no estábamos teniendo en cuenta del todo al que nos imponía las restricciones y requerimientos principales,
dejando muchos factores sin considerar o mal considerados, por lo que decidimos tener una reunión donde teníamos 
como finalidad obtener todos los requerimientos y restricciones directamente del usuario, asegurándolos con un
manuscrito firmado por él mismo.


Imagen

Aprendimos que el firmar lo acordado es de vital importancia, pues las palabras quedan en el aire y este se las
lleva, por lo que al acordar algo es necesario dejar un registro escríto bien detallado con lo acordado, además este
documento debe contar con la firma del cliente y de los desarrolladores, es decir de ambas partes, todo para
evitar cambios en el proceso de desarrollo.

## **Prototipo baja resolución**

A partir de lo obtenido, indagamos de manera verbal cómo sería más viable la construcción física - estética del
arbol, llegando a la conclusión inicial de que la forma más conveniente era una forma piramidal y simétrica, 
dejando un espacio hueco dentro de si para la conexión de los leds, por lo que desarrollamos un prototipo de
baja resolución, el cual se realizó en cartón paja con el único fin de observar la viabilidad de la forma, sin
tener en cuenta aspectos importantes como el material con el que sería construido finalmente.

Imagen

Este prototipo de baja resolución fue presentado al profesor, el cual nos realizó una serie de cuestionamientos
sobre nuestro proceso de diseño, de los cuales nos dimos cuenta de que no estábamos siguiendo un proceso confiable 
al no tener alternativas claras.

## **Selección estética**

Al percatarnos de nuestro error en el proceso de diseño, nos reunimos con el fin de realizar una lluvia de propuestas
para el diseño físico del kit, de esta reunión salieron 5 propuestas las cuales fueron evaluadas en conjunto, generando 
una discusión en la que definíamos pros y contras de cada propuesta, seleccionando la que se ajustaba de mejor maneras
a los requisitos y no violaba ninguna restricción.

El diseño escogido fue un arbol en dos dimensiones, con una cara frontal en la que se observan los leds y por lo tanto
el comportamiento de estos como medio de enseñanza, y una cara posterior en donde van todas las conexiones de los leds,
estos irían fijos en la pieza del arbol. En general el kit contaría con tres partes, una base, el arbol y los componentes
electrónicos los cuales serían montables y desmontables.

Imagen

Es importante aclarar que en el diseño escogido, los LEDs van montados en la pieza del arbol, es decir, van fijos y soldados
por la cara posterior del arbol, siendo la única parte "electrónica" que se encuentra fija y que se consideró directamente en
el diseño estético del arbol, debido a que el apartado electrónico se iba a desarrollar en una protoboard sin afectar directamente
el apartado estético, solo se consideró el espacio donde iría esta protoboard en este apartado.

Otro aspecto importante al momento de realizar la selección de diseño fue el tener en cuenta el requerimeiento de las medidas 
con las que tenía que contar la caja en donde irían las partes del kit, por lo que se escogió el diseño que se podía ajustar al 
tamaño de la caja y además de eso sin sacrificar resistencia pues el árbol será sometido a una prueba de resistencia.

## **Indagación electrónica**

Una vez identificado cómo sería la forma estética y teniendo en cuenta los requerimientos de diseño establecidos, iniciamos a
plantear el apartado electrónico del kit, el cual es de vital importancia para el éxito del proyecto, pues como objetivo principal
se debe enseñar electrónica analógica con este kit didáctico, por lo que el planteamiento electrónico tiene que enfocarse en ello.
Tuvimos diferentes ideas de implementación de este apartado, desde usar algún tipo de placa difetente al PCB o soldar los diferentes
elementos haciendo que estos estuvieran fijos, pero la idea que más se ajustó a lo que requerimos fue usar una protoboard en donde 
el usuario directamente montara el circuito y pudiera aprender de una forma más empírica.

Antes de cualquier cosa la primera pregunta que nos hicimos fue cómo poder hacer que un circuito dure un tiempo encendido determinado
y que se apagara después de un tiempo, planteamos diferentes integrados que nos podrían servir, pero al final analizamos las diferentes
configuraciones del 555, determinando que la configuración monoestable era la que se ajustaba a lo que necesitabamos.

Imagen

Como se ha mencionado se delegaron diferentes personas del equipo al desarrollo de diferentes partes del kit, mientras se realizaba el
desarrollo del temporizador, otra persona desarrolló el circuito que generaba el sonido utilizando el integrado propuesto por el profesor
UM66T, y otra persona desarrolló el circuito de intermitencia de luces, mientras que otra pulía el apartado estético para un correcto acople
del apartado estético y electrónico, todo esto en paralelo.

### Planteamiento de etapas

Teniendo el desarrollo individual de los circuitos que se iba a realizar, decidimos establecer diferentes etapas que al acoplarse se 
tendría el funcionamiento esperado, este manejo por estapas nos permite seccionar el funcionamiento de todo el circuito, haciendo más 
facil la comprensión parael usuario, también de esta forma los componentes electrónicos de cada etapa vendrán separados en diferentes 
bolsitas para que el montaje también sea seccionado, haciendolo más sencillo para el usuario.

imagen

## **Desarrollo estético**

Habiendo hecho el proceso de escoger el diseño más apto sobre el papel, seguía desarrollarlo para llevarlo a la realidad, para esto
se delegaron a dos personas del equipo, una se encargó de desarrollar la base y otra fue la encargada de desarrollar el arbol, siendo
del apartado estético estas dos partes.

Para la base se considararon diferentes materiales como por ejemplo cartón pluma u otros materiales comúnmente utilizados en la 
realización de maquetas de los estudiantes de arquitectura, llegamos a hablar con varios estudiantes de arquitectura para que nos 
asesoraran un poco en la realización de la base, pero al momento de de buscar la ayuda de ellos todos nos hacían un nuevo diseño
argumentando que no sería resistente el que estábamos haciendo, pero los diseños propuestos se alejaban de lo que requeríamos, por lo
que desidimos dejar ese asesoramiento, pues el efoque que ellos de daban era muy acorde a su carrera pero no a nuestros requerimientos.

Finalmenta para la base se propuso imprimirla en 3D, lo cual nos llamó la atención debido que al ser impresa en un material sintético
muy probablemente fuera resistente y se ajustaría a nuestros requerimientos, pero nos surgío otra duda, no sabíamos cuanto nos podría
llegar a costar y si podríamos hacerlo sin violar el requerimeiento del valor unitario, por lo que el siguiente paso en nuestra Check
List fue cotizar, para ello nos pedían un archivo con un modelo 3D digital, para poder realizar la simulación de costos.

imagen

El diseño se hizo considerando las dimensiones de la caja y el acople con la pieza del árbol. Una vez realizada la simulación de costos
vimos que el precio era perfectamente costeable, por lo que implementamos la base imprimiendolaen un material sintético. Como se nos
indicó inicialmente el árbol sería sometido a una prueba de resistencia, que era una caidadesde aproximadamente 1 metro de altura, por
lo que preeviendo esta situación, realizamos algunos refuerzos en un material que ayudara a absorber la energía del impacto, siendo 
el fomi el material elegido.

El desarrollo del arbol fue un poco más sencillo, pues este se ajustaría mecánicamente a la base. Consideramos distintos materiales 
para la realización de este arbol, los mismos que los que consideramos en la base, incluso realizarlo con un material sintético, pero
finalmente decidimos realizarlo en carton paja.

imagen

## **Desarrollo electrónico**

Realizando el planteamiento por etapas, se designaron distintas etapas para desarrollar a diferentes integrantes del equipo, en el
desarrollo del temporizador fue calcular los valores necesarios para que el monostable durara de 30 segundos a 3 minutos, finalmente
conseguimos que durara de 0 segundos a 3 minutos.

El desarrollo del circuito sonoro y del de intermitencia fue un poco más complejo, en el caso del circuito de sonido tuvimos varios 
inconvemientes para lograr que el sonido sonara claro, que se mantuviera estable y sin distorción durante los 3 minutos y que el integrado
UM66T no se calentara, para ello realizamos dierentes pruebas, desde un divisor de tensión, la implementación de un diodo zener, entre otras,
todas ellas conseguían una mejora a esta etapa, hasta que acoplamos las etapas y no nos presentó ningún problema de funcionamiento.

El circuito intermitente para las luces, fue sencillo en si, pero inicialmente se nos presentó un problema de potencia, por lo que pusimos
los diferentes LEDs en paralelo, posterior a esto el circuito no funcionó como debía, revisamos todo muchas veces sin encontrar un error 
aparente, por lo que decidimos probar los componente, descubriendo que un capacitor estaba defectuoso, luego de reemplazarlo todo 
funcionó correctamente.

Imagen


## **Equipo**

A lo largo del camino recorrido nos encontramos con multiples dificultades, tanto en el proceso de desarrollo como
en el trabajo de equipo en si. En términos generales el balance es muy positivo, pues a pesar de las dificultades 
íbamos encontrando la forma de superarlas de mejor forma, realizando cada uno un aporte personal vital para el desarrollo.

Poco a poco fuimos tomando roles dentro del desarrollo del proyecto, haciendo este mucho más ágil al momento de ejecutar
lo planeado, a pesar de que todos participamos en el desarrollo de los diferentes apartados, cada uno se destacó en uno específico:

Nicolle: Ella se caracteriza por tener un orden en todo, lo cual ayuda bastante en cuidar los diferentes recursos como lo es el
         tiempo, ella se destacó en la documentación del proceso del proyecto. 

Sofía: Ella es muy buena en el análisis de los circuitos, ella fue de vital importancia en el proceso de diseño electrónico,
       en definir las diferentes etapas y concluir en el mejor camino para el apartado electrónico.

Juan: Él demostró tener habilidades para el montaje de circuitos y soldar, siendo fundamental en el desarrollo
      del hardware del kit

Cesar: Él se caracteriza por su liderazgo cuando se trata de delegar tareas a cada miembro del equipo, coordinando los tiempos
       y definiendo los pasos a seguir, escuchando y proponiendo.
