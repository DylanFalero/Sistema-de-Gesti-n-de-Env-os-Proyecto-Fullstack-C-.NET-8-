🗓️ Duración: 1 mes (marzo-junio 2025)
🎯 Objetivo: Desarrollar una solución integral para la gestión de envíos de una empresa logística nacional, aplicando Clean Architecture y prácticas modernas de desarrollo backend y frontend desacoplado.

🧰 Tecnologías y herramientas
Lenguaje: C#

Frameworks: .NET 8, Entity Framework Core 8

Arquitectura: Clean Architecture, DDD

Acceso a datos: LINQ

Autenticación: JWT

Documentación API: Swagger

Frontend: ASP.NET MVC (cliente separado que consume la API via HttpClient)

Deploy: Microsoft Azure

🔑 Funcionalidades implementadas
Backend (Etapa 1)
Login de empleados (roles: administrador, funcionario)

Gestión CRUD de usuarios y envíos

Registro y seguimiento de envíos comunes y urgentes

Auditoría interna de acciones del sistema

Cálculo automático de eficiencia en entregas urgentes

Web API + Cliente MVC (Etapa 2)
Endpoints RESTful para clientes autenticados

Consulta por número de tracking (pública)

Búsqueda de envíos por fecha, estado o comentario

Cambio de contraseña

Vista histórica de actividad del cliente

Precarga de datos consistente para testing completo

🚀 Deploy y testing
API y aplicación publicadas en Azure

Testing de endpoints con Postman y Swagger

Scripts de inserción de datos y documentación de prompts utilizados con IA
