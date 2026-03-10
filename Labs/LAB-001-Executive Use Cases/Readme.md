# 🧪 Laboratorio MS-4004: Potenciá tu Equipo con Microsoft 365 Copilot
## Casos de Uso para Ejecutivos

> **Instructor:** Esteban Calabria — Microsoft Certified Trainer (MCT)
> **Nivel:** Intermedio | **Duración estimada:** 3-4 horas
> **Requisito:** Suscripción Microsoft 365 con licencia Microsoft 365 Copilot habilitada

---

## 📋 Descripción General

En el mundo empresarial actual, los ejecutivos enfrentan el desafío constante de tomar decisiones estratégicas bajo presión de tiempo y con una cantidad abrumadora de información. Este laboratorio demuestra cómo **Microsoft 365 Copilot** actúa como un socio inteligente que potencia las capacidades ejecutivas en toda la organización.

A lo largo de los ejercicios, vas a asumir el rol de **Director de Operaciones (COO) de Northwind Traders**, una empresa mediana especializada en alimentos y bebidas especiales. Usarás Copilot para analizar datos, crear comunicaciones ejecutivas, gestionar proyectos y obtener información estratégica que impulse resultados de negocio.

### ¿Qué vas a aprender?

Al finalizar este laboratorio, vas a poder:

- Sintetizar comunicaciones dispersas (emails, reuniones, chats) en resúmenes accionables usando **Copilot Chat en Teams**
- Transformar datos complejos de ventas en informes ejecutivos profesionales con **Copilot en Word**
- Realizar análisis de proyecciones financieras y escenarios what-if con **Copilot en Excel**
- Crear y gestionar planes de proyecto con el **Agente AI Project Manager en Microsoft Planner**
- Construir agentes de IA personalizados para monitoreo proactivo del negocio con **Copilot Studio lite**

---

## ⚙️ Configuración del Laboratorio

### Tarea de Configuración: Subir Archivos a OneDrive

Antes de comenzar con los ejercicios, necesitás subir los archivos de recursos a tu OneDrive para que Copilot pueda acceder a ellos durante todo el laboratorio.

> 📝 **Nota:** Si aparece una pantalla que dice "Estás a punto de terminar de configurar tu PC", seleccioná *Recordarme en 3 días*.

**Seguí estos pasos:**

1. Iniciá sesión en la máquina virtual como Administrador local con la contraseña `Pa55w.rd`.

2. En la barra de tareas de Windows, abrí **Microsoft Edge**.

3. En la barra de direcciones, navegá al repositorio de GitHub:
   ```
   https://github.com/MicrosoftLearning/MS-4004-Empower-workforce-copilot-use-cases
   ```

4. En la página del repositorio, hacé clic en el botón **Code** y luego seleccioná **Download ZIP** para descargar todos los archivos a tu máquina.

5. Una vez descargado el ZIP, abrí el **Explorador de archivos** y navegá hasta la carpeta de descargas.

6. Hacé clic derecho sobre el archivo ZIP descargado y seleccioná **Extraer todo**.

7. Volvé a **Microsoft Edge** y en la barra de direcciones ingresá:
   ```
   https://www.office.com
   ```

8. En la pantalla de bienvenida de Microsoft 365, seleccioná **Iniciar sesión**.

9. En el campo de inicio de sesión, ingresá `usuario@tutenantaqui.onmicrosoft.com` (usuario y tenant proporcionados por tu proveedor) y seleccioná **Siguiente**.

10. Ingresá la contraseña de tu cuenta y seleccioná **Iniciar sesión**.

11. En Microsoft 365, seleccioná **Aplicaciones** en el panel de navegación.

12. Dentro de Aplicaciones, seleccioná **OneDrive**.

13. En OneDrive, en la esquina superior izquierda, seleccioná **+ Crear o cargar** → **Carga de archivos**.

14. En el Explorador de archivos, navegá hasta donde extrajiste los archivos del repositorio de GitHub y abrí la carpeta **ResourceFiles**.

