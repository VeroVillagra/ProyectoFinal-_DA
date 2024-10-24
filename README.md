# Proyecto Airlines: proyección de Mejora Financiera 

## Descripción del Proyecto
Este proyecto se centra en la **aviación comercial**, abordando desafíos como fluctuaciones en la demanda de vuelos, variaciones en los precios de los combustibles y la creciente competencia entre aerolíneas. La búsqueda de mantener o aumentar la rentabilidad es crucial para el sector.

## Problema
El objetivo principal es aumentar la rentabilidad a través del análisis de dos flujos:
- *Desestimación de rutas no rentables.*
- *Captación de rutas aún no explotadas.*

## Objetivo
Identificar rutas potencialmente rentables mediante el análisis de la demanda y establecer rutas no rentables para desestimarlas o generar alternativas unificando rutas cercanas.

## Requerimientos
Como analistas, debemos:
- Identificar patrones de rutas.
- Realizar análisis geoespaciales.
- Analizar la rentabilidad de las rutas actuales.

## Plan de Análisis
1. **Exploración de datos**: Limpieza de datos y eliminación de valores nulos.
2. **Análisis de demanda**: Evaluar la ocupación promedio de las rutas actuales.
3. **Análisis geoespacial**: Mapear rutas existentes y posibles nuevas.
4. **Modelado predictivo**: Evaluar la demanda potencial de nuevas rutas.
5. **Simulación de costos**: Estimar costos de apertura y cierre de rutas.
6. **Recomendaciones**: Informe con recomendaciones de rutas a abrir o cerrar.

## Resultados Esperados e Impacto
- Detectar rutas con alto potencial de demanda.
- Recomendar la discontinuación de rutas no rentables.
- Mejorar la **eficiencia operativa** y **optimizar recursos**.

## Fases Propuestas
- **Procesamiento de datos**: Limpieza y tratamiento de valores faltantes.
- **Análisis exploratorio de datos (EDA)**: Visualización y análisis de patrones.
- **Modelado predictivo**: Anticipar la demanda en nuevas rutas.
- **Evaluación de rentabilidad**: Comparar demanda proyectada con costos operativos.

## Herramientas y Tecnologías
- **Python**: Análisis de datos.
- **SQL**: Almacenamiento y consulta de datos.
- **Pandas y Numpy**: Manipulación de datos.
- **Matplotlib y Seaborn**: Visualización de datos.
- **Geopandas**: Análisis geoespacial.
- **Power BI**: Generación de visualizaciones y reportes interactivos.
- **Google Cloud**: Almacenamiento de datos.

## Estructura del Proyecto
- **Airlines**: Carpeta principal.
  - **Base de Datos**: Archivos sobre conexión y estado de la base de datos.
    - *`Conexión Google Cloud-Power BI`*: Descripción de la conexión.
    - *`Limpieza de Datos y Creación de DDBB Local`*: Proceso de limpieza y creación de base de datos.
    - *`Proyecto Airlines en la Nube`*: Motivos para usar Google Cloud.
  - **Documentación**: Archivos con información variada.
    - *`Guía_Tablas`*: Información sobre las tablas del dataset.
    - *`Limpieza_Tablas`*: Proceso de limpieza del dataset.
  - **Power BI**: Archivos relacionados con reportes y visualizaciones.
    - *`Mockup`*: Representación visual del diseño final.
    - *`Airlines-dashboard`*: Dashboards de soporte.
    - *`Reporte`*: Reporte final del análisis.
  - **Raw_data**: Archivos CSV sin limpiar.
 
## Conclusiones 🚀

A través de técnicas avanzadas de análisis de datos, hemos logrado identificar rutas no rentables que pueden ser desestimadas y rutas emergentes con alto potencial de demanda. 

El enfoque de **análisis geoespacial**, combinado con el **modelado predictivo**, permitirá al cliente tomar decisiones estratégicas con datos respaldados, optimizando sus recursos y aumentando su competitividad en un mercado dinámico y desafiante.

### Impacto Esperado:
- **Reducción de costos** al eliminar rutas poco rentables.
- **Incremento en ingresos** mediante la apertura de rutas en mercados emergentes.
- **Optimización de operaciones** para una mayor eficiencia y sustentabilidad a largo plazo.

Gracias al uso de herramientas como **Python**, **Power BI**, y **Google Cloud**, el análisis ha sido exhaustivo y visualmente claro, facilitando la toma de decisiones basada en datos sólidos y proyecciones precisas.

Este proyecto ayuda a mejorar la eficiencia operativa y proporciona un marco escalable para futuros análisis dentro del sector de la aviación.


## Colaboradores
- **Verónica Villagra**  
  - Analista de datos
  - **LinkedIn**: [Verónica Villagra](https://www.linkedin.com/in/veronica-villagra)

- **María de los Angeles Páez**  
  - Analista de datos
  - **LinkedIn**: [María de los Angeles Páez](https://www.linkedin.com/in/maria-de-los-angeles-paez)

- **Emanuel Achar**  
  - Analista de datos
  - **LinkedIn**: [Emanuel Achar](https://www.linkedin.com/in/emanuel-achar)
## Licencia
Este proyecto está bajo la licencia MIT. Para más detalles, consulta el archivo [LICENSE](LICENSE).
