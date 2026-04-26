# Database Diagrams

En esta sección el equipo presenta y explica el Database Diagram que incluye los objetos de base de datos que permitirán la persistencia de información para los objetos de cada bounded context. Para el caso de un almacenamiento en base de datos relacional, se especifican tablas, columnas, constraints (por ejemplo, primary, foreign key) y se evidencian las relaciones entre tablas.

## Frontend Architecture Diagram
El siguiente diagrama ilustra la arquitectura y estructura de componentes del lado del cliente (Frontend). Se detalla la organización de los Pages/Components, ViewModels, Services y DTOs (Data Transfer Objects), permitiendo visualizar el flujo de datos y la interacción entre las diferentes capas de la interfaz de usuario.

![Diagrama de Arquitectura del Frontend](../assets/diagrams/frontend-diagram.png){width=100%}

## Backend Database Diagram
El siguiente diagrama entidad-relación (ERD) corresponde al diseño de base de datos del servidor (Backend). El diagrama modela la estructura de almacenamiento relacional para cada *bounded context*, detallando de manera específica las tablas, sus columnas, constraints (como claves primarias y foráneas), y las relaciones y multiplicidades existentes entre las diversas entidades del sistema.

![Diagrama de Base de Datos del Backend](../assets/diagrams/backend-diagram.png){width=100%}
