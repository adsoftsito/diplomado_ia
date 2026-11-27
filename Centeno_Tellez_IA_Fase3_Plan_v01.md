# Plan de clase completo · Fase 3: Evaluar con IAGen e integrar la experiencia educativa

**Universidad Veracruzana · Diplomado PROFA · Módulo II · Semana 3**  
**Producto 1 · Plan de clase completo · 35 % del módulo**  
**Versión:** v01 · **Fecha:** 2026-11-27

## 1. Encuadre y fundamentación

| Dato | Información |
| --- | --- |
| Docente participante | Adolfo Centeno Tellez |
| EE y programa educativo | Inteligencia Artificial · Licenciatura en Ingeniería de Software |
| Tema, unidad y alcance | Fundamentos, implementación y comparación de redes Hopfield y multicapa |
| Grupo, nivel y modalidad | 5.º semestre, aproximadamente 30 estudiantes, presencial |
| Duración disponible | 6 semanas; 30 horas totales; secuencia integrada de 200 minutos |
| Fecha y versión | 27 de noviembre de 2026 · v01 |

**Necesidad priorizada y evidencia del diagnóstico:**

Se observa una dependencia de agentes de IA para producir código y dificultades para explicar, depurar y validar resultados matemáticos. La evidencia procede de observaciones de entregas y entrevistas breves recogidas en la Fase 1: estudiantes que no pueden modificar una solución ni explicar operaciones, dimensiones o parámetros. Es una interpretación que requiere comprobación individual, no una atribución causal generalizada.

**Características de quienes aprenderán:**

Estudiantes de quinto semestre con bases de álgebra lineal y programación, experiencia frecuente con IAGen e interés por inteligencia artificial. Necesitan apoyo en transpuestas, dimensiones, activaciones, depuración y extracción de parámetros. Se dispone de laboratorio presencial, aunque el plan contempla acceso limitado mediante materiales impresos y trabajo sin equipo.

**Fundamentación de las decisiones didácticas:**

- El uso de operaciones matriciales y la red de Hopfield se fundamenta en el tratamiento de memoria asociativa de Hopfield (1982).
- La progresión hacia redes multicapa y entrenamiento se fundamenta en Goodfellow, Bengio y Courville (2016).
- La secuencia manual–desde cero–framework hace visibles las operaciones y limita el riesgo de confundir ejecución con comprensión.
- Los criterios exigen trazabilidad de W y b, pruebas reproducibles y defensa individual, de acuerdo con las instrucciones del Módulo II.

**Retroalimentación recuperada y cambios entre fases:**

| Componente | Decisión previa | Evidencia u observación que motivó el cambio | Versión actual y razón |
| --- | --- | --- | --- |
| Verificación | Ejemplos y prueba final | Fase 1 observó dificultades para explicar código; Fase 2 pidió reportes parciales | Checkpoints por operación y tabla de W/b; permiten retroalimentar antes del cierre |
| Tarea MLP | Consigna general de implementación | Script restaurado y necesidad de distinguir ejecución de comprensión | Pasos separados, criterios explícitos y defensa individual |
| Evidencia TensorFlow | Comparación final | Requiere comprobar parámetros y límites | Comparación con semilla fija y tabla de W/b |
| Uso de IAGen | Restricción amplia | Riesgo de generar solución evaluada | Uso prohibido en evidencia central; auditoría posterior opcional y declarada |

## 2. Resultados y mapa de evidencias

**Resultados de aprendizaje:**

- **R1.** Al finalizar la unidad, el estudiante construirá y verificará una red de Hopfield mediante operaciones matriciales y actualización de estados, explicando cada cálculo y recuperando al menos un patrón con ruido.
- **R2.** El estudiante implementará una red neuronal multicapa desde cero y registrará, comprobará y corregirá W y b por capa mediante Excel, Python y pruebas de control.
- **R3.** El estudiante reproducirá modelos equivalentes en TensorFlow con una configuración reproducible y comparará argumentos, parámetros y resultados con las implementaciones propias.
- **R4.** El estudiante declarará el uso de IAGen, verificará información técnica y justificará decisiones sin presentar una salida generada como producto propio.

**Relación con la unidad de competencia o propósito de la EE:**

