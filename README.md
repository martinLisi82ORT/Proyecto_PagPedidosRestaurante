# PNT2-20231C-GRUPO5-ProyectoFinal
Idea elegida: Gestión de Deliverys de Restaurante.

               Nombre de la app = Resto Vue Pedidos.
              
# Lista de los requerimientos técnicos
App para realizar pedidos de comida, con login de usuario. 
Se podra recorrer el menu de platos e ir cargando los pedidos a un "carrito de compras". Finalizada la seleccion, se podra ir a la seccion de pagos.

Login :
  - creación de usuario
  - logear a usuario ya creado
  - Usuarios no logueados pueden acceder solo a: Menú (pero se requiere estar logueado para realizar un pedido), index y login.
  - Roles: El usuario admin/gerente (creado por nosotros por lo que sabemos su mail y contraseña) es el unico usuario que puede acceder a la pagina de informes/estadísticas.

Componente de inicio : 
  - Componente inicio que muestre información general: nombre del restaurante, dirección y número de teléfono.
  - Permitir a los usuarios ver, en la barra de navegación, las páginas a las que puede acceder según su rol(definido en la sección login).

Menú y Pedidos : 
  - Menú completo del restaurante, platos disponibles con sus descripciones y precios
  - Permitir agregar platos al carrito de compras
  - Carrito: Muestra todo lo que se agrego al carrito y permitirá tanto confirmar la compra (confirmación del pedido) como cancelar el pedido, que limpiara todo el carrito.
  - Confirmación del pedido: Una vez confirmado el pedido se redireccionará al usuario a la pantalla de pago.

Carrito y Pago : 
  - Componente de pagos de los clientes 
  - Calcular total de la orden
  - Confirmación: Simular una transacción una vez que el usuario confirme
  - Enviar una confirmación del pedido al usuario después del pago
  - Cancelar: Si el usuario se arrepiente debería presionar en "Cancelar" que lo llevará de nuevo al menú de platos.

Informes :<br />
Log de acciones : estadísticas del restaurante , ingresos , platos más vendidos. Componente AppEstadisticas.vue
  - Permisos = solo el Usuario Admin
  - Calendario/tabla de platos mas pedidos por dia de la semana: Habria q ver como se haria esta funcionalidad.
      - OPCION -> agregar atributo FECHA a los Platos del Historial.Herramienta que puede servir: https://date-fns.org/

Historial :<br />
Componente: AppHistorial.vue
  - para mostrar un historial de los pedidos que hizo.
  - Mostrar-> plato: con precio y FECHA del pedido.


---

<div align="center">
<img src="https://img.shields.io/badge/Vue%20js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D" />

<img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" />

<img src="https://img.shields.io/badge/Node%20js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />

<img src="https://img.shields.io/badge/axios-671ddf?&style=for-the-badge&logo=axios&logoColor=white" />

<img src="https://img.shields.io/badge/Babel-F9DC3E?style=for-the-badge&logo=babel&logoColor=white" />

<img src="https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" />

</div
  
---


## Ejemplo de usuarios:

Usuario 1: Mail: user1@user1 - Contraseña: contra1

Usuario 2: Mail: user2@user2 - Contraseña: contra2

Usuario 3: Mail: user3@user3 - Contraseña: contra3

Usuario 4: Mail: user4@user4 - Contraseña: contra4

Usuario 5: Mail: user5@user5 - Contraseña: contra5

Usuario Administrador: Mail: admin@admin - Contraseña: contraadmin

### Ejemplo componente inicio:
![Inicio](https://github.com/martinLisi82ORT/Proyecto_PagPedidosRestaurante/assets/111402719/8d9a6a47-f235-4a0f-8584-78c097537dff)

### Ejemplo Menú y Pedidos:
![Menu](https://github.com/martinLisi82ORT/Proyecto_PagPedidosRestaurante/assets/111402719/ebc3bc81-9815-4e66-b383-2983509c0375)

### Ejemplo Login:
![Login](https://github.com/martinLisi82ORT/Proyecto_PagPedidosRestaurante/assets/111402719/4d7f57e3-adb2-4d89-a4f9-a6a26b550d59)

### Ejemplo componente Pago:
![Pago](https://github.com/martinLisi82ORT/Proyecto_PagPedidosRestaurante/assets/111402719/0e2030bc-c061-4a63-b081-cdc230c2c515)

