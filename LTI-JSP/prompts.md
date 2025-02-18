### Chatbot:
ChatGPT

## Prompt 1:
Debo crear unas historias de usuario basandome en las siguientes pautas.
Las user stories deben estar escritas desde la perspectiva del usuario final, no desde la perspectiva interna de la organización.
Utilizar personajes o "personas" para entender mejor las necesidades y objetivos de los usuarios.
Mantener un formato simple y conciso:
Seguir el formato estándar: "Como [tipo de usuario], quiero [realizar una acción] para [obtener un beneficio]".
Evitar detalles técnicos o instrucciones de implementación.
Priorizar las historias de usuario en función de su valor para el negocio y el usuario.
Estimar el esfuerzo requerido para implementar cada historia.
Definir claramente los criterios de aceptació que deben cumplirse para considerar una historia "terminada".

Ten en cuenta estas pautas y ya te doy el contexto de lo que debemos documentar con las historias de usuario.

## respuesta 1:
¡Listo! Compárteme el contexto y te ayudo a redactar las historias de usuario siguiendo esas pautas.

## Prompt 2:
LTI es una startup que quiere desarrollar el ATS (Applicant-Tracking System) del futuro. Si no sabes lo que es un ATS, aquí una imagen:  Ver imagen adjunta.

Tu rol será el de product manager y debes definir esas funcionalidades clave que harán brillar a LTI por encima de los competidores: aumentar la eficiencia para los departamentos de HR, mejorar la colaboración en tiempo real entre reclutadores y managers, automatizaciones, asistencia de IA en diversas tareas...es el momento de hacer brainstorming, investigar cuáles pueden ser las claves del éxito, y dejarlo plasmado para el resto del equipo.

## respuesta 2:

Genial! Para que LTI destaque en el mercado de los ATS, podemos enfocarnos en funcionalidades innovadoras que mejoren la eficiencia, la colaboración y la automatización. Algunas ideas clave:

1. Automatización y Asistencia de IA
Cribado automático de CVs: IA que analiza y clasifica postulaciones según criterios predefinidos.
Generación de descripciones de empleo: IA que sugiere descripciones basadas en roles similares y tendencias del mercado.
Chatbot para candidatos: Responde preguntas, informa sobre el estado del proceso y agenda entrevistas.
2. Colaboración en Tiempo Real
Comentarios y valoraciones en equipo: Espacio para que reclutadores y managers dejen feedback en cada candidato.
Panel en vivo de candidatos: Estado actualizado en tiempo real para evitar cuellos de botella en el proceso de selección.
Notificaciones y recordatorios inteligentes: Para entrevistas, pruebas y evaluaciones.
3. Experiencia del Candidato
Portal de seguimiento en tiempo real: Para que los candidatos consulten su estado en el proceso.
Evaluaciones gamificadas: Tests interactivos que hagan el proceso más atractivo.
Videoentrevistas con análisis de lenguaje corporal y tono (usando IA).
4. Integraciones y Adaptabilidad
Integración con LinkedIn y portales de empleo: Publicación automática y recepción de solicitudes.
Sincronización con calendarios: Para programar entrevistas sin fricciones.
Soporte para múltiples idiomas y normativas (GDPR, CCPA).
Siguientes pasos
Ahora podríamos convertir estas funcionalidades en historias de usuario concretas. ¿Quieres que empecemos con eso?


Si por favor

ChatGPT dijo:
Voy a estructurar algunas historias de usuario clave siguiendo el formato estándar.

Estos son algunos ejemplos iniciales. ¿Te gustaría que agregáramos más funcionalidades o priorizamos estas? 🚀

Historias de Usuario para el ATS de LTI
1. Cribado Automático de CVs con IA
Como reclutador,
quiero que el sistema analice automáticamente los CVs y me muestre los más relevantes según los criterios definidos,
para reducir el tiempo de revisión manual y centrarme en los candidatos más adecuados.

Criterios de Aceptación:
✅ La IA debe analizar CVs en diferentes formatos (PDF, DOC, etc.).
✅ El sistema debe asignar un puntaje de relevancia basado en experiencia, habilidades y palabras clave.
✅ Debe permitir ajustar los criterios de búsqueda y recibir sugerencias.

2. Generación Automática de Descripciones de Empleo
Como gerente de contratación,
quiero que el sistema sugiera automáticamente descripciones de empleo basadas en roles similares,
para agilizar la creación de nuevas vacantes y asegurar que la redacción sea clara y atractiva.

