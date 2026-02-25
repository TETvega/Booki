![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET 9](https://img.shields.io/badge/.NET%209-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Web API](https://img.shields.io/badge/Web%20API-EF2D5E?style=for-the-badge&logo=dotnet&logoColor=white)
# 🚀 BOOKI: Gestión Inteligente de Espacios Deportivos

**BOOKI** es una plataforma integral diseñada para la administración eficiente de centros deportivos. Resuelve la complejidad de gestionar múltiples canchas, horarios de trabajo y flujo de clientes en un solo lugar, permitiendo tanto reservas inmediatas como programadas.

---

## ✨ Funcionalidades Principales

* **👥 Gestión de Usuarios y Clientes:** Registro y administración de perfiles de deportistas y administradores de centros.
* **📅 Calendario Dinámico:** Visualización en tiempo real de la disponibilidad de canchas y gestión de horas programadas.
* **🏟️ Administración de Centros:** Configuración de múltiples sedes, tipos de canchas y horarios de operación específicos.
* **⏳ Sistema de Reservas:**
* *Pre-solicitud:* Apartado de espacios pendientes de confirmación.
* *Reserva Programada:* Agendamiento en bloques de tiempo específicos y recurrentes.


* **📊 Dashboard de Métricas:** Panel visual con estadísticas sobre las horas de mayor concurrencia y niveles de ocupación.

---

## 🛠️ Stack Tecnológico

El proyecto utiliza un ecosistema moderno y robusto para garantizar escalabilidad:

* **Backend:** [.NET 9](https://www.google.com/search?q=https://dotnet.microsoft.com/) (Web API Full)
* **Frontend:** [React](https://www.google.com/search?q=https://reactjs.org/) con [TypeScript](https://www.google.com/search?q=https://www.typescriptlang.org/)
* **Base de Datos:** [PostgreSQL (PQSL)](https://www.google.com/search?q=https://www.postgresql.org/)
* **Arquitectura:** Diseño orientado a dominios (Domain-Driven Design sugerido).

> [!TIP]
> Puedes consultar la lista completa de dependencias y bibliotecas de terceros en el archivo [DEPENDENCIES.md](https://www.google.com/search?q=./DEPENDENCIES.md) (próximamente).

---

## 🏗️ Arquitectura del Sistema

El sistema sigue un patrón de separación de responsabilidades para facilitar el mantenimiento.

Para un desglose detallado de los patrones de diseño y diagramas de flujo, visita nuestro [Archivo de Arquitectura](docs/architecture).

---

## 🚀 Instalación y Configuración Rápida

Sigue estos pasos para levantar el entorno de desarrollo local:

### Requisitos Previos

* .NET 9 SDK
* Node.js (v18 o superior)
* Instancia de PostgreSQL activa

### Pasos

1. **Clonar el repositorio:**
```bash
git clone https://github.com/tu-usuario/booki.git
cd booki

```


2. **Configurar el Backend:**
```bash
cd Booki.Api
dotnet restore
dotnet run

```


3. **Configurar el Frontend:**
```bash
cd ../Booki.Client
npm install
npm run dev

```


4. **Variables de Entorno:**
Asegúrate de configurar tu `appsettings.json` con la cadena de conexión a PostgreSQL.

---

## 🤝 Contribución

¿Quieres ayudar a mejorar BOOKI? ¡Eres bienvenido! Por favor, lee nuestras [Guías de Contribución](docs/CONTRIBUTION.MD) antes de enviar un Pull Request.

---

## 📄 Licencia

Todos los Derechos Reservados. Consulta el archivo `LICENSE` para más detalles.
