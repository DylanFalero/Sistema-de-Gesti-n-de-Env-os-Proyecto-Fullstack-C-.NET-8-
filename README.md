# 📦 Sistema de Gestión de Envíos – Proyecto Fullstack (.NET 8 / C#)

**⏳ Duración:** 1 mes (marzo – junio 2025)  
**🎓 Proyecto académico | Programación 3 – Universidad ORT Uruguay**

---

## 🧾 Descripción

Este proyecto simula un sistema real de gestión de envíos para una empresa de logística con cobertura nacional. Se implementó en dos etapas:

1. **Backend** con arquitectura limpia y lógica de negocio central.
2. **API RESTful** para clientes, con autenticación JWT, consultada desde un cliente MVC desacoplado usando `HttpClient`.

---

## ⚙️ Tecnologías utilizadas

- **Lenguaje:** C#
- **Framework:** .NET 8
- **Base de datos:** Entity Framework Core 8.0
- **Arquitectura:** Clean Architecture + Domain-Driven Design (DDD)
- **Consultas:** LINQ (sintaxis de método)
- **Autenticación:** JWT (Json Web Tokens)
- **Frontend cliente:** ASP.NET MVC separado
- **Consumo de API:** HttpClient
- **Documentación de API:** Swagger
- **Deploy:** Azure

---

## ✅ Funcionalidades implementadas

### 🔹 Etapa 1 – Backend (Gestión interna)

- Login de empleados (Administrador y Funcionario)
- ABM de empleados con auditoría de acciones
- Alta de envíos (urgentes y comunes)
- Seguimiento de envíos por etapas
- Cierre y cálculo de eficiencia de entregas urgentes
- Consultas por número de tracking

### 🔹 Etapa 2 – Web API + Cliente MVC (rol Cliente)

- Consulta pública de envío por tracking
- Login y Logout con JWT
- Cambio de contraseña
- Listado histórico de envíos por cliente
- Búsqueda por fechas y estados
- Búsqueda por comentarios de seguimiento
- Consumo exclusivo de la API desde MVC con `HttpClient`

---

## 🧪 Testing y despliegue

- API documentada con **Swagger**
- Testeo funcional desde **Postman**
- Precarga de datos coherente y completa (mínimo 10 registros por entidad)
- **Deploy realizado en Microsoft Azure**  

---
