# 📊 Integración Multidimensional de Datos para la Optimización de Créditos

## 🧠 Descripción del Proyecto

Este proyecto tiene como objetivo aplicar técnicas de **integración multidimensional de datos** para optimizar la asignación de créditos en una entidad del sector fintech.

A través del uso de variables financieras, demográficas y geográficas, se segmentaron los solicitantes mediante el algoritmo **K-Means**, permitiendo identificar diferentes perfiles de riesgo y mejorar la toma de decisiones.

---

## 🎯 Objetivos

* Reducir el número de sucursales físicas mediante la agrupación de clientes
* Identificar perfiles de riesgo crediticio
* Mejorar la eficiencia en la asignación de créditos
* Analizar la distribución geográfica de los solicitantes

---

## ⚙️ Metodología

1. **Selección de variables**

   * Ingresos, egresos, monto, edad, estrato, zona, entre otros

2. **Preprocesamiento**

   * Limpieza de datos
   * Normalización
   * Codificación de variables categóricas

3. **Clustering**

   * Aplicación del algoritmo K-Means con **k = 5**
   * Cada cluster representa una sucursal

4. **Análisis**

   * Número de clientes por cluster
   * Porcentaje de preaprobación y prenegación
   * Procedencia geográfica (municipios)

5. **Visualización**

   * Gráficos de radar
   * Gráficos de barras
   * Distribuciones por cluster

---

## 📈 Resultados

Se identificaron **5 clusters de clientes**, cada uno con características específicas:

* Diferentes niveles de aprobación y riesgo
* Concentración geográfica por municipios
* Distribución desigual de clientes entre clusters

Estos resultados permiten una mejor asignación de recursos y una toma de decisiones más eficiente.

---

## 🌐 Visualización Web

Los resultados fueron desplegados en una página web utilizando **GitHub Pages**, donde se pueden visualizar:

* Tabla resumen de clusters
* Gráficos de perfiles
* Distribución de clientes
* Análisis de aprobación/rechazo

---

## 🛠️ Tecnologías utilizadas

* Python (Pandas, NumPy, Scikit-learn)
* Matplotlib y Seaborn
* Google Colab
* GitHub

---

## 📌 Conclusión

El uso de técnicas de clustering permite segmentar a los clientes de manera eficiente, facilitando la reducción de sucursales y optimizando la asignación de créditos en función del perfil de riesgo.
