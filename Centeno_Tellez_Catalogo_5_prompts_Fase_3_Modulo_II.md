# Catálogo de cinco prompts · Fase 3: Evaluar con IAGen e integrar la experiencia educativa

**Universidad Veracruzana · Diplomado PROFA · Módulo II · Semana 3**
**Producto 2 · Catálogo de cinco prompts · 15 % del módulo**
**Nombre del archivo:** `Centeno_Tellez_Catalogo_5_prompts_Fase_3_Modulo_II.md`

**Docente:** Adolfo Centeno Tellez.
**EE o campo disciplinar:** Inteligencia Artificial, Licenciatura en Ingeniería de Software.
**Fecha y versión:** 27 de noviembre de 2026 · v01.

## Índice de los cinco prompts

| ID | Nombre | Función | Fase de origen | Estado |
| --- | --- | --- | --- | --- |
| P1 | Planeación alineada con el PEE | Planificar | Fase 1, registro del Anexo C | Probado |
| P2 | Guía de progreso para Hopfield | Planificar | Fase 1–2, depurado en Fase 3 | Revisado sin ejecución |
| P3 | Producción de una guía MLP con trazabilidad | Producir | Fase 2, basado en el portafolio M3 | Revisado sin ejecución |
| P4 | Contraste reproducible con TensorFlow | Producir | Fase 2–3, basado en el plan R3 | Revisado sin ejecución |
| P5 | Instrumento de retroalimentación disciplinar | Evaluar | Fase 3, derivado del plan de clase | Revisado sin ejecución |

## P1 · Planeación alineada con el PEE

**Función y fase de origen:** Planificar · Fase 1.
**Propósito didáctico:** Completar una planeación didáctica congruente con la EE sin atribuir al PEE datos institucionales no verificados.
**Relación con tu plan o materiales:** Sustenta la planeación de redes Hopfield, MLP y TensorFlow y las decisiones de uso responsable de IAGen.

**Información que debe proporcionar quien lo utilice:**

- Nombre, programa educativo, plantilla Markdown y PEE o fragmentos autorizados.
- Grupo, duración, recursos disponibles y resultados que realmente desea evaluar.
- Saberes, actividades, evidencias y decisiones institucionales que deben conservarse.
- Datos no identificables; no utilizar nombres, expedientes ni resultados individuales de estudiantes.

**Variables que se deben adaptar:** Sustituir `[EE]`, `[grupo]`, `[duración]`, `[materiales]` y `[resultado]`; ampliar o reducir los saberes según la plantilla vigente. La versión institucional, las horas y las ponderaciones deben proporcionarse, no inferirse.

### Texto íntegro del prompt depurado

```text
PROPÓSITO
Completar la plantilla Markdown de la Fase 1 del Diplomado PROFA, alineando la propuesta didáctica con el programa oficial de la Experiencia Educativa [EE].

AUDIENCIA
Docente universitario participante del Diplomado “IAGen para la docencia universitaria: construcción de experiencias de aprendizaje en la Universidad Veracruzana”.

CONTEXTO
El grupo cursa [nivel y programa], aproximadamente [número] estudiantes, modalidad [modalidad]. Sus saberes previos son [saberes previos]. La necesidad identificada es [necesidad no atribuida a IAGen sin evidencia]. El proyecto busca que el estudiante (1) comprenda y construya matemáticamente una red de Hopfield con operaciones de álgebra lineal y la programe en C o Java sin agentes de IA; (2) diseñe una red neuronal multicapa, aplique funciones de activación, simule sus operaciones en Excel y la implemente en Python sin frameworks, calculando y verificando pesos W y sesgos b; y (3) reproduzca ambos modelos con TensorFlow y compare parámetros y resultados con las implementaciones propias.

TIPO DE SALIDA
Documento académico de planeación didáctica en Markdown que conserve los apartados, tablas y anexos de la plantilla suministrada.

TONO Y ESTILO
Formal, académico, claro, analítico y orientado a la docencia universitaria.

HECHOS E INFORMACIÓN QUE DEBES RESPETAR
Usa solamente datos verificables del PEE y de las fuentes proporcionadas. El PEE oficial debe aportar los saberes, estrategias y evidencias aplicables. Si no aparecen Hopfield, TensorFlow, horas o porcentajes específicos, indícalo como una decisión propuesta y no como requisito textual.

RESTRICCIONES Y CRITERIOS DE CALIDAD
No atribuir al PEE contenidos, horas o porcentajes que no aparezcan en el documento. Distinguir entre contenido oficial y profundización propuesta. Completar la secuencia, las tareas, actividades, metas, evidencias, criterios, mediación y anexos. Mantener congruencia entre propósito, saberes, actividades y evaluación. No afirmar que todo uso de IA causa falta de aprendizaje. Establecer que las evidencias centrales de cálculo y programación desde cero se realicen sin agentes de IA. Incluir referencias académicas verificables en formato APA 7 y señalar límites de transferencia. Conservar el formato Markdown.

Si falta información indispensable, pregunta antes de completar la propuesta.
Explicita los supuestos. No inventes datos ni referencias. Señala los puntos que requieren verificación docente.
```