15. Seleccioná **todos los archivos** dentro de la carpeta ResourceFiles y hacé clic en **Abrir** para subirlos a OneDrive.

16. Cuando finalice la carga, vas a ver el mensaje *"Elementos cargados a Mis archivos"* en la parte inferior de la pantalla.

17. Dejá Edge abierto y continuá con el siguiente ejercicio.

---

### Tarea de Referencia: ¿Por qué algunos archivos no aparecen en Copilot?

Cuando uses Copilot, es posible que algunos archivos no aparezcan inmediatamente en las sugerencias. Esto ocurre porque ciertas experiencias de Copilot solo hacen referencia a archivos de la lista de **Usados Recientemente (MRU)**. Para asegurarte de que un archivo aparezca en esa lista, simplemente abrilo en la aplicación de Microsoft 365 correspondiente y se agregará automáticamente.

---

## 🏢 Ejercicio 1: Sintetizar Información de Comunicaciones en Microsoft Teams

### Contexto del Ejercicio

Como ejecutivo, cada día te llegan decenas de emails, participás en múltiples reuniones y mantenés conversaciones en distintos canales de Teams. Encontrar la información relevante de un proyecto específico entre todo ese ruido es una tarea que puede llevar horas. Con Copilot Chat en Teams, podés obtener un resumen completo y accionable en segundos.

---

### Tarea 1: Resumir Comunicaciones de un Proyecto con Copilot Chat

**Escenario:** Pensá en un proyecto importante en el que hayas trabajado durante los últimos 30 días. Necesitás un resumen claro y accionable de todas las comunicaciones relacionadas con esa iniciativa, sin tener que buscar manualmente entre hilos de email y conversaciones.

**Con un solo comando, Copilot Chat va a:**
- Recopilar emails relevantes, notas de reuniones y conversaciones de chat en todo tu entorno de Microsoft 365
- Destilar la información en un resumen conciso que destaque:
  - Decisiones clave tomadas
  - Actualizaciones de progreso e hitos
  - Desafíos pendientes y riesgos
  - Tendencias emergentes u oportunidades

**Pasos:**

1. En Microsoft Edge, iniciá sesión en `https://www.microsoft365.com`, seleccioná **Aplicaciones** y luego **Teams**.

2. En Teams para la web, buscá el ícono de **Copilot** en el panel de navegación izquierdo y seleccionalo. Se abre la ventana de **Microsoft 365 Copilot Chat**.

3. En el campo de texto, escribí el siguiente prompt (reemplazá el tema entre llaves con un proyecto real tuyo):
   ```
   Resumí todos mis emails, reuniones y chats de los últimos 30 días relacionados con {tema de tu elección}.
   ```

4. Cuando Copilot responda con el resumen, prestá atención a los **prompts sugeridos** que aparecen sobre el campo de texto. Estos son accesos directos que Copilot genera basándose en el contexto de la conversación.

5. Ahora pedile a Copilot que te liste todos los **ítems de acción pendientes** relacionados con el tema que elegiste. Podés usar un prompt sugerido si aparece uno apropiado, o escribirlo vos mismo.

6. Observá cómo los prompts sugeridos cambian con cada respuesta. Este diseño iterativo te permite profundizar progresivamente en el historial de comunicaciones del proyecto.

7. Finalmente, pedile a Copilot que redacte un **anuncio para las partes interesadas** basado en la actividad reciente del proyecto. No necesitás abrir Word ni ninguna otra aplicación; Copilot puede hacerlo directamente desde Teams.

> 💡 **Reflexión:** Notá cómo cada respuesta genera nuevos prompts sugeridos relacionados con los datos que Copilot encontró. Podés pedirle que genere un anuncio, que envíe un email a alguien, que identifique fechas límite, que detecte riesgos, y mucho más, todo sin salir de Teams.

---

### Tarea 2: Usar Copilot en un Chat de Teams para Resumir una Discusión

