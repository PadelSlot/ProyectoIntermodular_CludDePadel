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

[**2\. ANÁLISIS DEL CONTEXTO Y VIABILIDAD	11**](#2.-análisis-del-contexto-y-viabilidad)

[2.1. Sector profesional y perfil de usuarios	11](#2.1.-sector-profesional-y-perfil-de-usuarios)

[2.2. Análisis de la Necesidad	17](#2.2.-análisis-de-la-necesidad)

[2.3 Soluciones existentes	22](#2.3-soluciones-existentes)

[2.4. Partes interesadas (Stakeholders)	26](#2.4.-partes-interesadas-\(stakeholders\))

[2.5. Estudio de viabilidad técnica	28](#2.5.-estudio-de-viabilidad-técnica)

[2.6.Estudio de viabilidad económica	34](#2.6.estudio-de-viabilidad-económica)

[2.7 Estudio de viabilidad legal y normativa	40](#2.7-estudio-de-viabilidad-legal-y-normativa)

[2.8 Análisis de riesgos inicial	43](#2.8-análisis-de-riesgos-inicial)

[**REFERENCIAS IEEE	44**](#referencias-ieee)

# 1\. INTRODUCCIÓN  {#1.-introducción}

## 1.1. Contexto del proyecto  {#1.1.-contexto-del-proyecto}

El presente proyecto se desarrolla en el marco del módulo de Proyecto Intermodular de 2º curso del ciclo formativo de Desarrollo de Aplicaciones Web, como trabajo integrador de las competencias adquiridas en las asignaturas de Entorno Cliente, Entorno Servidor, Diseño de Interfaces Web y Despliegue de Aplicaciones Web. 

El sector de la gestión deportiva, y en particular el de los clubes de pádel, ha experimentado un crecimiento notable en los últimos años en España, lo que ha incrementado la necesidad de herramientas digitales que faciliten la gestión de instalaciones, socios, reservas y actividades del club tanto para el personal administrativo como para los usuarios finales.  En cuanto a las empresas del sector, la mayoría son pequeñas o medianas, con una plantilla reducida (recepción, mantenimiento, monitores de pádel) y su actividad principal es el alquiler de pistas por franjas horarias, al que suelen sumar clases y programas de socios con ventajas asociadas.

Muchos clubes de padel de tamaño medio han gestionado estos procesos mediante métodos poco automatizados, como llamadas telefónicas para la reserva de pistas, hojas de cálculo para el control de socios o grupos de mensajería para organizar clases y torneos. Este tipo de gestión puede resultar suficiente en clubes pequeños, pero se vuelve claramente insuficiente a medida que aumentan los practicantes, los socios y las instalaciones, generando una carga de trabajo mayor para el personal administrativo y una experiencia poco ágil para el usuario.

En este contexto, se plantea el desarrollo de **PadelSlot**, una aplicación web pensada para que cualquier club de pádel pueda incorporarse y gestionar desde ella sus propias instalaciones, socios, reservas y actividades. Para la presentación de este proyecto se ha tomado como caso de demostración un club de padel concreto, creado por nosotros, sobre el que se ha implantado el conjunto completo de funcionalidades que la plataforma ofrece. Este planteamiento permite aplicar de forma conjunta contenidos de programación cliente y servidor, diseño de interfaces, bases de datos y despliegue sobre un caso realista y con necesidades identificables en clubes de nuestro entorno.

## 

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

### 1.4.1. Objetivo general  {#1.4.1.-objetivo-general}

Desarrollar una aplicación web funcional que permita gestionar de forma centralizada las reservas de instalaciones, la actividad de socios y la organización de torneos de un club de pádel.

El sistema contará con una arquitectura cliente-servidor donde se separarán la parte visual de la parte visual de la parte lógica de la aplicación. Se establecerán a su vez roles de usuario que permitan controlar funcionalidades diferenciando entre socio, invitado o personal del club.

En resumidas cuentas, el objetivo principal es desarrollar un software que sea sencillo, accesible y permita mejorar la experiencia del usuario así como la gestión por parte del club.

### 1.4.2. Objetivos específicos  {#1.4.2.-objetivos-específicos}

\-**Diseñar un sistema de reserva de recursos** (pistas, vestuarios, clases) con disponibilidad en tiempo real y tarifas diferenciadas para socios y no socios. 

\-**Implementar un sistema de roles** (invitado, socio, administrador) con autenticación y control de acceso. 

**\-Desarrollar un módulo de gestión de torneos** con inscripción y generación de cuadros/emparejamientos. 

\-**Implementar un sistema de alta de socios** con gestión de descuentos y ventajas asociadas. 

\-**Diseñar una interfaz responsive**, accesible y coherente con los principios de usabilidad. 

\-**Aplicar principios de accesibilidad y usabilidad**, procurando que los contenidos sean comprensibles  y las principales funcionalidades se puedan realizar de forma sencilla desde cualquier dispositivo.

\-**Desplegar la aplicación en un entorno de producción** siguiendo buenas prácticas de seguridad (HTTPS, gestión de sesiones). 

\-**Mejorar la experiencia del usuario cliente** del club haciendo que las gestiones se realicen de forma digital.

\-**Facilitar la gestión del club** proporcionando información y herramientas que permitan controlar las actividades del club de forma centralizada.

## 1.5. Alcance del proyecto  {#1.5.-alcance-del-proyecto}

Comprende el diseño, desarrollo, pruebas y despliegue de una plataforma SaaS (Software as a Service) de gestión integral para clubes de pádel, estructurada en dos grandes módulos funcionales y soportada por un sistema de diseño unificado:

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

## 

## 1.6. Limitaciones y exclusiones  {#1.6.-limitaciones-y-exclusiones}

Para acotar los compromisos de entrega dentro del ciclo de desarrollo académico y mantener los estándares de calidad del software dentro de la organización económica existente (presupuesto basado en horas de personal y uso de herramientas en modalidad Free Tier), se definen las siguientes exclusiones, restricciones y medidas de prevención:

**Exclusiones de Funcionalidad (Out of Scope)**  
Algoritmos avanzados de matchmaking automático: No se incluye un sistema automatizado por Inteligencia Artificial para el nivelado de parejas o la organización automática de torneos/ligas (queda propuesto para futuras iteraciones).

**Facturación electrónica avanzada (ERP/Contabilidad externa):** No se contempla la integración directa con software de contabilidad de terceros (ej. Holded, SAP) ni la generación automática de modelos tributarios oficiales.

**Limitaciones Técnicas e Infraestructura**  
Cotas de la capa gratuita (Free Tier): Al hacer uso de servicios Cloud en modalidad gratuita (Supabase, Vercel), la plataforma presenta restricciones de almacenamiento máximo (500 MB en PostgreSQL) y límites de concurrencia simulada orientados al entorno de pruebas/prototipo.

**Soporte de aplicaciones nativas (iOS / Android):** La solución para clientes está optimizada como Web App Responsive (PWA / Mobile-First), por lo que no incluye la publicación en las tiendas de aplicaciones App Store ni Google Play Store en esta fase.

Pasarela de pago en modo prueba (Sandbox): Los procesamientos de cobro se realizan mediante credenciales de prueba sin transacciones económicas con dinero real.

**Prevención de Riesgos y Obligaciones Legales/Técnicas (Criterio de Rúbrica)**

Cumplimiento de Protección de Datos: Se contemplan las obligaciones de privacidad mediante el cifrado de contraseñas (hashing mediante algoritmos seguros), almacenamiento protegido de datos personales de los socios y solicitud de consentimiento explícito en los formularios de registro.

**Prevención de Riesgos de Seguridad y Disponibilidad:**

Inyección de datos y vulnerabilidades web: Implementación de validaciones de entrada en formularios (sanitización) y control de acceso seguro mediante tokens autenticados (JWT) para mitigar accesos no autorizados.

**Respaldo ante fallos del sistema**: Se establece una política de copias de seguridad (backups) automáticas periódicas sobre la base de datos para prevenir la pérdida imprevista de información durante la fase de auditoría y pruebas.

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

# 2\. ANÁLISIS DEL CONTEXTO Y VIABILIDAD {#2.-análisis-del-contexto-y-viabilidad}

## 2.1. Sector profesional y perfil de usuarios {#2.1.-sector-profesional-y-perfil-de-usuarios}

**ENTORNO PRODUCTIVO**

PadelSlot operará dentro de la actividad diaria de un club de pádel, un entorno de servicio presencial al cliente con una alta rotación de clientes a lo largo del día. Las pistas se alquilan por franjas de 90 minutos, por lo que cada pista dispone de hasta 10 franjas diarias. Así, un club de tamaño medio, de entre 4 y 8 pistas, puede gestionar entre 40 y 80 reservas al día en ocupación completa, además de las clases y demás actividades.

En ese entorno, la aplicación se usará en tres espacios físicos, cada uno con condiciones de uso propias. En primer lugar, la recepción del club, donde el personal trabaja de forma continua desde un ordenador, atendiendo a la vez el mostrador, el teléfono y la pantalla. En segundo lugar, las instalaciones, donde el personal y los jugadores realizan interacciones cortas desde el móvil o la tablet, como comprobar una pista o validar un código QR. Por último, fuera del club, donde el público general y los socios utilizan la aplicación web desde su móvil o ordenador personal, en cualquier momento o lugar.

Además, el entorno productivo presenta varias condiciones que la aplicación debe respetar:

* **Horario amplio**: todos los días de 8:00 a 23:00 aproximadamente, con picos de demanda por la tarde-noche entre semana y las mañanas de fin de semana. En esos picos el sistema debe responder con rapidez y sin conflictos de reserva.  
* **Personal reducido y polivalente**: la misma persona reserva, cobra, atiende al teléfono y resuelve incidencias, por lo que las tareas administrativas deben resolverse en pocos clics.  
* **Sin personal técnico propio**: el club no tiene informáticos, por lo que la solución no puede requerir instalación ni mantenimiento local, motivo por el que PadelSlot se plantea como un servicio web en la nube (SaaS).  
* **Variabilidad de servicios**: algunos clubes disponen de cafetería, parking o tienda y otros no, por lo que el sistema debe poder activar o desactivar módulos según el club y sus instalaciones.

**PERSONAS QUE INTERACTÚAN CON LA APLICACIÓN**

En cuanto a las personas y perfiles laborales que interactúan con la aplicación, aunque en un club intervienen perfiles muy diversos, todos ellos se agrupan en tres roles de aplicación: público general, socio y administrador. La siguiente tabla clasifica cada perfil real, su relación con la aplicación y su rol correspondiente.

| Perfil | Relación | Rol |
| :---- | :---- | :---- |
| Propietario del club | Usuario directo. Configura el club, tarifas y módulos. También gestiona socios, la ocupación y la facturación. | Administrador |
| Recepcionista | Usuario directo e intensivo. Crea, modifica y cancela reservas, da de alta socios y atiende incidencias. | Administrador |
| Personal del club | Usuarios indirectos como son los entrenadores de pádel, personal de mantenimiento, de cafetería y tienda | Sin rol propio (gestionados por el Administrador) |
| Socio | Usuario directo y recurrente. Reserva con tarifa de socio, consulta sus ventajas, se inscribe en torneos y clases. Además, usa su QR de acceso | Socio |
| Jugador ocasional (no socio) | Usuario directo y puntual. Consulta disponibilidad y precios, se registra para reservar y paga online. | Público general |
| Candidato a empleo | Usuario directo sin registro. Consulta la información pública del club y envía su candidatura (CV) a la bolsa de empleo | Público general |

**CARACTERIZACIÓN DEL SECTOR**

PadelSlot se enmarca en el sector de la gestión de instalaciones deportivas y el ocio deportivo (CNAE 93.11 y 93.12), concretamente en los clubes de pádel. España es el país de referencia mundial del pádel, ya que cuenta con unos 4.575 clubes y 17.300 pistas \[1\], con una media de casi 4 pistas por club. Esto confirma que el sector está formado mayoritariamente por pymes de tamaño pequeño y medio. En 2024 se alcanzaron 109.040 licencias federativas y se estima que más de 6 millones de personas juegan al pádel de forma amateur \[2\].

El club medio funciona con una plantilla reducida (gerencia, recepción, monitores y mantenimiento). Su principal fuente de ingresos es el alquiler de franjas horarias, complementado con cuotas de socios, escuela de pádel, torneos y servicios como cafetería, tienda o parking.

En cuanto a la digitalización, el sector avanza hacia la reserva y el pago online desde el móvil, que es el canal natural del usuario. Los clubes que utilizan herramientas digitales de reserva y gestión obtienen un rendimiento entre 3 y 5 veces superior al de sus competidores \[3\]. Ganan peso también los servicios fuera de pista y el control de accesos mediante QR.

De todo ello se derivan las principales necesidades tecnológicas del sector:

- Un calendario centralizado en tiempo real que evite dobles reservas.  
- Reserva y pago 24/7 desde el móvil.  
- Tarifas diferenciadas entre socios y público general.  
- Gestión de socios, clases y torneos.  
- Una solución en la nube (sin instalación) adaptable a las instalaciones de cada club.

**TABLA DESCRIPTIVA DEL SECTOR Y SUS CARACTERÍSTICAS ORGANIZATIVAS**

| Dimensión | Descripción |
| :---- | :---- |
| Sector | Gestión de instalaciones deportivas y ocio deportivo (CNAE 93.11 y 93.12) |
| Tamaño del mercado | Unos 4.575 clubes, aproximadamente 17.300 pistas, más de 109.040 licencias y más de 6 millones de practicantes |
| Tipo de empresa | Pymes o microempresas, con 3 o 4 pistas por club de media |
| Plantilla general | Gerente, de 1 a 3 recepcionistas, monitores, mantenimiento y personal de cafetería |
| Fuentes de ingresos | Alquiler de pistas, cuotas de socios, escuela, torneos, cafetería y tiendas |
| Horario y demanda | De 8:00 a 23:00 todos los días, con picos por la tarde-noche y los fines de semana |
| Gestión actual | Teléfono, WhatsApp, correo electrónico, hojas de cálculo o software poco adaptable |
| Tendencias | Reserva y pago desde el móvil, precios diferenciados, acceso por QR y servicios fuera de pista |

**BUYER PERSONA**

Representa a quién decide contratar la plataforma. Su objetivo es identificar las motivaciones, criterios de decisión y objeciones de compra del cliente que paga el servicio. Esta ficha descriptiva sirve para definir la propuesta de valor y el modelo de negocio de PadelSlot.

| Campo | Descripción |
| :---- | :---- |
| Rol laboral | Propietario o gerente de un club de padel pequeño o mediano |
| Competencias digitales previas | Maneja hojas de cálculo, correo electrónico, banca online y TPV, pero no tiene conocimientos técnicos ni personal informatico |
| Entorno de uso habitual | Ordenador del club o personal en horario laboral y móvil para consultas fuera de horario |
| Objetivos al contratar | Reducir la carga administrativa, agilizar el tema de las reservas y fidelizar a los socios |
| Criterios de decisión | Coste bajo y predecible, sin instalación, puesta en marcha con rapidez, adaptación a las instalaciones de cada club y facilidad de uso para el personal |
| Objeciones | Miedo a perder clientes durante el cambio, desconfianza en la curva de aprendizaje personal y en la seguridad de los datos y pagos |

**USER PERSONAS**

Representa a quien utiliza la plataforma en su día a día. Su objetivo es identificar las competencias digitales, el entorno de uso y las tareas de cada tipo de usuario. Sirve para tomar decisiones de diseño, usabilidad y funciones. A partir de los tres roles definidos, se ha elaborado una ficha de User Persona para cada uno de ellos.

\- Público general

| Campo | Descripción |
| :---- | :---- |
| Rol | Jugador no socio que reserva de forma puntual, sin club fijo |
| Competencias digitales previas | Habituado a reservar y pagar servicios onlines desde el móvil |
| Entorno de uso habitual | Uso de móvil en cualquier momento y lugar |
| Objetivos principales | Consultar pistas libres y precios, reservar y pagar en pocos pasos y recibir confirmación inmediata |
| Problemas actuales | Depender de correos, llamadas o WhatsApp, esperar respuesta y no conocer el precio antes de reservar |

\- Socio

| Campo | Descripción |
| :---- | :---- |
| Rol | Jugador recurrente con membresía activa y participa en clases y torneos. |
| Competencias digitales previas | Perfil de edad amplio, con peso relevante de jugadores veteranos, por lo que la interfaz debe ser sencilla |
| Entorno de uso habitual | Principalmente uso de móvil, ordenador de forma ocasional |
| Objetivos principales | Reservar con su tarifa de socio, consultar su cuota y ventajas, inscribirse en torneos y clases y usar su QR de acceso |
| Problemas actuales | Tener que reservar por teléfono o presencial cada semana, que no se le apliquen sus ventajas y enterarse tarde de las actividades del club |

\- Administrador

| Campo | Descripción |
| :---- | :---- |
| Rol | Personal del club encargado de la operativa diaria, como son las reservas, cobros, socios, clases y torneos |
| Competencias digitales previas | Trabaja con mucha información a la vez sin nada que le facilite el trabajo, para ello nuestro SaaS |
| Entorno de uso habitual | Ordenador de sobremesa en recepción durante toda la jornada, además de uso de tablet o móvil por las instalaciones o fuera del horario laboral |
| Objetivos principales | Ver el estado de todas las pistas en tiempo real, gestionar reservas en segundos, controlas socios y sus respectivas cuotas y organizar clases y torneos |
| Problemas actuales | Dobles reservas, tiempo perdido en correos, llamadas y WhatsApp, cuotas sin controlar y torneos organizados a mano |

**IMPLICACIONES EN EL DISEÑO**

Los perfiles analizados llevan a diseñar dos interfaces diferenciadas que comparten el mismo sistema de diseño:

* **Portal de clientes (público general y socio)**: diseño Mobile-First, una tarea por pantalla, botones grandes, tipografía legible y reserva en un máximo de 3 pasos. El socio ve automáticamente su precio, sus ventajas y su QR.  
* **Panel de administración**: pensado para escritorio y adaptado a tablet. Ofrece alta densidad de información, una vista general de todas las pistas y acciones rápidas sin cambiar de pantalla. Solo muestra los módulos activados por el club.

## 

## 

## 2.2. Análisis de la Necesidad {#2.2.-análisis-de-la-necesidad}

El desarrollo de la aplicación PadelSlot responde a la urgente necesidad de modernizar y digitalizar la gestión operativa de los clubes de pádel de tamaño medio. Actualmente, la combinación entre el vertiginoso incremento de aficionados a este deporte y la persistencia de métodos de gestión analógicos o desarticulados genera un cuello de botella operativo crítico. Este desfase no sólo satura al personal del club con tareas administrativas repetitivas, sino que menoscaba la experiencia de uso de los jugadores, provocando pérdidas económicas por cancelaciones, solapamientos en las pistas y fugas de clientes hacia instalaciones con mejor infraestructura tecnológica. Investir recursos en esta solución SaaS multiplataforma se justifica por la oportunidad de automatizar los flujos de trabajo, garantizar la disponibilidad del servicio y maximizar la rentabilidad global del centro deportivo.

**DIAGNOSTICO DE LA SITUACIÓN DE PARTIDA (As-Is)**

En la actualidad, una gran cantidad de clubes de pádel gestionan sus operaciones mediante procesos manuales fragmentados y no interoperables:

* Reserva de Pistas y Actividades: Se realiza de manera sincrónica a través de llamadas telefónicas directas, mensajes informales de WhatsApp o atención presencial en la recepción. El recepcionista debe anotar manualmente cada reserva en cuadernos de papel o en hojas de cálculo locales.  
* Gestión de Socios y Cuotas: El control de las membresías, cobros recurrentes y descuentos aplicables se administra mediante plantillas de Excel independientes o ficheros físicos. La información no está centralizada, lo que dificulta la verificación rápida de la validez del estado de socio en el momento del alquiler.  
* Coordinación de la Escuela y Torneos: Las clases dirigidas y las inscripciones a campeonatos se gestionan mediante grupos abiertos de mensajería instantánea y listas en papel, provocando desorganización en la asignación de monitores y el emparejamiento de jugadores.  
* Servicios Complementarios Inconexos: La cafetería/restaurante, la tienda de material deportivo y el control de estacionamiento funcionan como islas independientes sin conexión con el sistema de reservas, perdiendo oportunidades de venta cruzada e incrementando el trabajo de cuadre de caja al final de la jornada.

**PROBLEMAS Y CONSECUENCIAS IDENTIFICADAS**

El modelo operativo tradicional (As-Is) desencadena una serie de ineficiencias con un impacto directo en la sostenibilidad del negocio y en la satisfacción del cliente:

1. Alta carga administrativa y errores humanos: La transcripción manual de datos ocasiona frecuentemente dobles reservas (dos grupos asignados a la misma pista y hora), asignaciones erróneas de precios e incongruencias en los cierres de caja.

2. Pérdida de trazabilidad e informes tardíos: Al carecer de una base de datos unificada, la directiva del club no dispone de métricas en tiempo real sobre los niveles de ocupación, horas punta, rendimiento financiero o efectividad de las promociones.

3. Fricción y abandono del usuario casual: El cliente puntual exige inmediatez. La imposibilidad de consultar la disponibilidad de franjas horarias en tiempo real fuera del horario de atención telefónica impulsa al usuario a abandonar el proceso o elegir otro club de la competencia.

4. Desgaste y pérdida de fidelización del socio: La lentitud en la atención presencial, la dificultad para asegurar sus horas reservadas con antelación y la falta de transparencia en sus beneficios derivan en la cancelación progresiva de cuotas periódicas.

5. Obsolescencia e inoperabilidad del software: Las escasas soluciones informáticas utilizadas son sistemas rígidos de escritorio que no se adaptan a la movilidad que exige el usuario ni a la diversidad de instalaciones del centro (parking, cafetería, tienda).

**PROPUESTA DE VALOR Y SITUACIÓN DESEADA (To-Be)**

La implementación de la plataforma SaaS multiplataforma PadelSlot transforma de manera integral la operativa del club hacia un modelo ágil, automatizado y centrado en el usuario:

* Autonomía y Reserva 24/7 en \<3 Clics: Los jugadores consultan la disponibilidad en tiempo real y gestionan sus reservas de forma autónoma desde cualquier dispositivo móvil o de escritorio, eliminando la dependencia telefónica.  
* Gestión Centralizada e Integral: El personal del club gestiona desde un panel de control único las pistas, la agenda de la escuela de pádel, los torneos, el TPV presencial y el fichero de socios.  
* Tarificación Dinámica Automatizada: El sistema aplica de forma automática las reglas de negocio, asignando tarifas bonificadas para socios y precios estándar para clientes casuales.

* Ecosistema Modular Parametrizable: Permite activar o desactivar funcionalidades complementarias según las infraestructuras del club, tales como la asignación de parking mediante lectura de códigos QR, la reserva previa en cafetería o la compra de material deportivo integrado en la pasarela de pago.  
* Trazabilidad y Cero Errores Operativos: La persistencia de datos centralizada e instantánea imposibilita la duplicidad de franjas horarias y proporciona métricas de negocio actualizadas al momento.

**FUNDAMENTOS TEÓRICOS CONTRASTADOS**

La concepción de PadelSlot se fundamenta en principios consolidados de la ingeniería del software y la gestión de la transformación digital:

* Modelo SaaS y Arquitectura Cliente-Servidor Desacoplada: La adopción del modelo *Software as a Service* facilita el acceso multiinquilino (*multi-tenant*) sin requerir instalaciones locales complejas en los clubes. Desacoplar la capa de presentación (Frontend en arquitectura SPA/PWA) de la lógica de negocio (Backend API REST) garantiza escalabilidad, flexibilidad operativa y la posibilidad de ofrecer respuestas rápidas ante peticiones de alta concurrencia.  
* Estrategia Design System y Mobile-First (WCAG 2.1): Las bases teóricas de la experiencia de usuario (UX) sostienen que el diseño adaptado prioritariamente a dispositivos móviles reduce sustancialmente las tasas de abandono en sistemas de autoservicio. La integración de un sistema de diseño estandarizado guiado por pautas de accesibilidad web (WCAG 2.1) asegura una navegación intuitiva y accesible para todos los perfiles de usuario.  
* Control de Acceso Basado en Roles (RBAC) y Seguridad: Para garantizar la integridad de los datos y el cumplimiento normativo en materia de protección de datos personales (RGPD), se aplican esquemas de autenticación mediante tokens JWT y cifrado de datos en reposo y en tránsito (HTTPS).

**DIAGRAMAS CONCEPTUALES DE FLUJO: As-Is vs To-Be**

\- Flujo Actual (As-Is): Proceso Manual y Sincrónico

![][image1]

\- Flujo Propuesto (To-Be): Proceso Automatizado y Autónomo con PadelSlot

![][image2]

**NECESIDADES FUNCIONALES Y OPERATIVAS DE ALTO NIVEL**

| Categoría | Necesidad Funcional / Operativa | Justificación Técnica y Operativa |
| :---- | :---- | :---- |
| Autenticación y Perfiles | Control de Acceso basado en Roles (RBAC) | Garantiza la separación de permisos entre Administradores, Recepcionistas, Socios y Clientes Casuales, salvaguardando la seguridad de los datos. |
| Reserva de Recursos | Cuadrante dinámico de pistas con actualización en tiempo real | Elimina los colapsos por dobles reservas y permite a los usuarios gestionar partidos en menos de 3 clics sin intermediarios. |
| Gestión Financiera | Pasarela de pago integrada y monedero virtual | Reduce los impagos y agiliza el cobro de reservas presenciales o remotas mediante transacciones seguras. |
| Administración de Socios | Motor de tarifado dinámico y gestión de membresías | Aplica automáticamente ventajas y descuentos a los socios, fomentando su fidelización y automatizando el cobro de cuotas. |
| Punto de Venta (POS) | Módulo de TPV para tienda y cafetería | Centraliza en una misma caja los cobros presenciales de alquileres, consumiciones y material deportivo. |
| Control de Accesos | Generación de códigos QR para parking y pistas | Automatiza el flujo de entrada a las instalaciones físicas del club sin requerir presencia constante del personal de recepción. |
| Gestión de la Escuela | Planificación de clases y organización de torneos | Sustituye los grupos informales de mensajería por una gestión estructurada de alumnos, cuadros de torneos y entrenadores. |
| Usabilidad y Adaptabilidad | Interfaz Responsive Mobile-First accesible (WCAG) | Asegura el correcto funcionamiento de la plataforma en cualquier teléfono inteligente, tablet u ordenador, minimizando la curva de aprendizaje. |

## 

## 2.3 Soluciones existentes {#2.3-soluciones-existentes}

El análisis comparativo de mercado examina las soluciones comerciales existentes en el ámbito de la gestión deportiva para determinar cómo PadelSlot responde de forma optimizada a los cuellos de botella operativos de los clubes de pádel mediante una propuesta de valor competitiva.

**IDENTIFICACIÓN DE SOFTWARE COMPETIDOR**

Para evaluar el posicionamiento de la plataforma, se han seleccionado tres alternativas consolidadas en el mercado actual:

1. **Playtomic Manager**: Solución comercial de referencia en Europa estructurada como un *marketplace* masivo. Centraliza las reservas de múltiples centros a cambio de comisiones por transacción y dependencia del ecosistema de la propia plataforma.  
2. **TPC Matchpoin**t: Sistema integral tradicional (ERP/CRM) enfocado en grandes centros deportivos. Ofrece un abanico extenso de módulos administrativos, soportado sobre una arquitectura de software clásica.  
3. **Doinsport**: Plataformas SaaS enfocadas en la gestión de reservas deportivas y domótica de instalaciones (control de luces y accesos), comercializadas mediante modelos de suscripción mensual recurrentes.

**ANÁLISIS COMPARATIVO**

* **Coste de Implantación**:  
  * *Playtomic Manager* y *Doinsport* aplican modelos de cobro basados en suscripciones mensuales por pista o comisiones porcentuales sobre cada reserva gestionada.  
  * *TPC Matchpoint* requiere desembolsos elevados en licencias iniciales, mantenimiento y despliegue de infraestructura propia.  
  * *PadelSlot* elimina el coste de licenciamiento e infraestructura al ejecutarse sobre arquitecturas Cloud en modalidad *Free Tier*, maximizando la viabilidad económica en proyectos de demostración o clubes de tamaño pequeño y medio.  
* **Curva de Aprendizaje y Usabilidad**:  
  * *TPC Matchpoint* presenta una interfaz densa de tipo ERP tradicional que demanda formación continua para el personal.  
  * *Playtomic* ofrece usabilidad fluida para el jugador pero restringe la personalización corporativa del club.  
  * *PadelSlot* integra un *Design System* unificado en Figma con cumplimiento de pautas de accesibilidad WCAG 2.1 y la librería *Lucide Icons*, garantizando una interfaz intuitiva con curva de aprendizaje casi nula para administradores y usuarios.  
* **Capacidad Multiplataforma**:  
  * *TPC Matchpoint* depende de clientes de escritorio en Windows para la administración.  
  * *Playtomic* y *Doinsport* requieren la instalación de aplicaciones nativas desde tiendas oficiales (App Store / Google Play).  
  * *PadelSlot* está concebida como una Web App responsive con diseño *Mobile-First*, accesible al instante desde cualquier sistema operativo (Windows, Linux, macOS, iOS, Android) a través de un navegador web sin obligar a descargas previas.  
* **Extensibilidad y Limitaciones Detectadas**:  
  * Las alternativas comerciales ofrecen módulos cerrados donde añadir servicios complementarios incrementa la tarifa mensual.  
  * *PadelSlot* proporciona una estructura modular SaaS parametrizable, permitiendo a cada club activar o desactivar según sus necesidades físicas el control de parking con QR, el TPV para bar/tienda, la escuela de pádel o la bolsa de empleo.

**MATRIZ COMPARATIVA**

| Parámetro Evaluado | Playtomic Manager | TPC Matchpoint | Doinsport | PadelSlot (Propuesta) |
| ----- | ----- | ----- | ----- | ----- |
| Modelo de Licencia / Precio | Suscripción \+ Comisiones por reserva | Licencia inicial \+ Mantenimiento | Cuota fija mensual por pista | SaaS Gratuito (0,00 € en Free Tier) |
| Arquitectura Multiplataforma | App Nativa (iOS/Android) \+ Web | App Escritorio (Windows) \+ Intranet | App Nativa \+ Portal Web | Web App Responsive (Cualquier SO/Navegador) |
| Experiencia de Usuario (UI/UX) | Alta para jugador / Media para club | Baja (interfaz densa de tipo ERP) | Media-Alta | Alta (Design System, WCAG 2.1, Mobile-First) |
| Modularidad /Extensibilidad | Rígida (centrada en reserva) | Alta (a elevado coste por módulo) | Media (opciones prefijadas) | Alta (Módulos: Parking, TPV Bar, Tienda, Empleo) |
| Control de Accesos / QR | Integración externa de pago | Módulos de hardware dedicados | Integración domótica propia | Generación nativa de códigos QR para parking y pistas |
| TPV Integrado (Bar/Tienda) | No (orientado a reservas) | Sí (módulo ERP independiente) | Sí (POS de caja básico) | Sí (TPV/POS unificado para alquileres, tienda y bar) |
| Generación de Informes | Estándar sobre ocupación | Completa pero compleja | Estadísticas comerciales | Consolidada en panel administrativo centralizado |

**JUSTIFICACIÓN DE LA PROPUESTA**

La ventaja competitiva de PadelSlot radica en su capacidad para ofrecer un ecosistema SaaS integral y parametrizable que elimina las barreras financieras y técnicas del software comercial, reemplazando las elevadas comisiones por reserva o licencias rígidas de competidores como Playtomic o TPC Matchpoint por una plataforma Web App con coste cero en infraestructura Cloud. Frente a las interfaces complejas o fragmentadas del software tradicional, PadelSlot combina un diseño Mobile-First accesible con una arquitectura cliente-servidor desacoplada, la cual permite gestionar de manera unificada la reserva autónoma en menos de tres clics, el TPV presencial para la cafetería y tienda de material, el control de accesos mediante código QR y el motor de tarifas dinámicas para socios e invitados. Esta integración proporciona a los clubes de tamaño medio una herramienta autónoma, escalable y libre de comisiones de terceros que maximiza los ingresos del centro y optimiza la experiencia del cliente.

## 2.4. Partes interesadas (Stakeholders) {#2.4.-partes-interesadas-(stakeholders)}

Los **stakeholders** son todas aquellas personas, grupos o entidades que influyen en el proyecto o se ven afectados por él, diferenciando partes interesadas internas y externas. Para cada una se analizan sus expectativas y su grado de poder e interés. Esto permite clasificarlas en una matriz y definir la estrategia de comunicación más adecuada:

* **Gestionar de cerca**: quienes tienen alto poder y alto interés  
* **Mantener satisfechos**: quieren tienen alto poder pero poco interés  
* **Mantener informados**: quienes tienen alto interés pero poco poder  
* **Monitorizar**: el resto

**IDENTIFICACIÓN DE LAS PARTES INTERESADAS**

Partes interesadas internas

* **Equipo de desarrollo**: los 4 integrantes del grupo. Planifican, diseñan, desarrollan, despliegan y mantienen PadelSlot.

Partes interesadas externas

* **Propietario o gerente del club**: cliente principal (Buyer Persona). Decide contratar la plataforma y configura el club, las tarifas y los módulos.  
* **Personal administrativo del club (recepción)**: usuarios operativos del panel de administración.  
* **Personal indirecto del club**: monitores, mantenimiento, cafetería y tienda. Su trabajo se organiza a través de la aplicación.  
* **Público general**: jugadores ocasionales que consultan y reservan pistas.  
* **Socios**: usuarios recurrentes del portal de clientes.  
* **Organismos reguladores**: Agencia Española de Protección de Datos (AEPD), encargada de velar por el cumplimiento del Reglamento General de Protección de Datos (RGPD) y la Ley Orgánica de Protección de Datos Personales y Garantía de los Derechos Digitales (LOPDGDD).  
* **Proveedores tecnológicos**: Supabase (base de datos, *storage* y autenticación), Vercel (alojamiento y despliegue) y la pasarela de pago en modo de prueba.  
* **Competidores**: Playtomic Manager, TPC Matchpoint y Doinsport.  
* **Candidatos a empleo**: personas externas que envían su candidatura a través de la bolsa de empleo.

**MATRIZ DE INTERESADOS**

| Rol / Grupo | Tipo | Expectativas principales | Poder | Interés | Estrategia de comunicación |
| :---- | :---- | :---- | :---- | :---- | :---- |
| Equipo de desarrollo | Interno | Entregar una aplicación funcional, segura y bien documentada en los plazos de cada sprint | Alto | Alto | Reuniones semanales de seguimiento, proyectos en GitHUb y revisión al cierre de cada sprint |
| Propietario / gerente del club | Externo | Aumentar la ocupación, reducir la carga administrativa y fidelizar socios con un menor coste | Alto | Alto | Reuniones periódicas, demostraciones de cada versión y validación de requisitos y tarifas |
| Personal administrativo del club (recepción) | Externo | Gestionar reservas, cobros y socios de forma rápida y sin errores | Bajo | Alto | Demostraciones de la interfaz, formación inicial, manual de usuario y recogida de *feedback* |
| Personal indirecto del club | Externo | Organizar adecuadamente las clases, turnos y ventas | Bajo | Medio | Comunicacion a traves de la gerencia del club |
| Público general | Externo | Consultar disponibilidad y precios, y reservar en pocos pasos | Bajo | Alto | Información clara en el portal público y confirmaciones automáticas de reserva |
| Socios | Externo | Reservar fácilmente con su tarifa, consultar sus ventajas e inscribirse en clases y torneos | Bajo | Alto | Avisos en la aplicación, correo electrónico y canal de sugerencias |
| AEPD (organismo regulador) | Externo | Cumplimiento del RGPD y la LOPDGDD en el tratamiento de los datos personales | Alto | Bajo | Documentar las medidas de privacidad (consentimiento, *hashing*, control de accesos y política de retención) |
| Proveedores tecnológicos | Externo | Uso de sus servicios conforme a sus condiciones y límites del *Free Tier* | Medio | Bajo | Revisión periódica de sus cuotas, condiciones y cambios de servicio |
| Competidores | Externo | Mantener su cuota de mercado | Bajo | Bajo | Seguimiento de sus novedades y precios en el estudio de mercado |
| Candidatos a empleo | Externo | Enviar su candidatura de forma sencilla | Bajo | Bajo | Canal de consulta abierto en la sección pública de empleo |

**RESUMEN DE LA MATRIZ**

|  | Interés alto | Interés bajo |
| :---- | :---- | :---- |
| **Poder alto** | **Gestionar de cerca**: equipo de desarrollo y propietario / gerente del club | **Mantener satisfechos**: AEPD |
| **Poder bajo** | **Mantener informados**: recepción, socios, público general y personal indirecto | **Monitorizar**: proveedores tecnológicos, competidores y candidatos a empleo |

## 2.5. Estudio de viabilidad técnica {#2.5.-estudio-de-viabilidad-técnica}

El estudio de viabilidad técnica tiene como objetivo comprobar que el equipo de desarrollo dispone de los conocimientos, herramientas, equipos e infraestructura necesarios para desarrollar, integrar y desplegar la plataforma PadelSlot de forma adecuada.

El equipo dispone de ordenadores personales para las tareas de programación, diseño, documentación y pruebas, además de  conexión a Internet para utilizar los servicios y herramientas online del proyecto.

En cuanto al software utilizado, hemos seleccionado herramientas que ya conocemos y que no requieren inversión inicial, tales como Visual Studio Code para el desarrollo, Github para versionado y control así como colaboración entre los integrantes, Figma para el diseño etc.

La infraestructura planteada también resulta adecuada para las características del proyecto, ya que PadelSlot se ha diseñado como una aplicación web responsive, por lo que los usuarios podrán acceder a ella desde diferentes dispositivos mediante un navegador web. 

**PILA TECNOLÓGICA (TECH STACK)**

Para el desarrollo de PadelSlot se ha seleccionado una pila tecnológica basada principalmente en  **JavaScript**, ya que son lenguajes con los que el equipo de desarrollo ya tiene experiencia. Esto permite reducir la curva de aprendizaje y facilita el desarrollo del proyecto dentro del tiempo disponible.

**JavaScript** se utilizará como uno de los lenguajes principales para la parte lógica y de servidor de la aplicación. Su elección se debe principalmente a que es un lenguaje conocido por los miembros del equipo y permite desarrollar aplicaciones estructuradas y mantenibles.También se utilizará para el desarrollo de la parte cliente de la aplicación y para proporcionar interactividad a las diferentes funcionalidades de la plataforma. 

Al tratarse de una tecnología ampliamente utilizada en el desarrollo web y conocida por el equipo, permite trabajar de forma adecuada con las necesidades de una aplicación web responsive.

Para la gestión de la información se utilizará un sistema gestor de bases de datos relacional. Se trabajará con **SupaBase**, contando que ya se tienen conocimientos en consultas SQL, tablas, relaciones y gestión de datos podrán aplicarse al proyecto.

Como entorno de desarrollo se utilizará **Visual Studio Code**, que permitirá trabajar con el código del proyecto y utilizar extensiones destinadas al desarrollo y comprobación del código.

El control de versiones se realizará mediante **GitHub**, permitiendo que los integrantes del equipo puedan trabajar de forma colaborativa y mantener un historial de los cambios realizados. Además, **GitHub Projects** se utiliza para organizar y realizar el seguimiento de las tareas del proyecto.

Para el diseño de las interfaces se ha utilizado **Figma**, donde se han creado los prototipos y elementos del sistema de diseño. También se utilizará **Lucide Icons** para incorporar iconos a la interfaz.

Finalmente, para el despliegue de la aplicación se utilizará **Vercel**, aprovechando las posibilidades de su plan gratuito durante el desarrollo académico. Estas tecnologías permiten aprovechar los conocimientos previos del equipo, reducir el tiempo necesario para aprender nuevas herramientas y disponer de un entorno suficiente para desarrollar, probar y desplegar el proyecto.

**REQUISITOS DE HARDWARE Y DESPLIEGUE**

Para comprobar la viabilidad técnica de PadelSlot es necesario analizar tanto los equipos utilizados por el equipo de desarrollo como los dispositivos desde los que accederán los usuarios a la aplicación.

\- Equipos de desarrollo

Los integrantes del proyecto utilizarán sus equipos personales para realizar las tareas de programación, diseño, documentación, pruebas y gestión del proyecto. Estos equipos deberán disponer de unas características suficientes para ejecutar el entorno de desarrollo, las herramientas utilizadas y los servicios necesarios durante la fase de desarrollo.

Como requisitos mínimos para los equipos de desarrollo se establece:

| Componente | Requisito mínimo |
| ----- | ----- |
| Procesador | Procesador de 4 núcleos o equivalente |
| Memoria RAM | 8 GB |
| Almacenamiento | 20 GB de espacio libre |
| Conexión a Internet | Necesaria para GitHub, Figma, Supabase y servicios de despliegue |
| Gráficos | Gráficos integrados suficientes para las herramientas utilizadas |

Estas características permiten trabajar con Visual Studio Code, Git, GitHub, Figma y las herramientas necesarias para el desarrollo de la aplicación. Estas características se han establecido haciendo una comparación de los equipos personales de los  integrantes del equipo de desarrollo

\- Equipos clientes

PadelSlot se plantea como una aplicación web responsive, por lo que los usuarios no necesitarán instalar un programa específico en sus dispositivos. El acceso se realizará mediante un navegador web compatible.

Los requisitos mínimos previstos para los dispositivos cliente son:

| Componente | Requisito mínimo |
| ----- | ----- |
| Procesador | Cualquier procesador compatible con un navegador web moderno |
| Memoria RAM | 4 GB |
| Gráficos | Gráficos integrados suficientes para representar la interfaz |

No será necesaria una aceleración gráfica dedicada, ya que la aplicación no está destinada a realizar tareas de procesamiento gráfico avanzado. La interfaz estará diseñada para adaptarse a diferentes tamaños de pantalla siguiendo un enfoque responsive y Mobile-First.

**DESPLIEGUE**

La infraestructura planteada contempla el uso de **Vercel** para el despliegue de la aplicación y **SupaBase** como sistema gestor de base de datos.

Esta arquitectura permite separar los equipos utilizados durante el desarrollo de los dispositivos de los usuarios finales. Los desarrolladores necesitarán las herramientas de programación y desarrollo correspondientes, mientras que los clientes únicamente necesitarán un dispositivo con un navegador compatible y conexión a Internet.

**CURVA DE APRENDIZAJE Y MADUREZ TÉCNICA** 

La selección de las tecnologías para el desarrollo de PadelSlot se ha realizado teniendo en cuenta los **conocimientos previos del equipo**. Al tratarse de un proyecto desarrollado durante el ciclo de Desarrollo de Aplicaciones Web, se ha intentado utilizar principalmente tecnologías que ya han sido trabajadas durante la formación.

El equipo cuenta con conocimientos previos de JavaScript y SQL, por lo que no será necesario realizar un periodo de formación inicial para comenzar el desarrollo. En el caso de la base de datos, el equipo no ha trabajado anteriormente con SupaBase, dispone de conocimientos sobre bases de datos relacionales, consultas, tablas y relaciones pero con Oracle así que habrá que dedicarle un breve periodo de tiempo a su conocimiento

También existe experiencia previa con herramientas como Visual Studio Code, Git, GitHub y Figma. Esto facilita su incorporación al proyecto y permite que el equipo pueda centrarse principalmente en el desarrollo de las funcionalidades de PadelSlot.

A pesar de estos conocimientos previos, algunas partes del proyecto pueden requerir un periodo de autoformación. Principalmente, será necesario profundizar en aquellas librerías, frameworks o herramientas que se incorporen durante el desarrollo y que no hayan sido utilizadas anteriormente. Esta formación se realizará mediante documentación oficial, tutoriales y pruebas prácticas.

En cuanto a la madurez técnica, las tecnologías seleccionadas son herramientas consolidadas y ampliamente utilizadas en el desarrollo de aplicaciones, por lo que se consideran adecuadas para un proyecto de estas características.

Por tanto, la curva de aprendizaje prevista se considera **baja o moderada**, ya que la mayor parte de las tecnologías principales son conocidas por el equipo. 

**FICHA TÉCNICA DEL STACK DE DESARROLLO Y ENTORNO DE EJECUCIÓN**

A continuación se recoge una ficha técnica con las principales tecnologías y herramientas previstas para el desarrollo y ejecución de PadelSlot:

| Elemento | Tecnología / herramienta | Función |
| ----- | ----- | ----- |
| Lenguaje de programación | JavaScript | Desarrollo de la parte cliente e interactividad |
| Base de datos | Supabase | Almacenamiento y gestión de los datos |
| Entorno de desarrollo | Visual Studio Code | Desarrollo y edición del código |
| Control de versiones | Git / GitHub | Gestión de versiones y trabajo colaborativo |
| Gestión del proyecto | GitHub Projects | Organización y seguimiento de tareas |
| Diseño UI/UX | Figma | Prototipos, diseño de interfaces y Design System |
| Iconografía | Lucide Icons | Iconos de la interfaz |
| Despliegue | Vercel | Despliegue de la aplicación |
| Cliente | Navegador web | Acceso de los usuarios a la aplicación |

El entorno de ejecución estará basado en una aplicación web responsive, por lo que los usuarios podrán acceder a PadelSlot desde ordenadores, tablets y smartphones mediante un navegador compatible. No será necesario instalar una aplicación específica en el dispositivo del usuario.

**CONCLUSIÓN**

Después de analizar los recursos disponibles, el equipo dispone de conocimientos previos en tecnologías como JavaScript además de experiencia con herramientas de desarrollo, control de versiones y diseño. Esto permite reducir la curva de aprendizaje y facilita la puesta en marcha del proyecto.

La infraestructura necesaria tampoco requiere equipos de altas prestaciones para los usuarios finales, ya que PadelSlot será una aplicación web responsive. 

Aunque durante el desarrollo será necesario adquirir conocimientos sobre algunas herramientas o librerías que todavía no hayan sido utilizadas por todos los integrantes, se considera que este aprendizaje puede realizarse dentro del tiempo disponible mediante autoformación y documentación técnica.

Por todo ello, se concluye que **PadelSlot puede ser desarrollado, integrado, probado y desplegado con los recursos técnicos disponibles**, manteniéndose dentro del alcance y las limitaciones establecidas para el proyecto académico.

## 

## 2.6.Estudio de viabilidad económica {#2.6.estudio-de-viabilidad-económica}

El estudio de viabilidad económica tiene como objetivo analizar los costes y los recursos financieros necesarios para desarrollar, implantar y mantener la plataforma PadelSlot. De esta forma, se pretende comprobar que los recursos económicos previstos son suficientes para llevar a cabo el proyecto y que la solución resulta económicamente sostenible.

Para realizar este estudio se tendrán en cuenta los costes asociados al desarrollo de la aplicación, incluyendo los recursos humanos necesarios para su elaboración, así como los costes de infraestructura, software, servicios y licencias utilizados durante el proyecto.

También se analizarán los costes indirectos derivados del desarrollo y mantenimiento de la aplicación, como la electricidad, la conectividad y el posible soporte técnico posterior al despliegue.

Finalmente, se elaborará un presupuesto desglosado de las diferentes partidas y se realizará una valoración del posible retorno de la inversión o del ahorro de costes operativos que PadelSlot puede proporcionar a la entidad usuaria.

**ESTIMACIÓN DE COSTES DE DESARROLLO**

Para la estimación económica del proyecto se ha establecido una tarifa de referencia de **20 €/hora** para un perfil de desarrollador junior. Esta cifra se utiliza como estimación de coste de personal del proyecto y se contrasta con las tablas salariales del **XIX Convenio colectivo estatal de empresas de consultoría, tecnologías de la información y estudios de mercado**, publicado en el BOE y actualizado para 2026\. 

El equipo está formado por 4 integrantes, con una dedicación estimada de  **600 horas de trabajo** para la realización completa del proyecto.

La distribución estimada del trabajo y su coste es la siguiente:

| Fase | Horas estimadas | Coste |
| ----- | ----- | ----- |
| Análisis, investigación y UX | 105 h | 2.100,00 € |
| Diseño UI, sistema de diseño y prototipado | 95 h | 1.900,00 € |
| Desarrollo software (Front-end y Back-end) | 280 h | 5.600,00 € |
| Pruebas, optimización y documentación técnica | 120 h | 2.400,00 € |
| **Total** | **600 h** | **12.000,00 €** |

La fase con mayor dedicación corresponde al **desarrollo software**, con 280 horas, debido a la implementación de las funcionalidades de la plataforma, la gestión de reservas, la base de datos y la integración de los diferentes módulos.

Por tanto, el **coste estimado de los recursos humanos necesarios para desarrollar PadelSlot es de 12.000,00 €**.

**COSTES DE INFRAESTRUCTURA Y LICENCIAS**

Para el desarrollo e implantación de PadelSlot se han seleccionado herramientas y servicios que permiten reducir los costes de infraestructura y licencias. Se prioriza el uso de software gratuito, soluciones Open Source, planes gratuitos de servicios Cloud y licencias educativas.

En cuanto al **hardware**, el desarrollo se realizará utilizando los equipos informáticos disponibles por los integrantes del equipo. Al tratarse de equipos de uso general, no es necesario adquirir hardware específico para el proyecto. No obstante, para realizar una estimación económica completa se contempla la amortización del hardware utilizado durante el periodo de desarrollo.

En relación con el **software y las herramientas de desarrollo**, se utilizarán principalmente soluciones gratuitas o incluidas en programas educativos:

| Recurso | Uso | Coste |
| ----- | ----- | ----- |
| Visual Studio Code | Desarrollo de la aplicación | 0,00 € |
| Git / GitHub | Control de versiones y trabajo colaborativo | 0,00 € |
| GitHub Projects | Gestión y planificación del proyecto | 0,00 € |
| Figma | Diseño y prototipado de interfaces | 0,00 € |
| Google Workspace / Drive | Documentación y almacenamiento | 0,00 € |
| Lucide Icons / Heroicons | Iconografía | 0,00 € |
| Google Fonts | Tipografías | 0,00 € |
| Supabase | Gestión de la base de datos | Pendiente de concretar según licencia/entorno utilizado |
| Vercel | Despliegue de la aplicación | 0,00 €\* |

Se utilizará el plan gratuito disponible durante el desarrollo académico, siempre que sea suficiente para las necesidades del proyecto.

Por tanto, la estrategia adoptada permite mantener unos costes de software e infraestructura reducidos, aprovechando herramientas gratuitas, Open Source y licencias educativas. Los posibles costes adicionales se cubrirán mediante la partida destinada a contingencias e imprevistos.

**COSTES INDIRECTOS Y MANTENIMIENTO**

Durante el desarrollo y posterior despliegue de PadelSlot también se tendrán en cuenta determinados costes indirectos relacionados con el uso de los equipos, la conexión a Internet y la puesta en funcionamiento de la aplicación.

En primer lugar, se estima un coste aproximado de **20,00 € mensuales en electricidad** asociado al uso de los equipos informáticos utilizados por los cuatro integrantes del equipo para realizar las tareas de programación, diseño, documentación y pruebas. Teniendo en cuenta que el desarrollo del proyecto tendrá una duración aproximada de **5 meses**, el coste estimado será de **100,00 €**.

En cuanto a la **conectividad a Internet**, se establece un coste medio de **25,00 € mensuales por integrante**, suponiendo un coste total de **100,00 € mensuales para los cuatro integrantes**. Durante los 5 meses de desarrollo, el coste total del servicio sería de **500,00 €**.

Sin embargo, no todo el uso de la conexión a Internet está destinado al proyecto, ya que también se utiliza para fines personales. Por este motivo, se estima que aproximadamente un **30 % del coste**, equivalente a **150,00 €**, corresponde al uso relacionado con PadelSlot. Esta conexión será necesaria para utilizar herramientas como GitHub, Figma, servicios de desarrollo, repositorios y plataformas de despliegue.

También se contempla la adquisición de un dominio propio para el despliegue de la aplicación. Como referencia, IONOS ofrece actualmente dominios .es desde 1,00 € durante el primer año, sin IVA, por lo que se establece una partida presupuestaria de 5,00 € para cubrir el registro del dominio y posibles pequeñas variaciones de precio.

| Concepto | Coste estimado |
| :---- | :---- |
| Electricidad | 100,00 € |
| Conectividad a Internet | 150,00 € |
| Dominio web | 5,00 € |
| Total costes indirectos | 255,00 € |

El mantenimiento externo se establece inicialmente en **0,00 €**, ya que las tareas de mantenimiento previstas serán asumidas por el propio equipo del proyecto. En caso de que PadelSlot se implantase posteriormente en un entorno empresarial real, sería necesario realizar una nueva estimación en función del nivel de soporte y mantenimiento requerido.

**PRESUPUESTO DESGLOSADO**

El presupuesto de PadelSlot se ha elaborado teniendo en cuenta los costes de personal, infraestructura, software, servicios y contingencias necesarios para llevar a cabo el proyecto durante los cinco meses estimados de desarrollo.

| Partida | Concepto | Coste |
| ----- | ----- | ----- |
| Personal | 600 horas de desarrollo × 20 €/hora | 12.000,00 € |
| Software/Servicios | Electricidad | 100,00 € |
| Software/Servicios | Conectividad a Internet imputada al proyecto | 150,00 € |
| Software/Servicios | Dominio web | 5,00 € |
| Software/Servicios | Herramientas gratuitas, Open Source y licencias educativas | 0,00 € |
| Contingencias | Fondo para imprevistos técnicos | 50,00 € |
| **TOTAL** |  | 12.305,00 € |

Por tanto, el coste económico estimado para la realización completa del proyecto asciende a **12.305,00 €**.

**ANÁLISIS DEL RETORNO DE LA INVERSIÓN (ROI)**

Para realizar una estimación económica del posible retorno de PadelSlot se plantea un escenario orientativo basado en el ahorro de tiempo que puede producir la automatización de determinadas tareas administrativas relacionadas con la gestión de reservas, usuarios y disponibilidad de pistas.

Se estima que la utilización de la plataforma podría ahorrar aproximadamente **5 horas semanales** de trabajo administrativo. Tomando como referencia un coste de **20,00 €/hora**, utilizado también para calcular el coste de desarrollo del proyecto, el ahorro estimado sería:

5 horas/semana × 52 semanas \= 260 horas/año

260 horas × 20,00 €/hora \= 5.200,00 €/año

Por tanto, se estima un ahorro operativo aproximado de **5.200,00 € al año**, equivalente a **433,33 € mensuales**. El coste total estimado del proyecto es de **12.305,00 €**. Comparando esta inversión inicial con el ahorro anual previsto, se obtiene la siguiente evolución:

| Periodo | Ahorro acumulado | Inversión acumulada | Resultado |
| ----- | ----- | ----- | ----- |
| Año 1 | 5.200 € | 12.305 € | \-7.105 € |
| Año 2 | 10.400 € | 12.305 € | \-1.905 € |
| Año 3 | 15.600 € | 12.305 € | \+3.295 € |

El punto de recuperación de la inversión se alcanzaría aproximadamente a los **28-29 meses**. Si se calcula el ROI al finalizar el tercer año:

ROI \= (15.600 € \- 12.305 €) / 12.305 € × 100 \= 26,78 %

Por tanto, bajo esta estimación, PadelSlot podría generar un **ROI aproximado del 26,78 % al finalizar el tercer año**, además de proporcionar beneficios no directamente cuantificados, como una mejor organización de las reservas, reducción de errores, centralización de la información y mejora de la experiencia de los usuarios.

Esta estimación es orientativa, ya que las horas de trabajo administrativo ahorradas deberán comprobarse con datos reales una vez implantada la plataforma.

## 2.7 Estudio de viabilidad legal y normativa {#2.7-estudio-de-viabilidad-legal-y-normativa}

En este apartado analizamos las leyes que afectan a PadelSlot y cómo las vamos a tener en cuenta en el diseño de la aplicación. Como PadelSlot es un software que contratan los clubes para gestionar a sus propios socios y clientes, cada club es el responsable de los datos de sus usuarios. PadelSlot actúa como encargado del tratamiento, es decir, trata esos datos por cuenta del club.

**PROTECCIÓN DE DATOS PERSONALES**

La aplicación guarda datos personales de los usuarios, como el nombre, el correo, el teléfono, las reservas, los pagos o la matrícula del coche. Por ello debe cumplir el Reglamento General de Protección de Datos (RGPD) \[5\] y la Ley Orgánica 3/2018 de Protección de Datos (LOPDGDD) \[6\].

Las principales medidas que vamos a aplicar son las siguientes:

Datos mínimos y base legal. Solo se pedirán los datos necesarios para cada función y cada dato tendrá una base legal. Por ejemplo, para gestionar una reserva la base es el contrato, y para enviar publicidad hace falta el consentimiento del usuario. No guardaremos datos de salud, porque son especialmente protegidos y no los necesitamos.  
Contrato con cada club. Como PadelSlot trata los datos por cuenta del club, firmará con cada uno un contrato de encargo del tratamiento, tal y como exige el artículo 28 del RGPD \[7\].  
Seguridad. Las comunicaciones irán por HTTPS, las contraseñas se guardarán cifradas y los permisos dependerán del rol (invitado, socio o administrador). Además, cada club solo podrá ver sus propios datos y nunca los de otro club.  
Derechos del usuario. El usuario podrá consultar, corregir o borrar sus datos desde su perfil.  
Menores. En la escuela de pádel puede haber alumnos menores de edad. Si el alumno tiene menos de 14 años, el consentimiento debe darlo su padre, madre o tutor \[8\], así que el formulario de inscripción pedirá los datos del tutor.  
Parking. La Agencia Española de Protección de Datos considera la matrícula de un vehículo un dato personal \[9\]. Las imágenes de las cámaras se borrarán como máximo al mes, como marca el artículo 22 de la LOPDGDD , y el club deberá avisar con carteles de que existe ese sistema.  
Ubicación de los datos. La base de datos estará alojada en servidores de la Unión Europea.

**SERVICIOS DE LA SOCIEDAD DE LA INFORMACIÓN Y COOKIES** 

Al ser un servicio que se presta por internet, PadelSlot debe cumplir la Ley 34/2002 de Servicios de la Sociedad de la Información (LSSI) . Esto implica tres cosas:

Tener un aviso legal con los datos de la empresa.  
Enviar una confirmación al usuario después de cada reserva.  
No enviar publicidad por correo a quien no lo haya aceptado expresamente.

En cuanto a las cookies, la guía de la AEPD actualizada en 2023 exige que el botón de rechazarlas sea igual de visible que el de aceptarlas . Por ahora PadelSlot solo usará cookies técnicas, como las de sesión, que no necesitan consentimiento. Si más adelante añadimos herramientas de analítica, pondremos un aviso de cookies con ambos botones.

**PROTECCIÓN DE LOS CONSUMIDORES Y PAGOS**

Cuando un jugador reserva y paga una pista está haciendo una compra a distancia. Por eso se aplica la Ley General para la Defensa de los Consumidores y Usuarios . Antes de pagar, el usuario debe ver el precio final y la política de cancelación del club.

Esta ley da normalmente 14 días para echarse atrás en una compra online. Sin embargo, el artículo 103 excluye los servicios de ocio con una fecha concreta  y la reserva de una pista para un día y una hora determinados entra en esa excepción. Por eso las cancelaciones se regirán por la política que configure cada club en la aplicación.

Para los pagos usaremos una pasarela de pago externa y autorizada. De esta forma, PadelSlot no guarda los datos de las tarjetas ni recibe el dinero de los clubes. Si lo hiciera, la ley de servicios de pago le exigiría una autorización especial\].

El monedero virtual solo se podrá usar dentro del club que lo emite, porque así queda fuera de esa regulación \[9\]. Durante el proyecto, todos los pagos se harán en modo de prueba, sin dinero real.

El módulo de caja (TPV) solo generará justificantes internos y no facturas oficiales. Si en el futuro emitiera facturas, tendría que adaptarse al sistema Verifactu de Hacienda, que será obligatorio para las empresas a partir de 2027\.

**ACCESIBILIDAD**

Desde junio de 2025, la Ley 11/2023 obliga a que los servicios de venta online dirigidos a consumidores sean accesibles \[9\], aunque las microempresas quedan exentas. Como PadelSlot quiere servir a clubes de cualquier tamaño, nos marcamos como objetivo cumplir el nivel AA de las pautas WCAG 2.1 \[10\]. Esto supone cuidar el contraste de colores, permitir la navegación con teclado, etiquetar bien los formularios y que la aplicación funcione con lectores de pantalla.

**PROPIEDAD INTELECTUAL Y LICENCIAS**

El código de PadelSlot está protegido por la Ley de Propiedad Intelectual como obra de los cuatro miembros del equipo. Los recursos de terceros que usamos tienen licencias libres que permiten su uso comercial, siempre que se mencione a sus autores:

* Las fuentes Inter y Space Grotesk, con licencia SIL Open Font License.  
* Los iconos Phosphor y Lucide, con licencias MIT e ISC.  
* Los iconos Material Symbols, con licencia Apache 2.0.  
* Tailwind CSS, con licencia MIT.

**CONDICIONES DE LOS SERVICIOS EN LA NUBE** 

Los planes gratuitos que usamos tienen límites que también son legales:

* **Supabase**: El plan gratuito no incluye copias de seguridad automáticas y pausa el proyecto tras una semana sin uso , así que tendremos que hacer copias de seguridad nosotros mismos.  
* **Vercel**: El plan gratuito solo permite un uso personal y no comercial \[11\]. Sirve para el proyecto académico, pero si PadelSlot se comercializara habría que pasar a un plan de pago.

**CONCLUSIÓN**

PadelSlot es legalmente viable. Ninguna ley impide desarrollarlo, pero varias nos obligan a tomar decisiones desde el principio:

* Proteger bien los datos y separar los de cada club.  
* No guardar tarjetas ni dinero, y dejar los pagos en manos de una pasarela autorizada.  
* Informar al usuario antes de pagar.  
* Cuidar la accesibilidad de la aplicación.

## 2.8 Análisis de riesgos inicial {#2.8-análisis-de-riesgos-inicial}

**R-01: Desviación en la Estimación de Horas (Técnico)**

Medida Preventiva: Asignación de reuniones de seguimiento (daily/weekly) al inicio y final de cada Sprint para controlar el avance real frente al planificado. 

**R-02: Superación de Límites del Plan Gratuito (Infraestructura)**

Medida Preventiva: Optimización de consultas PostgreSQL, limpieza periódica de datos de prueba no necesarios y compresión de activos multimedia. 

**R-03: Vulnerabilidades y Accesos No Autorizados (Seguridad)**

Medida Preventiva: Implementación de autenticación mediante tokens JWT, control de accesos basado en roles (RBAC), sanitización estricta de formularios e implementación de HTTPS en el despliegue. 

**R-04: Incumplimiento del RGPD (Normativo)**

Medida Preventiva: Cifrado obligatorio de contraseñas (hashing mediante algoritmos seguros como Bcrypt), inclusión de casillas de verificación de política de privacidad en registros y limitación en la recogida de datos personales estrictamente necesarios. 

**R-05: Pérdida o Corrupción de la Base de Datos (Operativo)**

Medida Preventiva: Configuración de copias de seguridad automáticas (backups) en la plataforma Supabase y exportación semanal de un script DDL/DML con la estructura y datos de prueba. 

**R-06: Bajas Temporales en el Equipo de Trabajo (Operativo)**

Medida Preventiva: Documentación exhaustiva del código, uso estricto de control de versiones (Git/GitHub) y estandarización del sistema de diseño en Figma para que cualquier integrante pueda continuar la tarea de otro. 

# REFERENCIAS IEEE {#referencias-ieee}

\[1\] Padel Addict, “FIP World Padel Report 2025: así son las cifras globales del pádel,” *Padel Addict*, 2025\. \[En línea\]. Disponible en: [https\://www\.padeladdict.com/fip-world-padel-report-2025-cifras-globales-del-padel/](https://www.padeladdict.com/fip-world-padel-report-2025-cifras-globales-del-padel/) \[Consultado: 31/10/2026\].

\[2\] International Padel Federation (FIP), “Pádel en España, crecimiento de pistas y licencias de jugadores en 2024\. Morcillo: ‘Estos resultados reflejan el trabajo duro de los últimos años’,” *padelfip.com*, 27/02/2025. \[En línea\]. Disponible en: [https\://www\.padelfip.com/es/2025/02/padel-en-espana-crecimiento-de-pistas-y-licencias-de-jugadores-en-2024-morcillo-estos-resultados-reflejan-el-trabajo-duro-de-los-ultimos-anos/](https://www.padelfip.com/es/2025/02/padel-en-espana-crecimiento-de-pistas-y-licencias-de-jugadores-en-2024-morcillo-estos-resultados-reflejan-el-trabajo-duro-de-los-ultimos-anos/) \[Consultado: 31/10/2026\].

\[3\] Arab News, “Padel moves into the sporting mainstream,” *Arab News*, 2025\. \[En línea\]. Disponible en: [https\://www\.arabnews.com/sport/padel-moves-into-the-sporting-mainstream-2605902](https://www.arabnews.com/sport/padel-moves-into-the-sporting-mainstream-2605902) \[Consultado: 31/11/2026\].

\[4\] Playtomic y PwC Strategy&, “Global Padel Report 2026,” *Playtomic*, 2026\. \[En línea\]. Disponible en: [https\://playtomic.com/global-padel-report](https://playtomic.com/global-padel-report) \[Consultado: 31/11/2026\]. 

\[5\] Parlamento Europeo y Consejo de la Unión Europea, “Reglamento (UE) 2016/679, de 27 de abril de 2016, relativo a la protección de las personas físicas en lo que respecta al tratamiento de datos personales y a la libre circulación de estos datos (Reglamento general de protección de datos),” *Diario Oficial de la Unión Europea*, L 119, pp. 1–88, 4 may. 2016\. \[En línea\]. Disponible en: [https\://eur-lex.europa.eu/eli/reg/2016/679/oj?locale=es](https://eur-lex.europa.eu/eli/reg/2016/679/oj?locale=es). \[Accedido: 6 nov. 2026\].

\[6\] España, “Ley Orgánica 3/2018, de 5 de diciembre, de Protección de Datos Personales y garantía de los derechos digitales,” *Boletín Oficial del Estado*, núm. 294, 6 dic. 2018\. \[En línea\]. Disponible en: [https\://www\.boe.es/buscar/act.php?id=BOE-A-2018-16673](https://www.boe.es/buscar/act.php?id=BOE-A-2018-16673). \[Accedido: 6 nov. 2026\].

\[7\] Agencia Española de Protección de Datos, *Guía sobre el uso de las cookies*, Madrid, España: AEPD, may. 2024\. \[En línea\]. Disponible en: [https\://www\.aepd.es/guias/guia-cookies.pdf](https://www.aepd.es/guias/guia-cookies.pdf). \[Accedido: 6 nov. 2026\].

\[8\] España, “Ley 11/2023, de 8 de mayo, de trasposición de Directivas de la Unión Europea en materia de accesibilidad de determinados productos y servicios, migración de personas altamente cualificadas, tributaria y digitalización de actuaciones notariales y registrales,” *Boletín Oficial del Estado*, núm. 110, 9 may. 2023\. \[En línea\]. Disponible en: [https\://www\.boe.es/buscar/act.php?id=BOE-A-2023-11022](https://www.boe.es/buscar/act.php?id=BOE-A-2023-11022). \[Accedido: 6 nov. 2026\].

\[9\] International Organization for Standardization, “The new ISO 31000 keeps risk management simple,” *ISO News*, 2018\. \[En línea\]. Disponible en: [https\://www\.iso.org/news/ref2263.html](https://www.iso.org/news/ref2263.html). \[Accedido: 6 nov. 2026\].

\[10\] OWASP Foundation, “OWASP Top 10:2025,” 2025\. \[En línea\]. Disponible en: [https\://top10.owasp.org/2025/](https://top10.owasp.org/2025/). \[Accedido: 6 nov. 2026\].

\[11\] N. Martín Amaro, D. F. Pérez Montesinos y P. Y. Piñero Pérez, “Análisis cualitativo y cuantitativo de los riesgos en proyectos de software,” *Serie Científica de la Universidad de las Ciencias Informáticas*, vol. 14, núm. 4, pp. 96–110, abr. 2021\. \[En línea\]. Disponible en: [https\://dialnet.unirioja.es/descarga/articulo/8590500.pdf](https://dialnet.unirioja.es/descarga/articulo/8590500.pdf). \[Accedido: 6 nov. 2026\].

[image1]: <data:image/png;base64,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>

[image2]: <data:image/png;base64,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>