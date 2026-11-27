# Portafolio integrador · Fase 2: Producir y verificar

**Universidad Veracruzana · Diplomado PROFA · Módulo II · Semana 2**  
**Producto:** Portafolio de materiales y secuencia didáctica · 20 % del módulo  
**Nombre del archivo:** Centeno_Tellez_InteligenciaArtificial_Fase2_Portafolio_v01.md

## 1. Identificación y continuidad con la Fase 1

| Dato | Respuesta |
| --- | --- |
| Docente participante | Centeno Tellez Adolfo |
| Experiencia Educativa (EE) | Inteligencia Artificial |
| Programa educativo | Licenciatura en Ingeniería de Software |
| Grupo, nivel y modalidad | 5.º semestre, ~30 estudiantes, modalidad presencial |
| Tema o unidad que abordarás | Redes neuronales profundas desde fundamentos matemáticos (Hopfield, MLP y TensorFlow) |
| Duración disponible para la secuencia | 6 semanas (30 horas) |
| Fecha y versión del documento | 2026-11-21 · v01 |

**Problema de diseño o necesidad identificada en la Fase 1:**

Se observó dependencia de agentes de IA para producir código, con dificultades para explicar, depurar y validar resultados matemáticos de redes neuronales.

**Propósito, contenidos, estrategia metodológica y decisiones que recuperas de la fase 1 de tu planeación:**

Se mantiene la progresión: (1) cálculo manual y álgebra lineal, (2) implementación desde cero sin frameworks, (3) comparación con TensorFlow. Se ajusta la mediación para exigir trazabilidad de cálculos de W y b y explicación oral individual.

**Características del grupo relevantes para producir los materiales:**

Grupo con bases en álgebra lineal y programación, interés por IA generativa, buena asistencia. Requieren andamiaje para justificar resultados y verificar dimensiones, transpuestas, diagonales y activaciones.

**Retroalimentación recibida y ajustes que incorporarás:**

Se incorpora mayor énfasis en verificación: checklist por tema, evidencia de cálculo intermedio, y contraste explícito entre implementación manual y con framework.

**Fuentes que sustentan las decisiones:**

- Hopfield (1982): fundamento de memoria asociativa y matriz de pesos.
- Goodfellow, Bengio y Courville (2016): MLP, funciones de activación y entrenamiento.
- Planeación de Fase 1 (`/home/runner/work/diplomado_ia/diplomado_ia/Centeno_Tellez_InteligenciaArtificial_Fase1_Planeacion_v01.md`).

## 2. Desempeño y evidencia de aprendizaje

**Desempeño esperado:**

El estudiante construye y verifica una red de Hopfield y una red multicapa desde cero (sin frameworks), y luego modela ambas en TensorFlow para comparar salidas y parámetros W y b bajo condiciones controladas.

**Evidencia que permitirá reconocer ese desempeño:**

1. Hoja de cálculo con operaciones matriciales explícitas.
2. Código funcional de Hopfield en C o Java y MLP en Python sin frameworks.
3. Implementación equivalente en TensorFlow con extracción de pesos y sesgos.
4. Informe comparativo de resultados.

**Criterios iniciales para reconocer el logro:**

- Dimensiones, transpuestas y operaciones correctas.
- Justificación del cálculo de W y b por capa.
- Pruebas reproducibles y trazables.
- Comparación argumentada de diferencias entre implementaciones.

**Correspondencia con el diagnóstico:**

La evidencia exige razonamiento visible, no solo código final. Así se atiende la necesidad detectada de pasar de “usar IA para generar” a “comprender, verificar y defender decisiones”.

## 3. Secuencia didáctica

| Momento | Acción del estudiante | Mediación docente | Material y función | Evidencia y criterio inicial | Tiempo |
| --- | --- | --- | --- | --- | --- |
| Inicio | Recupera álgebra lineal con un patrón bipolar y calcula una matriz pequeña. | Presenta objetivo, criterios y ejemplo guiado. | M1 (consulta) y M2 (trabajo). | Cálculos iniciales correctos y explicados. | 40 min |
| Desarrollo | Implementa Hopfield y MLP desde cero; valida W y b con pruebas. | Acompaña con preguntas de depuración y checklist de verificación. | M2 y M3 (trabajo). | Código ejecutable + tabla de verificación por capa. | 120 min |
| Cierre | Reproduce en TensorFlow y compara resultados con implementación base. | Orienta cierre comparativo y reflexión sobre diferencias. | M4 (trabajo). | Informe corto con conclusiones y límites del modelo. | 40 min |