**Escenario:** Querés ponerte al día rápidamente con una conversación de Teams que se extendió durante varios días, sin tener que leer cada mensaje individualmente.

**Pasos:**

1. En Teams para la web, seleccioná **Chat** en la barra de navegación izquierda.

2. Elegí un hilo de chat que te resulte interesante, especialmente uno que se haya extendido a lo largo de varios días, como el de una reunión recurrente.

3. Hacé clic en el ícono de **Copilot** que aparece en la esquina superior derecha del chat.

4. En el panel de Copilot, vas a ver varios prompts predefinidos como *"Resumir esta discusión"*, *"¿Cuáles son los ítems pendientes?"* o *"¿Qué decisiones se tomaron?"*. Seleccioná **Ver más** para descubrir prompts adicionales y elegí el que más te interese.

5. En la respuesta de Copilot, prestá atención a las **citas al pie** que aparecen al final de cada afirmación. Cada cita es un enlace directo al mensaje original en el hilo. Hacé clic en algunas para ver cómo Copilot te lleva directamente al mensaje relevante sin que tengas que desplazarte manualmente.

6. Explorá qué dijo una persona específica en el hilo con este prompt (reemplazá con el nombre real):
   ```
   ¿Qué dijo {nombre de la persona}?
   ```

7. Usá las citas al pie para navegar directamente a los mensajes de esa persona. Notá la eficiencia de esta funcionalidad para ejecutivos que gestionan múltiples conversaciones.

---

### Tarea 3: Comparar Insights de Múltiples Proyectos

**Escenario:** Como ejecutivo, normalmente supervisás varias iniciativas estratégicas al mismo tiempo. Copilot Chat puede ayudarte a comparar el estado de distintos proyectos en segundos.

**Pasos:**

1. Abrí **Copilot Chat en Teams** como hiciste en la Tarea 1.

2. Identificá dos temas presentes en tus chats de Teams. En el campo de texto, pedile a Copilot que compare ambos proyectos:
   ```
   Compará el progreso, los riesgos y las decisiones clave de {proyecto 1} y {proyecto 2} durante los últimos 30 días. Incluí los hitos principales, decisiones tomadas, riesgos o bloqueos pendientes, y cualquier tendencia o dependencia entre ambos proyectos.
   ```

3. Revisá la respuesta y los prompts de seguimiento que sugiere Copilot. Explorá los que te parezcan útiles.

4. Para facilitar una presentación ejecutiva, pedile a Copilot que genere una **tabla comparativa lado a lado** de ambos proyectos.

5. Ahora pedile a Copilot que redacte un **email para el equipo** de uno de los proyectos. El email debe incluir los ítems de acción y los riesgos sin resolver. Aunque Copilot no abre Outlook automáticamente, sí genera el contenido del email para que puedas copiarlo y pegarlo.

---

### Tarea 4: Preparar un Resumen Ejecutivo

**Escenario:** Después de analizar las comunicaciones de los proyectos, necesitás condensar los hallazgos en un documento listo para presentar a la dirección.

**Pasos:**

1. Abrí **Copilot Chat en Teams**.

2. Basándote en los insights de la Tarea 3, pedile a Copilot que cree un resumen ejecutivo:
   ```
   Creá un resumen ejecutivo conciso con los hallazgos clave, riesgos y próximos pasos para {proyecto 1} y {proyecto 2} que pueda compartir en una reunión de liderazgo.
   ```

3. Si el resumen no tiene secciones claramente definidas (Panorama General, Aspectos Destacados, Riesgos, Recomendaciones), pedile a Copilot que lo reestructure.

4. Luego pedile que reformatee el resumen en **viñetas para una presentación de diapositivas**.

5. Finalmente, pedile que redacte una **publicación corta para Teams** que puedas compartir con ambos equipos de proyecto, resumiendo los puntos clave.

