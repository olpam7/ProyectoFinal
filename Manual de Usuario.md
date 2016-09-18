# ProyectoFinal
Proyecto Final Clase Algoritmos (Estructuras Logicas I)
Universidad de Occidente
Extensión Montesquieu


Ingeniería en Electrónica

Curso: Estructuras lógicas I

Catedrático: Ing. Christian Meléndez






























Elvis Enrique Santizo Bajxac
Milton Castellanos Alvarado

Carné: 160404011
Carné: 140405006

Fecha: 17-09-2016


























Objetivos

•	Desarrollar una aplicación en C # que pueda realizar operaciones aritméticas tomando en cuenta la jerarquía de operadores y la de signos de agrupación.

•	Desarrollar esta aplicación teniendo en cuenta los temas vistos en clase y mediante estos conocimientos obtenidos buscar la optimización del programa de ejecución.























Manual de Usuario
El proyecto de calcular operaciones en orden según sea ingresada la operación, fue desarrollado en C#, utilizando como IDE de programación SharpDevelop por cuestiones de recursos en la computadora utilizada.

En la pantalla principal que está en la figura 1, se puede observar cada uno de los atributos que posee el proyecto, así como la ruta para ingresar al ejecutable, la configuración y la plataforma.

	























Ingreso al programa para ejecutar.
1.	ingresa a la unidad de tu disco de almacenamiento.





En mi caso mi unidad se llama DVD (E:)
O bien puedes ingresar al siguiente link para descargar el programa.
https://github.com/henry026/proyecto_operaciones
2.	inicia navegando entre carpetas, busca Proyecto operaciones
 

3.	dentro de proyecto operaciones ingresa a bin
 










4.	Luego ingresa a Debug

 

5.	Y ejecuta la aplicación  Proyecto_Operaciones.
 

6.	En la pantalla CMD que aparece puedes ingresar la operación a resolver.

 











7.	Puedes utilizar símbolos como paréntesis, llaves, corchetes.
8.	Para sumar prueba la siguiente operación.

 
	Prueba con la siguiente operación y vemos el resultado.
 
Para salir del programa, presiona ENTER.






Estructuras Utilizadas

Durante el desarrollo de este proyecto se tomaron en cuenta varias estructuras las cuales fueron analizadas e incluso programadas. Entre ellas se pueden mencionar estructuras de colas y pilas.

Se buscó bibliografía en Internet que pudiese dar una idea de cómo realizar el programa de diferentes formas aplicando cada una de las estructuras anteriormente mencionadas. Sin embargo, por la aplicación de estas el programa presentaba diferentes problemas los cuales están descritos abajo:

Jerarquías: se encontró que en pilas las jerarquías no se respetaban y cualquier expresión que tomase una división o multiplicación lo hacía sobre toda la ecuación y no únicamente sobre el último dato ingresado. Se realizó la consulta con compañeros con mayor conocimiento pero no pudieron encontrar el error luego de una asesoría. Por lo que la idea fue descartada debido a que este era uno de los puntos más importantes que se requerían en el programa.

Signos de Agrupación: en el caso de colas, los signos de agrupación proveían de errores que no dejaban realizar el programa su labor. Esto complico el proyecto pues se tuvieron que realizar dos programas que al final no realizaron la tarea esperada.  Esto logro a que se encontrase con un camino sin salida, lo que hizo que se descartase el análisis de la ecuación con este tipo de estructura.

El programa se realizó con una combinación de If’s el cual puede encontrar en el archivo final. Realizando lo siguiente

•	Permitir un mejor análisis de ecuación
•	Permitir que la jerarquía se respetase sin ningún inconveniente. 
