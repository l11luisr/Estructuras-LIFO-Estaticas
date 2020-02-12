
					  UNIVERSIDAD AUTÓNOMA DE BAJA CALIFORNIA
				        FACULTAD DE CIENCIAS QUÍMICAS E INGENIERÍA
			                     ALGORITMOS Y ESTRUCTURA DE DATOS
		                                         2020-1
					               PRÁCTICA #2

Alumnos:

	* Cota Robledo Benjamín [1225836]

	* Rodriguez Muñoz José Luis [1260368]

Práctica: Estructuras LIFO Estáticas

Fecha: 02/11/2020

Competencia: Aplicar eficientemente el principio LIFO para generar soluciones creativas a problemas de ingeniería.

Actividad:
	Se desea implementar dos pilas, y se dispone de un solo vector de N componentes.
	Implemente ambas pilas de manera que se pueda aprovechar al máximo el vector.
	Las operaciones de pila tendrán que llevar un parámetro adicional que indique sobre qué pila se quiere realizar la operación 		(pila 1 ó pila 2).

Consideraciones:

	* Las dos pilas crecen partiendo de los extremos del arreglo.
	* El tamaño de cada pila es máximo N.
	* El tope de cada pila puede ir de 0 a N, por ejemplo: si el vector tiene tamaño N=10, y se meten 7 elementos a la pila 1, la pila dos tendría máximo 3 espacios. Si el vector tiene tamaño N=8 y se meten 8 elementos a la pila 1, la pila dos tendría máximo 0 espacios.
	* La cantidad de elementos entre ambas pilas no puede ser mayor a N.
	* Solamente puede usar un solo arreglo para implementar ambas pilas.
	* Las capturas de valores deben estar validadas.
	* El programa debe tener una opción mostrar para ver el contenido de las pilas sin sacar los elementos de ella.
	* Solo debe existir una función pop, push y mostrar.
	* El programa debe repetirse N veces hasta que se seleccione la opción de salida.
	* Una de las pilas debe iniciar en la posición 0 mientras que la otra en la última posición del vector.
	* Ambas pilas son de números enteros, donde 0 significa que la posición está vacía.