> 💡 **Reflexión:** Observá cómo Copilot puede adaptar exactamente la misma información para audiencias distintas: un resumen estructurado para la dirección, viñetas para una presentación y un mensaje informal para el equipo. Esta capacidad de comunicación adaptable es invaluable para líderes ejecutivos.

---

## 📊 Ejercicio 2: Impulsar Resultados de Negocio con Microsoft 365 Copilot

### Introducción

En este ejercicio, asumís el rol del **COO de Northwind Traders**. Vas a usar Copilot en diferentes aplicaciones de Microsoft 365 para completar una serie de tareas de alto impacto que simulan responsabilidades ejecutivas reales.

> 💡 **Consejo clave sobre prompts efectivos:** Recordá los cuatro elementos de un buen prompt: **Objetivo** (qué querés lograr), **Contexto** (quién sos y cuál es la situación), **Fuentes** (qué archivos o datos debe usar Copilot), y **Expectativas** (qué formato o detalle esperás en la respuesta).

---

### Tarea 1: Crear un Informe de Briefing Ejecutivo con Copilot en Word

**Escenario:** El Q3 terminó y debés preparar un resumen operacional para el equipo ejecutivo. Tenés los datos de ventas en un archivo Excel, pero transformarlos en un informe ejecutivo profesional tomaría horas. Copilot en Word lo hace en minutos.

**Pasos:**

1. Descargá el archivo de datos de ventas Q3 desde el siguiente enlace y guardalo en tu OneDrive:
   ```
   https://go.microsoft.com/fwlink/?linkid=2347618
   ```
   *(Archivo: Northwind Traders Q3 sales data.xlsx)*

2. Abrí la versión de escritorio de **Word** y creá un documento en blanco.

   > 📝 **¿Por qué usamos la versión de escritorio?** La versión de escritorio de Copilot en Word ofrece integración completa con OneDrive y archivos locales, lo que permite adjuntar archivos Excel directamente en los prompts. La versión web tiene capacidades más limitadas para este tipo de tareas.

3. En el campo *"Describí lo que querés redactar con Copilot"* que aparece al inicio del documento, adjuntá el archivo **Northwind Traders Q3 sales data.xlsx** que acabás de guardar en OneDrive.

4. En el mismo campo, ingresá el siguiente prompt. Prestá atención a cómo incorpora los cuatro elementos clave:

   ```
   Como COO de Northwind Traders, necesito que crees un informe de briefing estratégico para nuestro Equipo de Liderazgo Senior basado en los datos de desempeño de ventas del Q3 de la empresa, que se encuentran en el archivo adjunto Northwind Traders Q3 sales data.xlsx. Este archivo contiene datos detallados de ventas del Q3 junto con porcentajes de crecimiento interanual de ingresos y ganancias por categoría y región. Por favor, creá un informe ejecutivo profesional en Word que resuma las tendencias de ventas del Q3 y destaque las oportunidades emergentes y los riesgos potenciales. El informe debe incluir: un resumen ejecutivo, una lista con viñetas de insights clave (incluyendo las categorías y regiones de mayor rendimiento, las áreas con rendimiento en declive, y las oportunidades emergentes), y un análisis interanual claro (con gráficos) del crecimiento de ingresos y ganancias por categoría y región.
   ```

5. Revisá el documento generado. Notá que falta una sección de recomendaciones. Pedile a Copilot que la agregue:
   ```
   Agregá una sección de recomendaciones estratégicas para el Q4 que incluya iniciativas sugeridas, estrategias de mitigación de riesgos e ideas para acelerar el crecimiento.
   ```

   > 📝 **Tip:** Si Copilot muestra solo la nueva sección en lugar del informe completo, significa que el prompt no fue suficientemente específico. En ese caso, pedile: *"Mostrá el informe completo incluyendo la nueva sección de Recomendaciones Estratégicas para el Q4."*

6. Navegá entre los distintos borradores usando las flechas del panel de Copilot. Cada iteración se guarda como un borrador separado.

