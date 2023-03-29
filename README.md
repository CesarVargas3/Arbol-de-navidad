# **Arbol de navidad didactico (Versión 2.0)**

Hola!

En este repositorio encontrarás toda la información de funcionamiento, desarrollo, requerimientos, restricciones 
y todo lo relacionado al proyecto 2 del curso de electrónica analógica 3 del periodo 2023-1.

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

## **Nuevos requerimientos**

Para la realización del proyecto 2, se nos pidió agregar la activación por detección de movimiento utilizando un sensor 
piroeléctrico. La piroelectricidad es un fenómeno físico en el que ciertos materiales generan una carga eléctrica cuando 
experimentan un cambio en su temperatura. Esta carga eléctrica se produce como resultado de un desplazamiento en los 
centros de carga eléctrica positiva y negativa dentro de la estructura cristalina del material.

El efecto piroeléctrico se produce en algunos materiales que tienen una estructura cristalina asimétrica, lo que significa
que tienen una distribución desigual de átomos en su estructura. Estos materiales pueden generar una carga eléctrica cuando
se calientan o enfrían, y la magnitud y dirección de la carga eléctrica dependen de la dirección del cambio de temperatura.

Para la implementación de este nuevo requerimeinto planteado, el profesor nos brindó el sensor PIR D203S con el cual
deberíamos cumplir el nuevo requerimiento.

## **Mejoras**

El funcionamiento de las diferentes etapas planteadas en el proyecto 1 no fue el más óptimo, podemos decir que simplemente 
cumplía, pues el tiempo de funcionamiento determinado por el temporizador del 555 en configuración monoestable iba de 
0 segundos a aproximadamente 3 minutos, cuando lo requerido era de 30 segundos a 3 minutos. 

El sonido tampoco presentaba un funcionamiento limpio, pues el este no era muy fuerte, además de ello con el tiempo
el sonido se distorsionaba y el integrado UM66T se calentaba y no era estable en el tiempo máximo de funcionamiento, por lo
que hicimos diferentes pruebas, determinando que el problema principal era que le estaba llegando una sobre tensión a
esta estapa y que esta era la razón principal de este comportamiento anormal, entonces para no modificar toda la alimentación 
del circuito completo (todas las etapas acopladas), implementamos diferentes alternativas como el uso de un diodo zener, un
regulador de tensión o un divisor de tensión para poder estabilizar el voltaje, finalmente lo que mejor nos dió resultado en
las pruebas con la etapa aislada fue el uso combinado del diodo zener y el divisor de tensión.

Al realizar el acople de etapas el sonido bajó considerablemente, aún con los arreglos realizados, lo que ocurrió fue que también 
ajsutamos una resistencia en serie con el potenciómetro para garantizar los 30 segundos de funcionamiento mínimos requeridos, por
lo que esto afectaba al voltaje que llegaba a la etapa de sonido, podiendo el circuiti funcionar sin los arreglos realizados.

Conseguimos corregir el funcionamiento de las luces, para ello la tira que iba con LEDs amarillos y verdes la dejamos solo con amarillos
es decir, se reemplazaron los verdes, pero con esta modificación solo encendían todos directamente, pero al conectarlos al circuito 
oscilatorio no funcionaba de manera correctamente, emepezamos a indagar al respecto, descubriendo que uno de los capacitores estaba
defectuoso, al reemplazarlo todo funcionó correctamente.

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