### Revisión o prueba documentada

**Estado:** Probado.
**Herramienta, versión si está disponible, y fecha:** ChatGPT (OpenAI), 16 de noviembre de 2026.
**Entrada utilizada o contexto de revisión:** Plantilla de Fase 1, PEE de Inteligencia Artificial y contexto del grupo de quinto semestre descrito sin datos identificables.
**Evidencia del procedimiento:** Se conservó una salida inicial en el Anexo C de `Centeno_Tellez_IA_Fase1_Planeacion_v01.md`. El docente verificó la plantilla, ajustó el alcance y distinguió propuestas de requisitos institucionales.
**Cambios entre el prompt inicial y el depurado:**

| Fragmento o instrucción inicial | Ajuste | Razón y evidencia |
| --- | --- | --- |
| Completar la planeación sin reservar datos ausentes | Se añadió prohibición de atribuir horas, porcentajes o contenidos no presentes | Evitar fabricaciones por falta de detalle institucional |
| Uso central de IAGen sin límite | Se exige que cálculo y programación centrales sean sin agentes | Coincide con las reglas del Módulo II |
| “Completa el documento” | Se agregaron siete componentes, supuestos y solicitud de datos faltantes | Hace reutilizable el encargo por otro docente |

### Transferencia y límites

**Salida esperada y criterios para aceptarla:** Plan alineado con PEE proporcionado, campos completos, propuestas marcadas, fuentes APA verificables y decisiones docentes explícitas. Se acepta si las afirmaciones pueden trazarse al documento fuente.
**Qué no aceptar sin revisión:** Horas o porcentajes inventados, niveles AIAS atribuidos sin fuente, afirmaciones sobre el grupo no contrastadas y recomendaciones ajenas al PEE.
**Fuentes o procedimientos de comprobación:** PEE institucional vigente, plantilla del diplomado, referencias consultadas y revisión docente final.
**Decisión que conserva el docente:** Selección de contenidos, ponderación, temporalización, nivel AIAS y ajuste de nivel disciplinar.
**Condiciones de reutilización y procedencia:** Autoría: Adolfo Centeno Tellez, con apoyo de ChatGPT documentado el 16 de noviembre de 2026. En otra EE deben reemplazarse PEE, programa, tiempos y evidencias; no reutilizar las decisiones como si fueran normas institucionales.
**Pendientes:** Confirmar formato institucional vigente, horas, calendario y descriptor exacto AIAS 2.1.

## P2 · Guía de progreso para Hopfield

**Función y fase de origen:** Planificar · Fase 1–2, depurado en Fase 3.
**Propósito didáctico:** Preparar una guía graduada que permita planificar la construcción y verificación de una red Hopfield.
**Relación con tu plan o materiales:** Apoya M1/M2, el diagnóstico de álgebra lineal y el resultado R1 del plan de clase.

**Información que debe proporcionar quien lo utilice:**

- Nivel, patrón bipolares de ejemplo, dimensión pequeña y convenios de actualización.
- Tiempo disponible, recursos de C/Java, Excel o papel.
- Criterios exigidos y apoyo o alternativa de acceso.
- Una matriz o conjunto de patrones de ejemplo; no datos personales.

