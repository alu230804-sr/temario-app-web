# temario-app-web
# Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web

---

## 1. Introducción al desarrollo web

### Historia y evolución del desarrollo web
El desarrollo web comenzó en la década de 1990 con la invención de la World Wide Web por Tim Berners-Lee. Inicialmente, las páginas web eran simples documentos de solo texto con enlaces (HTML). Con el tiempo, la web evolucionó para soportar imágenes, estilos (CSS), interactividad (JavaScript), y posteriormente, la llegada de tecnologías como AJAX permitió experiencias más dinámicas. Hoy en día, el desarrollo web abarca aplicaciones complejas que pueden ejecutarse tanto en navegadores como en dispositivos móviles.

### Tipos de aplicaciones web

- **Estáticas:** Son páginas cuyo contenido no cambia, a menos que el desarrollador modifique el código fuente. Se entregan tal cual están almacenadas en el servidor.
- **Dinámicas:** Generan contenido en tiempo real, generalmente utilizando bases de datos y lenguajes de servidor como PHP.
- **SPA (Single Page Application):** Aplicaciones que cargan una sola página HTML y actualizan dinámicamente el contenido conforme el usuario interactúa, sin recargar la página completa (ejemplo: Gmail).
- **PWA (Progressive Web Application):** Aplicaciones web que usan tecnologías modernas para ofrecer una experiencia similar a una app nativa, incluyendo funcionamiento offline, notificaciones push y acceso desde la pantalla de inicio.

---

## 2. Arquitectura de aplicaciones web

### Cliente-Servidor
La arquitectura cliente-servidor divide el sistema en dos partes: el cliente (navegador) que solicita información y el servidor que procesa estas solicitudes y responde. El cliente muestra la interfaz de usuario, mientras que el servidor maneja la lógica y el acceso a datos.

### Arquitectura de tres capas
- **Presentación:** Interfaz de usuario (HTML, CSS, JavaScript).
- **Lógica de negocio:** Procesamiento de datos, reglas de negocio (normalmente en el servidor, con lenguajes como PHP).
- **Datos:** Manejo y almacenamiento de información (bases de datos como MySQL).

Esta separación mejora la organización, escalabilidad y mantenimiento de la aplicación.

### REST y API-first design
- **REST (Representational State Transfer):** Es un estilo de arquitectura para diseñar servicios web que utilizan HTTP y recursos identificables por URL. Permite una comunicación sencilla y escalable entre sistemas.
- **API-first design:** Es una metodología donde el diseño de la API es el punto de partida del desarrollo, asegurando que las funcionalidades estén bien definidas y sean reutilizables por diferentes clientes (web, móvil, etc.).

---

## 3. Lenguajes y tecnologías fundamentales

- **HTML (HyperText Markup Language):** Estructura básica de las páginas web.
- **CSS (Cascading Style Sheets):** Se encarga del diseño y la presentación visual.
- **JavaScript:** Lenguaje de programación que permite la interactividad y dinamismo en la web.
- **PHP:** Lenguaje de programación del lado del servidor para crear aplicaciones web dinámicas.
- **MySQL:** Sistema de gestión de bases de datos relacional, utilizado para almacenar información de forma estructurada.

---

## 4. Control de versiones

### Git y GitHub
- **Git:** Es un sistema de control de versiones distribuido que permite registrar los cambios realizados en los archivos de un proyecto, facilitando la colaboración y el seguimiento del historial.
- **GitHub:** Plataforma basada en la nube para alojar repositorios Git, colaborar en proyectos, gestionar problemas y revisar código.

### Flujo de trabajo con ramas (branching, merge, pull requests)
- **Branching (ramificación):** Permite crear copias independientes del código para trabajar en nuevas funcionalidades sin afectar la versión principal.
- **Merge (fusión):** Combina los cambios de diferentes ramas en una sola.
- **Pull Requests:** Solicitudes para fusionar cambios de una rama a otra, permitiendo revisiones antes de integrar nuevas características al proyecto principal.

---

Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web
1.-Diseño e implementación del frontend
Maquetación/Wireframe/Mockup
API
2.-Diseño e implementación del backend
Servidor
Manejo de peticiones y respuestas HTTP
Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)
3.-Bases de datos
 Modelado de datos y relaciones
ORM (Object Relational Mapping)
CRUD desde el backend
4.-Seguridad básica en aplicaciones web
Validación de formularios
Autenticación y autorización 

Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional
1. -Integración de frontend y backend
Interfaz de usuario Frontend
Manejo de API
Proceso de Solicitud y Respuesta de Backend

2.- Almacenamiento en Servidor
Tipos de servidores 
Servidores y servicios de hosting 
Proveedores de Servicios de Almacenamiento

3.-Optimización y rendimiento
Optimización de recursos (imágenes, scripts)
Despliegue de aplicaciones web
CI/CD básico
Documentación del proyecto