**Duración total:** 200 minutos por secuencia completa de práctica guiada.

**Revisión de viabilidad:**

Se confirma viabilidad en laboratorio presencial con software disponible (Excel/hoja de cálculo, compilador C/Java y Python). Si hay restricción de tiempo, se prioriza validación de una arquitectura mínima (2–4–1) manteniendo la evidencia de W y b.

## 4. Consigna transparente de una tarea

**Nombre de la tarea:** Construcción y verificación de una MLP desde cero.  
**Momento de la secuencia:** Desarrollo.  
**Materiales asociados:** M2, M3.

### Propósito

Comprender cómo una red multicapa transforma entradas mediante operaciones matriciales y funciones de activación, verificando explícitamente parámetros W y b sin depender de frameworks.

### Tarea

**Instrucciones dirigidas al estudiante:**

1. Completa en la hoja de cálculo la propagación hacia adelante capa por capa, registrando dimensiones y resultados intermedios.
2. Implementa la misma arquitectura en Python sin frameworks, usando únicamente operaciones con arreglos/matrices.
3. Verifica y documenta que W y b usados en código coincidan con tu simulación; reporta discrepancias y correcciones.

| Condición | Indicación para el estudiante |
| --- | --- |
| Modalidad de trabajo | Parejas para desarrollo; explicación individual al cierre |
| Tiempo disponible | 120 minutos |
| Recursos necesarios | `/tema2/tema2_neural_network_scratch.xlsx`, `/tema2/neural_network_numpy.py`, cuaderno de cálculos |
| Producto o actuación esperada | Script ejecutable + tabla de verificación de W y b + breve reflexión |
| Forma de entrega o presentación | Entrega en Eminus y defensa oral de 5 minutos |

### Criterios de logro

- Correcta correspondencia entre operaciones de Excel y Python.
- Registro explícito de W y b por capa.
- Pruebas con entradas de control y salida esperada.
- Explicación clara de decisiones y ajustes.

### Condiciones de participación de IAGen

**Nivel AIAS 2.1 elegido para esta tarea:** Nivel restrictivo (sin generación de solución para la evidencia evaluada).

**Justificación pedagógica:**

La evidencia busca comprobar dominio matemático y computacional propio en operaciones básicas y trazabilidad de parámetros.

**Usos permitidos y límites:**

Permitido: consulta de documentación oficial de Python/Numpy.  
No permitido: generación automática de la solución final de cálculo o código evaluado por agentes de IA.

**Verificación exigida:**

Comparar resultados con hoja de cálculo y pruebas de casos simples, registrando evidencia de coincidencia o diferencias.

**Declaración del uso:**

Cada estudiante declara herramientas usadas y decisiones realizadas durante la práctica.

**Aprendizaje que seguirá siendo observable:**

Razonamiento algebraico, diseño de arquitectura, verificación y depuración.

### Alternativa de acceso

Si no hay acceso a equipo, el estudiante resolverá la misma arquitectura en formato papel + hoja impresa y presentará pseudocódigo estructurado; el desempeño esperado y criterios se mantienen.

## 5. Selección de materiales por su función

| ID | Nombre y formato | Función: consulta, trabajo o revisión | Acción que permitirá al estudiante | Momento de uso | Razón de la elección |
| --- | --- | --- | --- | --- | --- |
| M1 | `/tema1/tema1_hopfield.pptx` | Consulta | Identificar conceptos y flujo de una red Hopfield | Inicio | Marco conceptual con lenguaje accesible |
| M2 | `/tema1/tema1_hopfield.xlsx` | Trabajo | Calcular matriz de pesos y actualización de estados | Inicio/desarrollo | Hace visible cada operación matricial |
| M3 | `/tema2/neural_network_numpy.py` + `/tema2/tema2_neural_network_scratch.xlsx` | Trabajo | Implementar y verificar una MLP sin frameworks | Desarrollo | Permite contraste matemático-código |
| M4 | `/tema3/gps_tensorflow_keras.py` | Revisión/Trabajo | Modelar con TensorFlow y comparar W y b | Cierre | Transferencia a framework profesional |

