# IISSI2

Evaluación individual laboratorio 2022-2023:
- [customRestaurantCategories](https://github.com/IISSI2-IS-2022-2023/Parciales/commits/customRestaurantCategories/)
- [restaurantDiscountCodes](https://github.com/IISSI2-IS-2022-2023/Parciales/commits/restaurantDiscountCodes/)
- [sortProductsByPriceSolution](https://github.com/IISSI2-IS-2022-2023/Parciales/commits/sortProductsByPriceSolution/)

Simulacro 2024: [simulacro-2024](https://github.com/fluserl/gazpacho/commits/simulacro-2024/)

Labs: [labs](https://github.com/fluserl/gazpacho/commits/labs/)

Preparación del entorno
a) Windows
Abra un terminal y ejecute el comando npm run install:all:win.
b) Linux/MacOS
Abra un terminal y ejecute el comando npm run install:all:bash.
Ejecución
Backend
Para rehacer las migraciones y seeders, abra un terminal y ejecute el comando

npm run migrate:backend
Para ejecutarlo, abra un terminal y ejecute el comando

npm run start:backend
Frontend
Para ejecutar la aplicación frontend de customer, abra un nuevo terminal y ejecute el comando

npm run start:frontend:customer
Para ejecutar la aplicación frontend de owner, abra un nuevo terminal y ejecute el comando

npm run start:frontend:owner
Depuración
Para depurar el backend, asegúrese de que NO existe una instancia en ejecución, pulse en el botón Run and Debug de la barra lateral, seleccione Debug Backend en la lista desplegable, y pulse el botón de Play.

Para depurar el frontend, asegúrese de que EXISTE una instancia en ejecución del frontend que desee depurar, pulse en el botón Run and Debug de la barra lateral, seleccione Debug Frontend en la lista desplegable, y pulse el botón de Play.

Test
Para comprobar el correcto funcionamiento de backend puede ejecutar el conjunto de tests incluido a tal efecto. Para ello ejecute el siguiente comando:

npm run test:backend

