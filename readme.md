### *ClinicFlow: Plataforma Corporativa y Portafolio Profesional*

---

### *Descripción: Propósito y Utilidad*

*ClinicFlow* es un proyecto académico diseñado para simular el desarrollo de un sitio web corporativo profesional y un portafolio de equipo en un entorno de trabajo colaborativo.

El proyecto tiene un *doble propósito*:
1.  Servir como un *escaparate digital* para una empresa de desarrollo de software ficticia, demostrando su oferta de valor.
2.  Funcionar como un *portafolio profesional* dinámico para sus cinco desarrolladores, exhibiendo sus habilidades y la experiencia adquirida en el proceso.

*Utilidad y Metas Estratégicas:*
* *Presentación Profesional:* Mostrar *ClinicFlow* como un proyecto con proyección digital y calidad profesional.
* *Exhibición de Talento:* Destacar a los integrantes del grupo y sus habilidades técnicas y blandas.
* *Difusión:* Facilitar la presentación del proyecto a *instituciones, profesores y clientes potenciales*.
* *Escalabilidad:* Contar con una Landing Page que sirva como base para futuras expansiones del sistema de gestión.

### *Tecnologías, Requisitos y Pila Tecnológica*

El proyecto se construyó sobre el ecosistema de *WordPress* por su robustez y facilidad de gestión de contenido.

#### *Requisitos para Ejecución Local*

Para replicar el entorno de *ClinicFlow* localmente, necesitarás:
* Un *servidor local* (ej.: *XAMPP* o *MAMP) con **PHP* y *MySQL*.
* *WordPress* descargado desde wordpress.org.
* Un *navegador web* actualizado.
* Acceso a los *archivos del tema/plantilla y la base de datos* de *ClinicFlow* (disponibles en futuras actualizaciones del repositorio).

#### *Herramientas Principales*

| Categoría | Herramienta | Uso Específico |
| :--- | :--- | :--- |
| *CMS* | *WordPress* | Núcleo del sitio web y gestión de contenido. |
| *Constructor Visual* | *Elementor* | Diseño frontend (drag and drop) de las páginas. |
| *Currículums* | *Creador de currículums* | Módulos para las páginas de CV de los integrantes. |
| *Formularios* | *FluentForms* | Gestión de leads y formularios de contacto. |
| *Comercio Electrónico* | *WooCommerce* | Añadir funcionalidad de *tienda online*, gestión de productos, pedidos y pagos. |
| *Caché/Rendimiento* | *WP Super Cache* | Generar *archivos estáticos* para acelerar la carga del sitio web y reducir la carga del servidor. |

--- 

### *Instrucciones de Instalación y Uso*

Sigue estos pasos para configurar *ClinicFlow* en un entorno local de desarrollo:

#### *Pasos de Instalación*

1.  *Clonar el Repositorio (Futura Actualización):*
    bash
    git clone [https://github.com/ISPC-WEB-2025/SGC-ClinicFlow.git](https://github.com/ISPC-WEB-2025/SGC-ClinicFlow.git)
    
2.  *Preparar WordPress:*
    * Descarga y descomprime los archivos de *WordPress* en la carpeta htdocs de tu servidor local.
    * Crea una base de datos vacía en *phpMyAdmin* (ejemplo: clinicflow_db).
3.  *Configuración Inicial:*
    * Accede a tu navegador en la ruta localhost/nombre_carpeta_wordpress e inicia el asistente de instalación de *WordPress*, vinculándola con la base de datos creada.
4.  *Importar Contenido:*
    * Una vez instalado, accede al panel de administración de *WordPress*.
    * Importa el *tema/plantilla* de *ClinicFlow* y la *base de datos* (SQL dump) si está disponible.
    * *Activa y personaliza* la Landing Page y las demás secciones.

#### *Uso Principal*

El sitio está diseñado con una arquitectura intuitiva que refleja las secciones de una empresa de desarrollo de software y un portafolio de equipo. Explora las siguientes secciones:

* *Inicio:* La Landing Page principal con la propuesta de valor.
* *Presentación:* Información sobre la empresa ficticia y el proyecto.
* *Integrantes:* Perfiles profesionales del equipo (con sub-páginas de CV).
* *Tecnologías:* Pila tecnológica utilizada.
* *Contacto:* Formularios, información y redes sociales.

---

### *Guía de Contribución*

¡Agradecemos tu interés en contribuir a *ClinicFlow*! Este proyecto es un esfuerzo colaborativo y está abierto a mejoras.

#### *Metodología de Trabajo*

El equipo adoptó una metodología *flexible* basada en los principios de *Kanban*. Las tareas se gestionaron a través de:

- *Tablero de GitHub:* Columnas To Do, In Progress y Done para el seguimiento visual del flujo de trabajo.

- *Comunicación:* *WhatsApp* para la coordinación rápida y *GitHub* para la documentación y la gestión de issues.

#### *Modelo de Roles*

Se implementó un *Enfoque de Roles Rotativos y Pares* para garantizar el aprendizaje equitativo y desarrollar la resiliencia del equipo. Los colaboradores rotaron entre:

- *Coordinación y Control de Avance:* Supervisar el flujo de trabajo (Kanban).
- *Desarrollo Técnico:* Configuración y personalización de *WordPress* y plugins.
- *Redacción y Contenido:* Creación de textos, diseño visual y estructura de la información.

#### *Pasos para Colaborar*

1. *Revisa la *Wiki*: Consulta la *[Wiki del Proyecto en GitHub](https://github.com/ISPC-WEB-2025/SGC-ClinicFlow/wiki)** (enlace a crear) para obtener una visión estratégica, metodológica y técnica detallada.
2. *Crea un *Issue*: Reporta *bugs* o sugiere nuevas funcionalidades en la sección de Issues de este repositorio.
3. *Envía un *Pull Request*: Si ya has realizado cambios, envía un *Pull Request* claro con la descripción de tu contribución.

---