**Variables que se deben adaptar:** `[nivel]`, `[dimensión]`, `[patrones]`, `[ruido]`, `[lenguaje]`, `[tiempo]` y `[apoyo]`.

### Texto íntegro del prompt depurado

```text
PROPÓSITO
Diseñar una guía breve de aprendizaje para construir y comprobar una red de Hopfield en [EE], haciendo visibles los cálculos y evitando que la ejecución sustituya el razonamiento.

AUDIENCIA
Estudiantes de [nivel] con conocimientos previos de [álgebra_lineal] y [programación].

CONTEXTO
Disponemos de [tiempo] minutos, [patrones] patrones bipolares de ejemplo y [lenguaje o formato]. La actividad debe avanzar desde la representación manual hasta el código propio en [C/Java/papel]. Hay acceso limitado a equipos: [condiciones].

TIPO DE SALIDA
Una guía con pasos numerados, una tabla de comprobación, al menos dos casos de prueba (uno completo y uno con ruido) y una pregunta de defensa individual. Máximo [número] páginas o [número] apartados.

TONO Y ESTILO
Claro, técnico y gradual; explica convenciones sin resolver la evidencia central del estudiante.

HECHOS E INFORMACIÓN QUE DEBES RESPETAR
Usa una dimensión explícita y coherente. La matriz W debe ser simétrica, con diagonal [convención: cero]. Las actualizaciones deben indicar si son síncronas o asíncronas. No inventes patrones, resultados ni convergencias.

RESTRICCIONES Y CRITERIOS DE CALIDAD
Incluir: cálculo por pasos, registro de dimensiones, prueba completa, prueba con ruido, error esperado o posible, criterio de aceptación y alternativa sin equipo. Separar guía y solución de ejemplo. Antes de cada fase, indicar qué decisión conserva el docente.

Si falta información indispensable, pregunta antes de completar la propuesta.
Explicita los supuestos. No inventes datos ni referencias. Señala los puntos que requieren verificación docente.
```

### Revisión o prueba documentada

**Estado:** Revisado sin ejecución.
**Herramienta, versión si está disponible, y fecha:** No ejecutado. Revisión documental el 27 de noviembre de 2026.
**Entrada utilizada o contexto de revisión:** Variables de P2, la matriz Hopfield del tema 1 y el resultado R1. No se utilizaron datos de estudiantes.
**Evidencia del procedimiento:** Se revisaron instrucciones, variables, formato de salida, criterios y límite de acceso. Falta comprobar que una herramienta siga todas las convenciones matemáticas para dimensiones, diagonal, tipo de actualización y convergencia.
**Cambios entre el prompt inicial y el depurado:**

| Fragmento o instrucción inicial | Ajuste | Razón y evidencia |
| --- | --- | --- |
| Actividad general de redes Hopfield | Se especificaron patrón bipolar, dimensión y actualización | Evita ambigüedad de entrada y salida |
| Solicitud sin criterios | Se añadieron tabla, pruebas con ruido y defensa | Alinea con M2 y R1 |
| Supone acceso a equipo | Se añadió alternativa en papel | Conserva equivalencia de desempeño y acceso |

### Transferencia y límites

**Salida esperada y criterios para aceptarla:** Guía con pasos ejecutables, convenciones, tabla W/b cuando aplique y criterios verificables. Se acepta si ninguna prueba requiere asumir datos no entregados.
**Qué no aceptar sin revisión:** Afirmaciones de convergencia sin procedimiento, matrices de dimensión incompatible, pérdida de diagonal cero y respuestas que generen la solución central del estudiante.
**Fuentes o procedimientos de comprobación:** Revisión contra Hopfield (1982), M2 y la rúbrica I1.
**Decisión que conserva el docente:** Patrón, convenio, nivel de ayuda, aceptación de una convergencia y uso de herramientas.
**Condiciones de reutilización y procedencia:** Prompt derivado de los contenidos y materiales del repositorio del curso; adaptar patrones y convenciones al nivel de otra EE. No atribuirlo a una fuente ajena.
**Pendientes:** Probar con una dimensión pequeña y dos patrones; comprobar que la herramienta no contradiga el tipo de actualización.

