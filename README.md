# 📊 Análisis Empírico: La Brecha Temporal de la Orientación Docente en el Uso de la IA

**Repositorio de Soporte para el Artículo Científico:**
> *“La Brecha Temporal de la Orientación Docente en el Uso de la IA: Un Análisis Empírico desde la Percepción Estudiantil y su Impacto en la Formación Ética de Futuros Ingenieros en Software.”*

Este repositorio contiene el código fuente, los cálculos y las visualizaciones generadas en Google Colab que sustentan empíricamente los hallazgos cuantitativos del artículo presentado a la Convocatoria para el Premio “Ágora” a la Investigación Educativa 2025.

---

## 📌 Descripción

La rápida adopción de herramientas de Inteligencia Artificial (IA) como ChatGPT, Gemini y GitHub Copilot en la educación de ingeniería ha generado nuevos desafíos éticos y pedagógicos. Este estudio, basado en una encuesta aplicada a **63 estudiantes** de la Universidad Politécnica de Durango, explora cómo la **oportunidad y distribución temporal de la orientación docente** influye en la percepción ética y los patrones de uso de la IA.

Este notebook de Google Colab es el **corazón analítico del estudio**. Aquí se procesan los datos crudos de la encuesta para:

*   Calcular frecuencias, porcentajes y distribuciones por ciclo académico.
*   Generar las tablas y gráficas que aparecen en el artículo.
*   Validar la coherencia interna de los resultados.
*   Proveer transparencia y reproducibilidad a la investigación.

---

## 🧩 Contenido del Notebook (Colab)

El notebook está estructurado para replicar fielmente los análisis del artículo. Incluye:

1.  **Carga y Preprocesamiento de Datos:**
    *   Importación de la base de datos de la encuesta (formato CSV o similar).
    *   Limpieza y organización de las variables (ciclo académico, percepción ética, orientación docente, etc.).

2.  **Análisis Cuantitativo y Generación de Tablas:**
    *   **Tabla 1:** Frecuencia de orientación docente por ciclo académico.
    *   **Gráficas 1 y 2:** Distribución de la percepción ética sobre el plagio con IA.
    *   **Gráfica 3:** Opinión sobre la prohibición de IA en exámenes, por ciclo.
    *   **Tabla 2:** Correlación entre uso de IA, productividad y dependencia.
    *   **Cálculos de porcentajes globales y por estratos** (ej: 20.63% sin orientación, 71.43% con percepción ética flexible, etc.).

3.  **Visualizaciones:**
    *   Gráficos de barras apiladas para mostrar la evolución de la orientación docente por ciclo.
    *   Gráficos de pastel o barras horizontales para la percepción ética.
    *   Gráficos comparativos para el rechazo a restricciones absolutas.

4.  **Validación de Resultados:**
    *   Verificación cruzada de sumas y porcentajes para asegurar que los datos del artículo cuadren con los cálculos en bruto (por ejemplo, corrigiendo el porcentaje del primer ciclo de 28.57% a 25% y la percepción ética de 81% a 71.43%).

---

## 🔍 ¿Por qué es importante este repositorio?

*   **Transparencia Académica:** Permite a revisores, pares académicos y lectores verificar la integridad de los datos y la metodología analítica.
*   **Reproducibilidad:** Cualquier investigador puede descargar el notebook, cargar sus propios datos (con la misma estructura) y replicar el análisis.
*   **Educación Abierta:** Sirve como recurso didáctico para estudiantes que deseen aprender a analizar datos de encuestas en contextos educativos usando Python (Pandas, Matplotlib, Seaborn).
*   **Base para Futuras Investigaciones:** El código puede adaptarse fácilmente para estudios similares en otras instituciones o con otras poblaciones.

---

## 🚀 Cómo Usar

1.  Haz clic en el enlace del notebook de Google Colab: **https://github.com/chriosch/CEINN-2025/blob/main/analisis_encuesta.ipynb**.
2.  Haz una copia del notebook en tu propia cuenta de Google Drive (Archivo > Guardar una copia en Drive).
3.  Si deseas replicar el estudio con tus propios datos, reemplaza el archivo de datos de entrada (`survey_data.csv`) y ajusta los nombres de las columnas en el código según sea necesario.
4.  Ejecuta todas las celdas para regenerar los análisis y gráficos.

---

## 📄 Relación con el Artículo

Este notebook **genera directamente las tablas y gráficas** que aparecen en la sección "Desarrollo" del artículo. Todos los porcentajes y cifras citados en el texto (una vez corregidos) se derivan de los cálculos realizados aquí.

**Artículo:** [Enlace al PDF del artículo, si está disponible, o mencionar "Ver archivo adjunto"]

---

## 👥 Autores

*   **Ríos Chavarría Christian** - Universidad Politécnica de Durango
*   **Fernández Arámburo Cristian Bladimir** - Universidad Politécnica de Durango
*   **Elva Liliana Limón Dávila** - Universidad Politécnica de Durango

---

## 📚 Referencias

Para el marco teórico y la discusión de resultados, consultar el artículo completo y sus referencias, que incluyen trabajos de Zawacki-Richter et al. (2019), Dignum (2019), Flores & Rodríguez (2024), entre otros.

---

## 📜 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

¡Gracias por tu interés en nuestra investigación! Esperamos que este recurso sea útil para la comunidad académica y educativa.