Criterios de Aceptación:
✅ El sistema debe generar una descripción inicial basada en datos históricos y tendencias del mercado.
✅ Debe permitir ajustes manuales antes de la publicación.
✅ Debe ofrecer sugerencias de mejoras basadas en engagement de anuncios previos.

3. Chatbot para Candidatos
Como candidato,
quiero interactuar con un chatbot que responda mis dudas sobre el proceso y me ayude a agendar entrevistas,
para obtener información rápida sin depender del equipo de RRHH.

Criterios de Aceptación:
✅ El chatbot debe responder preguntas frecuentes sobre el puesto y el estado de la postulación.
✅ Debe permitir el agendamiento automático de entrevistas según disponibilidad.
✅ Debe integrarse con la plataforma de mensajería de la empresa.

4. Feedback Colaborativo en Candidatos
Como reclutador,
quiero poder dejar y ver comentarios en los perfiles de los candidatos en tiempo real,
para facilitar la colaboración con mi equipo en la toma de decisiones.

Criterios de Aceptación:
✅ Debe permitir que varios usuarios dejen comentarios y calificaciones.
✅ Debe mostrar un historial de feedback de cada candidato.
✅ Debe notificar a los miembros del equipo cuando se añada un nuevo comentario.

5. Portal de Seguimiento para Candidatos
Como candidato,
quiero acceder a un portal donde pueda ver el estado de mi aplicación en tiempo real,
para evitar incertidumbre sobre mi proceso de selección.

Criterios de Aceptación:
✅ El portal debe mostrar el estado actualizado de la postulación.
✅ Debe enviar notificaciones cuando haya cambios (ej. “Entrevista programada”).
✅ Debe permitir la carga de documentos adicionales si es necesario.

## Prompt 3:
Podrías ajustar la HU "3. Chatbot para Candidatos" ya que considero que un candidato no debería poder auto agendarse entrevistas sin haber sido seleccionado previamente. Si consideras que se requiere otra nueva Hu puedes sugerirmela.

## Respuesta 3:
Buena observación. Ajustaré la historia para que el chatbot solo brinde información y, si es necesario, facilite el proceso de agendamiento cuando el candidato haya sido seleccionado. Además, agregaré una nueva historia para la programación de entrevistas por parte del reclutador.

3. Chatbot para Candidatos (ajustada)
Como candidato,
quiero interactuar con un chatbot que responda mis dudas sobre el proceso de selección y mi estado en él,
para obtener información rápida sin depender del equipo de RRHH.

Criterios de Aceptación:
✅ El chatbot debe responder preguntas frecuentes sobre el puesto, requisitos y etapas del proceso.
✅ Debe informar el estado actual de la postulación (ej. "Tu CV ha sido recibido", "Estás en evaluación").
✅ Debe ofrecer instrucciones sobre los siguientes pasos en caso de avanzar en el proceso.
✅ Si el candidato es seleccionado para una entrevista, el chatbot debe permitir solicitar horarios disponibles sin confirmación automática.

6. Programación de Entrevistas por Reclutadores (nueva HU)
Como reclutador,
quiero programar entrevistas con los candidatos seleccionados de forma rápida y organizada,
para optimizar la gestión de horarios y evitar cruces en la agenda.

Criterios de Aceptación:
✅ El sistema debe mostrar la disponibilidad de los entrevistadores antes de agendar.
✅ Debe enviar una invitación al candidato con posibles horarios para que seleccione uno.
✅ Debe confirmar la entrevista solo cuando el candidato acepte la propuesta.
✅ Debe sincronizarse con calendarios externos (Google Calendar, Outlook, etc.).
✅ Debe notificar automáticamente a todas las partes cuando la entrevista se confirme.

Ahora el chatbot informa y guía al candidato sin permitirle autoagendar entrevistas, y el reclutador tiene un proceso estructurado para gestionar las citas. ¿Te parece que esto cubre bien la funcionalidad o quieres afinar algún detalle más? 🚀

## Prompt 4:
Ahora quiero que me sugieras cuales consideras que serías las HU que tienen mayor prioridad, utiliza un Mapa de Historias para presentarlo.

## Respuesta 4:
Aquí tienes un Mapa de Historias de Usuario organizado por épicas y priorizado según el impacto en eficiencia, colaboración y automatización.

📌 Mapa de Historias de Usuario para el ATS de LTI
📌 Eje X (Horizontal): Etapas del proceso de contratación
📌 Eje Y (Vertical): Prioridad de la funcionalidad (Alta, Media, Baja)

