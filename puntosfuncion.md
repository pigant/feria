# Puntos de función

## Caso de uso del sistema

![Feria Uml](/imagenes/feria_casos_de_uso.png)


* [pedido] ver : Muestra lista de pedidos, se selecciona una, muestra información y permite anular

* [pedido] generar : muestra los puestos -> abre un puesto -> busca producto -> agrega a la lista -> quita de la lista -> confirma

* [pedido] calificar : muestra pedidos -> abre un pedido -> comenta -> califica

* [ficha usuario] dirección : entra en perfil -> entra en modificar -> cambia nombre usuario -> cambia dirección -> confirma

* [mantenedor] puesto : Nombre del puesto, número de telefono

## Entradas externas

Para las entradas del sistema.

Caso de uso                   |Archivos |Entradas |Tipo de dato elemental|Evaluación
------------------------------|---------|---------|----------------------|----------
[pedido] ver                  |0        |0        |0                     |Baja
[Pedido] generar              |4        |6        |6                     |Alta
[Pedido] calificar            |3        |2        |2                     |Alta
[ficha usuario] direccion     |1        |2        |2                     |Baja
[ficha usuario] celular       |1        |1        |1                     |Baja
[generar] reporte             |5        |10       |10                    |Alta
[mantenedor] puesto           |1        |2        |2                     |Baja
[mantenedor] producto         |1        |5        |5                     |Baja

* Con valor Bajo: 5
* Con valor Promedio: 0
* Con valor Alto: 3

## Salidas externas

Caso de uso                   |Archivos |Salidas  |Tipo de dato elemental|Evaluación
------------------------------|---------|---------|----------------------|----------
[pedido] ver                  |0        |0        |0                     |Baja
[Pedido] generar              |0        |0        |0                     |Baja
[Pedido] calificar            |0        |0        |0                     |Baja
[ficha usuario] direccion     |0        |0        |0                     |Baja
[ficha usuario] celular       |0        |0        |0                     |Baja
[generar] reporte             |5        |10       |10                    |Alta
[mantenedor] puesto           |0        |0        |0                     |Baja
[mantenedor] producto         |0        |0        |0                     |Baja

* Con valor Bajo: 7
* Con valor Promedio: 0
* Con valor Alto: 1


## Consultas
Caso de uso                   |Archivos |Tipo de dato elemental|Evaluación
------------------------------|---------|----------------------|----------
[pedido] ver                  |5        |16                    |Alto
[Pedido] generar              |0        |0                     |Bajo
[Pedido] calificar            |1        |5                     |Bajo
[ficha usuario] direccion     |1        |3                     |Bajo
[ficha usuario] celular       |1        |3                     |Bajo
[generar] reporte             |0        |0                     |Bajo
[mantenedor] puesto           |2        |8                     |Alto
[mantenedor] producto         |2        |4                     |Promedio

* Con valor Bajo: 5
* Con valor Promedio: 1
* Con valor Alto: 2

## Archivos lógicos internos

### Tablas
* Usuarios
* Feriantes
* Pedidos
* mensajes_alarma
* Puestos
* Productos

## Archivos de interfaz externa

## Caracteristicas generales del sistema
Característica                         |Evaluación
---------------------------------------|------------
Comunicación de datos                  | 5
Procesamiento distribuido de datos     | 3
Rendimiento                            | 4
Configuraciones fuertemente utilizadas | 3
Frecuencia de transacciones            | 5
Entrada de datos on- line              | 5
Eficiencia del usuario final           | 3
Actualizaciones Online                 | 5
Procesamiento complejo                 | 1
Reusabilidad                           | 4
Facilidad de instalación               | 3
Facilidad de operación                 | 4
Instalación en distintos lugares       | 2
Facilidad de cambio                    | 4
Total                                  |51

![Formula](/imagenes/gsc_formula.png)

Por lo que Vaf = 0.65 + 0.51

Vaf = 1.16

## Puntos de función desajustados

Tipo de componente  |  Bajo  |  Medio  |  Alto  |  Total
--------------------|--------|---------|--------|--------
Entrada externa     | 5   x3 |0      x4|3     x6|33
Salida externa      | 7   x4 |0      x5|1     x7|27
Consultas           | 5   x3 |1      x4|2     x6|31
Archivos internos   |   x7   |         |        |7
Archivos internos   |        |         |        |0
Total               |        |         |        |98

UFP = 98

## Puntos de función

*FP = UFP x Vaf*

FP = 98 * 1.16

FP = 113.68

** Estimación de esfuerzo

Utilizando un lenguaje de 4 generación se estima un tiempo por persona de 5 a 10 horas por punto de función

Siendo el total de puntos de función de 113.68, y si estimamos que por punto de función tendremos 8 horas, el tiempo total a utilizar para el proyecto será de 113.68 x 8, lo cual nos da un tiempo de 910 horas, si consideramos un horario de 45 horas semanales, la cantidad de semanas de trabajo se traducen a 21 semanas, y si llevamos esto a meses nos da un total de 6 meses para una sola persona.


113.68 



