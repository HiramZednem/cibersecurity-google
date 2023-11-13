# Introducción
En este modulo, aprenderemos como las organizaciones se protegen contra amenazas, riesgos y vulnerabilidades aprendiendo principios fundamentales como marcos, controles y ética.
La ciberseguridad se parece mucho a como cuidas un Jardín, a este lo cuidas, realizas una investigación para la siembra, preparas el ambiente, compras los materiales. Creas un plan en caso de plagas, etc... Si una plaga no puede ser erradicada con el plan antes mente creados tomas nuevas medidas, como construir una vaya, poner una cámara y poner un invernadero.

En este modulo aprenderemos los marcos (frameworks) y controles de seguridad, triada de confidencialidad, integridad y disponibilidad denominada la triada CID.

# Marcos y Controles de Seguridad
Como analista primero debes identificar los activos y riesgos cruciales, luego implementar los marcos y controles específicos.
## Marcos de Seguridad
Los marcos de seguridad son pautas usadas en la creación de planes para mitigar riesgos y amenazas a los datos y la privacidad. 
Estos marcos de seguridad esta conformado por políticas y normas que define la organización. Sigue políticas y cumple con normas y leyes. 

### Objetivos
- Proteger PII.
- Proteger información financiera.
- Identificar debilidades.
- Manejar los riesgos.
- Alinear la seguridad con los objetivos de la empresa.
### Componentes
Los marcos tienen cuatro componentes principales:
![[Pasted image 20231112161550.png]]
**Goals:** (Identificar y documentar los objetivos)
Por ejemplo, una organización tiene el objetivo de alinearse con el Reglamente General de Protección de Datos de la UE conocida como RGPD (ley de protección de datos para ciudadanos europeos).
**Guidelines:** (Crear pautas para alcanzar los objetivos)
Al implementar las políticas para cumplir RGPD, es posible que se tengan que crear nuevas políticas.
**Processes:** (Implementar procesos de seguridad fueres)
Básicamente como lo dice su nombre "implementarlos", si un usuario quiere borrar sus datos, que realmente esa data se elimine...
**Communication:** (Monitorear y comunicar los resultados)
Un ejemplo de esto puede ser al monitorear la red interna y reportar cualquier problema que ocurra.

## Controles de seguridad
Son medidas que reducen ciertos riesgos de seguridad

# Diseño Seguro
En la clase anterior, aprendimos sobre marcos y controles de seguridad, en esta clase se abordara los marcos y controles de seguridad específicos que son usados en las empresas.
## Triada CID:
La triada CID es una guía fundamental que informa como las organizaciones evalúan el riesgo y crean sistemas y políticas de seguridad.
![[Pasted image 20231112164312.png]]
CID es el acrónimo de: Confidencialidad, Integridad, Disponibilidad
- **Confidencialidad:**
	Deben implementarse controles estrictos para saber quien puede acceder a ciertos datos y quienes no.
- **Integridad:**
	Se debe hacer que los datos sean correctos, auténticos y confiables, para mantener la integridad se suele utilizar cifrado de datos. 
- **Disponibilidad:**
	Se refiere que la información este disponible para la gente que se necesite, por ejemplo la rectora puede tener acceso a toda la plantilla de directores y docentes, pero un director solo a la de docentes y un docente solo a la de alumnos...

Al hablar de CID, un termino muy importante son los **activos**. Porque ellos tienen un valor que esta definido por lo que son, no es lo mismo un activo de cuentas bancarias a un activo del nombre de un usuario, por tanto ciertos activos conllevan mas riesgos que otros.
## Marco de Ciberseguridad CSF del NIST.
El CSF del NIST es un marco de adhesión voluntaria que consiste en estándares, pautas y prácticas recomendadas para manejar riesgos de ciberseguridad.
Este marco es usado para gestionar los riesgos a corto y largo plazo.
Por tanto es importante como analista de ciberseguridad conocerlos ya que ayudan a gestionar y minimizar los riesgos de nuestros activos por los agentes de amenaza. 
Un agente de amenaza muy fuerte son empleados descontentos, y para minimizar esto el equipo de ciberseguridad debe hacer uso de el principio de disponibilidad y pautas organizacionales basadas en un marco de seguridad. 

