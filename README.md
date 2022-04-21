# TEAM3-EJ3-9-18-TA12!



## Ejercicio 3 Geografía


Crear un diseño entidad relación que permita almacenar datos geográficos referidos a España.

![ej3-Diagrama ER drawio](https://user-images.githubusercontent.com/19403472/164429429-29e67410-670e-4c0b-b163-88ae48cfa70d.png)

![ej3-Esquema Relacional drawio](https://user-images.githubusercontent.com/19403472/164429365-0e3086e7-6356-4bc8-81fa-ba1348164b9e.png)


## Ejercicio 9 Recetas de Cocina!![Uploading ej3-Diagrama ER.drawio.png…]()



Crear el esquema de entidad / relación que permita gestionar los datos sobre la preparación de recetas de cocina


![Recetas-entidad-relacion](https://user-images.githubusercontent.com/99056015/164424016-96f3ef8c-569c-47ed-9049-97c11a8a683e.jpeg)








## Ejercicio 18 Inmobiliaria

Crear el esquema de entidad / relación que permita gestionar los datos sobre la compra/alquiler de inmuebles a través de una inmobiliaria

![EntidadRelacion](https://user-images.githubusercontent.com/71872946/164405189-d414176c-0bde-4321-a326-842c8df2bc65.JPG)

### Modelo relacional

Cliente (<u>DNI</u>, Nombre, Apellidos, CP, Móvil, Fijo)
Vendedor (</u>DNI (FK Cliente), Nombre (FK Cliente), Apellidos (FK Cliente), CP (FK Cliente), Móvil (FK Cliente), Fijo (FK Cliente))
Comprar (<u>CódigoCompra</u>, FechaCompra, ValorCompra)
Alquilar (<u>CódigoAlquiler</u>, FechaPago, Valor)
Inmueble (<u>CódigoInmueble</u>, Dirección, Descripción, m2)
Inmobiliaria (<u>ID</u>)
Anunciar (<u>CódigoInmueble (FK Inmueble), ID_Inmobiliaria (FK Inmobiliaria)</u>)
Piso (<u>CódigoPiso</u>)
Local (<u>ID_Local</u>, Uso, Servicio)
Garaje (<u>NumGaraje</u>, Planta)