7. Para enriquecer el informe con una visualización final, pedile a Copilot en el último borrador:
   ```
   Insertá un gráfico que compare los ingresos del Q3 por región y categoría. Mostrá el informe completo con este nuevo gráfico incluido.
   ```

8. Cuando estés conforme con el resultado, seleccioná el botón **Conservar**. Guardá el documento como `Briefing Ejecutivo Q3.docx` en tu OneDrive. Lo vas a necesitar en la Tarea 4.

9. Ahora preparate para la reunión de liderazgo. En la pestaña **Inicio**, seleccioná la opción **Copilot** para abrir el panel lateral. Pedile:
   ```
   Generá una lista de 10 preguntas estratégicas que el CEO podría hacer después de leer este informe. Para cada pregunta, incluí una respuesta recomendada.
   ```

10. Revisá las preguntas y respuestas. Seleccioná el ícono de **Copiar respuesta** (no *Agregar al documento*) y pegá el contenido en un nuevo documento de Word para tu preparación personal.

---

### Tarea 2: Análisis de Proyección Presupuestaria con Copilot en Excel

**Escenario:** Con el Q4 a la vista, necesitás proyectar el desempeño financiero de Northwind Traders e identificar áreas donde se podrían optimizar los costos operativos. Copilot en Excel puede ayudarte a analizar tendencias, simular escenarios y tomar decisiones más informadas.

**Pasos:**

1. Descargá el archivo de proyección presupuestaria Q4 y guardalo en tu OneDrive:
   ```
   https://go.microsoft.com/fwlink/?linkid=2347811
   ```
   *(Archivo: Northwind Traders Q4 budget forecast.xlsx)*

2. En Microsoft Edge, abrí `https://www.microsoft365.com`, seleccioná **Aplicaciones** y luego **Excel**.

3. En Excel para la web, abrí el archivo **Northwind Traders Q4 budget forecast.xlsx**.

4. En la pestaña **Inicio**, seleccioná **Copilot**.
   - Si aparece un menú con las opciones **Chat** y **App Skills**, seleccioná **App Skills** para que Copilot trabaje directamente con la hoja de cálculo abierta.
   - Si tu versión de Excel ya migró a **Modo Agente**, seleccioná **Herramientas → Modo Agente**.

5. En el panel de App Skills, pedile a Copilot que analice el libro activo:
   ```
   Analizá el libro activo y proyectá los ingresos y gastos esperados para el próximo trimestre. Destacá las áreas con posible exceso de gasto, sugerí oportunidades de ahorro, y generá gráficos y tablas que resuman las métricas financieras clave.
   ```

6. Si el análisis no es suficientemente detallado, buscá el prompt *"Obtener resultados más profundos usando el modo de análisis avanzado"* en las sugerencias, o escribilo manualmente. Cuando Copilot pregunte si estás listo, seleccioná **Iniciar**.

7. Explorá los nuevos prompts sugeridos al pie del panel. Ejemplos como *"Visualizar tendencias de margen de ganancia por categoría y región"* o *"Analizar la distribución de factores de riesgo"* te ofrecen análisis más profundos. Tomá un momento para explorarlos.

8. Cuando termines, pedile a Copilot que simule un escenario de impacto:
   ```
   Creá un escenario "What-if" para una caída del 10% en las ventas y mostrá el efecto sobre el flujo de caja.
   ```

9. Para completar el análisis visual, pedile a Copilot que genere los siguientes gráficos (podés elegir todos o algunos según el tiempo disponible):

   - **Ingresos vs. Gastos por Mes** — Gráfico de columnas agrupadas que compare ingresos y gastos proyectados para el Q4
   - **Margen de Ganancia por Categoría** — Gráfico de barras que muestre qué categorías de productos tienen los márgenes más altos y más bajos
   - **Desempeño Regional** — Gráfico de columnas apiladas que muestre la contribución de ingresos por región (América del Norte, Europa, Asia) a lo largo del Q4
   - **Desglose de Costos Operativos** — Gráfico circular que muestre la proporción de costos de Cadena de Suministro, Marketing y Mano de Obra