## P3 · Producción de una guía MLP con trazabilidad

**Función y fase de origen:** Producir · Fase 2, basado en M3.
**Propósito didáctico:** Crear instrucciones y una plantilla de verificación para una MLP implementada desde cero.
**Relación con tu plan o materiales:** Se vincula con `tema2/neural_network_numpy.py`, `tema2/tema2_neural_network_scratch.xlsx` y R2.

**Información que debe proporcionar quien lo utilice:**

- Arquitectura, entradas y etiquetas de control.
- Funciones de activación y convenciones de dimensiones.
- Entorno Python permitido, sin frameworks en la evidencia central.
- Criterios de tolerancia, formato de entrega y recursos disponibles.

**Variables que se deben adaptar:** `[arquitectura]`, `[activación]`, `[datos]`, `[entorno]`, `[tol]`, `[tiempo]` y `[formato]`.

### Texto íntegro del prompt depurado

```text
PROPÓSITO
Producir una guía docente–estudiante para implementar una red neuronal multicapa desde cero y verificar pesos W y sesgos b por capa.

AUDIENCIA
Estudiantes de [nivel] que deben demostrar razonamiento matricial y depuración sin generar su solución final con IAGen.

CONTEXTO
Arquitectura [2-n-1 o otra], datos de control [datos], activación [sigmoide/ReLU/tanh], entorno [Python/Numpy] y tiempo [tiempo]. La evidencia debe coincidir con una hoja de cálculo o ejemplo manual y puede ejecutarse con una alternativa impresa si no hay equipo.

TIPO DE SALIDA
Una guía con: arquitectura y dimensiones; fórmula por capa; tabla para W y b; pruebas de entradas conocidas; tabla de discrepancias; checklist de entrega; cinco preguntas de defensa. No proporciones una solución completa ni ocultes cálculos intermedios.

TONO Y ESTILO
Didáctico, preciso y no prescriptivo sobre decisiones que correspondan al estudiante.

HECHOS E INFORMACIÓN QUE DEBES RESPETAR
Reportar dimensiones de cada entrada, producto y salida. Para cada capa indicar W, b, suma ponderada y activación. Usar tolerancia [tol] solo si se declara. No fabricar resultados ni afirmar coincidencia entre Python y Excel sin datos ejecutados.

RESTRICCIONES Y CRITERIOS DE CALIDAD
La guía debe exigir trazabilidad entre Excel y código, casos de control, registro de errores y corrección. IAGen no puede generar la solución evaluada ni completar W/b. Si falta información, preguntar. Separar claramente apoyo permitido, producto propio y decisión docente.

Si falta información indispensable, pregunta antes de completar la propuesta.
Explicita los supuestos. No inventes datos ni referencias. Señala los puntos que requieren verificación docente.
```

### Revisión o prueba documentada

**Estado:** Revisado sin ejecución.
**Herramienta, versión si está disponible, y fecha:** No ejecutado. Revisión documental el 27 de noviembre de 2026.
**Entrada utilizada o contexto de revisión:** R2, M3, arquitectura 2–4–1 como alternativa y criterios de IAGen del plan.
**Evidencia del procedimiento:** Se revisó que la salida solicita dimensiones, W/b, prueba manual–código y defensa. No se ejecutó la salida ni se usó el script con datos reales.
**Cambios entre el prompt inicial y el depurado:**

| Fragmento o instrucción inicial | Ajuste | Razón y evidencia |
| --- | --- | --- |
| “Crea una guía de redes” | Se fijó MLP desde cero con arquitectura y activación variables | Hace verificable la correspondencia |
| Código permitido sin límites | Se prohibió IAGen en el producto central | Regla explícita de instrucción.txt y Fase 2 |
| Solo resultado final | Se exigieron dimensiones, W/b y discrepancias | Trazabilidad y criterios del módulo |

### Transferencia y límites

