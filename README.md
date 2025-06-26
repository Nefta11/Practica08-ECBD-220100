# 📊 Análisis de Salarios Globales en IA/ML - Práctica 08

## 🎯 Descripción del Proyecto

Este proyecto forma parte de la **Práctica 08** del curso de Estructuras de Computación y Bases de Datos (ECBD-220100). El objetivo principal es realizar un análisis exhaustivo de los salarios globales en el campo de Inteligencia Artificial y Machine Learning, utilizando técnicas de ciencia de datos y visualización.

## 📁 Estructura del Proyecto

```
Practica08-ECBD-220100/
├── 📄 README.md                           # Documentación del proyecto
├── 📊 global_ai_ml_data_salaries.csv     # Dataset principal con datos de salarios
├── 📓 Untitled1.ipynb                    # Notebook principal con análisis
└── 🔍 Archivos de análisis y visualización
```

## 🗃️ Dataset

El dataset `global_ai_ml_data_salaries.csv` contiene información sobre salarios en el sector de IA/ML con las siguientes características:

- **work_year**: Año de trabajo
- **experience_level**: Nivel de experiencia (EN, MI, SE, EX)
- **employment_type**: Tipo de empleo (FT, PT, CT, FL)
- **job_title**: Título del trabajo
- **salary**: Salario en moneda local
- **salary_currency**: Moneda del salario
- **salary_in_usd**: Salario convertido a USD
- **employee_residence**: País de residencia del empleado
- **remote_ratio**: Porcentaje de trabajo remoto
- **company_location**: Ubicación de la empresa
- **company_size**: Tamaño de la empresa (S, M, L)

## 🔬 Metodología de Análisis

El notebook sigue una metodología estructurada que incluye:

### 📋 Step 1: Configuración de Librerías
- Importación de librerías esenciales para análisis de datos
- Configuración de estilos de visualización
- Manejo de advertencias y optimización de memoria

### 📂 Step 2: Carga del Dataset
- Carga segura del dataset con manejo de errores
- Validación de la integridad de los datos

### 🔍 Step 3: Exploración de Atributos
- Análisis de la estructura del dataset
- Identificación de tipos de datos y características

### 🧹 Step 4: Manejo de Valores Faltantes
- Detección y visualización de valores nulos
- Implementación de estrategias de limpieza

### 🔄 Step 5: Gestión de Duplicados
- Identificación de registros duplicados
- Eliminación y validación de datos únicos

### 📈 Step 6: Resumen Estadístico
- Cálculo de estadísticas descriptivas completas
- Análisis de distribuciones y tendencias centrales

## 🛠️ Tecnologías y Librerías Utilizadas

### 📊 Análisis de Datos
- **Pandas**: Manipulación y análisis de datos
- **NumPy**: Operaciones numéricas y álgebra lineal
- **SciPy**: Funciones estadísticas avanzadas

### 📈 Visualización
- **Matplotlib**: Gráficos estáticos y personalizados
- **Seaborn**: Visualizaciones estadísticas elegantes
- **WordCloud**: Nubes de palabras para análisis textual

### 🔧 Utilidades
- **RE**: Expresiones regulares
- **Itertools**: Herramientas de iteración
- **Warnings**: Manejo de advertencias
- **IPython**: Herramientas de visualización interactiva

## 🚀 Cómo Ejecutar el Proyecto

### Prerrequisitos
```bash
pip install pandas numpy scipy matplotlib seaborn wordcloud jupyter
```

### Ejecución
1. Clona o descarga el repositorio
2. Asegúrate de que el archivo `global_ai_ml_data_salaries.csv` esté en el directorio raíz
3. Abre el notebook `Untitled1.ipynb` en Jupyter Lab/Notebook
4. Ejecuta las celdas secuencialmente

## 📊 Resultados Esperados

El análisis proporciona insights sobre:
- 💰 Distribución de salarios por experiencia y ubicación
- 🌍 Tendencias geográficas en compensación
- 📈 Evolución temporal de salarios en IA/ML
- 🏢 Impacto del tamaño de empresa en la compensación
- 🏠 Efectos del trabajo remoto en los salarios

## 👥 Autor

**Práctica desarrollada para ECBD-220100**

## 📝 Notas Adicionales

- El dataset se actualiza periódicamente con nuevos registros
- Los análisis incluyen validaciones estadísticas robustas
- Las visualizaciones están optimizadas para presentación académica

---

*Este proyecto forma parte del aprendizaje en ciencia de datos y análisis estadístico aplicado al sector tecnológico.*
