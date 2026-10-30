# DigimonTaller

Taller de la Semana 6: aplicación ASP.NET MVC 5 con .NET Framework 4.8 que consume [Digi-API](https://digi-api.com/).

Permite consultar Digimon con búsqueda por nombre, filtros de nivel y paginación. La ficha de cada Digimon muestra sus datos, habilidades y evoluciones dentro de una interfaz con diseño de Digivice.

## Ejecutar el proyecto

1. Instala Visual Studio 2026 con la carga de trabajo **ASP.NET y desarrollo web** y el paquete de destino de **.NET Framework 4.8**.
2. Abre `S6P4.slnx`.
3. Restaura los paquetes NuGet de la solución.
4. Pulsa **F5** para iniciar la aplicación con IIS Express.

Se necesita conexión a Internet para consultar Digi-API y cargar las imágenes y las fuentes. La API no requiere clave ni token.

## Estructura

- `S6P4/Controllers/DigimonController.cs`: consultas a la API, búsqueda, filtros, paginación y detalle.
- `S6P4/Models/DigimonModels.cs`: modelos JSON, ViewModels y traducciones al español.
- `S6P4/Views/Digimon/`: vistas de lista y detalle.
- `S6P4/Views/Shared/_LayoutDigivice.cshtml`: estructura visual compartida.
- `S6P4/Content/digivice.css`: estilos del Digivice.

Los paquetes restaurados, los archivos de compilación y la configuración local de Visual Studio se excluyen del repositorio.