**Salida esperada y criterios para aceptarla:** Guía completa, tabla W/b por capa, pruebas controladas, registro de discrepancias y alternativa de acceso. Aceptar solo si el entorno y las tolerancias están declarados.
**Qué no aceptar sin revisión:** Pesos o sesgos ficticios, celdas sin fórmula, activaciones incompatibles, tolerancias no justificadas y solución generada por IA como evidencia propia.
**Fuentes o procedimientos de comprobación:** Comparar contra hoja Excel, `neural_network_numpy.py`, checklist de M3 y Goodfellow et al. (2016).
**Decisión que conserva el docente:** Arquitectura, activación, datos, tolerancia, nivel de apoyo y criterio de logro.
**Condiciones de reutilización y procedencia:** Derivado del portafolio de Fase 2 y de materiales base del tema 2. En otra EE pueden cambiarse lenguaje, nivel y arquitectura; conservar la separación entre ayuda y evidencia central.
**Pendientes:** Ejecutar el prompt, probar una arquitectura mínima y confirmar que la guía no exponga una solución completa.

## P4 · Contraste reproducible con TensorFlow

**Función y fase de origen:** Producir · Fase 2–3, basado en R3 y M4.
**Propósito didáctico:** Generar una guía para comparar una implementación propia con TensorFlow sin atribuir diferencias automáticamente a la herramienta.
**Relación con tu plan o materiales:** Apoya `tema3/gps_tensorflow_keras.py`, extracción de W/b y la evidencia E3.

**Información que debe proporcionar quien lo utilice:**

- Arquitectura, datos, semilla, inicialización y optimizador.
- Versión de TensorFlow y/o forma de ejecutar sin acceso.
- Tabla comparativa, precisión esperada y criterio de diferencias aceptables.
- Sin datos identificables de estudiantes.

**Variables que se deben adaptar:** `[arquitectura]`, `[datos]`, `[semilla]`, `[framework]`, `[versión]`, `[tol]`, `[hardware]`.

### Texto íntegro del prompt depurado

```text
PROPÓSITO
Producir una guía reproducible para comparar una implementación propia de una red con su equivalente en TensorFlow y explicar las diferencias observadas.

AUDIENCIA
Estudiantes de [nivel] que conservan una implementación propia verificable y deben interpretar su comparación con un framework.

CONTEXTO
Arquitectura [arquitectura], datos [datos], semilla [semilla], inicialización [inicialización], optimizador [optimizador], TensorFlow [versión] y tolerancia [tol]. Se dispone de [hardware] y [tiempo]. Mantener constantes el máximo posible.

TIPO DE SALIDA
Una guía y una tabla con W y b por capa, forma de entrada/salida, predicción de control, observación ejecutada, diferencia absoluta o relativa y explicación plausible. Incluir comandos o pasos de reproducción, pero no afirmar resultados.

TONO Y ESTILO
Experimental y crítico: distingue evidencia, hipótesis y decisión docente.

HECHOS E INFORMACIÓN QUE DEBES RESPETAR
No inventar semillas, versiones, pesos ni resultados. Cada diferencia debe relacionarse con inicialización, entrenamiento, precisión, redondeo o algoritmo verificable. Señalar si falta ejecutar TensorFlow o comparar datos.

RESTRICCIONES Y CRITERIOS DE CALIDAD
Exigir: equivalencia de arquitectura; datos iguales; semilla o aleatoriedad declarada; extracción de W/b; ejecución reproducible; comparación y límites. El docente decide si una diferencia es aceptable. Si la ejecución no es posible, entregar una salida esperada claramente marcada como hipótesis.

Si falta información indispensable, pregunta antes de completar la propuesta.
Explicita los supuestos. No inventes datos ni referencias. Señala los puntos que requieren verificación docente.
```

### Revisión o prueba documentada

**Estado:** Revisado sin ejecución.
**Herramienta, versión si está disponible, y fecha:** No ejecutado. Revisión documental el 27 de noviembre de 2026.
**Entrada utilizada o contexto de revisión:** Arquitectura propuesta en R3, script base de TensorFlow y criterios de semilla fija.
**Evidencia del procedimiento:** Se revisaron variables, comparabilidad, extracción de W/b y condiciones de interpretación. Falta ejecutar el script, fijar semillas y registrar versiones y datos reales.
**Cambios entre el prompt inicial y el depurado:**

