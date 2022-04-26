# TEAM3-EJ3-9-18-TA12!



## Ejercicio 3 Geografía


Crear un diseño entidad relación que permita almacenar datos geográficos referidos a España.
![imagen](https://user-images.githubusercontent.com/19403472/165278381-b5725fb6-3387-471d-9313-485f14e7d8fc.png)



## Ejercicio 9 Recetas de Cocina!!


Crear el esquema de entidad / relación que permita gestionar los datos sobre la preparación de recetas de cocina


![Recetas-entidad-relacion](https://user-images.githubusercontent.com/99056015/164432861-9d21d2e2-12c5-4ff3-84ad-0bc6265231c1.jpeg)


![Recetas-modelo relacional](https://user-images.githubusercontent.com/99056015/164432960-e8640592-22b4-41f6-a623-bf345e584b41.jpeg)





## Ejercicio 18 Inmobiliaria

Crear el esquema de entidad / relación que permita gestionar los datos sobre la compra/alquiler de inmuebles a través de una inmobiliaria

![EntidadRelacion](https://user-images.githubusercontent.com/71872946/164405189-d414176c-0bde-4321-a326-842c8df2bc65.JPG)

### Modelo relacional

Cliente (**"DNI"**, Nombre, Apellidos, CP, Móvil, Fijo)</br>
Vendedor (**"DNI"** (FK Cliente), Nombre (FK Cliente), Apellidos (FK Cliente), CP (FK Cliente), Móvil (FK Cliente), Fijo (FK Cliente))</br>
Comprar (**"CódigoCompra"**, FechaCompra, ValorCompra)</br>
Alquilar (**"CódigoAlquiler"**, FechaPago, Valor)</br>
Inmueble (**"CódigoInmueble"**, Dirección, Descripción, m2)</br>
Inmobiliaria (**"ID"**)</br>
Anunciar (**"CódigoInmueble (FK Inmueble), ID_Inmobiliaria (FK Inmobiliaria)"**)</br>
Piso (**"CódigoPiso"**)</br>
Local (**"ID_Local"**, Uso, Servicio)</br>
Garaje (**"NumGaraje"**, Planta)</br>
