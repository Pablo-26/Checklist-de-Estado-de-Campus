<h1 align="center"> Checklist de Estado de Campus </center></h1>
<p align="center">
<i>
Version 1.0<br/>
</i>
</p>

**_Autores_**
+ [Freddy Leon](https://github.com/Freddyleonn16) - Quality Assurance
+ [Carolina Alvarado](https://github.com/carolaljime21), UX/UI Developer
+ [Byron Castillo](https://github.com/ByronCast09), Frontend Developer
+ [Kevin Barrazueta](https://github.com/0KevinB), Security Manager
+ [Kevin Bustamante](), Backend Developer
+ [Pablo Ramon](https://github.com/Pablo-26), Software Architect


> Mantener un registro actualizado del estado de las instalaciones del campus es esencial para garantizar un entorno seguro y adecuado para estudiantes y personal. Un aplicativo en la nube que facilite la creación y seguimiento de checklists permitirá identificar y resolver problemas de manera oportuna, mejorando la calidad del entorno universitario. La computación en la nube asegurará que los datos sean accesibles desde cualquier dispositivo y en cualquier momento.*

Podemos usar react native para crear una aplicación que pueda crear una tarea para realizar ckecklists y a su vez se pueda compartir esta informacion con otros usuarios y para que se complete esa tarea y se haga el check list todos deben poner que, si se verifico la tarea establecida y cuando todos completen el check, automáticamente se ponga dentro de un apartado de tareas realizada. 

Para el desarrollo de la solucion se ha propuesto la utliización de React Native para el frontend. La aplicación permitira a los usuarios  

Cada estudiante deberá ingresar con sus credenciales para tener acceso a los diferentes apartados del aplicativo. 

Existen apartados, como aulas, laboratorios, salas de cómputo, cada uno de los apartados tendrá una lista con los diferentes números de aulas, laboratorios, etc. Cada sección del aula tendrá una lista con iluminación, proyector, escritorios, pizarras, instrumentos, etc. Dentro de esto se podrá ingresar una descripción de lo que se necesita, dar a conocer el estado, la cantidad de artículos, fotografías si es necesario. 

Los estudiantes o personal tendrán la opción de modificar ítems en caso de ser necesario con diferentes etiquetas,  

 
### Pasos para comenzar este reto.

1) Hacer y detallar los requisitos del negocio 

Dentro de esta sección hablaremos de la problemática a resolver, siendo lo más detallado posible para poder conocer todo el contexto y poder dar una solución efectiva que satisfaga los estándares de la empresa que nos confió su problemática. Se va a recolectar información sobre los problemas actuales del campus respecto al seguimiento del estado de las instalaciones, y se definen los objetivos que se buscan alcanzar con la solución. 

 

2) Oportunidad de negocio 

Se analizará el valor de esta solución que se puede aportar al campus y si es posible fuera del campus, se narrará los beneficios tangibles e intangibles conforme a nuestra solución planteada 

Aplicaciones de checklist para mantenimiento de campus 

2.1) iAuditor by SafetyCulture  

-) Características principales:  

* Creación de checklists personalizables 

* Captura de fotos y anotaciones 

* Generación de informes en tiempo real 

* Asignación de tareas y seguimiento 

-) Ventajas:  

* Interfaz intuitiva 

* Amplia biblioteca de plantillas 

-) Desventajas:  

* Puede ser costoso para equipos grandes 

2.2) Facility Management eXpress (FMX)  

-) Características principales:  

* Gestión de mantenimiento preventivo 

* Seguimiento de activos 

* Programación de tareas 

-) Ventajas:  

* Específicamente diseñado para gestión de instalaciones 

* Buena integración con otros sistemas 

-) Desventajas:  

* Puede ser complejo para usuarios no técnicos 

2.3) UpKeep 

-) Características principales:  

* Gestión de órdenes de trabajo 

* Seguimiento de inventario 

* Análisis y reportes 

-) Ventajas:  

* Interfaz móvil amigable 

* Buena para equipos de mantenimiento 

-) Desventajas:  

* Puede tener más funciones de las necesarias para un campus 

2.4) Checklist.com  

-) Características principales:  

* Creación simple de checklists 

* Colaboración en tiempo real 

* Integración con otras aplicaciones 

-) Ventajas:  

* Fácil de usar 

* Versión gratuita disponible 

-) Desventajas:  

* Puede carecer de funciones específicas para mantenimiento de campus 

2.5) MaintainX  

-) Características principales:  

* Gestión de procedimientos operativos estándar 

* Comunicación en tiempo real 

* Seguimiento de métricas 

-) Ventajas:  

* Buena para la comunicación del equipo 

* Interfaz móvil intuitiva 

-) Desventajas:  

* Algunas funciones avanzadas solo en planes premium 

 

3) Objetivos del negocio 

Narraremos los objetivos específicos que nosotros como empresa queremos lograr con la aplicación 

 

4) Riesgos potenciales 

Describiremos los posibles riesgos ya sean a futuro o durante el desarrollo de nuestra solución, entre ellos encontraremos riesgos de conectividad, accesibilidad o de integración; a su vez con su respectiva solución para estar prevenidos. 

 

5) Alcance y limitaciones 

Estableceremos las limitaciones que existen como el tiempo disponible, los recursos técnicos y humanos, y las limitaciones tecnológicas. Usaremos una herramienta para poder gestionar estas tareas como Jira 

 

6) Requisitos funcionales y no funcionales 

 **_Requisitos Funcionales Clave:_** 

- Autenticación y autorización de usuarios 

- Gestión de checklists personalizados 

- Realización de inspecciones con captura de fotos y anotaciones 

- Asignación y seguimiento de tareas 

- Generación de informes y dashboards 

- Sistema de notificaciones 

**_Requisitos No Funcionales Clave:_** 

- Rendimiento: Carga rápida y soporte para múltiples usuarios concurrentes 

- Seguridad: Encriptación de datos y autenticación segura 

- Disponibilidad: 99.9% de tiempo de actividad 

- Usabilidad: Interfaz intuitiva y accesible 

- Escalabilidad: Arquitectura que permite crecimiento futuro 

 

7) Arquitectura de alto nivel 

- Servicio de Autenticación y Autorización 

- Servicio de Gestión de Usuarios 

- Servicio de Gestión de Instalaciones 

- Servicio de Gestión de Checklists 

- Servicio de Inspecciones 

- Servicio de Tareas 

- Servicio de Notificaciones 

- Servicio de Reportes y Análisis 

- Servicio de Almacenamiento de Archivos 

- API Gateway 

 

<h2> Mapa de Capacidades </h2>
Imagen del mapa de capacidades y breve descripcion
