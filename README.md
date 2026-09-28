# ⚽ Fichas Técnicas LaLiga 25/26 — Dashboard Interactivo en Power BI

![Portada LaLiga](https://raw.githubusercontent.com/DanielPrados/Fichas-tecnicas-LA-LIGA-25-26/main/captura_portada.png)

## 📌 Descripción
Dashboard interactivo en **Power BI** para el análisis estadístico, táctico y de rendimiento de todos los clubes de **LaLiga EA Sports (Temporada 25/26)**. Diseñado para ofrecer tanto una vista macro de la competición como fichas técnicas pormenorizadas a nivel de plantilla y jugador.

---

## 🔍 Extracción y Modelado de Datos (ETL)
* **Base inicial:** Dataset procesado en Excel procedente del curso de *Objetivo Analista* (datos hasta la jornada 9).
* **Web Scraping & Automatización (Python):** Extracción de las jornadas restantes mediante scripts en Python realizando scraping sobre **FBref** y obtención de métricas avanzadas de **goles esperados (xG)** a través de **Understat**.
* **Estructuración:** Limpieza, unificación de formatos y modelado de datos final en `LaLiga_2526.xlsx`.

---

## ✨ Puntos Clave del Dashboard
* **🎨 UI/UX Personalizada:** Adaptación estética y cromática a la identidad visual de cada uno de los 20 clubes de LaLiga.
* **🔀 Navegación y Filtros Dinámicos:** Módulos interconectados para alternar entre el análisis colectivo del club y las métricas individuales por futbolista.
* **📊 Visión Global:** Panel general con métricas agregadas de la competición sin selección de equipo.
* **🎯 Métrica Avanzada (xG):** Evolución de goles esperados por partido frente a goles reales a favor y en contra.

---

## 🛠️ Stack Tecnológico
* **Power BI Desktop:** Modelado de datos (DAX), maquetación y diseño de interfaz.
* **Python (`requests`, `beautifulsoup4`, `pandas`):** Recolección y tratamiento de datos vía web scraping.
* **Excel / Power Query:** Transformación preliminar.

---

## 📁 Archivos del Repositorio
* [`Ficha equipos liga 25-26.pbix`](./Ficha%20equipos%20liga%2025-26.pbix): Informe fuente editable de Power BI.
* [`LaLiga_2526.xlsx`](./LaLiga_2526.xlsx): Libro con las tablas procesadas.

---

## 📸 Capturas de Pantalla

### Ficha Técnica de Club
![Ficha Club](https://raw.githubusercontent.com/DanielPrados/Fichas-tecnicas-LA-LIGA-25-26/main/captura_equipo.png)

### Análisis Comparativo de xG
![Análisis xG](https://raw.githubusercontent.com/DanielPrados/Fichas-tecnicas-LA-LIGA-25-26/main/captura_xg.png)
