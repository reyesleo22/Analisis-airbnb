# 🏙️ Airbnb CDMX - Análisis de Precios

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.3+-brightgreen)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

Un análisis completo de los precios de Airbnb en la Ciudad de México, identificando patrones, zonas más caras y factores clave que influyen en los precios.

## 📌 Tabla de Contenidos
- [Objetivos](#🎯-objetivos)
- [Dataset](#📂-dataset)
- [Hallazgos Clave](#🔍-hallazgos-clave)
- [Tecnologías](#🛠️-tecnologías)
- [Instalación](#⚙️-instalación)
- [Uso](#🚀-uso)
- [Resultados Visuales](#📊-resultados-visuales)
- [Recomendaciones](#💡-recomendaciones)
- [Contribución](#🤝-contribución)
- [Licencia](#📜-licencia)

## 🎯 Objetivos
1. Analizar la distribución de precios en Airbnb CDMX
2. Identificar las zonas más caras y económicas
3. Determinar factores que influyen en el precio
4. Crear un modelo predictivo básico
5. Generar recomendaciones para viajeros y anfitriones

## 📂 Dataset
El dataset contiene información de:
- 5,000+ propiedades en CDMX
- Variables analizadas:
  - Precio por noche 💰
  - Tipo de alojamiento 🏠
  - Ubicación geográfica 📍
  - Evaluaciones ⭐
  - Disponibilidad 📅

## 🔍 Hallazgos Clave
### 💰 Distribución de Precios
- Precio promedio: **$1,892 MXN**
- 50% de propiedades entre **$850 - $2,200 MXN**

### 🏆 Top 3 Colonias Más Caras
1. Polanco ($3,500 MXN)
2. Lomas de Chapultepec ($3,200 MXN)
3. Condesa ($2,800 MXN)

### 📈 Factores Clave
| Factor | Correlación | Impacto |
|--------|------------|---------|
| Tipo de propiedad | Alta | 🏨 > 🏠 > 🛌 |
| Disponibilidad | -0.28 | 📉 |
| Mínimo de noches | +0.35 | 📈 |

## 🛠️ Tecnologías
```python
📦 pandas - Análisis de datos
📊 matplotlib/seaborn - Visualización
🌍 folium - Mapas interactivos
🤖 scikit-learn - Modelo predictivo