# Controles, marcos y cumplimiento
**Controles de seguridad**:
Son medidas diseñadas para reducir riesgos específicos de seguridad. Por lo tanto, se utilizan junto con marcos para asegurar que los objetivos y procesos de seguridad se implementen correctamente y que las organizaciones cumplan con los requisitos regulatorios.
**Marcos de seguridad:**
son pautas utilizadas para elaborar planes que ayuden a mitigar riesgos y amenazas a los datos y la privacidad. Tienen cuatro componentes principales:
1. Identificación y documentación de objetivos de seguridad 
2. Establecimiento de pautas para lograr los objetivos de seguridad 
3. Implementación de procesos de seguridad sólidos
4. Supervisión y comunicación de resultados
**Cumplimiento normativo:**  _(compliance)_ 
Es el proceso de adhesión a reglamentos internos y regulaciones externas.
## Controles específicos, marcos y cumplimiento
El Instituto Nacional de Estándares y Tecnología (NIST) es una agencia con sede en los Estados Unidos que desarrolla varios marcos de cumplimiento voluntario que las organizaciones de todo el mundo pueden utilizar para ayudar a gestionar el riesgo.
**Ten en cuenta que** las especificaciones y pautas pueden variar según el tipo de organización para la que trabajes.
### La Comisión Federal de Regulación de Energía - Corporación de Confiabilidad Eléctrica América del Norte (FERC-NERC)
La FERC-NERC es una regulación que se aplica a las organizaciones que trabajan con electricidad o que están involucradas con la red eléctrica de los Estados Unidos y América del Norte.
### Programa Federal de Gestión de Riesgos y Autorizaciones (FedRAMP®)
El FedRAMP es un programa del gobierno federal de los Estados Unidos que estandariza la evaluación, autorización, monitoreo y gestión de seguridad de los servicios en la nube y las ofertas de productos.
### Centro de Seguridad en Internet  (CIS®)
El CIS es una organización sin fines de lucro que se enfoca en múltiples áreas. Proporciona un conjunto de controles que pueden utilizarse para proteger sistemas y redes contra ataques.
### Reglamento General de Protección de Datos (RGPD)
El RGPD es una normativa general de datos de la Unión Europea (UE) que protege el procesamiento de los datos de sus residentes y su derecho a la privacidad dentro y fuera del territorio. 
### Estándares de seguridad de datos del sector de las tarjetas de pago (PCI DSS)
PCI DSS es un estándar de seguridad internacional destinado a garantizar que las organizaciones que almacenan, aceptan, procesan y transmiten información de tarjetas de crédito lo hagan en un entorno seguro. 
### Ley de Transferencia y Responsabilidad de los Seguros Médicos (HIPAA)
La HIPAA es una ley federal de los Estados Unidos establecida en 1996 para proteger la información médica de las personas. Esta ley prohíbe que la información de un/una paciente sea compartida sin su consentimiento.
### Organización Internacional para la Normalización (ISO) 
La ISO fue creada para establecer estándares internacionales relacionados con la tecnología, la fabricación y la gestión en todo el mundo.
### Controles de Sistemas y Organizaciones (SOC tipo 1, SOC tipo 2)
Los informes SOC1 y SOC2 se enfocan en las políticas de acceso de los/as usuarios/as de una organización en diferentes niveles, tales como: 
- Asociado/a
- Supervisor/a
- Gerente/a
- Ejecutivo/a
- Proveedor/a
- Otros
**Consejo profesional**: Existen numerosas regulaciones que se revisan con frecuencia. Te recomendamos mantenerte al día con los cambios y explorar más marcos, controles y normas de cumplimiento. Dos sugerencias para investigar: la Ley Gramm-Leach-Bliley y la Ley Sarbanes-Oxley.