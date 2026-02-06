# ESTRATEGIA DE MERCADO 2017 - ANÁLISIS PREDICTIVO DE LA INDUSTRIA DE VIDEOJUEGOS: ECOMMERCE ICE

> **Misión:** Transformar datos históricos del periodo moderno (2012-2016) en una hoja de ruta comercial de alta fidelidad para maximizar el ROI en el lanzamiento de campañas de 2017.

---

## 📖 Contexto del Proyecto

En una industria multimillonaria, el éxito de una tienda de videojuegos depende de su capacidad predictiva, no del volumen de stock. Este análisis, situado en diciembre de 2016, utiliza datos de la tienda "Ice" para identificar patrones de éxito tras la contracción del mercado post-séptima generación. El reto es dirigir una transición estratégica y precisa hacia la era de PS4 y Xbox One.

---

## 📈 Resumen del Análisis Exploratorio (EDA)

A diferencia de análisis tradicionales, este proyecto se enfoca en el **Ciclo de Vida Moderno**, identificando que una plataforma tiene una vida útil promedio de **~8.4 años**.

### 1. Ecosistemas Dominantes
* **Hegemonía de PS4:** Controla el **54.49%** del volumen total de ventas en títulos multiplataforma.
* **La Paradoja de los Críticos:** Se identificó una correlación moderada entre las reseñas profesionales ($r = 0.41$) y las ventas, invalidando las reseñas de usuarios ($r = -0.03$) como métrica predictiva de éxito comercial.

### 2. Eficiencia Comercial por Género
* **Volumen:** El género de **Acción** lidera en cantidad de títulos lanzados (~1,000).
* **Rentabilidad:** Los **Shooters** son el género más eficiente, con una mediana de ventas de **0.44 M USD** por juego, superando casi por 4 veces la rentabilidad del género Acción (**0.12 M USD**).

### 3. Disonancia Regional
* **Occidente (NA/EU):** Mercado de sobremesa (PS4/Xbox) centrado en *Action* y *Shooter* con clasificación **Mature (M)**.
* **Japón (JP):** Ecosistema portátil (**Nintendo 3DS**) centrado en *Role-Playing* y contenido local fuera de la clasificación ESRB.

---

## 🧪 Validación Estadística

Para evitar conclusiones basadas en el azar, cada hallazgo fue sometido a un protocolo de prueba de hipótesis:

* **Plataformas (Xbox One vs. PC):** Se aceptó $H_0$ ($p = 0.5490$); no existe diferencia significativa en la satisfacción del usuario entre ambos ecosistemas.
* **Géneros (Action vs. Sports):** Se rechazó $H_0$ con un efecto de magnitud grande (**Cohen's d = 0.92**) a favor de la Acción.
* **Clasificación (M vs. E):** Se validó que los títulos para adultos generan una satisfacción significativamente superior ($p < 0.05$).

**Metodologías aplicadas:**
1.  **Test de Levene:** Para validación de homogeneidad de varianzas.
2.  **T-Test de Welch:** Para comparaciones robustas con varianzas desiguales.
3.  **Cohen's d:** Para medir el tamaño real del efecto en el negocio.

---

## 🚀 Hoja de Ruta Estratégica para 2017

1.  **Inversión de Inventario:** Prioridad absoluta a la **PS4** en Occidente y a la familia **Nintendo** en Japón.
2.  **Optimización de Catálogo:** Fomentar la adquisición de **Shooters** por su alta rentabilidad por unidad.
3.  **Segmentación de Marketing:** Campañas orientadas a público adulto (**Mature**) en Norteamérica y Europa para asegurar mayores ingresos y fidelidad.
4.  **Gestión de Prensa:** Priorizar la relación con críticos profesionales sobre los agregadores de usuarios para predecir el éxito de ventas.

---

## 📂 Estructura del Proyecto

* `Data Cleaning`: Tratamiento de valores "TBD" y saneamiento del **98.38%** del dataset.
* `EDA`: Análisis de ventas por plataforma, género y región.
* `Regional Profiling`: Creación de perfiles de usuario por mercado (NA, EU, JP).
* `Hypothesis Testing`: Validación estadística de supuestos de negocio.
* `Final Insights`: Recomendaciones estratégicas para la toma de decisiones.

---

## 🛠️ Tech Stack & Herramientas

| Categoría | Herramientas |
| :--- | :--- |
| **Lenguaje** | **Python** (Core Analysis) |
| **Manipulación** | **Pandas 3.0** (Manejo eficiente de NaNs y tipos de datos) |
| **Cálculo Numérico** | **NumPy** |
| **Visualización** | **Matplotlib** & **Seaborn** (Análisis comparativo regional) |
| **Estadística Inferencial** | **SciPy** (Módulos `stats` para validación de hipótesis) |

---