Los resultados trasladan el propósito de la EE —analizar y aplicar técnicas de aprendizaje automático— a acciones observables: calcular, implementar, verificar, comparar y explicar. La progresión recupera fundamentos matemáticos antes de usar el framework.

| Resultado y actividad | Evidencia observable e ID | Criterios prioritarios | Instrumento e ID | Momento y agente evaluador | Uso diagnóstico, formativo o sumativo |
| --- | --- | --- | --- | --- | --- |
| R1; cálculo y código Hopfield | E1; tabla matricial, código Java/C y pruebas de ruido | Correctitud dimensional, diagonal cero, recuperación, explicación | I1; rúbrica analítica | Inicio/desarrollo; docente y coevaluador | Formativo y sumativo |
| R2; MLP desde cero | E2; hoja Excel, script Python, tabla W/b y defensa | Correspondencia manual-código, W/b, pruebas, depuración | I1; rúbrica analítica | Desarrollo; docente, par | Formativo y sumativo |
| R3; comparación TensorFlow | E3; ejecución reproducible y tabla comparativa | Parámetros completos, semilla, interpretación de diferencias | I2; lista de cotejo + breve justificación | Cierre; docente | Sumativo |
| R4; declaración responsable | E4; registro de herramientas/prompts y defensa | Honestidad, trazabilidad, verificación disciplinar | I3; lista de cotejo | Todas las tareas; docente y estudiante | Formativo |

**Qué aprendizaje seguirá siendo observable cuando intervenga IAGen:**

Aunque se utilice IAGen en apoyo acotado, la evidencia central exige cálculos intermedios, fragmentos propios, ejecución reproducible, corrección de discrepancias y defensa oral individual. El dominio no se atribuye a una pantalla final sino a decisiones, comprobaciones y explicaciones con datos.

## 3. Secuencia didáctica integrada

| Momento y tiempo | Acción del estudiante | Mediación docente | Material e ID | Evidencia e instrumento | Retroalimentación y acción posterior |
| --- | --- | --- | --- | --- | --- |
| Inicio · 40 min | Representa patrones bipolares, calcula W con diagonal cero y prueba un patrón con ruido | Presenta criterios, modelo resuelto y checklist; identifica dudas sin resolver la evidencia | M1, M2 | E1; I1 | Señala un error prioritario y autoriza corrección antes de pasar a MLP |
| Desarrollo A · 60 min | Completa propagación hacia adelante y registra dimensiones, W y b en Excel | Revisa la tabla con preguntas de verificación y muestra casos límite | M3, M6 | E2; I1 | Retroalimenta correspondencia entre fórmulas y datos |
| Desarrollo B · 60 min | Implementa MLP en Python sin frameworks, ejecuta pruebas y compara con Excel | Facilita depuración mediante checklist; no escribe ni genera la solución | M3, M7 | E2; I1 | Marca diferencias y ofrece oportunidad de corregir el código y la tabla |
| Defensa y revisión · 20 min | Explica un cálculo y una decisión; declara herramientas usadas | Realiza preguntas individuales breves y registra decisiones | M2, M3, M9 | E1/E2; I1/I3 | Decide si la evidencia es suficiente o requiere una nueva prueba |
| Cierre · 40 min | Ejecuta TensorFlow con semilla fija, extrae W/b y compara con cálculos propios | Orienta el contraste y muestra criterios de interpretación | M4, M5 | E3/E4; I2/I3 | Entrega retroalimentación final y da una oportunidad de revisión escrita |

**Suma de tiempos:** 220 minutos durante las sesiones principales, dentro de las 30 horas de la unidad. La defensa individual de 5 minutos se distribuye en los 20 minutos finales.

**Comprobación de viabilidad:** Se reserva 40 minutos de inicio para consignas y diagnóstico, 120 minutos para cálculos e implementación, 20 minutos para defensa y 40 minutos para TensorFlow y cierre. Después de la sesión, se ofrece una ventana de 30 minutos asincrónicos para corregir una discrepancia documentada. Se prioriza una arquitectura mínima 2–4–1 si no alcanza el tiempo.

**Apoyos y alternativas de acceso:**

Se ofrecen tablas impresas, ejemplo trabajado mínimo, orientación verbal y formato de pseudocódigo. El lenguaje técnico se acompaña con términos y unidades; no se penaliza el formato salvo si impide evaluar el criterio disciplinar. Para falta de equipo se conserva papel/hoja impresa y compilador disponible en laboratorio.