**Coherencia del conjunto:**

Los materiales progresan de representación manual a implementación y validación. Ninguno sustituye el razonamiento del estudiante; todos exigen justificación de cálculos y decisiones.

## 6. Ficha de producción y adaptación

### Material M2 · Hoja de cálculo Hopfield

| Campo | Registro |
| --- | --- |
| Formato y versión | XLSX · v01 |
| Destinatarios y condiciones de acceso | Estudiantes de 5.º semestre en laboratorio |
| Desempeño al que contribuye | Cálculo y verificación de matriz de pesos |
| Función y momento de uso | Trabajo · inicio/desarrollo |
| Acción del estudiante | Calcular productos, diagonal y convergencia |
| Instrucciones de uso | Completar celdas guía y justificar cada operación |
| Archivo final o enlace | `/home/runner/work/diplomado_ia/diplomado_ia/tema1/tema1_hopfield.xlsx` |

**Fuentes e insumos del encargo:**

Planeación Fase 1, teoría de Hopfield y resultados esperados del bloque.

**Herramienta utilizada y fecha, o procedimiento de elaboración sin IAGen:**

Edición manual docente de hoja de cálculo y revisión el 2026-11-21.

**Prompt o encargo utilizado:**

```text
No aplica (material base institucional revisado y adaptado manualmente).
```

**Versión inicial:**

Archivo base de tema1.

**Decisiones de adaptación:**

| Elemento del borrador | Decisión: conservar, modificar o descartar | Cambio realizado | Razón didáctica, disciplinar o de acceso |
| --- | --- | --- | --- |
| Tabla de pesos | Conservar | Se mantiene estructura de cálculo | Alinea con evidencia requerida |
| Instrucciones | Modificar | Se agrega checklist de verificación externa | Mejora trazabilidad |

**Procedencia, atribución y condiciones de uso de recursos ajenos:**

Material de uso académico en el contexto del diplomado y la EE.

**Verificación asociada:**

Registro en sección 7 (M2).

### Material M3 · Script Python MLP sin frameworks

| Campo | Registro |
| --- | --- |
| Formato y versión | PY · v01 restaurado |
| Destinatarios y condiciones de acceso | Estudiantes con Python y Numpy instalados |
| Desempeño al que contribuye | Implementación desde cero y comprobación de W y b |
| Función y momento de uso | Trabajo · desarrollo |
| Acción del estudiante | Ejecutar, seguir trazas y contrastar con Excel |
| Instrucciones de uso | Ajustar pesos/entradas y verificar resultados |
| Archivo final o enlace | `/home/runner/work/diplomado_ia/diplomado_ia/tema2/neural_network_numpy.py` |

**Fuentes e insumos del encargo:**

Material base del tema 2 y requerimiento de implementación sin frameworks.

**Herramienta utilizada y fecha, o procedimiento de elaboración sin IAGen:**

Recuperación de código fuente original y validación sintáctica (2026-11-21).

**Prompt o encargo utilizado:**

```text
No aplica (restauración de material base original para mantener consistencia didáctica).
```

**Versión inicial:**

Archivo local dañado (HTML en vez de código Python).

**Decisiones de adaptación:**

| Elemento del borrador | Decisión: conservar, modificar o descartar | Cambio realizado | Razón didáctica, disciplinar o de acceso |
| --- | --- | --- | --- |
| Archivo `neural_network_numpy.py` | Modificar | Se restauró código Python funcional | Permitir uso real del material de trabajo |

**Procedencia, atribución y condiciones de uso de recursos ajenos:**

Repositorio público del autor del curso para uso educativo.

**Verificación asociada:**

Registro en sección 7 (M3).

### Material M4 · Script TensorFlow

