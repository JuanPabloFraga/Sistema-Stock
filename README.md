Sobre el trabajo:
Consiste en el sistema de stock de un negocio de zapatillas, en el cual un cliente puede
realizar compras, mientras que el administrador puede gestionar y monitorear los productos
y los movimientos que ocurren en base a estos.
Definición de los casos de uso / funcionalidades:
Administrador:
• Alta, baja y modificación de productos
• Vista de informes de estado de productos en relación a su stock
• Alta de pedidos de stock para productos
• Vista y aceptación de los pedidos
• Vista de consultas (traer pedidos y compras filtrando por fechas o producto)
Cliente:
• Compra de productos (baja en el stock)
Usuarios en general:
• Login – Logout.
Tecnologías utilizadas:
• Java 17
• Spring
• MySQL
• HTML, CSS, JS
• Git / GitHub
Links asociados:
• Repositorio: (https://github.com/JuanPabloFraga/Sistema-Stock.git) (Branch main)
• Video explicativo:
https://drive.google.com/file/d/1oyPd3GEx8iQ6zL1VysQl6kedbEsHKb-f/view
• Inserts para la base de datos:
https://drive.google.com/file/d/1scCiRpvyCNYsMql32pDzjxvvmuMwMvux/view
Cómo levantar el proyecto:
1. Clonar el repositorio alojado en Git Hub https://github.com/JuanPabloFraga/Sistema-Stock
2. Crear una base de datos llamada tpgrupo4
3. Configurar las siguientes variables de entorno para el application.yml
- DB_URL
Ejemplo: jdbc:mysql://localhost:3306/tpGrupo4?useSSL=false&serverTimezone=UTC
- PASSWORD
- USERNAME
4. Iniciar el proyecto, esperar a que compile y se carguen las tablas en la base de
datos.
(el proyecto se puede ver en el localhost 8080)
5. Una vez cargada, hacer los inserts del siguiente script en la base de datos:
https://drive.google.com/file/d/1scCiRpvyCNYsMql32pDzjxvvmuMwMvux/view
6. Ya puede probar todas las funcionalidades del proyecto.
Nombres de los usuarios para el login:
• Administrador
- Username: admin
- Password: admin
• Usuario / cliente
- Username: user
- Password: user
Le dejamos también los datos de un producto para agregar, aunque puede poner los que
quiera.
- Nombre: Zion 3
- Código:548
- Precio:259999
- Stock inicial:30
- Stock mínimo: 10
- Descripción: Zapatillas Jordan Unisex
- Link imagen: https://nikearprod.vtexassets.com/arquivos/ids/870477-1000-1000
(el link de la imagen es opcional para facilitar la carga de productos)
