🌙 Sueños Valenti – Portal de Sesiones de Supra Conciencia

Proyecto web desarrollado con Node.js, Express y EJS como práctica de backend en el ciclo de Desarrollo de Aplicaciones Web (DAW).

El objetivo del proyecto es crear la primera versión funcional de un portal web para la gestión de sesiones grupales de conexión con la supra conciencia, aplicando conceptos clave de servidor, rutas, formularios, sesiones y cookies.

🧠 Descripción del proyecto

La empresa ficticia Sueños Valenti quiere ofrecer una plataforma donde los usuarios puedan:

Informarse sobre las sesiones y la empresa

Registrarse mediante un formulario

Iniciar sesión y acceder a una zona privada

Gestionar sus sesiones desde una zona personal

Guardar preferencias visuales (modo claro / oscuro)

Registrar acciones del usuario en archivos del servidor

Todo el sistema se ha desarrollado sin base de datos real, utilizando JSON, sesiones y cookies, tal y como se solicita en el enunciado.

🛠️ Tecnologías utilizadas

Node.js

Express

EJS (motor de plantillas)

Express-session

Cookies

JavaScript

JSON

HTML / CSS básico

📁 Estructura del proyecto
/public        → Archivos estáticos (CSS)
/views         → Vistas EJS
/data          → Archivos JSON (usuarios)
/routes        → Rutas GET y POST
app.js         → Servidor principal


Proyecto organizado siguiendo una estructura clara y modular.

🔧 Funcionalidades implementadas
1️⃣ Servidor y rutas

Servidor Express configurado correctamente

Rutas GET y POST separadas

Renderizado dinámico con EJS

2️⃣ Página de inicio (GET /)

Nombre de la web: Sueños Valenti

Descripción del proyecto

Enlaces a:

Login

Registro

Preferencias

Sesiones

3️⃣ Registro de usuarios (GET /registro – POST /registro)

Formulario con:

Nombre

Email

Edad

Ciudad

Intereses (checkbox múltiple)

Validaciones:

Nombre obligatorio

Email válido

Edad mayor que 0

Los usuarios se guardan en:

/data/usuarios.json

4️⃣ Login y sesiones (GET /login – POST /login)

Acceso mediante email y contraseña (simplificada)

Creación de sesión con datos del usuario

Redirección a zona privada tras login correcto

5️⃣ Zona privada (/perfil)

Acceso solo con sesión activa

Muestra datos del usuario

Posibilidad de cerrar sesión

Gestión de sesiones mediante un carrito almacenado en sesión

6️⃣ Preferencias y cookies (GET /preferencias)

Cambio entre modo claro / oscuro

Preferencia guardada en una cookie

Aplicación dinámica de estilos al <body>

7️⃣ Gestión de ficheros

Lectura y escritura de archivos JSON

Registro de accesos y acciones del usuario usando appendFile

Logs almacenados en archivo de texto

✅ Criterios de evaluación cubiertos

✔ Rutas GET y POST funcionales
✔ Validaciones y control de errores
✔ Uso correcto de EJS
✔ Manejo de sesiones
✔ Cookies para preferencias visuales
✔ Acceso a ficheros JSON y logs
✔ Proyecto organizado y funcional

🚀 Conclusión

Este proyecto me ha permitido reforzar conceptos fundamentales de backend con Node.js, como el flujo de peticiones, la gestión de sesiones, el uso de plantillas EJS y el trabajo con datos persistentes mediante archivos.

Forma parte de mi aprendizaje práctico dentro del ciclo DAW.