10. Guardá el archivo **Northwind Traders Q4 budget forecast.xlsx** con el análisis completo en tu OneDrive. Lo vas a necesitar en la Tarea 4.

---

### Tarea 3: Crear un Plan de Proyecto con el Agente AI Project Manager en Planner

**Escenario:** Northwind Traders está preparando el lanzamiento de una nueva línea de snacks orgánicos. Como sponsor ejecutivo del proyecto, necesitás crear un plan organizado que involucre a los equipos de Marketing, Producción, Logística y Ventas. El Agente AI Project Manager en Planner puede generar este plan automáticamente.

> ⚠️ **Importante:** El Agente AI Project Manager en Planner está disponible dentro de la aplicación Planner en Microsoft Teams. Si abrís Planner desde la web (planner.microsoft.com), es posible que el botón de Copilot no aparezca o requiera un plan Premium.

**Pasos:**

1. En Microsoft Edge, abrí `https://www.microsoft365.com`, seleccioná **Aplicaciones** y luego **Teams**.

2. En el panel de navegación de Teams para la web, seleccioná el ícono de **Ver más aplicaciones** (los tres puntos). En el menú que aparece, buscá **Planner** o escribilo en el buscador.

3. En la página de Planner, seleccioná **Mis Planes** en el panel de navegación. Luego hacé clic en **+ Nuevo plan**.

4. En la ventana de creación, seleccioná el mosaico **Premium** (que incluye línea de tiempo, objetivos y funciones de IA).

5. En el campo **Nombre**, escribí `Nueva línea de snacks orgánicos`. Dejá el campo de grupo vacío y seleccioná **Crear**.

6. En la ventana del plan, buscá el ícono **"Chatear con tu Agente AI Project Manager"** en la esquina inferior derecha y seleccionalo.

7. En el panel del Agente, seleccioná el botón **Crear**. Esto inserta automáticamente el texto *"Crear un plan para"* en el campo de prompt. A continuación, completá con:
   ```
   la nueva línea de snacks orgánicos de Northwind Traders. El plan debe incluir tareas para los departamentos de Marketing, Producción, Logística y Ventas. Asigná fechas límite, responsables y dependencias entre tareas.
   ```

8. Revisá el plan de proyecto sugerido. Seleccioná el botón **Ir al Tablero** para ver cómo se organizaron las tareas. Es posible que el agente haya creado departamentos adicionales además de los solicitados.

9. Seleccioná **Ir a Objetivos** y revisá los resultados. Ajustá lo que consideres necesario.

10. Preguntale al Agente si puede generar **actualizaciones de progreso automáticas para las partes interesadas**. Explorá los prompts sugeridos que aparecen.

11. Pedile al Agente que exporte una **línea de tiempo visual** del proyecto para distribuir al Equipo de Liderazgo Senior.

12. Después de que el agente genere la línea de tiempo, pedile una versión descargable. Si tu versión de Planner lo soporta, descargá el archivo PNG y guardalo en tu OneDrive.

---

### Tarea 4: Crear el Agente "Northwind Business Insights"

**Escenario:** En lugar de esperar informes periódicos, querés crear un agente de IA personalizado que monitoree proactivamente los indicadores clave del negocio y alerte a los ejecutivos sobre problemas emergentes. Para esto, vas a usar la experiencia simplificada de Copilot Studio.

> 📝 **Nota:** En esta tarea usás la experiencia **Copilot Studio lite**, diseñada para usuarios de negocio sin necesidad de conocimientos de programación.

**Pasos:**

1. Abrí una nueva pestaña en Microsoft Edge y navegá a Microsoft 365.

2. En el panel de navegación, seleccioná **Nuevo agente**. Se abre el **Generador de Agentes de Copilot Studio**.