| Campo | Registro |
| --- | --- |
| Formato y versión | PY · v01 |
| Destinatarios y condiciones de acceso | Estudiantes con entorno TensorFlow |
| Desempeño al que contribuye | Transferencia de modelo y comparación de parámetros |
| Función y momento de uso | Cierre |
| Acción del estudiante | Entrenar, extraer W y b, comparar con modelos previos |
| Instrucciones de uso | Ejecutar con semilla fija y documentar diferencias |
| Archivo final o enlace | `/home/runner/work/diplomado_ia/diplomado_ia/tema3/gps_tensorflow_keras.py` |

## 7. Registro de verificación y mejora

| Material | Aspecto y elemento examinado | Fuente y ubicación, o procedimiento de comprobación | Hallazgo | Corrección o decisión | Evidencia conservada y estado |
| --- | --- | --- | --- | --- | --- |
| M2 | Contenido: cálculo de pesos Hopfield | Revisión de celdas y operaciones de matriz | Coherente con objetivo | Se mantiene con checklist adicional | Guía de tema1 · verificado |
| M3 | Funcionamiento: script Python | Validación `python -m py_compile` | Inicialmente inválido (HTML) | Se restauró archivo Python correcto | Script restaurado · verificado |
| M3 | Didáctica y consigna | Contraste con secuencia y evidencias | Requiere guía paso a paso | Se añadió guía de trabajo de tema2 | `tema2/tema2_guia_trabajo.md` · verificado |
| M4 | Uso responsable de IAGen | Definición de límites en consigna | Riesgo de sustituir razonamiento | Se restringió generación automática en evidencia evaluada | Sección 4 · verificado |
| M1-M4 | Procedencia y atribución | Registro de fuentes en fichas | Suficiente para trazabilidad | Se consolidó en portafolio e índice final | Documento fase2 · verificado |

### Prueba de recorrido, si la realizas

**Material y consigna revisados:** M3 + consigna de desarrollo.  
**Modalidad y fecha:** Autorrevisión, 2026-11-21.

**Dificultad identificada:** El material de código no era ejecutable por corrupción del archivo.

**Ajuste y razón:** Restauración del script original para habilitar práctica y verificación real.

**Qué necesitarás observar al utilizarlo con estudiantes:** Dónde fallan al justificar dimensiones y cómo corrigen discrepancias entre Excel y Python.

### Experiencia del estudiante (lentes LXD)

**Momento que despierta interés:** Ver la red recuperar patrones y luego reproducir ese comportamiento con TensorFlow.  
**Posible frustración y apoyo:** Errores de dimensiones; apoyo con checklist de shapes y ejemplo mínimo.  
**Decisión del estudiante y señal de progreso:** Ajusta W/b con evidencia de prueba reproducible.  
**Observación que cambió el plan:** Se agregó guía operativa por tema para reducir ambigüedad.

## 8. Declaración de uso o no uso de IAGen

**Declaración:**

Se utilizó apoyo de IA para estructurar y mejorar redacción del portafolio y guías, manteniendo bajo responsabilidad docente la validación conceptual, didáctica y técnica. La selección de contenidos, restricciones de uso estudiantil, criterios y verificaciones fueron decididos por el docente y documentados en secciones 4, 6 y 7.

**Decisiones que mantuviste bajo tu responsabilidad:**

Secuencia didáctica, criterios de evidencia, límites de uso de IAGen para estudiantes, verificación de materiales y corrección del script del tema 2.

## 9. Índice y revisión final del portafolio

| Elemento | Nombre del archivo o enlace | Versión | Acceso comprobado y observaciones |
| --- | --- | --- | --- |
| Plantilla integradora completa | `/home/runner/work/diplomado_ia/diplomado_ia/Plantilla_Fase_2_Producir_y_verificar_Modulo_II.md` | v01 | OK |
| Material de consulta M1 | `/home/runner/work/diplomado_ia/diplomado_ia/tema1/tema1_hopfield.pptx` | base | OK |
| Material de trabajo M2 | `/home/runner/work/diplomado_ia/diplomado_ia/tema1/tema1_hopfield.xlsx` | base | OK |
| Material de trabajo M3 | `/home/runner/work/diplomado_ia/diplomado_ia/tema2/neural_network_numpy.py` | restaurado | OK |
| Material de trabajo M4 | `/home/runner/work/diplomado_ia/diplomado_ia/tema3/gps_tensorflow_keras.py` | base | OK |
| Evidencias de producción y verificación | `/tema1/tema1_guia_trabajo.md`, `/tema2/tema2_guia_trabajo.md`, `/tema3/tema3_guia_trabajo.md`, sección 7 | v01 | OK |

