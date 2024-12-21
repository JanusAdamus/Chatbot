# Proyecto: Chatbot

## Software Requirements

## Plan de Calidad

## Arquitectura y Justificación

## Metodología y Justificación

## Código del Proyecto

## Documentación para Replicar

### Objetivo
Implementar un chatbot funcional equivalente al creado en este proyecto.

---

### Requisitos Previos
1. Cuenta en [Landbot](https://landbot.io/).
2. Flowchart del chatbot, incluyendo nodos y decisiones.
3. Contenido necesario:
   - Texto del mensaje inicial.
   - Opciones para los botones de la lista.
   - Recursos adicionales, como imágenes o enlaces.

---

### Pasos para Configurar el Chatbot

#### 1. Crear un Nuevo Chatbot
1. Inicia sesión en [Landbot Dashboard](https://app.landbot.io/).
2. Haz clic en **"Crear Chatbot"** y selecciona el tipo:
   - **Web**: Ideal para sitios web.
   - **WhatsApp**: Para comunicación en WhatsApp.
   - **Messenger**: Para Facebook Messenger.

---

#### 2. Configurar el Mensaje Inicial con List Buttons

1. **Añadir un Bloque de Pregunta:**
   - Arrastra un bloque de **"Botón de lista"** al canvas del editor.
   - Conecta el punto de inicio a este nuevo bloque.

2. **Configurar el Contenido del Mensaje Inicial:**
   - Escribe el texto del mensaje, por ejemplo:
     ```
     Aquí encontrarás toda la información que consideramos imprenscindible para que tengas todo el éxito
     ```
   - Añade las opciones según el flowchart:
     - **Opción 1:** "Bajas"
     - **Opción 2:** "Croquis"
     - **Opción 3:** "Actividades en el Itam"
     - **Opción 4:** "Org. Estudiantiles"
     - **Opción 5:** "Armar horario"
     - **Opción 6:** "Eventos"


---

#### 3. Diseñar los Flujos Posteriores

1. **Crear Bloques de Continuación:**
   - De acuerdo al diagrama de flujo, crea y conecta bloques de los siguientes tipos:
     - **"Mensaje"**: Para mostrar respuestas estáticas (texto o imágenes).
     - **"Botón de lista"**: Para capturar información adicional.



---

#### 4. Pruebas

1. Activa la **vista previa** para probar el flujo.
2. Simula diferentes rutas para verificar que todas las opciones funcionan correctamente.

---

#### 5. Publicación

1. Haz clic en **"Publicar"**.
2. Integra el chatbot en el canal deseado:
   - **Código para insertar**: Si es para un sitio web.
   - **Enlace compartible**: Para pruebas o acceso rápido.
   - **WhatsApp/Messenger**: Configura la integración correspondiente.

---

#### 6. Optimización Continua

1. **Seguimiento:**
   - Revisa métricas desde el panel de análisis:
     - Tasa de clics en los botones.
     - Conversaciones completadas.
2. **Ajustes:**
   - Realiza mejoras según los datos y la retroalimentación de los usuarios.

---


### Notas Finales

- Monitorea el rendimiento del chatbot regularmente.
- Actualiza el flujo según las necesidades de los usuarios.
- Documenta los cambios importantes para futuras referencias.


## Propuesta Económica

Esta sección presenta una propuesta económica detallada para el desarrollo del proyecto, incluyendo la construcción de un menú inicial y el desarrollo de opciones específicas derivadas de este. Además, se considera el impacto y los costos asociados a los roles de apoyo general y un costo fijo relacionado con el equipo. A través de un desglose claro de los días estimados, días reales, capacidad utilizada y costos por rol, esta propuesta busca ofrecer una visión transparente y precisa de la inversión necesaria para llevar a cabo el proyecto con éxito. Todos los cálculos realizados para esta propuesta pueden ser encontrados en el archivo [Propuesta Económica/PropuestaEconómica.xlsx](Propuesta%20Económica/PropuestaEconómica.xlsx).


### Equipo de Trabajo y Costos Individuales

| Rol                          | Salario Mensual | Horas Laborales | Horas Reales | Precio por Hora | Precio por Día |
|------------------------------|-----------------|-----------------|--------------|-----------------|----------------|
| Senior Software Developer    | $119,000 MXN    | 160             | 120          | $992 MXN        | $5,950 MXN     |
| Junior Software Developer    | $22,000 MXN     | 160             | 120          | $183 MXN        | $1,100 MXN     |
| Program Manager Intermedio   | $44,000 MXN     | 160             | 120          | $367 MXN        | $2,200 MXN     |
| Diseño UX Intermedio         | $23,000 MXN     | 160             | 120          | $192 MXN        | $1,150 MXN     |
| DevOps                       | $115,000 MXN    | 160             | 120          | $958 MXN        | $5,750 MXN     |
| Diseño UI Intermedio         | $23,000 MXN     | 160             | 120          | $192 MXN        | $1,150 MXN     |
| QA                           | $25,000 MXN     | 160             | 120          | $208 MXN        | $1,250 MXN     |
| **Costo de Equipo**          | $50,000 MXN     | 160             | 160          | $313 MXN        | $1,875 MXN     |

---

### Desglose de costos

#### Menú Inicial

| Funcionalidad     | Días Estimados | Días Reales | Rol                         | Capacidad Utilizada | Costo  |
|-------------------|----------------|-------------|-----------------------------|----------------------|--------|
| Menú Inicial    | 1              | 1.45        | Diseño UX Intermedio        | 25%                 | $417 MXN |
| Menú Inicial    | 1              | 1.45        | Junior Software Developer   | 30%                 | $479 MXN |
| Menú Inicial    | 1              | 1.45        | Senior Software Developer   | 20%                 | $1,726 MXN |

**Costo total del menú inicial**: **$2,621 MXN**

---

#### Opción: Bajas

| Funcionalidad     | Días Estimados | Días Reales | Rol                         | Capacidad Utilizada | Costo   |
|-------------------|----------------|-------------|-----------------------------|----------------------|---------|
| Bajas             | 1              | 1.45        | Diseño UI Intermedio        | 20%                 | $334 MXN |
| Bajas             | 1              | 1.45        | Diseño UX Intermedio        | 25%                 | $417 MXN |
| Bajas             | 2              | 2.9         | Senior Software Developer   | 30%                 | $5,177 MXN |

**Costo total de la opción "Bajas"**: **$5,927 MXN**

---

#### Opción: Croquis

| Funcionalidad     | Días Estimados | Días Reales | Rol                         | Capacidad Utilizada | Costo   |
|-------------------|----------------|-------------|-----------------------------|----------------------|---------|
| Croquis           | 2              | 2.9         | Junior Software Developer   | 20%                 | $638 MXN |

**Costo total de la opción "Croquis"**: **$638 MXN**

---

#### Opción: Actividades en el ITAM

| Funcionalidad               | Días Estimados | Días Reales | Rol                         | Capacidad Utilizada | Costo   |
|-----------------------------|----------------|-------------|-----------------------------|----------------------|---------|
| Actividades en el ITAM      | 1              | 1.45        | Diseño UI Intermedio        | 20%                 | $334 MXN |
| Actividades en el ITAM      | 1              | 1.45        | Diseño UX Intermedio        | 15%                 | $250 MXN |
| Actividades en el ITAM      | 2              | 2.9         | Senior Software Developer   | 40%                 | $6,902 MXN |

**Costo total de la opción "Actividades en el ITAM"**: **$7,486 MXN**

---

#### Opción: Org. Estudiantiles

| Funcionalidad        | Días Estimados | Días Reales | Rol                         | Capacidad Utilizada | Costo   |
|----------------------|----------------|-------------|-----------------------------|----------------------|---------|
| Org. Estudiantiles   | 1              | 1.45        | Diseño UI Intermedio        | 20%                 | $334 MXN |
| Org. Estudiantiles   | 1              | 1.45        | Diseño UX Intermedio        | 20%                 | $334 MXN |
| Org. Estudiantiles   | 2              | 2.9         | Senior Software Developer   | 10%                 | $1,726 MXN |
| Org. Estudiantiles   | 2              | 2.9         | Junior Software Developer   | 30%                 | $957 MXN |

**Costo total de la opción "Org. Estudiantiles"**: **$3,350 MXN**


---

#### Opción: Armar horario

| Funcionalidad        | Días Estimados | Días Reales | Rol                         | Capacidad Utilizada | Costo   |
|----------------------|----------------|-------------|-----------------------------|----------------------|---------|
| Armar horario        | 1              | 1.45        | Diseño UI Intermedio        | 20%                 | $334 MXN |
| Armar horario        | 1              | 1.45        | Diseño UX Intermedio        | 25%                 | $417 MXN |
| Armar horario        | 2              | 2.9         | Junior Software Developer   | 30%                 | $957 MXN |
| Armar horario        | 2              | 2.9         | Senior Software Developer   | 10%                 | $1,726 MXN |

**Costo total de la opción "Armar horario"**: **$3,433 MXN**

---

#### Opción: Eventos

| Funcionalidad        | Días Estimados | Días Reales | Rol                         | Capacidad Utilizada | Costo   |
|----------------------|----------------|-------------|-----------------------------|----------------------|---------|
| Eventos              | 1              | 1.45        | Diseño UI Intermedio        | 20%                 | $334 MXN |
| Eventos              | 1              | 1.45        | Diseño UX Intermedio        | 20%                 | $334 MXN |
| Eventos              | 2              | 2.9         | Junior Software Developer   | 30%                 | $957 MXN |

**Costo total de la opción "Eventos"**: **$1,624 MXN**

---

#### Roles de Apoyo General

| Funcionalidad           | Días Estimados | Días Reales | Rol                         | Capacidad Utilizada | Costo    |
|-------------------------|----------------|-------------|-----------------------------|----------------------|----------|
| Todas las actividades   | 13             | 18.85       | Program Manager Intermedio  | 20%                 | $8,294 MXN |
| Todas las actividades   | 13             | 18.85       | QA                          | 20%                 | $4,713 MXN |
| Todas las actividades   | 13             | 18.85       | DevOps                      | 20%                 | $21,678 MXN |

**Costo total roles generales**: **$34,684 MXN**

---

#### Costo Fijo

| Funcionalidad      | Días Estimados | Días Reales | Rol          | Capacidad Utilizada | Costo    |
|--------------------|----------------|-------------|--------------|----------------------|----------|
| Precio Operativo   | 13             | 18.85       | -            | 23%                 | $7,952 MXN |

**Costo total fijo**: **$7,952 MXN**

---

### Resumen y Totalización


| Concepto                      | Costo         |
|-------------------------------|---------------|
| Menú inicial                  | $2,621 MXN    |
| Bajas                         | $5,927 MXN    |
| Croquis                       | $638 MXN      |
| Actividades en el ITAM        | $7,486 MXN    |
| Org. Estudiantiles            | $3,350 MXN    |
| Armar horario                 | $3,433 MXN    |
| Eventos                       | $1,624 MXN    |
| Roles generales               | $34,684 MXN   |
| Costo fijo                    | $7,952 MXN    |
| **Subtotal**                  | $67,714 MXN   |
| **IVA (16%)**                 | $10,834 MXN|
| **Total con IVA**             | **$78,548 MXN** |

**Costo total del proyecto**: **$78,548 MXN**

### Conclusión

El costo total de desarrollar el Chatbot para alumnos de nuevo ingreso al ITAM es de **$78,548 MXN**. La propuesta presentada ofrece un desglose claro y detallado de los costos asociados al desarrollo del proyecto, garantizando transparencia en cada etapa del proceso. Con un enfoque en la eficiencia y el aprovechamiento óptimo de los recursos del equipo, esta inversión no solo asegura la entrega de un producto funcional y de alta calidad, sino que también establece una base sólida para futuras expansiones o mejoras. 