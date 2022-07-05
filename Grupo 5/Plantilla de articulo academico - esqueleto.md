Diseño y especificaciones de un sistema de información para un Hotel

*David Santiago Paniagua Hernández-Jaziel Ruiz Gutierrez-Guillermo Josué Obando Cerón-Juan José Sánchez Ulloa-Valeria Solano Suarez*

Universidad Latina de Costa Rica, Sede San Pedro

Recibido DD/MM/AAAA

Aprobado DD/MM/AAAA
|8|Tecnología Vital Por Confirmar – Mes Año|
| :- | -: |




***Resumen— — El objetivo de esta investigación es diseñar un plan sistema de información para un hotel y todas las partes que lo conforman, como el esquema de red, los casos de uso, la seguridad del sistema y definir las diferentes tecnologías y herramientas a utilizar, entre otros. También se documentó todo el trabajo realizado para llegar al diseño final, esta documentación se fue registrando mientras se iba completando el trabajo cada cierto tiempo haciendo uso de la herramienta Jira. Esto a su vez, representa la forma en que se estaría trabajando a la hora de realizar tareas de mantenimiento del sistema, así como implementar nuevas funcionalidades que se requieran, haciendo uso de metodologías agiles, en nuestro caso Scrum.

***Abstract-** The goal of the research on this document is to present the design for a system of information for a hotel, this includes the network diagram, use cases, security and explain the technologies and tools used. All the work done to achieve the current was documented using Jira, all the work was documented on this platform similar to how it would be done when the final product is implemented, and the system is up and running. Palabras claves: computación en la nube, seguridad, diagrama de flujo, sistema de información. Keywords: cloud computing, security, workflow, information system, databases.

1. **INTRODUCCIÓN** 

Para iniciar con el diseño del sistema de información se toma en cuenta las características y escala del hotel, esto incluye cantidad de empleados, ingresos, cantidad de sedes, entre otros. Tomando en cuenta estos aspectos, se diseñó un sistema para un hotel de capacidad mediana, el cual cubre las necesidades del hotel para el registro de colaboradores con los debidos niveles de permisos y seguridad requerida para operar de manera correcta. Para la documentación del proceso, se utilizó la versión gratuita del software Jira, que permite llevar un control del progreso del proyecto usando historias de usuario y tareas que se asignan cada cierto tiempo.

2. **ANTECEDENTES DEL PROBLEMA DE ESTUDIO** 

El requerimiento del diseño del sistema de información surge cuando se decide llevar a cabo un proyecto para abrir un hotel, este emprendimiento requiere de un diseño completo y detallado del sistema que se utilizara para que el hotel pueda llevar a cabo sus actividades de negocio criticas e indispensables, tales como hospedaje de huéspedes, reservaciones, contratación de colaboradores, colaboración, finanzas, servicio al cliente, entre muchas otras actividades. Se requiere que el diseño de este sistema sea lo más cercano posible a la implementación final para entender el esfuerzo requerido y costo del proceso. 

3. **PLANTEAMIENTO DEL PROBLEMA** 

Falta de un diseño completo de un sistema de información seguro y escalable para un hotel, tener un buen diseño y plan de implementación, así como un cálculo aproximado del costo total, es indispensable cuando se quiere implementar un sistema seguro y que satisfaga las necesidades del hotel en la parte informática. En este proyecto se detallan los puntos más relevantes para hacer una implementación exitosa del sistema 

4. **JUSTIFICACIÓN**

A raíz del requerimiento del diseño completo del sistema, se necesita una investigación a fondo para entender cuales herramientas encajan mejor para la solución final, tomando en cuenta toda la funcionalidad que el sistema debe ofrecer. Así como calcular el costo total aproximado que tendrá llevar a cabo la implementación de este diseño y que el costo se encuentre dentro del presupuesto de la compañía.

5. **OBJETIVO GENERAL**

