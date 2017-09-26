# Estimación de costes usando modelo cocomo

Para este proyecto se estimó una cantidad de 2220 kloc lo cual implica, se requieren 2 personas (analistas y programadores) para trabajar en un periodo de 6 meses en donde cada uno recibirá un salario de $600.000 /mes líquido, $1.500.000 mensual con AFP y Salud, el cual tendrá un coste total de $9.000.000 por 6 meses de desarrollo. La estimación fue generada por:

Se usó el modo Semi encajado o semi orgánico dado su nivel de complejidad medio-alto.

MODO | a | b | c | d 
-----|---|---|---|---
orgánico | 2.40 | 1.05 | 2.50 | 0.38 
semi - orgánico | 3.00 | 1.12 | 2.50 | 0.35
empotrado | 3.60 | 1.20 | 2.50 | 0.33

## esfuerzo requerido por el proyecto, personas necesarias por mes

E= a(kloc)^bxm(X)

E = 3.0(2220)^1.12x1000

E = 17 persona/mes

## tiempo requerido para desarrollar el proyecto, en meses

Tdev = c(E)^d

Tdev = 2.50(17)^0.35

Tdev = 6 meses

## número de personas necesarias para desarrollar el proyecto

P = E/Tdev

P = 17/6

P = 2 personas

## Costo total del proyecto

CosteE = P * salario medio entre analistas y programadores

CosteE = 2 * 600.000

CosteE = 1.200.000 /mes

CosteE 6 meses = 1.200.000 x 6 = $7.200.000.-

## cantidad total líneas de código (kloc)


Cantidad total casos de uso | cantidad total Kloc
--------------------------- | -------------------
21             | 2220

# kloc por caso de uso

Caso de Uso | Kloc
----------- | ------------
[generar]      |  100
[generar] reporte     | 200  
[generar] pedido      |  200
[pedido] ver         |  200
[ver] estado      |  80
[ver] abierto     |  80
[ver] pausa       |  80
[ver] cerrado     |  80
[ver] cancelar     |  80
[pedido]      |  50
[pedido] generar     |  200
[pedido] calificar   |  100
[ficha usuario] |  120
[ficha usuario] direccion   | 50
[ficha usuario] celular     | 50
[mantenedor] | 150
[mantenedor] puesto      | 80
[mantenedor] producto    | 80
[mantenedor] precio      | 80
[mantenedor] nombre      | 80
[mantenedor] cantidad    | 80

