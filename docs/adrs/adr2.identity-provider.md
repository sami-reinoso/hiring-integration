# ADR #2 - Proveedor de autenticación

## Context
La aplicación requiere una solución de Single Sign-On (SSO) para mejorar la experiencia del usuario y la seguridad en la autenticación. 

## Options
Firebase Authentication:

1. Firebase Authentication
2. Azure Active Directory B2C
3. Keycloak
4. PingFederate
5. Okta Identity Cloud
6. Gluu Server
7. Stormpath (ahora Okta)
8. One Identity

## Desicion
Se ha decidido seleccionar Auth0. Auth0 ofrece una solución integral de identidad y acceso que ofrece SSO para diversas aplicaciones. 

## Consequences

### Pros
* Facilidad de Implementación: Auth0 ofrece una implementación sencilla y rápida con bibliotecas y SDK para varias plataformas.
* Autenticación Multifactor (MFA): Soporte para autenticación multifactor para una capa adicional de seguridad.
* Personalización y Extensibilidad: Permite personalizar la experiencia de autenticación y autorización según las necesidades específicas del negocio.
* Amplia Compatibilidad: Compatible con una amplia gama de plataformas, lenguajes de programación y frameworks.
* SSO (Single Sign-On): Ofrece SSO para permitir a los usuarios acceder a múltiples aplicaciones con un solo conjunto de credenciales.
* Conectores y Federación de Identidades: Admite la federación de identidades y proporciona conectores para integrarse fácilmente con proveedores de identidad externos.
* Gestión de Usuarios: Funcionalidades completas de gestión de usuarios, incluyendo registro, inicio de sesión social y administración de perfiles.
* Seguridad: Cumple con los estándares de seguridad, como OAuth 2.0 y OpenID Connect.
* Escalabilidad: Escalable para manejar aplicaciones de cualquier tamaño, desde startups hasta empresas.

### Cons

* Costo: Puede resultar costoso, especialmente para grandes volúmenes de usuarios o características avanzadas.
* Dependencia del Proveedor: Al utilizar una solución de terceros, existe una dependencia del proveedor, lo que podría plantear problemas si se produce una interrupción del servicio.
* Personalización Compleja: Algunas personalizaciones avanzadas pueden requerir un tiempo adicional y comprensión más profunda de la plataforma.
* Documentación Compleja: La documentación puede resultar compleja para aquellos que son nuevos en la plataforma, y puede llevar tiempo entender todas las funcionalidades.
* Requisitos de Conectividad: En situaciones en las que la conectividad a Internet es limitada, la dependencia de un servicio en la nube puede ser un inconveniente.
* Necesidad de Conocimientos Específicos: Para aprovechar al máximo Auth0, es posible que se requiera cierto nivel de experiencia en autenticación y autorización.
* Posible Complejidad en Implementaciones Grandes: En implementaciones muy grandes o complejas, la configuración y administración pueden volverse más desafiantes.
