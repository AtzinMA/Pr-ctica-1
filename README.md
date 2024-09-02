# Práctica 1
## Integrantes:
- Dante Mejía Silva
- Atzin Morales Alejandre
## Introducción
La primera práctica del laboratorio de robótica consiste en la instalación del programa Epson RC+ y visualizar mediante ella los primeros movimientos con el robot. 

Epson es líder mundial en automatización industrial y ofrece una impresionante combinación de alto rendimiento y simplicidad. Respaldados por una reputación mundial por su fiabilidad y soporte excepcionales, los robots industriales Epson están proporcionando sistemas de fabricación automatizada y altamente productiva a un conjunto cada vez más amplio de sectores industriales en todo el mundo. 
## Instrucciones

## Movimiento del robot en world y joint
"World" y "Joint," son dos diferentes modos de mover el brazo robótico.

1.	Movimiento "World" (o cartesiano): En este modo, el movimiento del brazo robótico se especifica en términos de un sistema de coordenadas cartesiano, que se refiere a la posición del brazo en el espacio. En el modo "World" se puede mover el brazo en línea recta a lo largo de los ejes X, Y y Z del sistema de coordenadas. Esto es útil para tareas que requieren un movimiento lineal y preciso del efector final a través del espacio.

2.	Movimiento "Joint": En este modo el movimiento se controla a nivel de cada articulación individual del brazo robótico. En lugar de especificar posiciones en un espacio tridimensional aquí se controla directamente los ángulos de cada una de las articulaciones del brazo.
## Análisis de las Diferencias
•	Sistema de Control:

La principal diferencia entre los modos "World" y "Joint" radica en cómo se controla el movimiento del brazo robótico. El modo "World" utiliza coordenadas cartesianas para definir la posición y orientación del efector final en el espacio, mientras que el modo "Joint" controla el movimiento a través de los ángulos de cada una de las articulariones (J1-J6).

En el modo "World", las trayectorias al ser lineales podrían ser más fáciles de planificar porque están basadas en coordenadas. En el modo "Joint", las trayectorias al depender de la rotación de cada articulación puede resultar en movimientos más fluidos, pero más difíciles de planificar, especialmente si el robot tiene muchas articulaciones, sin embargo este modo puede ser útil para evitar colisiones que se podrían producir al emplear el modo “World”.
## Conclusiones
Atzin Morales Alejandre: En esta primera se logró la instalación y configuración del software Epson RC+ y se exploraron los conceptos fundamentales del control de un brazo robótico, específicamente a través de los modos de movimiento "World" y "Joint". Además, esto permitió la familiarización con parte de la interfaz del software, así como con las capacidades del simulador antes de interactuar con el robot físico.

A través de la exploración práctica de los modos "World" y "Joint", se pudo comprender cómo estos diferentes enfoques de control ofrecen diversas ventajas según las necesidades de la tarea. El modo "World" proporciona un control sencillo y directo en un espacio cartesiano, ideal para movimientos lineales precisos. Por otro lado, el modo "Joint" permite un control más detallado a nivel de cada articulación, proporcionando mayor flexibilidad en entornos complejos o cuando se requiere evitar obstáculos.

Ambos modos de operación son esenciales para obtener mejores resultados en diferentes aplicaciones industriales. Esta práctica permitió sentar las bases para un entendimiento más profundo de las técnicas de programación y control en robótica que se verán a lo largo del curso así como preparación para desafíos más avanzados en futuras prácticas.

Dante Mejía Silva: En esta primera fase del proyecto, se completó exitosamente la instalación y configuración del software Epson RC+, lo cual permitió adentrarse en los principios fundamentales del control de brazos robóticos. Se hizo un enfoque particular en los modos de movimiento "World" y "Joint", que son esenciales para el control preciso y eficiente del robot. La familiarización con la interfaz del software y las funcionalidades del simulador sentó las bases para una comprensión más profunda de estos conceptos antes de interactuar con el robot físico.

El análisis práctico de los modos de control evidenció cómo "World" facilita movimientos lineales y precisos en un espacio cartesiano, mientras que "Joint" ofrece un control detallado de cada articulación, lo que resulta útil en entornos más complejos. Este conocimiento no solo es fundamental para la programación y operación de robots en aplicaciones industriales, sino que también prepara a los participantes para enfrentar desafíos más avanzados en futuras sesiones prácticas.

