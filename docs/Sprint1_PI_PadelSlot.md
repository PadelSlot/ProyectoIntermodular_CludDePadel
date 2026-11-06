**MEMORIA DEL PROYECTO INTERMOLECULAR**  
Ciclo Formativo de Grado Superior en DAW  
---

**PadelSlot**  
Software para gestionar las reservas de clubes de pádel  
---

**Componentes del grupo:**  
Pablo Márquez López  
Javier Oliveros Lepe  
Ismael Frías Fernández  
Alberto Rueda Romero

**Profesores:**  
Willman Acosta Lugo  
Manuel Granados López  
Nuria Pajares  
María del Mar del Molino  
---

[**1\. INTRODUCCIÓN	3**](#1.-introducción)

[1.1. Contexto del proyecto	3](#1.1.-contexto-del-proyecto)

[1.2. Problema o necesidad detectada	4](#1.2.-problema-o-necesidad-detectada)

[1.3. Propuesta de solución	5](#1.3.-propuesta-de-solución)

[1.4. Objetivos del proyecto	6](#1.4.-objetivos-del-proyecto)

[1.4.1. Objetivo general	6](#1.4.1.-objetivo-general)

[1.4.2. Objetivos específicos	6](#1.4.2.-objetivos-específicos)

[1.5. Alcance del proyecto	7](#1.5.-alcance-del-proyecto)

[1.6. Limitaciones y exclusiones	8](#1.6.-limitaciones-y-exclusiones)

[1.7. Estructura de la memoria	9](#1.7.-estructura-de-la-memoria)

# 1\. INTRODUCCIÓN  {#1.-introducción}

## 1.1. Contexto del proyecto  {#1.1.-contexto-del-proyecto}

El presente proyecto se desarrolla en el marco del módulo de Proyecto Intermodular de 2º curso del ciclo formativo de Desarrollo de Aplicaciones Web, como trabajo integrador de las competencias adquiridas en las asignaturas de Entorno Cliente, Entorno Servidor, Diseño de Interfaces Web y Despliegue de Aplicaciones Web. 

El sector de la gestión deportiva, y en particular el de los clubes de pádel, ha experimentado un crecimiento notable en los últimos años en España, lo que ha incrementado la necesidad de herramientas digitales que faciliten la gestión de instalaciones, socios, reservas y actividades del club tanto para el personal administrativo como para los usuarios finales.  En cuanto a las empresas del sector, la mayoría son pequeñas o medianas, con una plantilla reducida (recepción, mantenimiento, monitores de pádel) y su actividad principal es el alquiler de pistas por franjas horarias, al que suelen sumar clases y programas de socios con ventajas asociadas.

Muchos clubes de padel de tamaño medio han gestionado estos procesos mediante métodos poco automatizados, como llamadas telefónicas para la reserva de pistas, hojas de cálculo para el control de socios o grupos de mensajería para organizar clases y torneos. Este tipo de gestión puede resultar suficiente en clubes pequeños, pero se vuelve claramente insuficiente a medida que aumentan los practicantes, los socios y las instalaciones, generando una carga de trabajo mayor para el personal administrativo y una experiencia poco ágil para el usuario.

En este contexto, se plantea el desarrollo de **PadelSlot**, una aplicación web pensada para que cualquier club de pádel pueda incorporarse y gestionar desde ella sus propias instalaciones, socios, reservas y actividades. Para la presentación de este proyecto se ha tomado como caso de demostración un club de padel concreto, creado por nosotros, sobre el que se ha implantado el conjunto completo de funcionalidades que la plataforma ofrece. Este planteamiento permite aplicar de forma conjunta contenidos de programación cliente y servidor, diseño de interfaces, bases de datos y despliegue sobre un caso realista y con necesidades identificables en clubes de nuestro entorno.

## 1.2. Problema o necesidad detectada {#1.2.-problema-o-necesidad-detectada}

A raíz del contexto expuesto donde la rápida expansión de la afición al pádel contrasta con la permanencia de procesos de gestión obsoletos, se identifica una acusada fragmentación e ineficiencia en la digitalización operativa de los clubes. Esta situación afecta negativamente tanto a la viabilidad comercial del centro como a la experiencia del jugador, estructurando el problema en tres ejes fundamentales:

* Ineficiencia y carga administrativa en la gestión: La gran mayoría de los clubes de pádel continúan gestionando reservas de pistas, clases dirigidas, torneos y altas de socios mediante métodos manuales (llamadas telefónicas, WhatsApp u hojas de cálculo) o mediante herramientas de software heterogéneas y desconectadas. Esta falta de centralización provoca duplicidad de tareas, errores humanos en la asignación de pistas (dobles reservas) y una pérdida sistemática de tiempo operativo. Además, las soluciones de software rígidas del mercado no se adaptan a la diversidad de infraestructuras entre clubes (centros que disponen de parking o bar frente a instalaciones centradas únicamente en las pistas).  
* Fricción y abandono del usuario casual: Para el cliente ocasional, el proceso actual de reserva requiere una interacción sincrónica y dependiente de terceros (esperar respuesta telefónica o confirmación por mensaje). Esta pérdida de tiempo genera una alta tasa de abandono: ante la falta de inmediatez y la imposibilidad de consultar la disponibilidad en tiempo real las 24 horas, el usuario casual opta por no reservar o migrar a otros clubes con mejor infraestructura digital.  
* Desgaste y pérdida de fidelización del socio habitual: Los jugadores recurrentes y socios sufren de manera prolongada la falta de agilidad del sistema manual. La dificultad constante para asegurar pista, gestionar sus cuotas o acceder a sus beneficios de socio termina por desgastar su experiencia, incrementando la tasa de cancelación de membresías.

## 1.3. Propuesta de solución  {#1.3.-propuesta-de-solución}

Como respuesta directa a las carencias y retos operativos identificados en el apartado anterior, se propone el diseño y desarrollo de PadelSlot, una plataforma web de gestión y reservas en formato SaaS (Software as a Service) con arquitectura modular y parametrizable, capaz de adaptarse con precisión a la infraestructura y dimensión de cualquier club de pádel.

La solución articula en su núcleo base un panel de administración que proporciona al personal del centro una herramienta unificada para la gestión en tiempo real de pistas, la programación de clases dirigidas, la organización de torneos y el control automatizado de cuotas y estados de socios. De forma paralela, integra un portal de autoservicio que permite a los usuarios consultar disponibilidad y reservar pistas de forma autónoma desde cualquier dispositivo, aplicando automáticamente reglas de precios dinámicos con tarifas generales para clientes casuales o beneficios exclusivos para socios.

De manera complementaria, la plataforma incorpora un ecosistema adaptable de módulos opcionales que cada club de pádel puede activar o desactivar independientemente según sus instalaciones físicas. Entre estas funcionalidades adicionales se incluyen la asignación y bonificación automatizada de plazas de estacionamiento durante el horario de juego, la reserva previa de mesa en la cafetería o zona de restauración para el "tercer tiempo", y la venta cruzada de material deportivo (bolas, ropa, grips) integrada directamente en el proceso de pago. Asimismo, se habilita una sección pública de bolsa de empleo para canalizar la recepción de currículums y candidaturas destinadas a cubrir puestos de monitores, personal de recepción o hostelería dentro del propio club.

## 

## 1.4. Objetivos del proyecto {#1.4.-objetivos-del-proyecto}

**Ordenar por números los objetivos específicos,  ordenar por importancia, y cuando realicemos el último objetivo específico, habremos logrado el objetivo general**

### 1.4.1. Objetivo general  {#1.4.1.-objetivo-general}

Desarrollar una aplicación web funcional que permita gestionar de forma centralizada las reservas de instalaciones, la actividad de socios y la organización de torneos de un club de pádel.

El sistema contará con una arquitectura cliente-servidor donde se separarán la parte visual de la parte visual de la parte lógica de la aplicación. Se establecerán a su vez roles de usuario que permitan controlar funcionalidades diferenciando entre socio, invitado o personal del club.

En resumidas cuentas, el objetivo principal es desarrollar un software que sea sencillo, accesible y permita mejorar la experiencia del usuario así como la gestión por parte del club.

### 1.4.2. Objetivos específicos  {#1.4.2.-objetivos-específicos}

\-Diseñar un sistema de reserva de recursos (pistas, vestuarios, clases) con disponibilidad en tiempo real y tarifas diferenciadas para socios y no socios. 

\-Implementar un sistema de roles (invitado, socio, administrador) con autenticación y control de acceso. 

\-Desarrollar un módulo de gestión de torneos con inscripción y generación de cuadros/emparejamientos. 

\-Implementar un sistema de alta de socios con gestión de descuentos y ventajas asociadas. 

\-Diseñar una interfaz responsive, accesible y coherente con los principios de usabilidad. 

\-Aplicar principios de accesibilidad y usabilidad, procurando que los contenidos sean comprensibles  y las principales funcionalidades se puedan realizar de forma sencilla desde cualquier dispositivo.

\-Desplegar la aplicación en un entorno de producción siguiendo buenas prácticas de seguridad (HTTPS, gestión de sesiones). 

\-Mejorar la experiencia del usuario cliente del club haciendo que las gestiones se realicen de forma digital.

\-Facilitar gestión del club proporcionando información y herramientas que permitan controlar las actividades del club de forma centralizada.

## 1.5. Alcance del proyecto  {#1.5.-alcance-del-proyecto}

El alcance del proyecto comprende el diseño, desarrollo, pruebas y despliegue de una plataforma SaaS (Software as a Service) de gestión integral para clubes de pádel, estructurada en dos grandes módulos funcionales y soportada por un sistema de diseño unificado:

1. Módulo 1: Gestión Administrativa (Panel de Control)  
   Cuadro de mando y gestión de pistas: Panel interactivo para la visualización del estado de ocupación en tiempo real, calendario dinámico, bloqueo de franjas horarias y asignación de mantenimientos.

Punto de Venta (POS / TPV) y Caja: Módulo de cobro rápido para reservas presenciales, venta directa de material deportivo y consumo en la cafetería/restaurante del club.

Administración de usuarios y perfiles: Gestión de roles (RBAC) diferenciando Administrador, Recepcionista, Socio y Cliente no socio con permisos dinámicos.

Gestión de la Escuela de Pádel: Organización de clases particulares/colectivas y asignación de entrenadores.

Control de Accesos y Parking: Generación y validación mediante lectura de códigos QR para la apertura automática de barreras.

2. Módulo 2: Aplicación para Clientes / Jugadores  
   Búsqueda y Reserva Autónoma: Interfaz Mobile-First para consulta de disponibilidad en tiempo real y reserva de pistas en menos de 3 clics.

Pasarela de Pagos Integrada: Cobro seguro mediante tarjeta bancaria y saldo en monedero virtual recargable.

Portal de Mi Perfil y Reservas: Historial de partidos, gestión de cancelaciones (según política de tiempos) y código QR personal para el parking/acceso a pistas.

Servicios Complementarios: Consulta de la carta del restaurante/bar del club y solicitud de clases con monitores.

3. Infraestructura y Sistema de Diseño  
   Sistema de Diseño Unificado (UI/UX): Design System documentado en Figma con componentes accesibles (cumplimiento parcial WCAG 2.1), librería Lucide Icons, tipografía corporativa y paleta adaptada.

## 1.6. Limitaciones y exclusiones  {#1.6.-limitaciones-y-exclusiones}

Para acotar los compromisos de entrega dentro del ciclo de desarrollo académico y mantener los estándares de calidad del software dentro de la organización económica existente (presupuesto basado en horas de personal y uso de herramientas en modalidad Free Tier), se definen las siguientes exclusiones, restricciones técnicas y medidas de prevención:  
PNG

1. Exclusiones de Funcionalidad (Out of Scope)  
   Algoritmos avanzados de matchmaking automático: No se incluye un sistema automatizado por Inteligencia Artificial para el nivelado de parejas o la organización automática de torneos/ligas (queda propuesto para futuras iteraciones).

Facturación electrónica avanzada (ERP/Contabilidad externa): No se contempla la integración directa con software de contabilidad de terceros (ej. Holded, SAP) ni la generación automática de modelos tributarios oficiales.

2. Limitaciones Técnicas e Infraestructura  
   Cotas de la capa gratuita (Free Tier): Al hacer uso de servicios Cloud en modalidad gratuita (Supabase, Vercel), la plataforma presenta restricciones de almacenamiento máximo (500 MB en PostgreSQL) y límites de concurrencia simulada orientados al entorno de pruebas/prototipo.

Soporte de aplicaciones nativas (iOS / Android): La solución para clientes está optimizada como Web App Responsive (PWA / Mobile-First), por lo que no incluye la publicación en las tiendas de aplicaciones App Store ni Google Play Store en esta fase.

Pasarela de pago en modo prueba (Sandbox): Los procesamientos de cobro se realizan mediante credenciales de prueba sin transacciones económicas con dinero real.

3. Prevención de Riesgos y Obligaciones Legales/Técnicas (Criterio de Rúbrica)

Cumplimiento de Protección de Datos: Se contemplan las obligaciones de privacidad mediante el cifrado de contraseñas (hashing mediante algoritmos seguros), almacenamiento protegido de datos personales de los socios y solicitud de consentimiento explícito en los formularios de registro.

Prevención de Riesgos de Seguridad y Disponibilidad:

Inyección de datos y vulnerabilidades web: Implementación de validaciones de entrada en formularios (sanitización) y control de acceso seguro mediante tokens autenticados (JWT) para mitigar accesos no autorizados.

Respaldo ante fallos del sistema: Se establece una política de copias de seguridad (backups) automáticas periódicas sobre la base de datos para prevenir la pérdida imprevista de información durante la fase de auditoría y pruebas.

Alineación con la Viabilidad Económica: Todas las limitaciones planteadas se alinean con la estructura de costes a 0,00 € en herramientas e infraestructura, garantizando la viabilidad real del prototipo sin incurrir en licencias o gastos operativos adicionales durante el ciclo académico.

## 1.7. Estructura de la memoria {#1.7.-estructura-de-la-memoria}

La estructura de la memoria sigue un orden secuencial de capítulos que refleja las distintas fases por las que ha pasado el desarrollo del proyecto. Empezaremos con una breve introducción al proyecto y una investigación propia del sector. Luego haremos una planificación de la gestión y los requisitos necesarios, y finalmente iremos con el diseño, el desarrollo y la implementación. Una vez hecho esto, realizaremos un periodo de pruebas, revisando también pequeños detalles. Cuando todo funcione a la perfección, desplegaremos la aplicación web y la pondremos en producción, realizando los manuales de uso y haciendo una conclusión y evaluación final. 

A continuación, se hará una pequeña explicación de lo que se hará en cada una de estas fases.

En primer lugar, se presentará una introducción a la memoria. Se explicarán el contexto del proyecto, el problema detectado y la solución propuesta, los objetivos generales y específicos, y el alcance de la aplicación web, junto con las limitaciones y exclusiones que condicionan su realización.

En segundo lugar, se expondrá el análisis del contexto y la viabilidad. Se examinarán el sector profesional, el perfil de usuarios, la necesidad detectada y las soluciones existentes, y se estudiará la viabilidad técnica, económica y legal, incluyendo la protección de datos personales, las licencias y la accesibilidad. Por último, se realizará un análisis de riesgos inicial que sirva de base para la planificación.

En tercer lugar, se desarrollará la planificación y gestión del proyecto, una de las fases más importantes para el desarrollo de la aplicación. Se definirán la metodología, la organización del equipo, el reparto de responsabilidades y roles dentro de este, y el plan de trabajo. Luego también se hará el cronograma de hitos, la estimación de recursos, el presupuesto y la gestión de riesgos. Además, se describirán las herramientas de comunicación, coordinación y seguimiento, y la gestión de versiones y del repositorio de código.

En cuarto lugar, se llevará a cabo el análisis de requisitos de la aplicación. Se identificarán los usuarios y perfiles, y se definirán los requisitos funcionales y no funcionales, indicando su orden de prioridad. Después se recogerán las reglas de negocio, los casos de uso y la matriz de trazabilidad de los requisitos.

En quinto lugar, se abordará el diseño de la solución, empezando por una visión general de la arquitectura. Se detallarán la arquitectura software, el diseño de la base de datos, el diseño de la interfaz de usuario (usabilidad, accesibilidad, navegación y wireframes), el diseño de seguridad y el de integraciones y APIs externas.

En sexto lugar, se detallará el desarrollo e implementación de la aplicación web. Se expondrán las tecnologías, lenguajes y frameworks utilizados, el entorno de desarrollo y la estructura del proyecto, todo ello junto con la implementación de las funcionalidades principales, la persistencia de datos y la interfaz de usuario. También se explicarán las integraciones con servicios externos, la gestión de dependencias, el control de versiones con su estrategia de ramas y las decisiones técnicas más relevantes.

En séptimo lugar, se describirán las pruebas y el aseguramiento de la calidad. Se definirá la estrategia de pruebas, el entorno y las herramientas empleadas. Luego se realizarán pruebas unitarias, funcionales, de integración, de seguridad, de usabilidad y de accesibilidad. Por último, se recogerán los resultados, las incidencias detectadas con sus correcciones y la evaluación del cumplimiento de los requisitos.

En octavo lugar, se explicará el despliegue y puesta en producción de la aplicación. Se describirán la infraestructura, los requisitos de instalación y el proceso de despliegue, así como la configuración de servicios y variables de entorno, el dominio, los certificados y las comunicaciones seguras. Además, se expondrán las copias de seguridad y recuperación, la monitorización, el registro de errores y el plan de mantenimiento.

En noveno lugar, se elaborarán los manuales de uso como el manual de instalación, el manual técnico, el manual de usuario y la guía de administración, teniendo aparte un apartado de preguntas frecuentes e incidencias habituales. Su objetivo es que cualquier persona pueda instalar, utilizar y administrar la aplicación sin depender del equipo que la desarrolló.

En décimo lugar, se presentarán los resultados y la evaluación final del proyecto. Se analizará el producto desarrollado, el grado de cumplimiento de los objetivos y de los requisitos, y el valor aportado a usuarios y clubes, y se comparará la planificación inicial con el resultado final. También se recogerán las dificultades encontradas, las soluciones adoptadas y las competencias técnicas y transversales aplicadas.

Por último, se expondrán las conclusiones y líneas futuras. Se recogerán las conclusiones del trabajo, las posibles mejoras, la escalabilidad y evolución posible de la plataforma, y una reflexión final sobre el aprendizaje adquirido a lo largo del proyecto.

