# Arquitectura

## Atributos de calidad relevantes

Disponibilidad
Escalabilidad 
Rendimiento
Seguridad
Usabilidad

## Componentes involucrados en la integración

![](/images/architecture-fig1-ntier.png)

| Nombre | Descripción |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Web Application (Recruitment) | Proporciona una interfaz web para el sistema de reclutamiento y selección. |
| Web Application (Human Capital Management) | Ofrece una interfaz web del sistema de gestión de capital humano. |
| Identity Provider | Proporciona servicios de autenticación y gestión de identidades para garantizar un acceso seguro a las aplicaciones y sistemas. |
| Users Tenant n Database | Gestiona la información de usuarios en un tenant específico y la base de datos asociada, asegurando la segregación de datos entre diferentes instancias de la aplicación. |
| Employee Integration | Facilita la integración de datos relacionados con los empleados desde diversas fuentes, garantizando la coherencia y la actualización de la información. |
| Logs Tenant n Database | Registra eventos y actividades del sistema en un tenant específico (tenant) y la base de datos asociada, permitiendo un seguimiento detallado y la generación de informes. |
| Recruitment | Facilita la búsqueda y atracción de candidatos, incluyendo la publicación de empleos en diversos canales, la gestión de eventos de reclutamiento y la promoción de la marca empleadora. |
| Candidate Management | Facilita el seguimiento de los candidatos a lo largo del proceso de contratación, desde la aplicación hasta la decisión final. |
| Employee Management | Incluye funciones básicas como el mantenimiento de perfiles de empleados, detalles de contacto, historial laboral, y otra información relevante. |
| Document Management | Almacena y gestiona documentos relacionados con los empleados, como contratos, certificados y evaluaciones. |
| Jobs Tenant n Database | Gestiona información específica sobre puestos de trabajo en un tenant específico (tenant) y la base de datos asociada, permitiendo un seguimiento detallado de las oportunidades laborales. |
| Candidates Tenant n Database | Gestiona información específica sobre candidatos en un tenant específico (tenant) y la base de datos asociada, asegurando la segregación de datos entre diferentes instancias de la aplicación. |
| Employees Tenant n Database | Gestiona información específica sobre empleados en un tenant específico (tenant) y la base de datos asociada, garantizando la segregación de datos entre diferentes instancias de la aplicación. |
| Document Tenant n Database | Gestiona información específica sobre documentos en un tenant específico (tenant) y la base de datos asociada, permitiendo el almacenamiento y gestión eficiente de archivos relacionados con los empleados. |





