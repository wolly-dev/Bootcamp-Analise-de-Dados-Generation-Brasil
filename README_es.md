# 📊 Análisis de Rendimiento y Retroalimentación de Usuarios – NetGuard Pro

> **Ejercicio de Análisis de Datos con Soporte de IA**  
> Bootcamp de Análisis de Datos | 30 Junio 2026

---

## 📌 Visión General del Proyecto

Este repositorio documenta un **ejercicio práctico de Análisis de Datos** realizado durante un bootcamp, con un doble objetivo:

1. **Simular un escenario real de evaluación de software** (el ficticio **NetGuard Pro**), utilizando datos cuantitativos (métricas de servidores) y cualitativos (retroalimentación de usuarios).
2. **Practicar el uso de IA generativa como herramienta de apoyo para el analista de datos**, en todas las etapas del proceso: desde la interpretación y categorización de grandes volúmenes de datos textuales hasta la estructuración de informes técnicos y recomendaciones estratégicas.

El ejercicio fue deliberadamente diseñado para que el analista actuara como **curador y estratega**, mientras que la IA actuaba como **asistente inteligente** — agilizando tareas repetitivas, sugiriendo patrones y organizando información, sin reemplazar el juicio crítico humano.

**Principales aprendizajes prácticos del ejercicio:**
- Cómo integrar IA en el flujo de trabajo de un analista de datos.
- Cómo extraer insights accionables a partir de datos no estructurados (textos).
- Cómo cruzar datos cualitativos y cuantitativos para fundamentar decisiones.
- Cómo estructurar un informe técnico claro, objetivo y con recomendaciones priorizadas.

---

## 🎯 Objetivos del Análisis

- Evaluar la calidad de la experiencia del usuario basándose en comentarios y métricas de rendimiento.
- Identificar los principales errores o problemas reportados.
- Proponer cambios y mejoras basados en los datos analizados.
- Estructurar un informe técnico claro y objetivo para la toma de decisiones.

---

## 🤖 El Papel de la IA en Este Ejercicio

A diferencia de un análisis de datos tradicional, este ejercicio fue planificado para **integrar activamente herramientas de IA generativa** en el proceso analítico. La IA fue utilizada como:

| Etapa | Cómo se utilizó la IA |
|-------|------------------------|
| **Lectura e interpretación** | Ayudó en la lectura e interpretación de grandes volúmenes de datos textuales (50 comentarios de usuarios). |
| **Categorización** | Sugirió categorías de funcionalidades y agrupamientos semánticos para los comentarios. |
| **Análisis de sentimiento** | Apoyó la identificación de tonos (positivo, neutro, negativo) en cada comentario. |
| **Estructuración del informe** | Organizó la información según el formato de la plantilla técnica, garantizando coherencia y fluidez. |
| **Generación de recomendaciones** | Propuso soluciones basadas en los patrones identificados, que fueron validadas y priorizadas por el analista. |

**Importante:** en ningún momento la IA reemplazó el juicio del analista. Todas las conclusiones, priorizaciones y recomendaciones finales fueron **validadas y refinadas manualmente**, garantizando que el producto final reflejara la visión estratégica y el sentido crítico del profesional.

> 🧠 **Objetivo pedagógico:** Este ejercicio demuestra que la IA es una **herramienta de aumento de capacidad** (augmentation), no de sustitución. El analista mantiene el control del proceso, mientras que la IA acelera tareas operativas y amplía la capacidad de procesamiento de información.

---

## 📁 Estructura de los Datos

### 1. Informe de Rendimiento (`SA-AIR_Performance_Report_pt-BR.xlsx`)
- Contiene métricas de **100 servidores**, incluyendo:
  - Uso de CPU, memoria y disco.
  - Latencia, pérdida de paquetes y tasa de éxito de conexión.
  - Eventos de conmutación por error, tipos de error y servicios afectados.

### 2. Retroalimentación de Usuarios (`SA-AIR_User_Feedback_pt-BR.xlsx`)
- Contiene **50 reseñas de usuarios** (ficticios), incluyendo:
  - Calificación por estrellas (1 a 5).
  - Comentarios cualitativos sobre funcionalidades.
  - Sugerencias y quejas específicas.

### 3. Plantilla de Informe Técnico (`SA-AIR_Template-TECH_pt-BR.docx`)
- Estructura utilizada para organizar los hallazgos del análisis.
- Incluye categorías de funcionalidades, identificación de problemas y resumen ejecutivo.

---

## 🧠 Metodología Aplicada

El análisis se llevó a cabo en **5 hitos principales**, con **integración continua de IA** en todas las etapas:

