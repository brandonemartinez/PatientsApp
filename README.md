# PatientsApp

**PatientsApp** es una aplicación web desarrollada con .NET 8 y Blazor que permite la gestión de pacientes y consultas médicas. La aplicación utiliza Entity Framework Core para la interacción con la base de datos y ASP.NET Core Identity para la autenticación y autorización de usuarios.

## Características

- **Gestión de Pacientes**: Permite agregar, editar y eliminar información de pacientes.
- **Gestión de Consultas**: Permite registrar, editar y visualizar consultas médicas.
- **Autenticación y Autorización**: Implementa ASP.NET Core Identity para la gestión de usuarios y roles.
- **Interfaz de Usuario**: Utiliza Blazor para crear una interfaz de usuario interactiva y moderna.
- **Migraciones de Base de Datos**: Utiliza Entity Framework Core para manejar las migraciones y el acceso a la base de datos.

## Tecnologías Utilizadas

- .NET 8
- Blazor
- Entity Framework Core
- ASP.NET Core Identity
- SQL Server

## Estructura del Proyecto

- **Components**: Contiene los componentes de Blazor utilizados en la aplicación.
- **Data**: Contiene los modelos de datos y el contexto de la base de datos.
- **Pages**: Contiene las páginas de Blazor para la interfaz de usuario.
- **Program.cs**: Configuración principal de la aplicación, incluyendo servicios y middleware.

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/usuario/PatientsApp.git
   ```
   
2. Navega al directorio del proyecto:
   ```bash
   cd PatientsApp
   ```
   
3. Restaura los paquetes NuGet:
   ```bash
   dotnet restore
   ```
   
4. Aplica las migraciones a la base de datos:
   ```bash
   dotnet ef database update
   ```
   
5. Ejecuta la aplicación:
   ```bash
   dotnet run
   ```

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