🔹 Alta Prioridad (Core del sistema, impacto inmediato)
✅ Cribado Automático de CVs con IA (Reducir carga manual en RRHH)
✅ Programación de Entrevistas por Reclutadores (Gestión eficiente de tiempos y citas)
✅ Feedback Colaborativo en Candidatos (Mejor toma de decisiones en equipo)
✅ Portal de Seguimiento para Candidatos (Mejor experiencia del postulante, reduce incertidumbre)

🔸 Prioridad Media (Mejoras importantes, pero no críticas para MVP)
🔸 Chatbot para Candidatos (Mejor comunicación con postulantes, sin reemplazar interacción humana)
🔸 Generación Automática de Descripciones de Empleo (Ahorro de tiempo en la publicación de ofertas)
🔸 Evaluaciones Gamificadas y Online (Filtrado de candidatos de manera más interactiva y atractiva)

⚪ Baja Prioridad (Funcionalidades avanzadas, diferenciadores competitivos)
⚪ Videoentrevistas con IA (análisis de lenguaje corporal y tono) (Innovación, pero requiere validación en mercado)
⚪ Integración con Redes Sociales y Portales de Empleo (Aumenta alcance, pero no bloquea la operatividad inicial)
⚪ Notificaciones Inteligentes y Recordatorios (Optimiza el flujo, pero puede añadirse después del MVP)

|               🔹Alta Prioridad               |
|---------------------------------------------|
| ✅ Cribado de CVs  | ✅ Programación Entrevistas |
| ✅ Feedback Colaborativo  | ✅ Portal Candidatos |
|---------------------------------------------|
|               🔸Prioridad Media             |
|---------------------------------------------|
| 🔸 Chatbot Candidatos  | 🔸 Generación Descripción |
| 🔸 Evaluaciones Online |                          |
|---------------------------------------------|
|               ⚪ Baja Prioridad              |
|---------------------------------------------|
| ⚪ Videoentrevistas IA | ⚪ Integración con Portales |
| ⚪ Notificaciones Inteligentes |               |
|---------------------------------------------|


Este esquema permite priorizar lo esencial para un MVP sólido, enfocándonos en eficiencia y automatización desde el inicio.

¿Qué te parece? ¿Harías algún ajuste en las prioridades? 🚀

## Prompt 5:
Antes de continuar, puedes darme volver a listar todas las HU que hemos definido hasta ahora?
Este item se realizo ya que el mapa no lo realizo correctamente

## Respuesta 5:
Por supuesto, aquí tienes todas las Historias de Usuario (HU) que hemos definido hasta ahora:
.
.
.

## Prompt 6:
Perfecto. Puedes generar un backlog especificando las subtareas y la HU a la cual pertenece cada subtarea. El backlog debe contemplar dependencias entre tareas, impacto y priorización de actividades pensando en el valor del producto, debe permitir ver la complejidad y esfuerzo de cada tarea.

## Respuesta 6:
Aquí tienes un Backlog estructurado con las subtareas de cada Historia de Usuario (HU), junto con su prioridad, impacto, esfuerzo estimado y dependencias.

📌 Backlog del ATS de LTI
📊 Criterios de Priorización y Esfuerzo:
Prioridad: 🔴 Alta | 🟠 Media | 🔵 Baja
Impacto: 🌟 Crítico | ⭐ Alto | ✨ Medio | 🌑 Bajo
Esfuerzo: ⚡ Bajo (1-2 días) | 🔧 Medio (3-5 días) | 🏗️ Alto (6+ días)
🔹 1. Cribado Automático de CVs con IA (🔴 Alta Prioridad, 🌟 Impacto Crítico, 🏗️ Alto Esfuerzo)
🔹 Subtareas:
1️⃣ Definir criterios de filtrado según requisitos del puesto (⚡ Bajo).
2️⃣ Desarrollar el motor de IA para analizar CVs (🏗️ Alto).
3️⃣ Entrenar el modelo con datos históricos (🏗️ Alto).
4️⃣ Diseñar interfaz para visualizar ranking de candidatos (🔧 Medio).
5️⃣ Integrar con la carga de CVs en la plataforma (🔧 Medio).

📌 Dependencias:
☑️ Requiere la funcionalidad de carga de CVs activa.

