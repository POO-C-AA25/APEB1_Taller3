# Taller 3 (Laboratorio)

## Creación de programas usando los conceptos iniciales de POO

* Leer detenidamente cada problemática propuesta.
* Usar el programa **DIA-UML** _(Open source)_ para generar la representación de su solución _(modelado)_, vía diagramas de clases.
* Para cada diagrama/solución _(modelado de su solución)_, genere/agregue 2 archivos _(fuente e img: \*.dia y \*.png \*.jpeg, etc)_. No olvide titular a cada clase, con el nombre representativo del análisis/solución. Para el nombrado de cada archivo use el formato: _Problema-NroProbl_NombClase_. Ejemplo **Problema-1_Trabajador**. Todos estos archivos agréguelos en el subDirectorio: **Modelos_UML**
* En el subDirectorio **Solucion_Codigo** cree un único proyecto NetBeans - _Java Aplication_ (o con el IDE de su preferencia) y en él, agrégue todas las clases necesarias para la solución de cada problema _(no use paquetes aun)_. Y para facilitar la revisión, utilice para la clase base el formato _Problema-NroProbl_NombClaseBase_, y para la clase de prueba/ejecutor use _Problema-NroProbl_NombClaseEjecutor_ (Ésta última es la clase de prueba que genera/instancia con objetos cada entidad/clase y verifica su funcionalidad). 
* Respete la arquitectura MVC, es decir, no implemente entradas/salidas desde/hacia teclado-consola directamente en la clase base. Los datos de entrada y resultados deben ser ingresados/mostrados desde/hacia teclado-consola, en la clase de prueba/ejecutor.
* Para retornar los datos del objeto, usar el método toString, vía cadena con formato legible. 
* Recuerde, según el problema, puede existir método establecer que no requieren argumentos, pero si un procesamiento. 

___

## Problema 1

Elaborar una solución que calcule e imprima el costo de un terreno rectangular; se tiene como datos el ancho y el largo en metros; el valor del metro cuadrado. El area del terreno es igual a largo por ancho. El costo del terreno es igual al valor del metro cuandrado por el area del terreno. Luego del análisis se decide usar las siguientes entidades:

* Entidades o Clases
	* Terreno 
	* Ejecutor
	
* Terreno, tiene los siguientes atributos
	* costo_terreno
	* ancho
	* largo
	* area
	* valorMetroCuadrado
* Ejecutor
	* Tiene el método main

> [!Note]
> - .

## Problema 2

Elaborar una solución que lea una cantidad de horas e imprima su equivalente en minutos, segundos, días.

* Entididades o Clases
	* EquivalenteHora
	* Ejecutor
	
* EquivalenteHora
	* horas
	* minutos
	* segundos
	* dias
	
* Ejecutor
	* Tiene el método main

> [!Note]
> - .

## Problema 3

Se necesita representar una entidad que permite administrar Instituciones Educativas. Cada institución tienen como características: nombre, tipo de institución, número de alumnos, número de docentes, número de sedes, gastos proyectado por estudiante, presupuesto. El presupuesto es igual a la cantidad de alumnos de la institución por el gatos proyectado por estudiante.

> [!Note]
> - .

## Problema 4

Para un sistema, es necesario abstraer las características de dispositivos electrónicos como los son los Equipo Celulares. Cada Equipo Celular tienen como características: sistema operativo, tamaño de pantalla, costo inicial, iva en porcentaje, iva del costo inicial costo final, dirección mac, información IMEI. El costo final del equipo es igual costo inicial más el iva del costo inicial. 

> [!Note]
> - .

## Problema 5

* Se requiere representar una entidad que permita crear objetos con características como:  nombre de estudiante, calificación de materia 1, calificación de materia 2, calificación de materia 3 y promedio de calificaciones. 

> [!Note]
> - .

## Problema 6

* Los profesores de un instituto tienen algunas características: nombre, apellido, sueldo básico, sueldo total y cédula. El sueldo total es igual al sueldo básico más el 20% del sueldo básico.

> [!Note]
> - .

## Problema 7

* Un automotor tiene entre sus características, cédula del dueño, marca de vehículo, año de fabricación, valor de vehículo y valor de la matricula. El valor de la matricula es igual al 0.002% del valor de vehículo por el número de años de antiguedad del vehiculo.

> [!Note]
> - .

## Problema 8

* En una entidad financiera se requiere manejar los cheques. Cada cheque tiene las siguientes propiedades: nombre del cliente, nombre del banco, valor del cheque y comisión que cobra el banco. La comisión del banco es igual al valor del cheque por el 0.003%.

> [!Note]
> - .

## Problema 9

Diseña una clase llamada Pedido para gestionar los pedidos realizados en una tienda online. La clase debe permitir registrar la información relevante de un pedido, como los productos solicitados, la cantidad de cada producto, el total del pedido y la dirección de envío.

La clase debe incluir métodos para añadir productos al pedido, calcular el total del pedido, actualizar la cantidad de un producto, eliminar un producto del pedido y mostrar la información completa del pedido.

Este problema permite practicar el diseño de una clase para gestionar un aspecto específico de un sistema más amplio, como es el caso de los pedidos en una tienda online. La flexibilidad en el diseño de la clase permite adaptarla a las necesidades particulares del sistema. 

> [!Note]
> - Es potestad de su análisis, determinar los niveles de acceso para los datos de los objetos involucrados.