| Hito | Descripción | Participación de la IA |
|------|-------------|-------------------------|
| **1. Preparación de Datos** | Revisión y organización de los conjuntos de datos (hojas de cálculo). | Ayuda en la validación de consistencia e identificación de campos relevantes. |
| **2. Análisis de Retroalimentación** | Categorización por funcionalidad, evaluación de sentimiento y extracción de sugerencias. | **Papel central:** categorización semántica de los 50 textos, sugerencia de agrupamientos e identificación de patrones de sentimiento. |
| **3. Análisis de Datos de Rendimiento** | Identificación de patrones, cálculo de estadísticas y cruce con comentarios. | Generación automática de estadísticas descriptivas y correlaciones iniciales. |
| **4. Resumen de Hallazgos** | Creación de un documento resumen con insights y recomendaciones. | Estructuración del texto del informe, manteniendo la coherencia lógica entre secciones. |
| **5. Revisión y Refinamiento** | Ajustes finales, validación de referencias y preparación para la entrega. | Verificación de consistencia de las referencias y sugerencias de mejora en la redacción. |

> 💡 **Diferenciador del ejercicio:** la IA no se utilizó como "generadora automática de respuestas", sino como **copiloto inteligente** — sugiriendo, organizando y acelerando, mientras el analista validaba, ajustaba y daba el tono estratégico final.

---

## 🔍 Principales Hallazgos

### ✅ Puntos Fuertes
- La **conmutación por error (failover)** y la **estabilidad de la red** (baja pérdida de paquetes) son muy elogiadas.
- El **monitoreo de sesiones y disco** se considera completo y confiable.

### ⚠️ Problemas Identificados
| Problema | Frecuencia | Gravedad |
|----------|------------|----------|
| Alto uso de CPU y lentitud del panel | 36% de los comentarios | **Crítica** |
| Complejidad en la configuración del firewall | 24% de los comentarios | **Alta** |
| Falta de priorización inteligente del ancho de banda | 18% de los comentarios | **Media** |

---

## 🛠️ Recomendaciones Propuestas

1. **Optimizar el uso de CPU** – Revisar la arquitectura, implementar caché y separar procesos críticos.
2. **Simplificar la configuración del firewall** – Crear un asistente de configuración y plantillas visuales.
3. **Implementar QoS para el ancho de banda** – Priorizar dinámicamente tareas críticas.

---

## 📄 Entregables

- `Relatorio_Analise_NetGuard_Pro.pdf` – Informe final completo con análisis, problemas y recomendaciones.
- Este archivo `README.md` – Documentación resumida del proyecto.

---

## 🧩 Tecnologías y Herramientas

- **Hojas de cálculo:** Lectura y análisis de datos estructurados (Excel).
- **IA Generativa:** Soporte en interpretación, categorización y estructuración del informe.
- **Procesamiento de Texto:** Organización y formato del documento final.

---

## 💭 Reflexión sobre el Uso de IA en Análisis de Datos

Este ejercicio evidenció que la IA generativa puede ser una **aliada poderosa** para los analistas de datos, especialmente en tareas que involucran:

- **Datos textuales no estructurados:** donde la IA acelera la categorización y el análisis de sentimientos.
- **Generación de informes:** donde la IA ayuda en la estructuración y formato, permitiendo que el analista se enfoque en el contenido estratégico.
- **Sugerencia de patrones:** donde la IA identifica correlaciones iniciales que pueden ser validadas o refutadas por el analista.

**Lecciones aprendidas:**
- La IA es eficiente para tareas de **bajo esfuerzo cognitivo y alto volumen**, como la lectura y categorización de textos.
- El **juicio humano** sigue siendo esencial para la priorización, validación de contexto y toma de decisiones.
- La **curaduría del analista** sobre las salidas de la IA es lo que garantiza la calidad final del trabajo.

> "La IA no reemplaza al analista; amplía su capacidad de procesar información y enfocarse en lo que realmente importa: interpretar, priorizar y recomendar."

---

## 👩‍💻 Sobre el Autor

Este proyecto fue desarrollado como parte de un bootcamp de Análisis de Datos, con el objetivo de simular un escenario real de evaluación de software y toma de decisiones basada en datos, integrando IA como herramienta de apoyo a lo largo de todo el proceso.

---

## 📌 Licencia

Este proyecto es de uso educativo y no tiene fines comerciales. Los datos utilizados son ficticios y fueron creados exclusivamente para fines de aprendizaje.

---

**📬 Contacto:**  
Si tienes preguntas o sugerencias, no dudes en abrir un *issue* o ponerte en contacto.

---