## 4. Consignas y AIAS 2.1 por tarea

### Tarea T1 · Construcción y verificación de Hopfield

**Propósito:** Construir una matriz de pesos válida y explicar cómo un patrón con ruido recupera su estado.

**Pasos, recursos, modalidad, tiempo y evidencia:**

1. Trabaje individualmente el patrón bipolar y entregue la matriz W con diagonal cero.
2. En pareja, revise cálculos y registro de actualización; cada estudiante conserva su explicación individual.
3. Implemente la actualización en C o Java, con al menos dos pruebas, y defienda un cálculo seleccionado en 5 minutos.
4. Entregue tabla de pruebas, código y declaración de herramientas.

**Criterios:** dimensiones correctas; diagonal y transpuesta coherentes; recuperación reproducible; prueba con ruido; explicación sin contradicción entre código y cálculo.

**Instrumento:** I1, disponible al iniciar (véase sección 6).

**Nivel AIAS 2.1:** Nivel 0 — sin IAGen en el cálculo, el código ni la explicación evaluada. Se verifica con el docente antes de la entrega y con declaración de cada estudiante.

**Papel y límites de IAGen:** No se permite generar matrices, soluciones, código, pruebas ni explicaciones centrales. Puede consultarse documentación oficial que no produzca la solución completa.

**Verificación y declaración:** Comparar código, tabla y salida; registrar entradas y salidas; declarar cualquier apoyo técnico utilizado.

**Evidencia bajo estas condiciones:** E1: cálculos propios, código ejecutable y explicación individual.

**Alternativa sin IAGen ni equipo:** Hoja impresa, pseudocódigo y ejecución validada por el docente o en equipo de laboratorio.

**Revisión respecto a Fase 2:** Se conservó el contenido, y se agregó una rúbrica antes de comenzar y una defensa breve.

### Tarea T2 · MLP desde cero

**Propósito:** Relacionar operaciones manuales con una implementación Python sin frameworks y detectar discrepancias.

**Pasos:**

1. Simular una arquitectura 2–4–1 en Excel y registrar W y b por capa.
2. Ejecutar y adaptar `neural_network_numpy.py` sin frameworks.
3. Probar entradas conocidas y comparar salida, forma y activación con la hoja.
4. Corregir al menos una discrepancia si aparece y documentar la causa.

**Criterios:** correspondencia manual-código; dimensiones; W/b completos; pruebas reproducibles; explicación de ajustes.

**Instrumento:** I1.

**Nivel AIAS 2.1:** Nivel 0 — sin IAGen para fórmulas, pesos, código o resultados evaluados.

**Papel y límites:** Permitidas herramientas de depuración del entorno y documentación. Prohibida la generación de soluciones completas o correcciones sin interpretación propia.

**Verificación y declaración:** Conservar fórmula visible, salida de consola, tabla de W/b y una declaración breve.

**Evidencia:** E2: hoja, script, tabla de contraste y breve defensa.

**Alternativa:** Resolver operaciones en hoja impresa y presentar pseudocódigo más una ejecución guiada en laboratorio.

**Revisión Fase 2:** Se separaron cálculo, ejecución y defensa; se incorporó el criterio de corregir una diferencia.

### Tarea T3 · TensorFlow y auditoría crítica

**Propósito:** Reproducir un modelo equivalente y comparar implementación propia, framework y resultados.

**Pasos:**

1. Ejecutar el script con semilla fija y arquitectura documentada.
2. Extraer W y b de cada capa y registrar forma y valor.
3. Comparar con E1/E2 y explicar diferencias plausibles.
4. Declarar herramientas y, si se consulta IAGen, verificar y documentar cada afirmación.

**Criterios:** arquitectura correcta; extracción completa de parámetros; comparación reproducible; interpretación disciplinar; declaración.

**Instrumento:** I2 e I3.

**Nivel AIAS 2.1:** Nivel 0 para los cálculos y tablas centrales. Nivel acotado de colaboración únicamente para la actividad posterior de revisar un ejemplo controlado; no sustituye E3.

**Papel y límites:** IAGen puede sugerir preguntas de depuración o explicar documentación, pero no sustituye ejecución ni extrae parámetros del producto del estudiante.

