# 3. Alcance del proyecto

## 3.1. Alcance funcional
El proyecto se centrará en diseñar y configurar la infraestructura informática necesaria para el funcionamiento del Gimnasio Paso a Paso.

Dentro del proyecto se incluirán las siguientes funciones:

- Gestión de la información de los clientes.
- Gestión de actividades y horarios.
- Gestión de usuarios y permisos.
- Almacenamiento de información mediante una base de datos.
- Configuración de servicios web.
- Configuración de servicios de red.
- Realización de copias de seguridad.
- Recuperación de información ante posibles fallos.
- Aplicación de medidas de seguridad.
- Comprobación del funcionamiento de los servicios.
- Documentación de la infraestructura.

Quedan fuera del alcance del proyecto:

- Gestión de nóminas.
- Gestión contable completa.
- Sistemas de pago reales.
- Desarrollo de una aplicación móvil.
- Gestión comercial completa.
- Compra e instalación de todo el equipamiento físico del gimnasio.

## 3.2. Alcance técnico
La parte técnica del proyecto incluirá diferentes sistemas y servicios necesarios para crear la infraestructura.

Se trabajará con:

- Sistemas operativos Linux o Windows.
- Docker.
- Bases de datos.
- Servicios web.
- Servicios de red.
- Almacenamiento.
- Copias de seguridad.
- Seguridad y control de acceso.
- Máquinas virtuales para realizar las pruebas necesarias.

Docker será la plataforma principal para desplegar y gestionar determinados servicios mediante contenedores.

La infraestructura se probará en un entorno controlado antes de plantear su posible utilización en un entorno real.

## 3.3. Alcance temporal
El proyecto se dividirá en diferentes fases para organizar el trabajo.

| Fase | Trabajo | Resultado |
|---|---|---|
| 1 | Análisis y planificación | Definición del proyecto y sus requisitos |
| 2 | Diseño | Diseño de la infraestructura |
| 3 | Instalación y configuración | Sistemas y servicios configurados |
| 4 | Seguridad y copias de seguridad | Medidas de protección y recuperación |
| 5 | Pruebas | Comprobación del funcionamiento |
| 6 | Documentación | Memoria del proyecto |
| 7 | Presentación | Exposición y defensa del proyecto |

## 3.4. Alcance de recursos
Para realizar el proyecto serán necesarios diferentes recursos.

### Recursos humanos
Las tareas principales serán:

- Planificación del proyecto.
- Diseño de la infraestructura.
- Instalación y configuración.
- Realización de pruebas.
- Aplicación de medidas de seguridad.
- Documentación del trabajo realizado.

### Recursos hardware
Para realizar el proyecto se necesitará principalmente:

- Ordenador para el desarrollo.
- Memoria RAM suficiente para ejecutar máquinas virtuales y contenedores.
- Espacio de almacenamiento suficiente para los sistemas y copias de seguridad.
- Conexión de red.

### Recursos software
Se utilizarán diferentes herramientas y tecnologías:

- Docker.
- Sistemas operativos necesarios para el proyecto.
- Herramientas de administración de sistemas.
- Gestores de bases de datos.
- Servidores web.
- Herramientas de red.
- Herramientas para realizar copias de seguridad.

El presupuesto se concretará cuando se hayan definido todos los elementos necesarios para la infraestructura.

## 3.5. Elección de plataforma
Para el desarrollo del proyecto se han considerado las tres opciones indicadas: **GNS3, AWS y Docker**.

La plataforma principal elegida será **Docker**.

Docker permite ejecutar diferentes servicios mediante contenedores independientes. Esto facilita la instalación, configuración y mantenimiento de los servicios utilizados en el proyecto.

Se ha elegido Docker porque encaja con el planteamiento del proyecto, especialmente para trabajar con servicios como bases de datos, servidores web y otros servicios que puedan ejecutarse mediante contenedores.

Además, el uso de contenedores permite realizar pruebas en un entorno controlado y facilita modificar o sustituir un servicio sin tener que cambiar toda la infraestructura.

GNS3 podrá utilizarse como herramienta complementaria para determinadas pruebas relacionadas con la red, pero no será la plataforma principal del proyecto.

AWS tampoco será la plataforma principal, ya que el proyecto se desarrollará inicialmente en un entorno de pruebas local.