🔹 2. Generación Automática de Descripciones de Empleo (🟠 Media Prioridad, ⭐ Impacto Alto, 🔧 Medio Esfuerzo)
🔹 Subtareas:
1️⃣ Definir estructura estándar de descripciones de empleo (⚡ Bajo).
2️⃣ Desarrollar modelo de IA para sugerir contenido (🔧 Medio).
3️⃣ Permitir ajustes manuales antes de publicación (⚡ Bajo).
4️⃣ Integrar con el módulo de publicación de vacantes (🔧 Medio).

📌 Dependencias:
☑️ Debe estar listo el módulo de creación de vacantes.

🔹 3. Chatbot para Candidatos (🟠 Media Prioridad, ⭐ Impacto Alto, 🔧 Medio Esfuerzo)
🔹 Subtareas:
1️⃣ Diseñar flujo de conversación del chatbot (⚡ Bajo).
2️⃣ Implementar respuestas a preguntas frecuentes (⚡ Bajo).
3️⃣ Conectar chatbot con estado del proceso de selección (🔧 Medio).
4️⃣ Integrar con módulo de entrevistas para sugerir horarios (🔧 Medio).

📌 Dependencias:
☑️ Requiere que la base de datos de estado de postulaciones esté disponible.

🔹 4. Feedback Colaborativo en Candidatos (🔴 Alta Prioridad, ⭐ Impacto Alto, 🔧 Medio Esfuerzo)
🔹 Subtareas:
1️⃣ Diseñar sistema de comentarios y calificaciones (⚡ Bajo).
2️⃣ Crear permisos y visibilidad según roles (⚡ Bajo).
3️⃣ Integrar notificaciones en tiempo real (🔧 Medio).
4️⃣ Historial de feedback en cada perfil de candidato (🔧 Medio).

📌 Dependencias:
☑️ Debe existir el módulo de perfiles de candidatos.

🔹 5. Portal de Seguimiento para Candidatos (🔴 Alta Prioridad, 🌟 Impacto Crítico, 🏗️ Alto Esfuerzo)
🔹 Subtareas:
1️⃣ Definir estados posibles de las postulaciones (⚡ Bajo).
2️⃣ Diseñar UI para el portal de candidatos (🔧 Medio).
3️⃣ Implementar tracking en tiempo real del estado (🏗️ Alto).
4️⃣ Notificaciones automáticas en cambios de estado (🔧 Medio).

📌 Dependencias:
☑️ Debe estar funcionando el flujo de selección y entrevistas.

🔹 6. Programación de Entrevistas por Reclutadores (🔴 Alta Prioridad, 🌟 Impacto Crítico, 🔧 Medio Esfuerzo)
🔹 Subtareas:
1️⃣ Mostrar disponibilidad de entrevistadores (⚡ Bajo).
2️⃣ Enviar invitaciones a candidatos con opciones de horarios (🔧 Medio).
3️⃣ Sincronizar con Google Calendar y Outlook (🔧 Medio).
4️⃣ Confirmar la entrevista tras aceptación del candidato (⚡ Bajo).

📌 Dependencias:
☑️ Debe estar lista la integración con calendarios externos.


Historia de Usuario	Prioridad	Impacto	Esfuerzo
Cribado Automático de CVs con IA	🔴 Alta	🌟 Crítico	🏗️ Alto
Feedback Colaborativo en Candidatos	🔴 Alta	⭐ Alto	🔧 Medio
Portal de Seguimiento para Candidatos	🔴 Alta	🌟 Crítico	🏗️ Alto
Programación de Entrevistas	🔴 Alta	🌟 Crítico	🔧 Medio
Chatbot para Candidatos	🟠 Media	⭐ Alto	🔧 Medio
Generación Automática de Descripciones	🟠 Media	⭐ Alto	🔧 Medio
Este backlog permite visualizar qué tareas son críticas para el MVP, qué dependencias existen y cuál es el esfuerzo estimado para cada historia de usuario.

¿Qué opinas? ¿Hacemos algún ajuste? 🚀

Este backlog permite visualizar qué tareas son críticas para el MVP, qué dependencias existen y cuál es el esfuerzo estimado para cada historia de usuario.

¿Qué opinas? ¿Hacemos algún ajuste? 🚀

## Prompt 7
Genera el backlog expuesto en una tabla markdown

# 📌 Backlog del ATS de LTI