**Verificación y declaración:** Registrar fuente de datos, semilla, salida y correcciones; citar IAGen si se utilizó.

**Evidencia:** E3/E4: informe breve y declaración; no se requiere una aplicación real para entregarlo.

**Alternativa:** Utilizar salida simulada proporcionada por el docente y compararla con el cálculo propio, sin descargar datos ni compartir información personal.

**Revisión Fase 2:** Se hizo explícita la semilla y la extracción de W/b, y se separó auditoría de evidencia central.

## 5. Materiales y acceso

| ID | Nombre y función | Actividad | Archivo o enlace vigente | Acceso, atribución y verificación |
| --- | --- | --- | --- | --- |
| M1 | Presentación consulta Hopfield | T1 inicio | [`tema1/tema1_hopfield.pptx`](tema1/tema1_hopfield.pptx) | Archivo local comprobado; material base v01 |
| M2 | Hoja de cálculo Hopfield | T1 trabajo | [`tema1/tema1_hopfield.xlsx`](tema1/tema1_hopfield.xlsx) | Archivo local comprobado; fórmulas visibles |
| M3 | Guía y hoja/guía MLP | T2 desarrollo | [`tema2/tema2_neural_network_scratch.xlsx`](tema2/tema2_neural_network_scratch.xlsx) y [`tema2/tema2_guia_trabajo.md`](tema2/tema2_guia_trabajo.md) | Locales comprobados; v01 |
| M4 | Guía TensorFlow | T3 cierre | [`tema3/tema3_guia_trabajo.md`](tema3/tema3_guia_trabajo.md) | Local comprobado; v01 |
| M5 | Script TensorFlow/Keras | T3 trabajo | [`tema3/gps_tensorflow_keras.py`](tema3/gps_tensorflow_keras.py) | Python local; verificado por revisión y ejecución esperada |
| M6 | Guía de trabajo tema 1 | T1 consulta | [`tema1/tema1_guia_trabajo.md`](tema1/tema1_guia_trabajo.md) | Local comprobado; v01 |
| M7 | Script NumPy MLP sin frameworks | T2 trabajo | [`tema2/neural_network_numpy.py`](tema2/neural_network_numpy.py) | Restaurado y comprobado con `python -m py_compile` |
| M8 | Presentación tema 2 | T2 consulta | [`tema2/tema2_neuralnet_scratch.pptx`](tema2/tema2_neuralnet_scratch.pptx) | Archivo local comprobado |
| M9 | Plantilla de declaración y registro | Todas | sección 9 de este plan | Editable; sin datos identificables |
| M10 | Presentación TensorFlow tema 3 | T3 consulta | [`tema3/tema3_tensorflow.pptx`](tema3/tema3_tensorflow.pptx) | Archivo local comprobado |

Los anexos extensos no deben estar incrustados en el plan. Los archivos anteriores son versiones vigentes recuperadas de las fases 1 y 2.

## 6. Instrumentos completos y revisión

### Instrumento I1 · Rúbrica analítica de cálculo e implementación

**Evidencia y resultado:** E1/E2; R1/R2. **Tipo:** rúbrica analítica por criterios observables. **Usuario:** docente y par; inicio/desarrollo y antes de la defensa. **Instrucciones:** revisar producto, citar ubicación de la evidencia y registrar nivel sin inferir dominio por el diseño o la apariencia.

**Regla de valoración:** 4 niveles por criterio; nivel inicial = 1, intermedio = 2, alto = 3. No se utiliza el nivel ausente. Suma máxima 12; ≥10 logro alto, 7–9 logro en desarrollo, ≤6 apoyo prioritario. Uso formativo si se corrige dentro de 30 minutos; sumativo en entrega final.

