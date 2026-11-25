<div align="center">

# Juan José Acevedo Morales

### Desarrollador de Software Junior · Backend Java · MySQL · JavaScript

Construyo aplicaciones backend con Java y bases de datos relacionales,<br>
e interfaces web con JavaScript que resuelven problemas concretos.

**Bucaramanga, Santander, Colombia**

[![Portafolio](https://img.shields.io/badge/Portafolio-0B0909?style=for-the-badge&logo=githubpages&logoColor=D4AF5F)](https://juanacevedo124.github.io/Portafolio/)
[![Hoja de vida](https://img.shields.io/badge/Hoja_de_vida-7A1626?style=for-the-badge&logo=readthedocs&logoColor=white)](https://juanacevedo124.github.io/Portafolio/cv.html)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/juan-acevedo-b24759450/)
[![Correo](https://img.shields.io/badge/Correo-D4AF5F?style=for-the-badge&logo=gmail&logoColor=0B0909)](mailto:juanacevedo1240@gmail.com)

</div>

---

## Sobre mí

Soy desarrollador de software en formación en **Campuslands** (enero de 2026 – actualidad), con enfoque en construir aplicaciones que resuelven problemas reales y no solo ejercicios aislados.

La mayor parte de mi trabajo está en el **backend con Java**: modelo las reglas de negocio con programación orientada a objetos, aplico principios SOLID y patrones de diseño, y conecto las aplicaciones a **MySQL** mediante JDBC, con la base de datos en Docker cuando el proyecto lo requiere. En el **frontend** trabajo con JavaScript, HTML y CSS para construir interfaces responsive, componentes reutilizables y sitios que consumen APIs REST.

Me gusta entender bien el problema antes de escribir código. Cuando algo no está claro, investigo por mi cuenta hasta llegar a una solución correcta, y prefiero un sistema que funcione bien a uno que solo cumpla la lista de requisitos.

---

## Tecnologías

| Área | Tecnologías |
|---|---|
| **Lenguajes** | ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=databricks&logoColor=white) |
| **Backend** | ![POO](https://img.shields.io/badge/POO-5A2D82?style=flat-square) ![SOLID](https://img.shields.io/badge/SOLID-5A2D82?style=flat-square) ![JDBC](https://img.shields.io/badge/JDBC-007396?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-básico-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white) |
| **Frontend** | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![Web Components](https://img.shields.io/badge/Web_Components-29ABE2?style=flat-square&logo=webcomponentsdotorg&logoColor=white) |
| **Bases de datos** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) |
| **Automatización** | ![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white) |
| **Herramientas** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white) ![NetBeans](https://img.shields.io/badge/NetBeans-1B6AC6?style=flat-square&logo=apachenetbeanside&logoColor=white) |
| **Metodologías** | ![Scrum](https://img.shields.io/badge/Scrum-6DB33F?style=flat-square&logo=scrumalliance&logoColor=white) ![GitFlow](https://img.shields.io/badge/GitFlow-F05032?style=flat-square&logo=git&logoColor=white) |

---

## Proyectos destacados

### MediSalud: gestión de citas médicas

Sistema de consola para administrar pacientes, médicos, citas, historias clínicas y facturación de una clínica.

**Problema:** una clínica necesita agendar citas entre pacientes y médicos, controlar su estado, llevar la historia clínica y facturar consultas con distintas tarifas, sin perder información ni permitir transiciones inválidas.

**Solución:** una aplicación en capas (vista, controlador, servicios, repositorios y persistencia) que valida cada cambio de estado de una cita y guarda la información en MySQL sobre Docker.

**Tecnologías:** Java · MySQL · JDBC · Docker Compose · Stream API · Concurrencia

**Funcionalidades**

- Agendamiento de citas con control de estados y validación de transiciones
- Cancelación de citas con registro del motivo y migración SQL correspondiente
- Historia clínica por paciente
- Facturación con recargo nocturno o descuento para afiliados
- Reportes por médico, por cancelaciones y por edad de los pacientes
- Notificaciones en un hilo separado

**Qué aprendí:** a aplicar patrones de diseño donde resuelven un problema real (Strategy para las tarifas, Decorator para recargos y descuentos, Observer para las notificaciones, State para el ciclo de vida de la cita y Facade para simplificar el agendamiento) y a organizar un proyecto grande con arquitectura MVC.

[Ver repositorio](https://github.com/JuanAcevedo124/Gestion-de-citas-)

---

### CrediYa S.A.S.: sistema de préstamos y cobros

Aplicación de consola para gestionar empleados, clientes, préstamos y pagos de una empresa de créditos.

**Problema:** la empresa llevaba sus préstamos y abonos a mano, lo que dificultaba calcular saldos, detectar préstamos vencidos y conocer el total de la cartera.

**Solución:** un sistema que calcula automáticamente intereses, cuotas y saldos, y guarda la información en archivos y en MySQL al mismo tiempo, de modo que sigue funcionando aunque no haya conexión a la base de datos.

**Tecnologías:** Java 17 · MySQL 8 · JDBC · Streams y lambdas

**Funcionalidades**

- Registro de empleados y clientes con herencia desde una clase abstracta `Persona`
- Préstamos con cálculo automático de interés, total y valor de la cuota
- Abonos con historial de pagos y saldo pendiente
- Reportes de préstamos activos, vencidos, clientes morosos y total de cartera
- Configuración externa de la conexión, sin credenciales en el código

**Qué aprendí:** a separar responsabilidades con un DAO por entidad, un Singleton para la conexión y una capa de servicio para las reglas de negocio, y a diseñar una persistencia con respaldo ante fallos.

[Ver repositorio](https://github.com/JuanAcevedo124/CrediYa)

---

### Hotel El Rincón del Carmen: sistema de reservas

Aplicación web para buscar y reservar habitaciones de hotel, con panel administrativo.

**Problema:** un hotel necesita que sus clientes reserven en línea sin que dos reservas se crucen en las mismas fechas, y que un administrador gestione habitaciones y reservas.

**Solución:** una interfaz modular construida con Web Components nativos que valida la disponibilidad antes de confirmar cada reserva.

**Tecnologías:** JavaScript ES6+ · Web Components · HTML5 · CSS3 · localStorage

**Funcionalidades**

- Registro e inicio de sesión de usuarios
- Búsqueda por fechas y huéspedes con cálculo automático del precio total
- Validación que impide reservas en fechas que se cruzan
- Cancelación que libera las fechas de inmediato
- Panel administrativo para habitaciones y reservas
- Diseño responsive con enfoque mobile-first

**Qué aprendí:** a modularizar una interfaz sin frameworks, a manejar el estado de la aplicación en el navegador y a escribir la regla de cruce de rangos de fechas.

[Ver repositorio](https://github.com/JuanAcevedo124/Proyecto-Javascript) · [Ver demo](https://juanacevedo124.github.io/Proyecto-Javascript/)

---

### Mini portal de Colombia

Sitio web que consume la API pública api-colombia.com para mostrar departamentos, platos típicos y presidentes del país.

**Problema:** la información sobre los departamentos, la gastronomía y los presidentes de Colombia está dispersa en distintas fuentes.

**Solución:** un portal que centraliza esos datos consultando una API REST en tiempo real.

**Tecnologías:** JavaScript ES6+ · Fetch API · async/await · HTML5 · CSS3

**Funcionalidades**

- Departamentos con región, capital, población y conteo por región
- Galería de platos típicos con filtro
- Presidentes ordenados por periodo de mandato
- Estados de carga y mensajes de error cuando la API no responde

**Qué aprendí:** a consumir APIs REST, a manejar respuestas asíncronas y errores con `try/catch`, y a renderizar datos dinámicamente en el DOM.

[Ver repositorio](https://github.com/JuanAcevedo124/Juan-Acevedo-API-COLOMBIA) · [Ver demo](https://juanacevedo124.github.io/Juan-Acevedo-API-COLOMBIA/)

---

### Eventos Premier S.A.S.: base de datos de reservas

Base de datos para gestionar salones, clientes, reservas y pagos de una empresa de eventos.

**Problema:** la empresa necesita evitar reservas duplicadas de un mismo salón, calcular el valor de cada evento y conservar el historial de cambios de precio.

**Solución:** un modelo relacional con la lógica de negocio dentro de la base de datos mediante funciones, triggers y vistas.

**Tecnologías:** MySQL · Funciones · Triggers · Vistas

**Funcionalidades**

- Función que calcula el valor total de una reserva con IVA
- Función que verifica la disponibilidad de un salón en un rango de fechas
- Triggers que actualizan el estado del salón al reservar o liberar
- Auditoría automática de los cambios de precio
- Vista de resumen y consultas para la toma de decisiones

**Qué aprendí:** a modelar y normalizar una base de datos y a decidir qué reglas conviene llevar al motor de base de datos.

[Ver repositorio](https://github.com/JuanAcevedo124/proyecto-mysql)

---

### Portafolio

Mi sitio personal: el lugar central para ver mis proyectos, conocimientos, hoja de vida y datos de contacto.

**Tecnologías:** HTML5 · CSS3 · JavaScript · GitHub Pages

[Ver repositorio](https://github.com/JuanAcevedo124/Portafolio) · [Ver sitio](https://juanacevedo124.github.io/Portafolio/)

---

## Prácticas de desarrollo

Mis proyectos aplican prácticas que hacen el software más fácil de mantener:

- **Programación orientada a objetos:** herencia, polimorfismo, encapsulamiento y clases abstractas
- **Principios SOLID:** cada clase con una responsabilidad clara y dependencias a través de interfaces
- **Patrones de diseño:** DAO, Singleton, Strategy, Observer, State, Decorator, Builder y Facade
- **Arquitectura en capas:** vista, controlador, servicio y acceso a datos separados
- **Manejo de errores:** excepciones personalizadas y validación de datos de entrada
- **Bases de datos:** modelado entidad-relación, normalización y lógica con funciones y triggers
- **Seguridad básica:** configuración externa y credenciales fuera del repositorio
- **Control de versiones:** Git con ramas, GitFlow y repositorios documentados

---

## Aprendiendo actualmente

- **Pruebas unitarias:** JUnit para verificar automáticamente el comportamiento del código
- **Spring Boot:** APIs REST con controladores, servicios e inyección de dependencias
- **Docker:** contenedores para aplicaciones Java y sus bases de datos
- **Inglés técnico:** nivel B1, avanzando hacia la lectura y escritura fluida de documentación

---

## Actividad en GitHub

Cada repositorio refleja un problema que me propuse resolver y las decisiones técnicas detrás de la solución. Puedes explorar el código o escribirme con comentarios.

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=JuanAcevedo124&show_icons=true&include_all_commits=true&hide_border=true&bg_color=0B0909&title_color=D4AF5F&icon_color=A32A3E&text_color=E9E1D3&locale=es" alt="Estadísticas de GitHub de Juan José Acevedo Morales">
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JuanAcevedo124&layout=compact&langs_count=6&hide_border=true&bg_color=0B0909&title_color=D4AF5F&text_color=E9E1D3&locale=es" alt="Lenguajes más usados">

</div>

---

## Metas profesionales

- Integrarme a un equipo de desarrollo como desarrollador junior o practicante, aportando a software en producción y aprendiendo de desarrolladores con experiencia
- Profundizar en el backend con Java y Spring Boot
- Escribir código más limpio, mejor probado y mejor estructurado en cada proyecto
- Seguir creciendo con buenas prácticas, revisión de código y metodologías ágiles

---

## Contacto

- **Portafolio:** [juanacevedo124.github.io/Portafolio](https://juanacevedo124.github.io/Portafolio/)
- **Hoja de vida:** [Ver en línea](https://juanacevedo124.github.io/Portafolio/cv.html)
- **LinkedIn:** [juan-acevedo-b24759450](https://www.linkedin.com/in/juan-acevedo-b24759450/)
- **Correo:** [juanacevedo1240@gmail.com](mailto:juanacevedo1240@gmail.com)

Disponible para oportunidades como desarrollador junior o practicante, colaboraciones y conversaciones técnicas.

---

<div align="center">
<sub>Desarrollando software con Java, MySQL y JavaScript · Bucaramanga, Colombia</sub>
</div>
