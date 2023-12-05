# Arquitectura

## Atributos de calidad

Disponibilidad
Escalabilidad 
Rendimiento
Seguridad
Usabilidad

## Componentes involucrados

![](/images/architecture-fig1-ntier.jpg)

| Nombre | Descripción |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Recruitment portal | Proporciona una interfaz web para el sistema de reclutamiento y selección. |
| HCM portal | Proporciona una interfaz web para el sistema de Gestión de capital humano. |
| Integration | Facilita la integración de datos relacionados con los empleados desde diversas fuentes, garantizando la coherencia y la actualización de la información. |
| Recruitment | Facilita la búsqueda y atracción de candidatos, incluyendo la publicación de empleos en diversos canales, la gestión de eventos de reclutamiento y la promoción de la marca empleadora. |
| Candidate Management | Facilita el seguimiento de los candidatos a lo largo del proceso de contratación, desde la aplicación hasta la decisión final. |
| Employee Management | Incluye funciones básicas como el mantenimiento de perfiles de empleados, detalles de contacto, historial laboral, y otra información relevante. |
| Recruitment Database | Gestiona información específica sobre puestos de trabajo, permitiendo un seguimiento detallado de las oportunidades laborales. |
| Candidates Tenant n Database | Gestiona información específica sobre candidatos, asegurando la segregación de datos entre diferentes instancias de la aplicación. |
| Employees Tenant n Database | Gestiona información específica sobre empleados, garantizando la segregación de datos entre diferentes instancias de la aplicación. |