| Criterio | Alto (3) | Intermedio (2) | Inicial (1) | Evidencia ausente/no interpretable | Peso |
| --- | --- | --- | --- | --- | --- |
| Cálculos y dimensiones | Fórmulas, formas y operaciones completas y correctas; transpuesta/diagonal o propagación y activación correctas | Una discrepancia menor; explica y corrige | Errores recurrentes de dimensión o operación que impiden interpretación | No presenta cálculo o no permite localizarlo | 25 % |
| Parámetros W y b | Registra valores, formas y ubicación de W/b en todas las capas aplicables | Completa la mayoría; omisión o error menor localizado | W/b incompletos o no trazables al modelo | No muestra W/b | 25 % |
| Ejecución y pruebas | Código ejecuta; entradas y respuestas esperadas documentadas y reproducibles | Ejecuta con corrección menor o prueba incompleta | Ejecuta parcialmente; prueba no permite comprobar resultado | Código ausente o no ejecutable | 25 % |
| Explicación y depuración | Justifica decisiones y relaciona código, cálculo y error con evidencia propia | Explica parcialmente; confunde formato y contenido | No explica discrepancias o atribuye decisión a una herramienta | No hay defensa ni declaración suficiente | 25 % |

**Interpretación:** Los resultados orientan la siguiente actuación; no se promedian rasgos ausentes ni se penaliza dos veces el mismo error.

### Instrumento I2 · Lista de cotejo de comparación TensorFlow

| Indicador observable | Sí | No | Evidencia/ubicación | Orientación |
| --- | --- | --- | --- | --- |
| Arquitectura documentada y reproducible con semilla fija | [ ] | [ ] | E3 | Indicar arquitectura, semilla y comando |
| W y b extraídos y registrados por capa | [ ] | [ ] | E3 tabla | Mostrar forma y valor, no solo salida |
| Parámetros comparados con MLP/Hopfield propios | [ ] | [ ] | E3 contraste | Comparar casos equivalentes |
| Diferencias explicadas sin afirmar equivalencia absoluta | [ ] | [ ] | E3 conclusión | Señalar inicialización, entrenamiento o escala |
| Ejecución y fuente declaradas | [ ] | [ ] | E3/E4 | Registrar archivos y herramientas |

**Interpretación:** Es sumativa para completitud técnica y se complementa con la argumentación. La presencia de una captura no sustituye la explicación.

### Instrumento I3 · Lista de cotejo de declaración responsable

| Indicador observable | Sí | No | Evidencia/ubicación | Orientación |
| --- | --- | --- | --- | --- |
| Declara si utilizó o no IAGen y qué herramienta | [ ] | [ ] | E4 | Especificar finalidad y fecha |
| Distingue insumo propio, fuente ajena y salida de IAGen | [ ] | [ ] | E4 | Usar declaraciones distintas |
| Verifica datos, código y afirmaciones | [ ] | [ ] | E1-E3 | Mantener pruebas locales |
| No presenta salida generada como producción propia | [ ] | [ ] | E4 | Explicar decisión y omitir datos personales |

### Revisión con dos respuestas breves contrastantes

Estas muestras son simulaciones explícitas, no resultados de estudiantes reales.

| Muestra | Fragmento o procedencia | Criterio aplicado y evidencia | Valoración justificada | Ambigüedad detectada | Cambio al instrumento |
| --- | --- | --- | --- | --- | --- |
| A · mayor logro | Simulada: “En z = Wx+b, W tiene 2×4, b es 4×1. La salida coincide con Excel en entradas (1,0) y (0,1). Corrigí b al comparar preactivaciones.” | I1: dimensiones correctas, W/b visibles, prueba reproducible y explicación propia | Alto: 11/12 | No distingue si se incluyó IAGen | Se mantiene; se añadió obligación de declarar apoyo |
| B · dificultad relevante | Simulada: “El script produjo una salida; copié el valor de TensorFlow y escribí que coincide.” No muestra formas ni comparación. | I1: ejecución superficial, W/b ausentes y explicación insuficiente | Inicial/intermedio: 5/12 | “Coincide” no identifica qué se compara ni con qué entrada | Se agregó pedir entradas, W/b por capa y causa de la diferencia |

**Revisión de sesgos y acceso:** Los criterios valoran cálculo y ejecución, no fluidez del lenguaje ni velocidad. Se permiten formatos alternos y apoyo técnico. No se usa el estilo visual del código como sustituto de su corrección.

**Alcance:** La revisión comprueba claridad y contraste, pero no constituye validez psicométrica ni evidencia de eficacia con estudiantes.

## 7. Retroalimentación y oportunidad de mejora

