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
ARACTERÍSTICA |DESCRIPCIÓN
--------------|------------
Comunicación de datos |	Cuántas facilidades de comunicación hay disponibles para ayudar en el intercambio de información con la aplicación o el sistema?
Procesamiento distribuido de datos |	Cómo se manejan los datos y las funciones de procesamiento distribuido
Rendimiento |	Existen requerimientos de velocidad o tiempo de respuesta?
Configuraciones fuertemente utilizadas |	Cómo de intensivas se utilizan las plataformas hardware donde se ejecuta el sistema
Frecuencia de transacciones |	Con qué frecuencia se ejecutan las transacciones? Diariamente, semanalmente,…
Entrada de datos on- line |	Qué porcentaje de la información se ingresa on-line’
Eficiencia del usuario final |	Aplicación diseñada para maximizar la eficiencia del usuario final
Actualizaciones Online |	Cuántos Archivos Lógicos Internos se actualizan por una transacción on-line?
Procesamiento complejo |	Hay procesamientos lógicos o matemáticos intensivos en la aplicación’
Reusabilidad |	La aplicación se desarrolla para suplir una o muchas de las necesidades de los usuarios?
Facilidad de instalación |	Qué tan difícil es la instalación y la conversión al nuevo sistema?
Facilidad de operación |	Cómo de efectivos y/o automatizados deben ser los procedimientos de arranque, parada, backup y restore
Instalación en distintos lugares |	La aplicación fue concebida para su instalación en múltiples sitios y organizaciones?
Facilidad de cambio |	La aplicación fue concebida para facilitar los cambios sobre la misma?