•	Diseñar un sistema de información para un hotel de tamaño mediano, cubriendo debidamente los aspectos más relevantes en materia de arquitectura, seguridad y recuperación en caso de desastres.

6. **OBJETIVOS ESPECÍFICOS** 
•	Diseñar un sistema de información que sea de gran escalabilidad a futuro tomando en cuenta el potencial crecimiento del hotel. 
•	Diseñar un esquema de red que cumpla con los requisitos a nivel de arquitectura y seguridad para la capacidad del hotel
•	Definir un plan de recuperación en caso de desastres. 
•	Definir los niveles y medidas de seguridad que los colaboradores deben seguir cuando hagan uso del sistema del hotel.

7. ` `**DELIMITACIÓN, ALCANCE O COBERTURA** 

El alcance de la solución presentada en este proyecto está delimitado por la capacidad y tamaño físico del hotel, debido a que en general la escala del hotel es mediana, la arquitectura de la solución no requiere de un diseño demasiado complejo.

8. **RESTRICCIONES Y/O LIMITACIONES**

La principal limitación a la hora de trabajar en el diseño del sistema fue la falta de licencias para las herramientas de software o el uso de las versiones gratuitas o de prueba. Esto limita la capacidad de representar el producto final de la mejor manera, ya que usualmente las versiones gratuitas de estas herramientas no tienen todas las capacidades y opciones que ofrecen las versiones completas o con licencia. Sin embargo, en este caso, las herramientas de software en su versión gratuita nos proporcionaron bastante funcionalidad y logramos una buena representación del sistema con todos los aspectos de arquitectura y diseño requeridos. Un ejemplo claro es el uso de la herramienta Jira en su versión gratuita, esta, a pesar de no contar con todas las capacidades de la versión completa, nos proporciona la capacidad de no solo registrar la actividad relacionada a historias de usuario y tareas, sino que también nos permitió trabajar y colaborar entre los 3 miembros del equipo.

9. **MARCO SITUACIONAL METODOLÓGICO**

Una vez realizada la investigación de las herramientas tomando en cuenta el presupuesto, se da inicio al diseño de la solución como tal, durante el proceso se hace uso de la herramienta de gestión de proyectos Jira. En el primer sprint, se realizan los diagramas de casos de uso, en los cuales se representan las acciones que podrían realizar tanto usuarios como empleados en el sistema del hotel, para la representación de estos casos de uso se utilizó la herramienta Visio de Microsoft. El proceso del diseño de estos casos se documentó en Jira y las tareas e historias de usuario se marcaron como completadas y aceptadas, simulando la dinámica y metodología que se estaría implementando para trabajar con tecnologías de información en la cadena hotelera. Posteriormente, se procede a realizar la construcción de diferentes documentos requeridos para el análisis y diseño del sistema, como son: Bill of materials, Request Access form y el presente documento que detalla todos los pasos del proceso. Para la lista de servicios y sus costos (Bill of materials), se hizo uso de la calculadora de precios de Microsoft Azure donde se escogieron diferentes servicios de Microsoft que se emplearan en la implementación de la solución final. El documento de la solicitud de acceso y permisos (Request Access form), se diseñó teniendo en cuenta los permisos y roles que los empleados que harán uso del sistema puedan requerir. También se diseñó para que la solicitud de este acceso sea analizada por los administradores y estos decidan si es seguro otorgar el acceso a la persona que lo está solicitando. Posteriormente, se procede con el diseño del esquema de red que será utilizado en la implementación del diseño, para esto se hace uso de la herramienta Microsoft Visio. La arquitectura de esta red se diseñó tomando en cuenta que el hotel es de capacidad mediana y por lo tanto, la red se diseñó con tal de que cumpliera con los requisitos pero tenga la posibilidad de ser ampliada en un futuro dependiendo del crecimiento del hotel. Una vez finalizado el diseño de la red, se procede con la definición de los niveles y medidas de seguridad del sistema. Cabe destacar que, al hacer uso de varias herramientas de Microsoft en la nube para el almacenamiento y gestión de datos, una gran parte de la seguridad de los datos es gestionada por Microsoft. Esto no significa que los administradores del sistema del hotel no tengan que preocuparse por implementar y seguir medidas seguridad, pero si reduce la carga que tendrían los administrados del sistema en tareas más tediosas y complejas en temas de seguridad. Una de las áreas más importantes de las que los administradores del sistema del hotel se tienen que encargar, es hacer una gestión responsable y ordenada de los niveles de permisos de los colaboradores y trabajadores por contrato, ya que si no se tiene un control de estos permisos hay una alta posibilidad de sufrir una pérdida de datos o filtración de estos, medidas como la solicitud de acceso ayudan en esta parte de la seguridad si se emplean de la manera correcta. Una vez completada la mayor parte de todos estos puntos, se procede a terminar con la documentación de todo el trabajo en Jira, donde está el registro de todas las actividades realizadas para completar los objetivos mediante el uso de Scrum. Y por último se trabaja en los detalles finales del presente documento donde se hace una documentación general de toda la investigación.

