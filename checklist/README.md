# Checklist

## Backend

|Requerimiento funcional|cant. mín.<br>1 o 2 integ|cant. máx.<br>3 o 4 integ|Detalle/Listado de casos|Cumple|
|:-|-:|-:|:-|-|
|ABMC simple|1 x integ|1 x integ| ABMC User <br/>ABMC Owner <br/>ABMC Province <br/>ABMC PropertyType |
|ABMC dependiente|1|2| ABMC City<br/> ABMC Property |
|Listado simple|1|1| Listado de provincias <br/>Listado de ciudades |
|Listado complejo obligatorio|1|2| Listado de propiedades disponibles en una ciudad <br/>Listado de propietarios con sus datos y cantidad de propiedades |
|Listado adicional con filtro|0|0| Listado de propiedades por precio |
|Detalle básico|1(*)|2(*)| Detalle de Contratos <br/>Listado de propietario con cada propiedad que posee
|Detalle parametrizable|0|0|
|Otros|0|0|

(\*) Los detalles básicos pueden ser reemplazado por un detalle parametrizados en los

## Frontend

|Requerimiento|Cumple|
|:-|-|
|Invocar API listado||
|Invocar API detalle||
|Mostrar detalle al hacer click <br>en elemento del listado||

## Requerimientos Técnicos

|Requerimiento técnico|Cumple|
|:-|-|
|Framework frontend||
|Framework CSS o preprocesador CSS||
|Framework backend||
|Uso de API REST o GraphQL||
|ORM/ODM||
|Base de datos persistente||