**Lista de revisión:**

- [x] La propuesta recupera la misma EE y explica los ajustes a la Fase 1.
- [x] El desempeño se reconoce en una acción y una evidencia de aprendizaje.
- [x] La secuencia relaciona acciones, mediación docente, materiales, criterios y tiempos viables.
- [x] La consigna explicita propósito, tarea, criterios y condiciones de IAGen justificadas.
- [x] La tarea contempla una alternativa para quienes no puedan utilizar IAGen.
- [x] Cada material tiene una función clara y permite realizar la acción prevista.
- [x] Las fichas documentan el encargo, la versión inicial, los cambios y las decisiones pertinentes.
- [x] La verificación incluye contenido, didáctica y consigna, accesibilidad, procedencia y atribución, uso responsable de IAGen y funcionamiento.
- [x] Las fuentes y los recursos ajenos están atribuidos y el uso o no uso de IAGen está declarado.
- [x] El índice permite localizar los archivos finales y sus evidencias de revisión.
- [x] Los pendientes están identificados y se ha señalado cómo se resolverán antes del uso con estudiantes.

**Revisión complementaria:**

- [x] Incluí al menos un material de consulta y dos de trabajo.
- [x] Cada material se relaciona con una decisión del diagnóstico.
- [x] Verifiqué sesgos, estereotipos y adecuación al contexto.
- [x] Las imágenes informativas tienen explicación equivalente y el audio o video tiene alternativa textual.
- [x] El material no depende únicamente del color.
- [x] Registré dónde puede aparecer frustración, qué apoyo habrá y cómo se reconocerá el progreso.
- [x] Incorporé referencias APA 7, procedencia, condiciones de uso y evidencia anonimizada.
- [x] Conservé los prompts y cambios en mi archivo de registro como candidatos al catálogo final.
- [x] Si no tuve acceso a IAGen, adapté el borrador de práctica y declaré el procedimiento sin atribuir una ejecución no realizada.

**Pendientes y decisión antes de entregar:**

Aplicar pilotaje con estudiantes de un grupo y ajustar tiempos finales por evidencia real de aula.

## 10. Continuidad hacia la Fase 3

**Evidencias para las que desarrollarás instrumentos de evaluación:**

Script Hopfield, script MLP sin frameworks, implementación TensorFlow y reporte comparativo de W y b.

**Retroalimentación que necesitarán tus estudiantes:**

Sobre consistencia entre cálculo manual y código, validez de pruebas, interpretación de diferencias y calidad de justificación técnica.

**Ajustes que deberán reflejarse en el plan de clase completo:**

Checkpoints de verificación por capa, tiempos de depuración y rúbrica de explicación oral individual.

## 11. Autoevaluación con la rúbrica

| Criterio | Qué se comprueba | Nivel 0–2 | Evidencia (sección) y ajuste |
|---|---|---|---|
| Secuencia y consignas | Congruencia con Fase 1 y articulación de acciones, tiempos, consignas y nivel AIAS. | 2 | Secciones 1, 3 y 4 |
| Pertinencia de los materiales | Al menos 1 material de consulta y 2 de trabajo con función clara. | 2 | Sección 5 |
| Calidad disciplinar y verificación | Contraste de datos y documentación de correcciones. | 2 | Sección 7 |
| Accesibilidad y funcionamiento | Legibilidad y acceso efectivo a archivos. | 2 | Secciones 4 y 9 |
| Autoría y trazabilidad | Registro de procedencia, uso de IA y decisiones docentes. | 2 | Secciones 6, 8 y 9 |

**Referencias (APA 7):**

- Goodfellow, I., Bengio, Y., & Courville, A. (2016). *Deep Learning*. MIT Press.
- Hopfield, J. J. (1982). Neural networks and physical systems with emergent collective computational abilities. *Proceedings of the National Academy of Sciences, 79*(8), 2554–2558. https://doi.org/10.1073/pnas.79.8.2554