| Elemento | Registro |
| --- | --- |
| Muestra, evidencia e instrumento | Muestra B; E2; I1 |
| Logro observado | El estudiante ejecutó el script y reportó una salida observable |
| Dificultad prioritaria | Falta registrar formas y comparar entradas y W/b contra Excel |
| Acción de mejora | Completar una tabla de dos entradas, calcular preactivaciones y explicar una diferencia |
| Apoyo disponible | M3, M7, checklist de dimensiones y revisión breve del docente |
| Momento y canal | Feedback escrito durante el desarrollo y 30 minutos asincrónicos |
| Oportunidad de mejora | Corregir el archivo y demostrar la comparación en una nueva ejecución |
| Evidencia de mejora | La nueva tabla incluye datos coincidentes o explica la discrepancia, y la defensa repite el razonamiento |

**Mensaje dirigido al estudiante:**

> Lograste ejecutar el script y obtener una salida verificable. Para demostrar el razonamiento falta una evidencia concreta: registra las formas de W y b en cada capa, compara una entrada conocida con el resultado de Excel y señala dónde coincide o diverge. Revisa primero las dimensiones y luego usa el checklist de M3. Dispones de 30 minutos de tutoría o trabajo asincrónico para entregar una nueva tabla y realizar una ejecución corregida. Si el resultado sigue diferente, explica cuál operación introdujo la discrepancia. Lo que revisaré es el contraste entre tus dos ejecuciones y la precisión de tu explicación.

**Papel de IAGen:** En esta simulación no se utilizó IAGen para producir el mensaje ni la respuesta. El docente conserva la decisión final y prioriza una evidencia matemática concreta.

## 8. Revisión del plan como experiencia

**Modalidad:** Autorrevisión, al no contar con una revisión de colega registrada en el repositorio.  
**Nombre:** Autorrevisión.  
**Fecha y duración:** 27 de noviembre de 2026 · 25 minutos.

| Pregunta | Hallazgo | Decisión |
| --- | --- | --- |
| 1. ¿Se entiende qué hacer? | Cada tarea tiene pasos, criterios y evidencia; el flujo manual–Python–TensorFlow es visible | Conservar; mantener ejemplos mínimos solo como apoyo |
| 2. ¿Los materiales están disponibles? | Los once IDs son rutas locales y varios archivos existen; los formatos requieren software esperado | Se verificó el índice; si falta TensorFlow se ofrece salida controlada |
| 3. ¿Los criterios permiten reconocer logro? | I1 distingue cálculo, parámetros, ejecución y explicación; I2 complementa el cierre | Se agregó el límite de máximo y una interpretación sumativa |
| 4. ¿Las condiciones IAGen son claras? | Tres consignas explican prohibición central, uso permitido y alternativa | Conservar; exigir declaración en E4 |

- [x] Necesidad alineada con resultados.
- [x] Actividades preparan la operación evaluada.
- [x] Materiales tienen función explícita.
- [x] Consignas y AIAS corresponden a evidencias.
- [x] Instrumentos completos y utilizables.
- [x] Retroalimentación abre una acción y oportunidad.
- [x] Tiempos y alternativas permiten recorrer la experiencia.
- [x] Cambios y pendientes documentados.

**Momento que despierta interés:** Comparar la recuperación de patrones con la implementación TensorFlow.

**Posible frustración y apoyo:** Errores de dimensiones y divergencia entre Excel/Python; apoyo con checklist, ejemplos mínimos y revisión de 30 minutos.

**Decisión del estudiante y señal de progreso:** Ajustar W/b o código con base en una prueba reproducible y explicar qué cambió.

**Observación que cambió el plan:** Se agregó el control de 30 minutos para corregir, una defensa individual y una alternativa sin equipo.

## 9. Fuentes, uso de IAGen y decisiones docentes

**Referencias APA 7:**

- Goodfellow, I., Bengio, Y., & Courville, A. (2016). *Deep learning*. MIT Press.
- Hopfield, J. J. (1982). Neural networks and physical systems with emergent collective computational abilities. *Proceedings of the National Academy of Sciences, 79*(8), 2554–2558. https://doi.org/10.1073/pnas.79.8.2554