## 📊 Criterios de Priorización y Esfuerzo:
- **Prioridad:** 🔴 Alta | 🟠 Media | 🔵 Baja  
- **Impacto:** 🌟 Crítico | ⭐ Alto | ✨ Medio | 🌑 Bajo  
- **Esfuerzo:** ⚡ Bajo (1-2 días) | 🔧 Medio (3-5 días) | 🏗️ Alto (6+ días)  

---

## 🏗️ **Backlog Detallado**

| **HU** | **Subtarea** | **Prioridad** | **Impacto** | **Esfuerzo** | **Dependencias** |
|--------|-------------|--------------|-------------|-------------|------------------|
| **Cribado Automático de CVs con IA** | Definir criterios de filtrado | 🔴 Alta | 🌟 Crítico | ⚡ Bajo | - |
|  | Desarrollar el motor de IA | 🔴 Alta | 🌟 Crítico | 🏗️ Alto | - |
|  | Entrenar el modelo con datos históricos | 🔴 Alta | 🌟 Crítico | 🏗️ Alto | - |
|  | Diseñar interfaz para visualizar ranking | 🟠 Media | ⭐ Alto | 🔧 Medio | - |
|  | Integrar con la carga de CVs | 🟠 Media | ⭐ Alto | 🔧 Medio | La carga de CVs debe estar lista |
| **Generación Automática de Descripciones** | Definir estructura estándar | 🟠 Media | ⭐ Alto | ⚡ Bajo | - |
|  | Desarrollar modelo de IA | 🟠 Media | ⭐ Alto | 🔧 Medio | - |
|  | Permitir ajustes manuales | 🟠 Media | ⭐ Alto | ⚡ Bajo | - |
|  | Integrar con publicación de vacantes | 🟠 Media | ⭐ Alto | 🔧 Medio | Módulo de vacantes debe estar listo |
| **Chatbot para Candidatos** | Diseñar flujo de conversación | 🟠 Media | ⭐ Alto | ⚡ Bajo | - |
|  | Implementar respuestas FAQ | 🟠 Media | ⭐ Alto | ⚡ Bajo | - |
|  | Conectar chatbot con estado del proceso | 🟠 Media | ⭐ Alto | 🔧 Medio | La base de datos de estados debe estar disponible |
|  | Integrar con módulo de entrevistas | 🟠 Media | ⭐ Alto | 🔧 Medio | Módulo de entrevistas debe estar listo |
| **Feedback Colaborativo en Candidatos** | Diseñar sistema de comentarios | 🔴 Alta | ⭐ Alto | ⚡ Bajo | - |
|  | Crear permisos y visibilidad según roles | 🔴 Alta | ⭐ Alto | ⚡ Bajo | - |
|  | Integrar notificaciones en tiempo real | 🔴 Alta | ⭐ Alto | 🔧 Medio | - |
|  | Historial de feedback en cada perfil | 🔴 Alta | ⭐ Alto | 🔧 Medio | Módulo de perfiles de candidatos debe estar listo |
| **Portal de Seguimiento para Candidatos** | Definir estados de postulaciones | 🔴 Alta | 🌟 Crítico | ⚡ Bajo | - |
|  | Diseñar UI para el portal | 🔴 Alta | 🌟 Crítico | 🔧 Medio | - |
|  | Implementar tracking en tiempo real | 🔴 Alta | 🌟 Crítico | 🏗️ Alto | - |
|  | Notificaciones automáticas en cambios de estado | 🔴 Alta | 🌟 Crítico | 🔧 Medio | Flujo de selección debe estar activo |
| **Programación de Entrevistas** | Mostrar disponibilidad de entrevistadores | 🔴 Alta | 🌟 Crítico | ⚡ Bajo | - |
|  | Enviar invitaciones a candidatos | 🔴 Alta | 🌟 Crítico | 🔧 Medio | - |
|  | Sincronizar con Google Calendar y Outlook | 🔴 Alta | 🌟 Crítico | 🔧 Medio | - |
|  | Confirmar entrevista tras aceptación del candidato | 🔴 Alta | 🌟 Crítico | ⚡ Bajo | Integración con calendarios debe estar lista |

---

## 📌 Priorización Global del Backlog

| **Historia de Usuario** | **Prioridad** | **Impacto** | **Esfuerzo** |
|-----------------|------------|---------|---------|
| **Cribado Automático de CVs con IA** | 🔴 Alta | 🌟 Crítico | 🏗️ Alto |
| **Feedback Colaborativo en Candidatos** | 🔴 Alta | ⭐ Alto | 🔧 Medio |
| **Portal de Seguimiento para Candidatos** | 🔴 Alta | 🌟 Crítico | 🏗️ Alto |
| **Programación de Entrevistas** | 🔴 Alta | 🌟 Crítico | 🔧 Medio |
| **Chatbot para Candidatos** | 🟠 Media | ⭐ Alto | 🔧 Medio |
| **Generación Automática de Descripciones** | 🟠 Media | ⭐ Alto | 🔧 Medio |