3. En el campo de prompt de la página Nuevo Agente, ingresá la siguiente descripción y seleccioná el ícono de envío:
   ```
   Creá un agente llamado "Agente de Insights de Negocio Northwind". El propósito de este agente es responder preguntas relacionadas con el desempeño de ventas de Northwind Traders, la salud de la cadena de suministro, el sentimiento de los clientes y los resultados comparados con el presupuesto proyectado del Q4. El agente solo debe usar los archivos que le asignemos como fuentes de conocimiento. El agente está destinado a una audiencia ejecutiva.
   ```

4. Esperá uno o dos minutos mientras Copilot crea el agente. Cuando aparezca el nombre y la descripción en el panel de vista previa, seleccioná la pestaña **Configurar**.

5. En la pestaña Configurar, revisá los campos **Nombre**, **Descripción** e **Instrucciones**. Notá cómo Copilot tradujo tu descripción en lenguaje natural a un conjunto detallado de instrucciones. Esta automatización es uno de los mayores valores de Copilot Studio lite.

6. Para enriquecer las instrucciones del agente, seleccioná la pestaña **Describir** e ingresá:
   ```
   Actualizá las instrucciones para incluir lo siguiente: Al generar respuestas, el agente debe: señalar información faltante o incompleta, nunca inventar datos ni basarse en fuentes externas a los documentos de conocimiento definidos, y mantenerse dentro del contexto del negocio de Northwind Traders.
   ```

7. Verificá los cambios en la pestaña **Configurar** → sección **Instrucciones**.

8. Para mejorar aún más el agente, preguntale a Copilot desde la pestaña **Describir**:
   ```
   ¿Qué otras instrucciones recomendarías para mejorar este agente?
   ```

9. Revisá las recomendaciones y pedile a Copilot que las agregue todas a las instrucciones del agente.

10. En la pestaña **Configurar**, desplazate hasta la sección **Conocimiento** y verificá que el interruptor *"Buscar en todos los sitios web"* esté **desactivado**.

11. Seleccioná el ícono **Cargar desde dispositivo** y navegá hasta tu carpeta de OneDrive. Seleccioná los siguientes archivos como fuentes de conocimiento del agente:
    - `Briefing Ejecutivo Q3.docx` (creado en la Tarea 1)
    - `Northwind Traders Q4 budget forecast.xlsx` (guardado en la Tarea 2)

12. Para los **prompts sugeridos**, probá ambos métodos:
    - **Automático:** Desde la pestaña Describir, pedile a Copilot que genere 3 prompts sugeridos para el agente.
    - **Manual:** Desde la pestaña Configurar → sección Prompts Sugeridos, agregá los prompts que elijas de la siguiente lista:

    | Título | Mensaje |
    |--------|---------|
    | Principales riesgos | ¿Cuáles son los principales riesgos para alcanzar el pronóstico de ingresos del Q4? |
    | Sentimiento del cliente | Resumí las tendencias de sentimiento del cliente de los últimos informes. |
    | Presupuesto vs. Ventas | Comparar el desempeño real de ventas con la proyección presupuestaria del Q4. |
    | Cuellos de botella | Identificá cuellos de botella en la cadena de suministro que puedan afectar los plazos de entrega del Q4. |
    | Categorías top | Destacá las categorías de productos con mejor desempeño según los datos de ventas recientes. |
    | Tendencias de mercado | ¿Qué tendencias de mercado emergentes debemos monitorear para el próximo trimestre? |

13. Probá varios de los prompts sugeridos para verificar que el agente esté tomando datos correctamente de los documentos de conocimiento.

14. Cuando estés conforme con los resultados, seleccioná el botón **Crear** para finalizar la creación del agente.

15. En el cuadro de diálogo de confirmación, seleccioná **Ir al agente**.

---

### Tarea 5: Usar el Agente para Responder Preguntas Ejecutivas

**Escenario:** Ahora que el agente está listo, es momento de ponerlo a prueba con preguntas reales de negocio basadas en los datos de ventas del Q3 y el presupuesto del Q4.

