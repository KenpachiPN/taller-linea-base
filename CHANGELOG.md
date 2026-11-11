# Changelog

Todos los cambios notables de este proyecto se documentan en este archivo.
El formato está basado en [Keep a Changelog](https://keepachangelog.com/es-ES/1.0.0/)
y este proyecto adhiere a [Semantic Versioning](https://semver.org/lang/es/).

## [1.0.0-baseline] - 2026-11-11

### Agregado
- Establecimiento de la línea base inicial del Sistema Integral de Gestión de Restaurante (SIGR — "El Gourmet").
- Módulos operativos frontend en HTML5, CSS3 y JavaScript ES6+ vanilla:
  - **Pedidos:** gestión de órdenes con carrito de compras y estadísticas.
  - **Reservas:** control de mesas y estados (confirmada, pendiente, cancelada).
  - **Menú Digital:** CRUD completo de platillos por categorías, precios y disponibilidad.
  - **Usuarios:** administración de empleados con roles (admin, mesero, cocinero).
  - **Clientes:** registro, filtros de búsqueda en tiempo real y paginación.
  - **Facturación:** generación de facturas con cálculo automático de IVA.
  - **Reportes:** visualización de métricas de ventas, clientes frecuentes y reservas.
- Capacidades transversales: diseño responsivo, validaciones de formulario, notificaciones toast y soporte de persistencia en `localStorage`.
- Documentación de gestión de configuración: `CHANGELOG.md` y `LICENSE.txt`.

### Pendiente / Planificado (GitHub Issues)
- **Issue #1:** Corrección tipográfica en la sección de licencia de `README.md`.
- **Issue #2:** Implementación de módulo de inicio de sesión asociado a los roles del sistema.
- **Issue #3:** Migración de persistencia hacia API REST / base de datos e integración de cierre de caja.