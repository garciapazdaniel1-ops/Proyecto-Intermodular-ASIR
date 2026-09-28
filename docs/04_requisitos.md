# 4. Requisitos del proyecto
Los requisitos definen las funciones y características que deberá cumplir la infraestructura del Gimnasio Paso a Paso.

## 4.1. Requisitos funcionales
Los requisitos funcionales indican qué funciones deberá realizar la infraestructura.

| ID | Descripción | Estado |
|---|---|---|
| RF-001 | El sistema permitirá gestionar la información de los clientes. | Pendiente |
| RF-002 | El sistema permitirá gestionar las actividades y horarios del gimnasio. | Pendiente |
| RF-003 | El sistema permitirá gestionar usuarios y permisos de acceso. | Pendiente |
| RF-004 | Se dispondrá de servicios web para las aplicaciones necesarias. | Pendiente |
| RF-005 | Se utilizará una base de datos para almacenar la información. | Pendiente |
| RF-006 | Se realizarán copias de seguridad de la información importante. | Pendiente |
| RF-007 | Se podrá recuperar la información en caso de fallo. | Pendiente |

## 4.2. Requisitos no funcionales
Los requisitos no funcionales indican cómo debe funcionar la infraestructura.

| ID | Descripción | Estado |
|---|---|---|
| RNF-001 | Los sistemas deberán contar con medidas de seguridad. | Pendiente |
| RNF-002 | Los servicios deberán estar disponibles cuando sean necesarios. | Pendiente |
| RNF-003 | Los servicios deberán tener un rendimiento adecuado. | Pendiente |
| RNF-004 | La infraestructura deberá permitir futuras ampliaciones. | Pendiente |
| RNF-005 | La configuración deberá estar documentada para facilitar su mantenimiento. | Pendiente |
| RNF-006 | Los sistemas deberán disponer de mecanismos de recuperación ante fallos. | Pendiente |

## 4.3. Requisitos de negocio
Los requisitos de negocio están relacionados con las necesidades del gimnasio.

| ID | Descripción |
|---|---|
| RN-001 | La información del gimnasio deberá estar organizada y disponible para los usuarios autorizados. |
| RN-002 | Los servicios principales deberán poder recuperarse después de un fallo. |
| RN-003 | La información deberá estar protegida frente a accesos no autorizados. |
| RN-004 | La infraestructura deberá poder ser administrada y mantenida. |
| RN-005 | La infraestructura deberá permitir incorporar nuevos servicios en el futuro. |
| RN-006 | La organización de los sistemas deberá facilitar la detección y solución de problemas. |

## 4.4. Requisitos por módulo

### 4.4.1. ASGBD
El proyecto deberá incluir:

- Instalación y configuración de un sistema gestor de bases de datos.
- Creación y administración de bases de datos.
- Creación de tablas y gestión de la información.
- Gestión de usuarios y permisos.
- Realización de copias de seguridad.
- Recuperación de la información.

### 4.4.2. ASO
El proyecto deberá incluir:

- Instalación y configuración de sistemas operativos.
- Administración de usuarios.
- Gestión de permisos.
- Configuración de servicios.
- Gestión del almacenamiento.
- Mantenimiento de los sistemas.

### 4.4.3. IAW
El proyecto deberá incluir:

- Instalación y configuración de un servidor web.
- Publicación de una aplicación o página web.
- Configuración del servicio web.
- Comprobación del funcionamiento del servicio.
- Conexión con la base de datos cuando sea necesario.

### 4.4.4. Servicios de Red e Internet
El proyecto deberá incluir:

- Diseño de la red.
- Configuración del direccionamiento IP.
- Configuración de servicios de red.
- Resolución de nombres.
- Comunicación entre los diferentes equipos.
- Comprobación de la conectividad.

### 4.4.5. Seguridad y Alta Disponibilidad
El proyecto deberá incluir:

- Gestión de usuarios y permisos.
- Control de acceso.
- Protección de los servicios.
- Copias de seguridad.
- Recuperación ante fallos.
- Medidas para mantener disponibles los servicios.
- Comprobaciones de seguridad.

## 4.5. Matriz de trazabilidad
La matriz de trazabilidad permite relacionar los requisitos del proyecto con los diferentes módulos de 2.º ASIR.

| ID | Descripción | Tipo | ASGBD | ASO | IAW | Serv. Red | Seguridad | Estado |
|---|---|---|---|---|---|---|---|---|
| RF-001 | Gestión de clientes | RF | ✓ |  | ✓ |  | ✓ | Pendiente |
| RF-002 | Gestión de actividades y horarios | RF | ✓ |  | ✓ |  |  | Pendiente |
| RF-003 | Gestión de usuarios y permisos | RF | ✓ | ✓ |  | ✓ | ✓ | Pendiente |
| RF-004 | Servicios web | RF |  | ✓ | ✓ | ✓ | ✓ | Pendiente |
| RF-005 | Base de datos | RF | ✓ | ✓ | ✓ |  | ✓ | Pendiente |
| RF-006 | Copias de seguridad | RF | ✓ | ✓ |  |  | ✓ | Pendiente |
| RF-007 | Recuperación de información | RF | ✓ | ✓ |  |  | ✓ | Pendiente |
| RNF-001 | Seguridad | RNF | ✓ | ✓ | ✓ | ✓ | ✓ | Pendiente |
| RNF-002 | Disponibilidad | RNF |  | ✓ | ✓ | ✓ | ✓ | Pendiente |
| RNF-003 | Rendimiento | RNF | ✓ | ✓ | ✓ | ✓ |  | Pendiente |
| RNF-004 | Escalabilidad | RNF | ✓ | ✓ | ✓ | ✓ |  | Pendiente |
| RNF-005 | Mantenibilidad | RNF | ✓ | ✓ | ✓ | ✓ | ✓ | Pendiente |
| RNF-006 | Recuperación ante fallos | RNF | ✓ | ✓ |  |  | ✓ | Pendiente |
| RN-001 | Gestión organizada | RN | ✓ | ✓ | ✓ |  |  | Pendiente |
| RN-002 | Continuidad de los servicios | RN | ✓ | ✓ | ✓ | ✓ | ✓ | Pendiente |
| RN-003 | Seguridad de la información | RN | ✓ | ✓ | ✓ | ✓ | ✓ | Pendiente |
| RN-004 | Administración de la infraestructura | RN | ✓ | ✓ | ✓ | ✓ | ✓ | Pendiente |
| RN-005 | Ampliación futura | RN | ✓ | ✓ | ✓ | ✓ | ✓ | Pendiente |
| RN-006 | Reducción de incidencias | RN | ✓ | ✓ | ✓ | ✓ | ✓ | Pendiente |