| Fragmento o instrucción inicial | Ajuste | Razón y evidencia |
| --- | --- | --- |
| Comparar implementaciones libremente | Se añadieron arquitectura, datos y semilla iguales | Permite atribuir diferencias |
| Afirmar que los resultados coinciden | Se exige salida ejecutada y tolerancia | Evita conclusiones sin evidencia |
| No declarar entorno | Se requiere versión, hardware y tiempo | Reproducibilidad |

### Transferencia y límites

**Salida esperada y criterios para aceptarla:** Tabla reproducible de W/b y resultados; diferencias cuantificadas; explicación con causas verificables; limitaciones declaradas.
**Qué no aceptar sin revisión:** Pesos inventados, datos no iguales, ejecución sin semilla ni versión, diferencias atribuidas sin prueba y uso de métricas inconmensurables.
**Fuentes o procedimientos de comprobación:** Ejecutar `gps_tensorflow_keras.py`, comparar con el modelo propio y comprobar documentación del framework usado.
**Decisión que conserva el docente:** Configuración, tolerancia, criterio de equivalencia y forma de interpretar diferencias.
**Condiciones de reutilización y procedencia:** Adaptado del plan de clase y material base del tema 3. Otro curso debe declarar framework, versión y entorno.
**Pendientes:** Ejecutar en TensorFlow disponible, registrar versión y semilla, extraer W/b y comparar con una implementación desde cero.

## P5 · Instrumento de retroalimentación disciplinar

**Función y fase de origen:** Evaluar · Fase 3, derivado del plan de clase.
**Propósito didáctico:** Construir un borrador de criterios y retroalimentación para una evidencia técnica; la calificación sigue bajo responsabilidad docente.
**Relación con tu plan o materiales:** Apoya I1/I2/I3 y la retroalimentación de resultados R1–R4.

**Información que debe proporcionar quien lo utilice:**

- Evidencia técnica, fragmentos relevantes y criterios conocidos.
- Resultado de aprendizaje, nivel, modalidad y oportunidad de corrección.
- Límites, datos anonimizados y decisión final que conserva el docente.
- No enviar nombres, expedientes ni datos sensibles.

**Variables que se deben adaptar:** `[evidencia]`, `[criterios]`, `[nivel]`, `[actividad]`, `[máximo]`, `[retroalimentación]`.

### Texto íntegro del prompt depurado

```text
PROPÓSITO
Diseñar una lista de cotejo o rúbrica breve y una retroalimentación formativa para [actividad], sin sustituir la valoración ni las decisiones del docente.

AUDIENCIA
Docente de [EE] y estudiante no identificado. La salida debe ayudar a revisar una evidencia técnica de nivel [nivel].

CONTEXTO
Resultado [resultado], evidencia [evidencia], criterios [criterios], modalidad [modalidad], tiempo de corrección [tiempo] y límite [límites]. Solo proporciona fragmentos anonimizados y suficientes para verificar el desempeño.

TIPO DE SALIDA
Una tabla con criterio, evidencia observable, nivel logrado, señal de mejora y acción posterior. Luego, un comentario breve con máximo [máximo] puntos fuertes, [máximo] errores prioritarios y una próxima acción. No asignar calificación final ni acreditar razonamiento que no esté demostrado.

TONO Y ESTILO
Específico, respetuoso, accionable y centrado en evidencia.

HECHOS E INFORMACIÓN QUE DEBES RESPETAR
No inventar cálculos, ejecuciones ni declaraciones del estudiante. Separar lo observado, lo supuesto y lo pendiente de comprobar. Para evidencia matemática o de código, verificar únicamente lo entregado.

RESTRICCIONES Y CRITERIOS DE CALIDAD
Priorizar un máximo de tres errores relevantes. Señalar si falta información para juzgar un criterio. No inferir ética o comprensión fuera de la evidencia. Mantener los criterios aprobados por el docente y la posibilidad de corregir.

Si falta información indispensable, pregunta antes de completar la propuesta.
Explicita los supuestos. No inventes datos ni referencias. Señala los puntos que requieren verificación docente.
```

