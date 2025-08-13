# Análisis de Tendencias en la Industria de Videojuegos

## Descripción

Este proyecto presenta un análisis de tendencias sobre un dataset de videojuegos utilizando **Python**, **Pandas** y visualizaciones estáticas. Se complementa con **pruebas de hipótesis** para identificar las plataformas, géneros y estrategias de comercialización más prometedoras de cara al año 2017.

## Objetivo del Proyecto

Explorar datos históricos de ventas, calificaciones y plataformas de videojuegos para generar conclusiones útiles en la planeación de campañas y estrategias comerciales, con el fin de maximizar el retorno de inversión en diferentes mercados.

---

## Herramientas Utilizadas

* **Python**
* **Pandas** para la manipulación y análisis de datos.
* **Matplotlib** y **Seaborn** para la creación de visualizaciones.
* **NumPy** para operaciones numéricas.
* **SciPy** para la ejecución de pruebas de hipótesis estadísticas.

---

## Flujo de Trabajo del Análisis

El proyecto siguió una estructura secuencial para garantizar un análisis ordenado y lógico.

[1] Carga y limpieza de datos
↓
[2] Análisis exploratorio (EDA)
↓
[3] Visualizaciones estáticas para tendencias globales y regionales
↓
[4] Pruebas de hipótesis (comparaciones entre plataformas y géneros)
↓
[5] Interpretación de resultados
↓
[6] Conclusiones y recomendaciones para 2017

---

## Principales Hallazgos

* El período de **2005 a 2011** registró la mayor densidad de ventas, impulsado por el auge simultáneo de consolas como DS, Wii, PS3 y Xbox 360.
* A partir de **2012**, las ventas globales disminuyeron debido al fin de ciclo de vida de varias consolas importantes.
* Para el año 2017, **PS4**, **Xbox One** y **PC** mostraban el mayor potencial de mercado, con la PS4 como líder en crecimiento.
* Las plataformas modernas (PS4, XOne y PC) presentan valores atípicos positivos en ventas, indicando un alto potencial para generar grandes éxitos comerciales (*blockbusters*).
* Se encontró una **correlación moderada** entre las calificaciones de la crítica especializada y las ventas. En contraste, la correlación entre las calificaciones de los usuarios y las ventas fue casi nula.
* Los géneros más rentables a nivel global son **Action**, **Shooter** y **Sports**.
* **Diferencias regionales clave**:
    * **Norteamérica y Europa**: Prefieren los géneros *Action* y *Shooter*.
    * **Japón**: Muestra una clara preferencia por el género *Role-Playing (RPG)*, seguido de *Action*.
* Las clasificaciones de la ESRB que más venden son **M** (Mature), **E** (Everyone) y **T** (Teen).

---

## Pruebas de Hipótesis

1.  **Xbox One vs. PC (Calificaciones de usuarios)**: No se encontró una diferencia estadísticamente significativa en las calificaciones promedio de los usuarios entre ambas plataformas.
2.  **Action vs. Sports (Calificaciones de la crítica)**: Se encontró una diferencia estadísticamente significativa en las calificaciones promedio de la crítica entre estos dos géneros.

---

## Conclusiones y Recomendaciones para 2017

* **Plataformas prioritarias**: Se recomienda enfocar los esfuerzos de desarrollo y marketing en **PS4**, seguida de **Xbox One** y **PC**.
* **Géneros prioritarios**:
    * Mercado occidental (NA/EU): **Action**, **Shooter** y **Sports**.
    * Mercado japonés: **Role-Playing**.
* **Clasificaciones recomendadas**: Los juegos con clasificación **E**, **T** y **M** tienen el mayor potencial de ventas, adaptando la estrategia al público objetivo de cada mercado.

---

## Dataset

Los datos utilizados para este análisis fueron proporcionados como parte de un proyecto académico.