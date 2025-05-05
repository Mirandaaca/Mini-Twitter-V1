# Backend - Mini Twitter V1

Este directorio contiene la API REST desarrollada con ASP.NET Core (.NET 8).

## 🛠 Tech Stack

- .NET 8 (ASP.NET Core Web API)
- Entity Framework Core (Code-First)
- JWT para autenticación
- Swagger / OpenAPI para documentación de endpoints
- xUnit + Moq para tests unitarios

## 📂 Estructura de Carpetas
Backend/
├── src/
│   ├── Core/               # Entidades y lógica de dominio
│   ├── Infrastructure/      # EF Core, migraciones y repositorios
│   ├── WebApi/             # Controllers, DTOs y configuración
│   └── Tests/              # Proyectos de pruebas unitarias e integración
├── Backend.sln             # Solución de Visual Studio
└── appsettings.json        # Configuración (DB, JWT, etc.)