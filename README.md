# **Análisis del Sector de Telecomunicaciones en Argentina**

Este proyecto realiza un análisis del sector de telecomunicaciones en Argentina, con un enfoque en el acceso a internet y su evolución en términos de tecnología y cobertura. El análisis se complementa con la creación de KPIs clave para evaluar el desempeño del sector y proporcionar recomendaciones estratégicas.

---

## **Descripción del proyecto**

### **Contexto**
El sector de telecomunicaciones en Argentina ha demostrado ser fundamental para la conectividad y el desarrollo tecnológico. En este proyecto,
asumimos el rol de analista de datos para una empresa de telecomunicaciones que busca identificar oportunidades de crecimiento, 
mejorar la calidad del servicio y brindar soluciones personalizadas a sus clientes.

El trabajo incluye:
- **Análisis Exploratorio de Datos (EDA):** Identificar patrones, valores atípicos y comportamientos significativos.
- **Definición y evaluación de KPIs:** Crear indicadores clave de desempeño para medir objetivos estratégicos.
- **Dashboard interactivo:** Visualización de los resultados y métricas clave en Power BI.

---

## **Estructura del repositorio**

El repositorio está organizado de la siguiente manera:

### **1. Notebooks**
- 'eda_telecomunicaciones.ipynb': Jupyter Notebook que incluye:
  - **Análisis Exploratorio de Datos (EDA)**:
    - Limpieza de datos: tratamiento de valores nulos y duplicados.
    - Identificación de patrones y tendencias en los datos.
    - Visualización de datos para comprender el comportamiento del sector.
  - **Cálculo de KPIs**:
    - Función para calcular el KPI de aumento en accesos por cada 100 hogares.
    - Función para calcular el KPI de crecimiento absoluto en accesos de fibra óptica.
    - Función para calcular el KPI de incremento en la penetración de fibra óptica.
  - **Reporte**: Resumen de los hallazgos, conclusiones y recomendaciones derivadas del análisis.

### **2. Datos**
- 'datos_enacom': Dataset utilizado para el análisis, que incluye información sobre accesos por tecnología, provincias y periodos.
- 'diccionario_datos': Documento que explica las columnas del dataset.

### **3. Dashboard**
- 'dashboard.pbix': Archivo del dashboard interactivo creado en Power BI, que incluye:
  - Representaciones gráficas de los KPIs.
  - Filtros interactivos para explorar los datos por provincia, trimestre y tecnología.
  - Medidores para visualizar dinámicamente el cumplimiento de los KPIs.

### **4. Documentación**
- 'README.md': Este archivo, que describe la estructura y propósito del repositorio.


---

## **KPIs del proyecto**

1. **KPI 1: Aumento del acceso a internet por cada 100 hogares.**
   - **Descripción:** Mide si el acceso a internet crece un 2% trimestre a trimestre por provincia.
  
   - **Fórmula:** 

       $\text{KPI} = \left( \frac{\text{Nuevo acceso} - \text{Acceso actual}}{\text{Acceso actual}} \right) \times 100$


   - **Visualización:** Medidor en Power BI para comparar el incremento esperado vs. el real.

2. **KPI 2: Crecimiento absoluto en accesos de fibra óptica.**
   - **Descripción:** Evalúa si el crecimiento trimestral de accesos de fibra óptica es igual o superior al 3% en números absolutos.
   - **Fórmula:** 
     
     $\text{KPI Fibra Óptica} = \left( \frac{\text{Accesos actuales} - \text{Accesos previos}}{\text{Accesos previos}} \right) \times 100$
     
    
   


   - **Visualización:** Gráfico de barras comparando periodos.

3. **KPI 3: Incremento en la penetración de fibra óptica.**
   - **Descripción:** Analiza el crecimiento relativo de la penetración de fibra óptica respecto al total de tecnologías es igual o superior al 3%.
   - **Fórmula:** 

   
     $\text{KPI Penetración} = \left( \frac{\text{Penetración actual} - \text{Penetración referencia}}{\text{Penetración referencia}} \right) \times 100$


   - **Visualización:** Medidor en Power BI.

---

## **Cómo ejecutar el proyecto**

### **1. Requisitos**
- Python 3.8 o superior.
- Librerías necesarias: 'pandas', 'numpy', 'matplotlib', 'seaborn', 'jupyter'.
- Power BI Desktop para visualizar el dashboard.

### **2. Ejecución**
1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/analisis-telecomunicaciones.git

--- 
## Fuente de datos

- [Enacom](https://indicadores.enacom.gob.ar/datos-abiertos) 
- [Diccionario de datos](https://docs.google.com/document/d/1BYW0vT_DNIjjKM9v4hNg5KmqjRNOc7OBB1jCXc80gnI/edit#heading=h.hjukififf3ol)
