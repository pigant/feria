# Estimación de costes usando modelo cocomo

Para este proyecto se estimó una cantidad de 9600 kloc lo cual implica, se requieren 7 personas (analistas y programadores) para trabajar en un periodo de 12 meses en donde cada uno recibirá un salario de $600.000 /mes y el cual tendrá un mensual total de $4.200.000/mes, y un coste total anual de $50.400.000. La estimación fue generada por:

Se usó el modo Semi encajado dado su nivel de complejidad medio-alto.

MODO | a | b | c | d 
-----|---|---|---|---
orgánico | 2.40 | 1.05 | 2.50 | 0.38 
semi - orgánico | 3.00 | 1.12 | 2.50 | 0.35
empotrado | 3.60 | 1.20 | 2.50 | 0.33

## esfuerzo requerdio por el proyecto, personas necesarias por mes

E= a(kloc)^b

E = 3.0(9600)^1.12

E = 87 persona/mes

## tiempo requerido para desarrollar el proyectoi, en meses

Tdev = c(E)^d

Tdev = 2.50(87)^0.35

Tdev = 12 meses

## número de personas necesarias para desarrollar el proyecto

P = E/Tdev

P = 82/12

P = 7 personas

## Costo total del proyecto

CosteE = P * salario medio entre analistas y programadores

CosteE = 7 * 600.000

CosteE = 4.200.000 /mes

CosteE Anual = 4.200.000 x 12 = $50.400.000.-

## cantidad total líneas de código (kloc)


Cantidad total casos de uso | cantidad total Kloc
--------------------------- | -------------------
21             | 9600

# kloc por caso de uso

Caso de Uso | Kloc
----------- | ------------
[generar]      |  500
[generar] reporte     |  500
[generar] pedido      |  500
[pedido] ver         |  500
[ver] estado      |  500
[ver] abierto     |  500
[ver] pausa       |  500
[ver] cerrado     |  500
[ver] cancelar     |  500
[pedido]      |  500
[pedido] generar     |  700
[pedido] calificar   |  600
[ficha usuario] |  500
[ficha usuario] direccion   | 300
[ficha usuario] celular     | 300
[mantenedor] | 700
[mantenedor] puesto      | 300
[mantenedor] producto    | 300
[mantenedor] precio      | 300
[mantenedor] nombre      | 300
[mantenedor] cantidad    | 300

