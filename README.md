# Proyecto: Chatbot

## Software Requirements

## Plan de Calidad

## Arquitectura y Justificación

El chatbot está diseñado para manejar flujos de conversaciones predefinidos, por lo que cada interacción del estudiante genera una respuesta predeterminada. Además, está planeado para funcionar en WhatsApp, un método de comunicación instantáneo y bien conocido por la comunidad itamita. Entonces, la arquitectura ideal es una combinación de las siguientes dos.

Arquitectura basada en eventos: Esta es la arquitectura principal y está constituida por un disparador, un procesador, y una respuesta a eventos. Un evento se dispara cada vez que un alumno le envía un mensaje al chatbot. El procesador guía la petición por una cadena de respuestas previamente elaboradas (figura 1). La respuesta determinada por el procesador se envía por el chat de regreso para que el estudiante la pueda leer. 

 ![image](https://github.com/user-attachments/assets/bfaa25f7-fdab-4ab4-b60f-39b05b3bef1b)
Figura 1. Flujo de respuestas preelaboradas. En rosa se ven las opciones de peticiones que el alumno puede hacer, y en blanco se ven las respuestas que dará el chatbot.

Arquitectura de microservicios: Esta arquitectura emplea archivos tipo json para leer y transmitir peticiones a APIs de otras aplicaciones. En este caso, la única API que se usa es la de WhatsApp, a través de la cual se abre el canal de comunicación entre los estudiantes y el chatbot. Sin embargo, queda la arquitectura montada para eventualmente enlazar otros servicios. Un ejemplo podría ser la API de Entérate ITAM, un servicio creado por la oficina de comunicación que se usa para anunciar los eventos institucionales que se llevan a cabo semana con semana.

El flujo total se ve así (figura 2): la interacción sucede a través de la API de WhatsApp, y el resto sucede dentro del bloque de procesadores de eventos que conforman al chatbot.

 ![image](https://github.com/user-attachments/assets/ded1d885-dd19-4223-ad2b-a93520d2226f)
Figura 2. Arquitectura global de chatbot.

## Metodología y Justificación

El producto está dirigido a estudiantes de nuevo ingreso a la universidad – una población de perfiles muy variados y que cambia semestre con semestre. A pesar de que ya son adultos legalmente, la mayoría no cuenta con experiencia previa haciendo trámites ni solicitando servicios académicos. Ocupan orientación clara, accesible, y actualizada, pues las reglas del ITAM también van evolucionando con el tiempo. Por ello, se eligió la siguiente combinación de metodologías, considerando que el desarrollo debe ser altamente adaptable.

Metodología feature-driven: Esta metodología permite descomponer el proyecto en fracciones según las cambiantes necesidades de los estudiantes y las cambiantes exigencias de la institución. Los módulos considerados de primera instancia son: manual sobre bajas de materias, croquis, actividades no académicas disponibles, organizaciones estudiantiles, creación de horarios e información de eventos.

Metodología por prototipos: Dentro de los módulos, se planea usar un diseño por prototipos para probar las distintas maneras de interactuar con el chatbot que tendrán los estudiantes. Esta metodología permite crear flujos de conversación variados y validar la eficiencia de cada uno antes de elegir el/los que se usará/n en producción.

Metodología ágil: La iteración incremental permite revisitar los módulos para integrar mejoras basadas en retroalimentación y actualizaciones requeridas por la universidad y sus estudiantes. Además, partir los módulos en sprints permite enfocar y aligerar la carga de los desarrolladores.

## Código del Proyecto

## Documentación para Replicar

## Propuesta Económica

