\# SIGR – Sistema Integral de Gestión de Restaurante



Aplicación web para la gestión integral de un restaurante: autenticación

por roles, menú, pedidos por mesa, reservas, reportes de ventas y cierre

de caja. Construida con HTML5, CSS3, JavaScript (vanilla) y MySQL 8.



Versión actual: v1.0.0



\## Requisitos previos

\- Navegador moderno (Chrome, Firefox, Edge o Safari, últimas 2 versiones)

\- Servidor web local para archivos estáticos (p. ej. XAMPP, Laragon,

\- extensión Live Server de VS Code o `python -m http.server`)

\- MySQL Server 8.0 o superior y MySQL Workbench

\- Git 2.30 o superior



\## Instalación

1\. Clonar el repositorio:

\-  git clone 

\-  cd sigr

2\. Crear la base de datos:  

3\. Cargar los datos de prueba:  

4\. Configurar la URL base de la API en js/utils.js



5\. Publicar la carpeta sigr/ en el servidor web local.



\## Ejecución

\- Abrir http://localhost:8000/index.html (o el puerto configurado).

\- Usuarios de prueba:

\- admin@sigr.com / Admin2026\*   (administrador) #ejemplos de simulación

\- mesero@sigr.com / Mesero2026\* (mesero) #ejemplos de simulación

\- cliente@sigr.com / Cliente2026\* (cliente) #ejemplos de simulación



\## Capturas de pantalla

\- Inicio: portada con acceso al menú y botón de reserva.

\- Login: formulario de correo y contraseña con mensajes de error.

\- Menú: tarjetas de platos por categoría con buscador.

\- Pedidos: selección de mesa, lista de platos y total en vivo.

\- Dashboard: indicadores del día y accesos por rol.

\- Reportes: ventas diarias, top 5 de platos y cierre de caja.



\## Contribución

1\. Crear una rama desde develop: feature/<nombre-funcionalidad>

2\. Usar Conventional Commits: feat(menu): agregar filtro por precio

3\. Abrir un pull request hacia develop con al menos 1 revisor.

4\. Reportar errores y mejoras en GitHub Issues con la etiqueta adecuada.



\## Licencia

Distribuido bajo la licencia MIT. Ver el archivo LICENSE.txt.



