# IceGames Analytics: Inteligencia de Mercado y Modelado Predictivo para la Industria de Videojuegos

Este proyecto desarrolla un análisis predictivo y un estudio de inteligencia comercial a gran escala para identificar los patrones clave que determinan el éxito financiero de un videojuego en el mercado global. A través del procesamiento de datos históricos de ventas, reseñas de expertos y clasificaciones de usuarios, el sistema permite predecir tendencias emergentes y optimizar la planeación de presupuestos publicitarios para los próximos periodos comerciales.

## 🎯 Objetivos Estratégicos
* **Detección de Proyectos Prometedores:** Identificar los factores críticos (plataformas, géneros y clasificaciones de edad) que impulsan las ventas millonarias de un título.
* **Ciclo de Vida de Plataformas:** Analizar la velocidad de adopción y obsolescencia de las consolas en el mercado mundial (Sony, Microsoft, Nintendo, PC) para mitigar riesgos de inversión en hardware saliente.
* **Segmentación de Consumidores por Región:** Construir el perfil de usuario definitivo para los mercados de Norteamérica (NA), Europa (UE) y Japón (JP) para personalizar campañas de marketing geolocalizadas.
* **Validación Estadística de Hipótesis:** Aplicar pruebas de hipótesis robustas para evaluar diferencias significativas en las preferencias de los usuarios entre plataformas y géneros comerciales.

## 🛠️ Tecnologías y Metodología Avanzada
* **Python 3.x:** Lenguaje principal de análisis.
* **Pandas & NumPy:** Procesamiento, limpieza profunda y tratamiento de datos atípicos, valores ausentes y manejo de variables en estado indeterminado (como datos etiquetados como `TBD`).
* **Matplotlib & Seaborn:** Genereción de diagramas de caja (*Boxplots*) para análisis de dispersión de ventas, gráficos de dispersión (*Scatter plots*) para estudios de correlación y análisis de distribuciones anuales de lanzamientos.
* **SciPy (Stats):** Implementación de pruebas estadísticas de dos muestras (*T-Test*) para la validación científica de comportamientos y calificaciones del mercado.

## 📊 Arquitectura del Análisis Operativo
El flujo de análisis e ingeniería de datos en el Jupyter Notebook está estructurado formalmente en las siguientes fases de negocio:

1. **Estandarización y Calidad de Información:** Limpieza de variables categóricas (nombres en minúsculas), corrección de tipos de datos y cálculo unificado de la columna métrica de Ventas Globales Totales combinando todas las regiones.
2. **Determinación del Periodo Relevante:** Análisis retrospectivo del ciclo de vida comercial del software para aislar datos históricos obsoletos y centrar el modelo predictivo únicamente en el mercado moderno activo para el año de planeación.
3. **Análisis de Correlación (Críticos vs. Ventas):** Modelado matemático para medir el impacto real de las reseñas de profesionales y usuarios en las decisiones de compra del consumidor dentro de una misma plataforma.
4. **Validación de Perfiles de Consumo Regional:** Mapeo de cuotas de mercado por región (NA, EU, JP) analizando cómo los géneros preferidos y las regulaciones de edad de la ESRB afectan el volumen de ventas local.

## 📂 Estructura del Repositorio
```text
├── data/                    # Set de datos histórico de la industria de videojuegos (CSV)
├── notebooks/               # Entorno de desarrollo para la limpieza de datos y modelado estadístico
├── ice_games_analytics.ipynb # Jupyter Notebook principal con conclusiones y celdas ejecutadas
└── README.md                # Portada ejecutiva y documentación del proyecto
```

## 📈 Conclusiones Comerciales Clave (Resumen)
El modelo matemático y los análisis visuales implementados logran resolver preguntas operativas fundamentales:
* **Fórmula del Éxito:** Segmentación automatizada de los géneros más rentables económicamente a nivel global frente a aquellos con altas distribuciones de lanzamientos pero bajo retorno de inversión.
* **Decisiones Basadas en Datos:** Resultados listos para ser presentados ante directivos y agencias de publicidad, asegurando una distribución eficiente de los recursos financieros en las consolas y títulos con mayor probabilidad de convertirse en éxitos comerciales.