Este backlog en Markdown está listo para usarse en plataformas como Jira, Trello, GitHub Projects o Notion. 📊🚀

Si necesitas algún ajuste, dime y lo refinamos. 😃

## Prompt 8:
Tomando la HU 1 puedes sugerir un listado de actividades técnicas  (desarrollo) para ésta Hu y sus sutareas.

## Respuesta 8:
Aquí tienes un listado de actividades técnicas para la HU 1: Cribado Automático de CVs con IA, desglosado por subtareas.

🔹 HU 1: Cribado Automático de CVs con IA
Como reclutador, quiero que el sistema analice automáticamente los CVs y los clasifique según su compatibilidad con la oferta, para agilizar el proceso de selección y centrarme en los mejores candidatos.

📌 Actividades Técnicas por Subtarea
1️⃣ Definir criterios de filtrado (⚡ Bajo esfuerzo)
✅ Actividades:

 Analizar los criterios de selección estándar de HR.
 Definir qué atributos del CV serán evaluados (habilidades, experiencia, educación, etc.).
 Determinar el peso de cada criterio en la clasificación final.
 Establecer reglas de filtrado manuales y automáticas.
2️⃣ Desarrollar el motor de IA (🏗️ Alto esfuerzo)
✅ Actividades:

 Seleccionar el framework de IA (TensorFlow, PyTorch, Scikit-learn, etc.).
 Construir el pipeline de preprocesamiento de CVs (parseo, limpieza de texto, extracción de datos clave).
 Implementar técnicas de NLP (Procesamiento de Lenguaje Natural) para analizar textos de los CVs.
 Entrenar modelos de clasificación de candidatos según criterios definidos.
 Evaluar el rendimiento del modelo con métricas como precisión y recall.
 Implementar un sistema de feedback para mejorar el modelo con datos reales.
3️⃣ Entrenar el modelo con datos históricos (🏗️ Alto esfuerzo)
✅ Actividades:

 Recopilar datos de procesos de selección anteriores (CVs, resultados de entrevistas, contrataciones).
 Anonimizar datos sensibles según regulaciones de privacidad (GDPR, etc.).
 Convertir datos en un formato estructurado (JSON, CSV, base de datos).
 Ajustar hiperparámetros del modelo para mejorar la precisión.
 Implementar validación cruzada para evitar sobreajuste (overfitting).
 Evaluar desempeño del modelo en casos de prueba reales.
4️⃣ Diseñar interfaz para visualizar ranking de candidatos (🔧 Medio esfuerzo)
✅ Actividades:

 Crear wireframes y mockups de la UI para visualizar los candidatos clasificados.
 Diseñar una tabla o dashboard interactivo con filtros y ordenamientos.
 Implementar una barra de progreso o puntuación para cada candidato.
 Permitir a los reclutadores modificar manualmente los rankings.
 Conectar la UI con el backend para obtener datos en tiempo real.
5️⃣ Integrar con la carga de CVs en la plataforma (🔧 Medio esfuerzo)
✅ Actividades:

 Implementar un sistema de subida de archivos (PDF, DOCX, TXT).
 Utilizar una librería de extracción de texto como Tika o PyMuPDF.
 Almacenar los datos extraídos en una base de datos estructurada.
 Enviar los CVs al motor de IA para su análisis.
 Mostrar los resultados de clasificación en la UI de reclutadores.
📌 Dependencias Técnicas
✅ Requiere:
☑️ Un módulo de carga de CVs funcional.
☑️ Una base de datos estructurada con candidatos.
☑️ Un framework de IA y NLP para el análisis.
☑️ Una UI funcional para la visualización de resultados.

Este desglose cubre desde definición de reglas hasta implementación de IA, UI e integración con otros módulos del ATS. 🚀

¿Quieres que agreguemos algo más, como pruebas o seguridad? 😃

## Conclusión
Creo que los prompt que generaron los mejores resultados fueron el 1 y 2 donde se genero el contexto d elo que se buscaba, ya que el asistente, se empezo a comportar de forma intuitiva y concreta, conociendo que el objetivo era el backlog. 