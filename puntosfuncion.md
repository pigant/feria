# Puntos de función

## Caso de uso del sistema

![Feria Uml](/imagenes/feria_casos_de_uso.png)


* [pedido] ver : Muestra lista de pedidos, se selecciona una, muestra información y permite anular`

* `[pedido] generar : muestra los puestos -> abre un puesto -> busca producto -> agrega a la lista -> quita de la lista -> confirma`

* `[pedido] calificar : muestra pedidos -> abre un pedido -> comenta -> califica`

* `[ficha usuario] dirección : entra en perfil -> entra en modificar -> cambia nombre usuario -> cambia dirección -> confirma`

* _[mantenedor]  : Nombre del puesto, número de telefono`

## Entradas externas

Para las entradas del sistema.

Caso de uso                   |Entradas |Tipo de dato elemental
------------------------------|---------|----------------------
[pedido] ver                  |0        |0
[Pedido] generar              |6        |6
[Pedido] calificar            |2        |2
[ficha usuario] direccion     |2        |2
[ficha usuario] celular       |1        |1
[generar] reporte             |10       |10
[mantenedor] puesto           |2        |2
[mantenedor] producto         |5        |5

## Salidas externas

## Consultas

## Archivos lógicos internos

### Tablas
* Usuarios
* Feriantes
* Pedidos
* mensajes_alarma

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

