# Changelog

Todos los cambios notables de este proyecto se documentan en este archivo.
El formato está basado en [Keep a Changelog](https://keepachangelog.com/es-ES/1.0.0/)
y este proyecto adhiere a [Semantic Versioning](https://semver.org/lang/es/).

## [1.0.0-baseline] - 2026-11-11

### Agregado
- Establecimiento de la línea base inicial del Sistema Integral de Gestión de Restaurante (SIGR — "El Gourmet").
- Interfaz frontend en HTML5, CSS3 y JavaScript ES6+ vanilla con navegación entre los 7 módulos operativos: Pedidos, Reservas, Menú Digital, Usuarios, Clientes, Facturación y Reportes.
- Diseño responsivo para escritorio (`1440x900`) y dispositivos móviles (`390x844`).
- Documentación de gestión de configuración: `CHANGELOG.md` y `LICENSE.txt`.

### Errores Conocidos (GitHub Issues)
- **Issue #4:** `fix: corregir ReferenceError renderPedidos en js/script.js línea 149` — excepción en tiempo de ejecución en la línea base original del docente que bloquea la precarga inicial de datos en `localStorage` y el renderizado de registros de prueba.

### Pendiente / Planificado (GitHub Issues)
- **Issue #1:** `docs: Corregir error tipográfico en la sección de licencia del README`.
- **Issue #2:** `feat: Implementar inicio de sesión con control de roles (admin, mesero, cocinero)`.
- **Issue #3:** `feat: Migrar persistencia a API REST e integrar módulo de cierre de caja`.