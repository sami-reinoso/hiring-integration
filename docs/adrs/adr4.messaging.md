# ADR #4 - Tecnología de Mensajería

## Context
En el proceso de integración del Sistema de Gestión de Capital Humano (HCM), se reconoce la necesidad de seleccionar una tecnología de mensajería adecuada para facilitar la comunicación entre los diversos componentes del sistema. Se han identificado varias opciones, cada una con sus propias características y consideraciones.

## Options

### 1. Apache Kafka

#### Pros
- Alta capacidad de escalabilidad horizontal.
- Tolerancia a fallos y durabilidad de mensajes.
- Bajo acoplamiento entre productores y consumidores.
- Soporte para flujos de datos en tiempo real.
- Comunidad activa y amplia adopción en la industria.

#### Contras
- Curva de aprendizaje para equipos no familiares con Kafka.
- Requiere recursos significativos, especialmente en entornos pequeños.
- Configuración inicial puede ser compleja.

### 2. RabbitMQ

#### Pros
- Facilidad de configuración y uso.
- Buena documentación y comunidad activa.
- Soporte para varios patrones de mensajería.

#### Contras
- Menos escalabilidad horizontal en comparación con Kafka.
- Menor rendimiento en flujos de datos en tiempo real.

### 3. ActiveMQ

#### Pros
- Integración con tecnologías Java.
- Soporte para múltiples protocolos de mensajería.

#### Contras
- Puede ser más complejo de configurar que soluciones más simples.
- Rendimiento puede ser un problema en escenarios de alta carga.

### 4. Apache Pulsar:

#### Pros
- Arquitectura multitenancy y escalabilidad.
- Soporte para flujos de datos en tiempo real.
- Alta durabilidad y rendimiento.

#### Contras
- Menor adopción en comparación con Kafka.
- Curva de aprendizaje inicial.

## Decision
Hemos decidido implementar Kafka como la solución de mensajería para la integración. Esta elección se basa en las necesidades específicas del proyecto, considerando factores como escalabilidad, tolerancia a fallos, rendimiento y la familiaridad del equipo con la tecnología seleccionada.

## Consequences
Aprovecharemos los beneficios específicos de la tecnología seleccionada.
Nos enfrentaremos a desafíos particulares asociados con la elección, como la curva de aprendizaje o posibles limitaciones de rendimiento.