### Revisión o prueba documentada

**Estado:** Revisado sin ejecución.
**Herramienta, versión si está disponible, y fecha:** No ejecutado. Revisión documental el 27 de noviembre de 2026.
**Entrada utilizada o contexto de revisión:** Instrumentos I1–I3 y criterios de R1–R4, con evidencia simulada y sin datos personales.
**Evidencia del procedimiento:** Se revisó que separa hecho, supuesto y pendiente; limita errores prioritarios; conserva criterios y decisión docente. Falta probar la salida con un fragmento real de evidencia y comprobar su utilidad.
**Cambios entre el prompt inicial y el depurado:**

| Fragmento o instrucción inicial | Ajuste | Razón y evidencia |
| --- | --- | --- |
| Solicitar calificación automática | Se limitó a borrador formativo | La valoración permanece bajo responsabilidad docente |
| Comentarios generales | Se exigieron evidencia, nivel, mejora y acción | Permiten retroalimentar |
| Entrada con resultados identificables | Se exige datos anonimizados | Protección de información estudiantil |

### Transferencia y límites

**Salida esperada y criterios para aceptarla:** Tabla trazable, comentarios accionables, límites declarados y sin calificación final. Aceptar si distingue ejecución comprobada de inferencia.
**Qué no aceptar sin revisión:** Juicios globales sin evidencia, datos identificables, calificación sin criterios, inferencias sobre integridad ética y consejos ajenos al contexto.
**Fuentes o procedimientos de comprobación:** I1–I3 del plan de clase, criterios aprobados y contraste con el fragmento entregado.
**Decisión que conserva el docente:** Criterio, nivel, calificación, oportunidad de corrección y uso de la retroalimentación.
**Condiciones de reutilización y procedencia:** Derivado del diseño docente de Fase 3. Adaptar criterios y anonimizaciones a otra EE; no reutilizar la salida como evaluación automática.
**Pendientes:** Ejecutar con una evidencia simulada, comprobar sesgos, longitud y utilidad antes de usarla con un estudiante.

## Revisión del conjunto y entrega

- [x] Incluí exactamente cinco prompts con su texto completo.
- [x] El conjunto cubre planificación, producción y evaluación.
- [x] Cada prompt tiene una función identificable y relación con el trabajo del módulo.
- [x] Las variables y los insumos permiten que otro docente lo adapte.
- [x] Declaré si se probó o se revisó sin ejecución y conservé evidencia del procedimiento.
- [x] Documenté cambios, criterios de aceptación y límites de cada salida.
- [x] Distinguí las propuestas de IAGen de las decisiones docentes.
- [x] Identifiqué procedencia, atribuciones y pendientes.

**Prueba final de uso independiente:** Al leer P4 como otro docente se cuentan con arquitectura, datos, semilla, inicialización, optimizador, versión, tolerancia, hardware y tiempo. También se indican tipo de salida, prohibición de inventar resultados y decisión que conserva el docente. P4 puede iniciar el trabajo sin ayuda. Las variables P2–P5 están explícitas en cada ficha.

| Criterio del catálogo | Peso | Nivel 0–3 | Evidencia y ajuste |
| --- | --- | --- | --- |
| Cobertura y pertinencia | 20 | 3 | Cinco fichas: P1–P2 planifican, P3–P4 producen y P5 evalúa; todas se relacionan con el plan. |
| Contexto y estructura | 20 | 3 | Cada ficha conserva los siete componentes, variables, insumos y relación didáctica. |
| Revisión, prueba y mejora | 20 | 3 | P1 declara prueba con ChatGPT; P2–P5 declaran revisión sin ejecución y pendientes concretos. |
| Verificación y juicio docente | 20 | 3 | Se indican criterios, fuentes, límites y decisiones docentes; no se atribuyen resultados no ejecutados. |
| Transferencia y organización | 20 | 3 | Índice completo, procedencia, adaptaciones y prueba final de uso independiente. |

**Autoevaluación global:** 15/15 posibles. Ajustes pendientes: ejecutar P2–P5 y conservar una evidencia breve de salida y revisión antes de reutilizarlas en aula.