10. **DIAGNÓSTICO DEL ESTADO ACTUAL** 

Actualmente, después de finalizado el diseño del sistema, la solución debe ser presentada a los stakeholders para que sea aprobada y se dé el visto bueno para proceder con la implementación de la solución. Una vez que se haga la demostración de la solución y se tenga la aprobación, el primer paso sería la implementación física del esquema de red y la configuración de esta. Posteriormente se va a hacer una revisión general para asegurarse de que todo esté listo para moverse a producción.

11. **Propuesta de Cambio** 

El primer paso y el más importante consiste en instalar la red física en los 5 hoteles y completar la configuración detallada en el diseño de la solución, es importante tener la aprobación de todos los stakeholders y el product owner del equipo. Esto para asegurarse que no haya espacios vacíos y áreas que no se hayan contemplado, ya que el objetivo de implementar el esquema de red y completar la configuración es tener todo listo para que se empiece a usar tanto por cliente como por colaboradores y que la cadena de hoteles pueda empezar con sus actividades críticas de negocio.

12. **Conclusión**
En conclusión, en esta investigación y proceso del diseño del sistema, se utilizaron diferentes tecnologías, así como metodologías de trabajo que requirieron horas de exploración e investigación para entender la mejor manera de implementarlas y maximizar los beneficios que pueden proporcionar. Gracias a esto, se adquirió un conocimiento valioso que permitirá no solo mantener el negocio operando de manera exitosa, sino que hará posible la expansión e implementación exitosa de nuevas funcionalidades o tecnologías que aumenten la productividad o reduzcan gastos y, de esta manera lograr un crecimiento exponencial de la empresa.

13. **Recomendación**

La principal recomendación para mantener un buen nivel de seguridad es realizar una administración responsable de los permisos que se otorgan a los colaboradores o cualquier persona que requiera acceder a las bases de datos de la cadena hotelera. Esto es indispensable para mantener el orden en la organización y evitar fallas en la seguridad

14. **Referencias**

Azure. (s.f.). Pricing calculator. Obtenido de https://azure.microsoft.com/en-us/pricing/calculator/
Azure, M. (14 de Marzo de 2022). tic.portal. Obtenido de https://www.ticportal.es/temas/cloud-computing/microsoft-cloud/microsoft-azure
Github. (s.f.). The home for all developers — including you. Obtenido de https://github.com/
IBM. (s.f.). ¿Qué es un plan de recuperación de desastres (DR)? Obtenido de https://www.ibm.com/mx-es/services/business-continuity/disaster-recovery-plan
Kaspersky. (s.f.). ¿Qué son los ataques DDoS? Obtenido de https://latam.kaspersky.com/resource-center/threats/ddos-acks
