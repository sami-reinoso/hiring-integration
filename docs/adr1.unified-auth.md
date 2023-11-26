# ADR #1 - Autenticación unificada
La autenticación unificada busca mejorar la experiencia del usuario al reducir la necesidad de iniciar sesión repetidamente en cada sistema, sin necesidad de recordar dos pares de credenciales.

## Options
1. SSO (Single Sign-On): Implementar un protocolo estándar de SSO que permita a los usuarios autenticarse una vez para acceder a ambos sistemas.
2. Sincronizar credenciales: Mantener autenticación independiente, pero sincronizar las credenciales entre los dos sistemas para reducir la complejidad del inicio de sesión.
3. Compartir Token de Seguridad: Intercambiar tokens de seguridad entre los sistemas para permitir el acceso unificado.

## Decision
La opción seleccionada es SSO (Single Sign-On). Esto se elige para simplificar el proceso de inicio de sesión, proporcionar una experiencia de usuario fluida y mejorar la eficiencia al permitir a los usuarios acceder a ambos sistemas con una sola autenticación de manera segura.


### Pros
* Seguridad: Garantizar la seguridad de las credenciales y la integridad de los datos durante el proceso de autenticación mediante SSO.
* Usabilidad: Mejorar la experiencia del usuario al proporcionar un acceso simplificado y reducir la carga cognitiva asociada con múltiples inicios de sesión.
* Eficiencia: Optimizar el tiempo de acceso a ambas plataformas al eliminar la necesidad de ingresar credenciales múltiples.

### Cons
* Complejidad: Posibles desafíos técnicos durante la implementación de SSO, necesidad de coordinación entre equipos de desarrollo.
* Costos: Características avanzadas de SSO puede ocasionar gastos adicionales a medida que el proyecto crezca
* Soporte multitenancy: Es necesario configurar un proveedor de identidad multi-tenancy