# 🍔 FoodRush — App de Comida

>JUAN CAMILO BAEZ BAUTISTA 
> Requisitos Funcionales y No Funcionales

---

## 📋 Descripción del Problema

Los usuarios quieren pedir comida a domicilio de manera rápida y sencilla desde su celular o computador, sin necesidad de llamar por teléfono. Los restaurantes necesitan recibir y gestionar pedidos de forma eficiente. La solución es un sistema de delivery digital que conecte clientes, restaurantes y repartidores en una sola plataforma.

---

## ✅ Requisitos Funcionales

Los requisitos funcionales describen **qué debe hacer** el sistema.

### RF-01 — Registro e inicio de sesión
El sistema debe permitir que los usuarios se registren con correo electrónico y contraseña, y que puedan iniciar sesión de forma segura.

### RF-02 — Búsqueda de restaurantes y productos
El sistema debe permitir a los usuarios buscar restaurantes por nombre, categoría de comida o ubicación, y consultar el menú de cada restaurante.

### RF-03 — Gestión del carrito de compras
El sistema debe permitir al usuario agregar, modificar y eliminar productos de un carrito de compras antes de confirmar el pedido.

### RF-04 — Realización del pedido
El sistema debe permitir al usuario confirmar su pedido, seleccionar la dirección de entrega y elegir el método de pago (efectivo, tarjeta o billetera digital).

### RF-05 — Seguimiento del pedido en tiempo real
El sistema debe mostrar al usuario el estado de su pedido en tiempo real: recibido, en preparación, en camino y entregado.

### RF-06 — Historial de pedidos
El sistema debe registrar y mostrar el historial de pedidos realizados por cada usuario, incluyendo fecha, productos y valor total.

### RF-07 — Calificación y reseñas
El sistema debe permitir al usuario calificar el restaurante y el repartidor una vez entregado el pedido.

### RF-08 — Gestión de restaurantes (administrador)
El sistema debe permitir a los administradores de restaurantes agregar, editar y eliminar productos del menú, y gestionar la disponibilidad del restaurante.

### RF-09 — Notificaciones
El sistema debe enviar notificaciones al usuario cuando el estado de su pedido cambie.

### RF-10 — Panel de repartidor
El sistema debe mostrar al repartidor los pedidos asignados, la ruta sugerida y permitirle actualizar el estado de la entrega.

---

## 🔒 Requisitos No Funcionales

Los requisitos no funcionales describen **cómo debe comportarse** el sistema.

### RNF-01 — Rendimiento
El sistema no debe tardar más de 3 segundos en cargar la lista de restaurantes disponibles. Si supera este tiempo, debe mostrar un indicador de carga.

### RNF-02 — Disponibilidad
El sistema debe estar disponible el 99% del tiempo (24/7), especialmente en horas pico de pedidos (11am–2pm y 6pm–9pm).

### RNF-03 — Seguridad
El sistema debe cumplir con la Ley de Protección de Datos Personales. Las contraseñas deben almacenarse cifradas y los pagos deben procesarse bajo protocolos seguros (HTTPS, SSL).

### RNF-04 — Usabilidad
El sistema debe ser intuitivo y fácil de usar para personas sin conocimientos técnicos. Un usuario nuevo debe poder realizar su primer pedido en menos de 5 minutos.

### RNF-05 — Compatibilidad
El sistema debe funcionar correctamente en los navegadores Chrome, Firefox y Safari, y en dispositivos móviles Android e iOS.

### RNF-06 — Escalabilidad
El sistema debe soportar al menos 1.000 usuarios simultáneos sin degradar su rendimiento.

### RNF-07 — Mantenibilidad
El código del sistema debe estar documentado y estructurado de forma modular para facilitar futuras actualizaciones o correcciones.