| Herramienta y fecha, o elaboración sin IAGen | Finalidad e insumos | Salida o versión inicial | Verificación, cambios y decisión docente | Registro o prompt |
| --- | --- | --- | --- | --- |
| IAGen; 16–27 noviembre de 2026 | Redacción y organización inicial de las Fases 1 y 2; plantillas, instrucciones y objetivos | Borradores estructurados y propuestas didácticas | El docente verificó contenido, archivos, criterios y restricciones; decidió conservar las evidencias sin IA central | Se conserva en Anexo C de la Fase 1 |
| Elaboración manual; 21 noviembre de 2026 | Restauración y adaptación de materiales y guías | Versiones base de temas 1–3 | Se restauró el script Python y se comprobó con `python -m py_compile`; se conservaron las fuentes técnicas | Registro de Fase 2, sección 7 |
| IAGen; 27 noviembre de 2026 | Integrar el plan completo y revisar contraste | Versión inicial de este plan | Se revisaron rutas, resultados, instrumentos y declaración; se corrigió el alcance y se mantuvo la autoría docente | Esta sección |
| Sin IAGen | Implementación prevista en las tareas centrales | Cálculos, código y pruebas propios | IAGen permanece prohibida en E1–E3; E4 registra cualquier uso posterior | Consigna T1–T3 |

**Declaración final:** Este plan y sus decisiones didácticas son responsabilidad del docente. Los materiales base proceden del repositorio del curso; IAGen apoyó organización y redacción, no ejecutó las tareas ni obtuvo los datos. Toda información estudiantil se mantendrá anonimizada.

## 10. Índice, autoevaluación y siguiente aplicación

| Archivo o anexo | Contenido | Nombre exacto o enlace | Versión y acceso comprobado |
| --- | --- | --- | --- |
| Plan | Documento integrado vigente | [`Centeno_Tellez_IA_Fase3_Plan_v01.md`](Centeno_Tellez_IA_Fase3_Plan_v01.md) | v01; acceso local comprobado |
| Fase 1 | Planeación base | [`Centeno_Tellez_InteligenciaArtificial_Fase1_Planeacion_v01.md`](Centeno_Tellez_InteligenciaArtificial_Fase1_Planeacion_v01.md) | v01; local |
| Fase 2 | Portafolio integrado | [`Plantilla_Fase_2_Producir_y_verificar_Modulo_II.md`](Plantilla_Fase_2_Producir_y_verificar_Modulo_II.md) | v01; local |
| Material M1–M10 | Presentaciones, hojas, scripts y guías | Véase sección 5 | V1/base vigentes; rutas comprobadas |
| Instrumentos | I1, I2 e I3 completos | Sección 6 | V1; revisados con muestras simuladas |
| Registros | Simulaciones y autorrevisión | Secciones 6–8 | Sin datos identificables |

| Criterio del plan | Peso | Nivel 0–3 | Evidencia y ajuste necesario |
| --- | ---: | ---: | --- |
| Alineación y fundamentación | 20 | 3 | Secciones 1–2: necesidad, fuentes y resultados R1–R4 |
| Secuencia, materiales y viabilidad | 20 | 3 | Secciones 3–5: 220 minutos, alternativas y diez materiales |
| Instrumentos y revisión | 20 | 3 | Sección 6: rúbrica completa, dos muestras contrastantes y cambio documentado |
| Retroalimentación y mejora | 15 | 3 | Sección 7: criterio, evidencia, acción, apoyo y oportunidad |
| AIAS, trazabilidad y responsabilidad docente | 15 | 3 | Secciones 4 y 9: nivel por tarea, límites y declaración |
| Integración y revisión de la experiencia | 10 | 3 | Sección 8: recorrido, hallazgos y decisiones; sección 10: índice |

**Autoevaluación:** 3 en los seis criterios. La evidencia se encuentra dentro del plan y los ajustes se señalaron antes de la siguiente aplicación.

**Pendientes antes de la puesta en práctica:**

- Confirmar descriptores oficiales vigentes de AIAS 2.1.
- Validar el tiempo real de defensa de cada estudiante.
- Pilotear el script M5 en el laboratorio y conservar una salida anonimizada.
- Confirmar permisos y disponibilidad de software en el dispositivo asignado.

**Qué observará al aplicar el plan con estudiantes:**

Tiempos de cálculo y depuración, errores de dimensiones, correspondencia entre W/b y resultados, calidad de explicación individual, uso real de retroalimentación y momentos de frustración o interés. Estos datos se utilizarán para ajustar la experiencia sin atribuir causalidad individual al IAGen.
