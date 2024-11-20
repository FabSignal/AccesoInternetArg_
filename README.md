# **Análisis del Sector de Telecomunicaciones en Argentina**

Este proyecto realiza un análisis del sector de telecomunicaciones en Argentina, con un enfoque en el acceso a internet y su evolución en términos de tecnología y cobertura. El análisis se complementa con la creación de KPIs clave para evaluar el desempeño del sector y proporcionar recomendaciones estratégicas.

---

## ** Descripción del proyecto **

### ** Contexto **
El sector de telecomunicaciones en Argentina ha demostrado ser fundamental para la conectividad y el desarrollo tecnológico. En este proyecto,
asumimos el rol de analista de datos para una empresa de telecomunicaciones que busca identificar oportunidades de crecimiento, 
mejorar la calidad del servicio y brindar soluciones personalizadas a sus clientes.

El trabajo incluye:
- **Análisis Exploratorio de Datos (EDA):** Identificar patrones, valores atípicos y comportamientos significativos.
- **Definición y evaluación de KPIs:** Crear indicadores clave de desempeño para medir objetivos estratégicos.
- **Dashboard interactivo:** Visualización de los resultados y métricas clave en Power BI.

---

## ** Estructura del repositorio **

El repositorio está organizado en las siguientes carpetas y archivos:

### ** 1. `eda_telecomunicaciones.ipynb` **
 Notebook donde se realiza el Análisis Exploratorio de Datos (EDA). Incluye:
  - Limpieza de datos: tratamiento de valores nulos y duplicados.
  - Identificación de patrones y tendencias.
  - Visualización de datos para comprender el comportamiento del sector.

#### ** KPIs **
-  Función para calcular el KPI de aumento en accesos por cada 100 hogares.
-  Función para calcular el KPI de crecimiento absoluto en accesos de fibra óptica.
-  Función para calcular el KPI de incremento en la penetración de fibra óptica.



### ** 2. Dashboard **
- `dashboard.pbix`: Archivo del dashboard interactivo creado en Power BI, que incluye:
  - Representaciones gráficas de los KPIs.
  - Filtros interactivos para explorar los datos por provincia, trimestre y tecnología.
  - Medidores para visualizar dinámicamente el cumplimiento de los KPIs.

### ** 3. Datos **
- `datos_telecom.csv`: Dataset utilizado para el análisis, que incluye información sobre accesos por tecnología, provincias, y periodos.
- `diccionario_datos.md`: Documento que explica las columnas del dataset.

---

## ** KPIs del proyecto **

1. **KPI 1: Aumento del acceso a internet por cada 100 hogares.**
   - **Descripción:** Mide si el acceso a internet crece un 2% trimestre a trimestre por provincia.
   - **Fórmula:** 
     \[
     \text{KPI} = \left( \frac{\text{Nuevo acceso} - \text{Acceso actual}}{\text{Acceso actual}} \right) \times 100
     \]
   - **Visualización:** Medidor en Power BI para comparar el incremento esperado vs. el real.

2. **KPI 2: Crecimiento absoluto en accesos de fibra óptica.**
   - **Descripción:** Evalúa el crecimiento trimestral de accesos de fibra óptica en números absolutos.
   - **Fórmula:** 
     \[
     \text{KPI Fibra Óptica} = \left( \frac{\text{Accesos actuales} - \text{Accesos previos}}{\text{Accesos previos}} \right) \times 100
     \]
   - **Visualización:** Gráfico de barras comparando periodos.

3. **KPI 3: Incremento en la penetración de fibra óptica.**
   - **Descripción:** Analiza el crecimiento relativo de la penetración de fibra óptica respecto al total de tecnologías.
   - **Fórmula:** 
     \[
     \text{KPI Penetración} = \left( \frac{\text{Penetración actual} - \text{Penetración referencia}}{\text{Penetración referencia}} \right) \times 100
     \]
   - **Visualización:** Medidor en Power BI.

---

## ** Cómo ejecutar el proyecto **

### ** 1. Requisitos **
- Python 3.8 o superior.
- Librerías necesarias: `pandas`, `numpy`, `matplotlib`, `seaborn`, `jupyter`.
- Power BI Desktop para visualizar el dashboard.

### ** 2. Ejecución **
1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/analisis-telecomunicaciones.git

--- 
## Fuente de datos

- [Datasets principales](https://indicadores.enacom.gob.ar/datos-abiertos) -Obligatorio: Internet-
- [Diccionario de datos](https://docs.google.com/document/d/1BYW0vT_DNIjjKM9v4hNg5KmqjRNOc7OBB1jCXc80gnI/edit#heading=h.hjukififf3ol)
