# 🎮 Análisis de Ventas de Videojuegos para Ice

## 📌 Resumen del Proyecto
Este proyecto tiene como objetivo identificar los factores que determinan el éxito comercial de los videojuegos, utilizando datos históricos de ventas, reseñas, plataformas y géneros. El análisis ayuda a detectar tendencias, evaluar plataformas rentables y planificar campañas publicitarias eficaces para el año 2017.

---

## 📂 Tecnologías Utilizadas
- Python (Pandas, NumPy, Matplotlib, Seaborn, SciPy)
- Jupyter Notebook
- Estadística inferencial y análisis exploratorio de datos (EDA)

---

## 🔍 Principales Hallazgos

### 📉 Plataformas que solían ser populares pero desaparecieron
- **PS2**: Dominó los 2000, pero desapareció después de 2012.
- **PSP**: Tuvo buen rendimiento entre 2005–2012.
- **DS**: Pico entre 2008–2009, desapareció tras 2014.
- **GBA**: Activa entre 2001 y 2007.
- **PS1**: Líder hasta 2002.

### ⏱️ Duración de vida útil:
- **Plataformas exitosas**: 7–10 años
- **Plataformas menores**: 4–6 años
- **Tiempo para alcanzar el pico**: 1–3 años tras su lanzamiento

### 📈 Tendencias en Plataformas
**En Crecimiento:**
- **PS4**: Ventas crecientes, potencial alto
- **PC**: Estable, sin grandes caídas

**En Declive:**
- PS2, PS3, X360, Wii, DS, PSP: Cayeron después de 2012–2014

### 📊 Análisis de Ventas por Plataforma
- Las ventas varían significativamente entre plataformas.
- **Wii, PS2, PS3, X360, WiiU**: Mayor promedio de ventas
- **PSV, PC, PSP**: Menor promedio y mayor dispersión

📌 **Conclusión:** Las plataformas líderes no solo venden más, sino que tienen más títulos exitosos.

## 🌍 Preferencias Regionales

**América del Norte (NA)**
- Género líder: Acción
- Plataforma popular: PS4

**Europa (EU)**
- Similar a NA, con fuerte presencia de Acción y Shooter

**Japón (JP)**
- Género líder: Rol (RPG)
- Plataforma fuerte: 3DS

🔎 **Recomendación:** Enfocar campañas de RPG en Japón, especialmente en 3DS.

## 📈 Reseñas y Correlaciones
- **Correlación entre calificaciones de usuarios y ventas**: Baja, no significativa
- **Correlación con críticas profesionales**: Ligeramente mayor, pero aún moderada

🎯 **Insight:** Las calificaciones no predicen ventas con fuerza. Otros factores (género, plataforma, región) pesan más.

## 🧪 Pruebas de Hipótesis

**Xbox One vs PC (User Score)**
- Resultado: Diferencia significativa
- p-valor < 0.05 → Se rechaza H₀

**Acción vs Deportes (User Score)**
- Resultado: Sin diferencia significativa
- p-valor > 0.05 → No se rechaza H₀

---

## 📈 Conclusiones Generales
- Las plataformas exitosas duran hasta 10 años; las débiles desaparecen en 4–6.
- Las ventas dependen más del género, la región y la plataforma que de las reseñas.
- PS4 es la única consola con tendencia creciente al final del período.
- El género de acción domina en América y Europa, mientras que rol (RPG) tiene más aceptación en Japón.
- El análisis de datos permite a la empresa Ice enfocar sus esfuerzos de marketing y distribución de forma más eficiente y rentable.

---

## 🧠 Lecciones Aprendidas
- Aplicación de técnicas estadísticas y pruebas de hipótesis reales en negocios.
- Evaluación crítica de datos faltantes y su impacto en el análisis.
- Visualización y comparación efectiva de múltiples variables categóricas y numéricas.
