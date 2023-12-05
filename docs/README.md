# Integración 'Reclutamiento y selección'  <!-- {docsify-ignore-all} -->

## Objetivo
Facilitar la sincronización entre el sistema de 'Reclutamiento y Selección' y el sistema para la gestión de capital humano

![](/images/index-fig1-context.jpg)

> El flujo de información principal se origina en el sistema "Recruitment and Hiring" y se dirige hacia el sistema "Human Capital Management". Este flujo garantiza una transferencia eficiente de datos relacionados con el proceso de contratación y selección de personal hacia la gestión integral del capital humano. 


| Nombre      | Descripción |
| ----------- | ----------- |
| Recruitment and hiring | Sistema de software cuyo objetivo es facilitar y optimizar los procesos relacionados con la adquisición de talento en una organización. Sus funciones abarcan desde la publicación de ofertas de trabajo hasta la selección y contratación de candidatos. |
| Human capital management (HCM) | Sistema de software que se centra en la administración integral de las personas dentro de una organización. Busca optimizar la gestión de colaboradores desde su incorporación hasta su desarrollo y eventual retiro. |

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

## Atributos de calidad relevantes

* Disponibilidad: La disponibilidad se refiere a la capacidad del sistema de estar operativo y accesible cuando se necesita.
* Escalabilidad: La escalabilidad se refiere a la capacidad del sistema para manejar un crecimiento en la carga de trabajo sin comprometer su rendimiento.
* Rendimiento: El rendimiento se refiere a la eficiencia y velocidad con la que el sistema responde a las solicitudes.
* Seguridad: La seguridad implica proteger la integridad, confidencialidad y disponibilidad de la información. 
* Usabilidad: La usabilidad se refiere a la facilidad con la que los usuarios pueden interactuar con el sistema.
* Interoperabilidad: La interoperabilidad se refiere a la capacidad del sistema para integrarse y cooperar con otros sistemas de manera efectiva.