**Pasos:**

1. El **Agente de Insights de Negocio Northwind** debería seguir abierto en tu navegador.

2. Probá las siguientes preguntas ejecutivas y verificá que las respuestas sean precisas y accionables:

**Preguntas sobre el Presupuesto Q4:**

> *¿Cuál es el ingreso proyectado y el margen de ganancia para Bebidas en América del Norte en diciembre? ¿Qué conclusiones podés sacar de esta información?*

Respuesta esperada: Ingreso proyectado ~101.996 USD, margen del 16%, con análisis de factores como presión de precios competitivos, demanda estacional navideña e impacto potencial de la cadena de suministro.

---

> *Proporcioná las tres principales categorías de productos y regiones con mayor factor de riesgo proyectado en el Q4. ¿Cómo puede Northwind Traders mitigar estos riesgos?*

Respuesta esperada: Condimentos/América del Norte, Condimentos/Asia y Lácteos/Europa, con estrategias de mitigación específicas para cada caso.

---

**Preguntas sobre Ventas Q3:**

> *¿Cuál fue el ingreso y ganancia total de Snacks en América del Norte en el Q3? Proporcioná un desglose por mes.*

---

> *¿Cómo cambiaron los márgenes de ganancia de Lácteos en Asia de julio a septiembre? ¿Qué factores podrían explicar este cambio?*

---

**Preguntas Cruzadas entre Documentos:**

> *¿Cómo se comparan los márgenes de ganancia proyectados para el Q4 con los márgenes reales del Q3 para Condimentos en América del Norte?*

---

> *¿Qué escenarios "what-if" deberían preocupar más a los ejecutivos, dados los datos de ventas recientes y los riesgos proyectados?*

---

3. Además de las preguntas anteriores, creá tus propias consultas personalizadas. Para cada respuesta, verificá que el agente haga referencia a la fuente de datos correcta y brinde insights claros y accionables.

---

## ✅ Resumen del Laboratorio

¡Felicitaciones por completar el laboratorio! 🎉

A lo largo de estos ejercicios, experimentaste de primera mano cómo **Microsoft 365 Copilot** transforma la manera en que los ejecutivos trabajan:

| Tarea | Herramienta | Habilidad desarrollada |
|-------|-------------|----------------------|
| Síntesis de comunicaciones | Copilot Chat en Teams | Obtener resúmenes ejecutivos de emails, reuniones y chats |
| Informe de briefing ejecutivo | Copilot en Word | Transformar datos complejos en documentos profesionales |
| Análisis presupuestario | Copilot en Excel | Proyecciones financieras y escenarios what-if |
| Plan de proyecto con IA | Copilot en Planner | Creación automática de planes con el Agente AI |
| Agente de insights personalizado | Copilot Studio lite | Construcción de agentes de IA sin conocimientos técnicos |

### ¿Cuál es el próximo paso?

- Explorá los otros módulos del curso MS-4004 para casos de uso en otros roles (Marketing, Finanzas, RRHH, Legal, IT)
- Considerá cómo podés aplicar estas herramientas en tu entorno laboral real
- Compartí el agente creado con tu equipo para maximizar su valor organizacional

---

## 📁 Recursos Adicionales

- 🔗 [Repositorio GitHub del curso](https://github.com/MicrosoftLearning/MS-4004-Empower-workforce-copilot-use-cases)
- 🔗 [Documentación oficial de Microsoft 365 Copilot](https://learn.microsoft.com/microsoft-365-copilot)
- 🔗 [Guía de prompting efectivo para Copilot](https://adoption.microsoft.com/copilot)
- 🔗 [Microsoft Copilot Studio](https://copilotstudio.microsoft.com)

---

*Laboratorio elaborado por **Esteban Calabria** — Microsoft Certified Trainer (MCT)*
*Basado en el curso oficial MS-4004 de Microsoft Learning — Marzo 2026*
