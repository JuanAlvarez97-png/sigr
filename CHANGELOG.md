\# Changelog simulado. documento de ejemplo

Todos los cambios notables de este proyecto se documentan en este archivo.

El formato se basa en Keep a Changelog 

y el proyecto sigue Versionado Semántico .



\## \[Unreleased]



\## \[1.0.0] - 2026-11-01  (Línea base)

\### Added

\#### Autenticación

\- Inicio y cierre de sesión con correo y contraseña (HU-01).

\- Redirección por rol: cliente, mesero y administrador.

\- Bloqueo temporal tras 5 intentos fallidos y expiración de sesión.

\- Gestión de usuarios: crear, editar, activar y desactivar (HU-13).

\#### Menú

\- Visualización del menú por categorías con buscador (HU-02).

\- CRUD de platos con validación de precio y baja lógica (HU-07 a HU-09).

\- Gestión de categorías con nombre único (HU-10).

\#### Pedidos

\- Registro de pedidos por mesa con cálculo automático de totales (HU-03).

\- Seguimiento del estado con refresco cada 15 s (HU-04).

\- Historial de pedidos con filtros y paginación (HU-14).

\- Actualización secuencial de estados (HU-15).

\#### Reservas

\- Creación de reservas con validación de capacidad y solapamiento (HU-05).

\- Cancelación de reservas hasta 2 horas antes (HU-06).

\#### Caja/Reportes

\- Reporte de ventas diario con top 5 de platos y exportación CSV (HU-11).

\- Apertura y cierre de caja con control de diferencias (HU-12).

\#### Base de datos

\- Script sigr\_schema.sql con 8 tablas, claves e índices.

\- Script sigr\_datos\_prueba.sql con datos de ejemplo.

\#### Documentación

\- README, CHANGELOG, LICENSE, manual de usuario y de despliegue.



\### Fixed

\- Los pedidos ya no pueden retroceder a un estado anterior.

\- La mesa se libera automáticamente al marcar un pedido como pagado.



\[Unreleased]:

