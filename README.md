# 📞 Telecom Operator Efficiency Analysis

## 📋 Descripción

Este proyecto analiza el desempeño de operadores de un centro de llamadas utilizando Python, SQL y Tableau con el objetivo de identificar operadores ineficaces mediante indicadores de rendimiento obtenidos a partir de registros de llamadas.

Se realizó un proceso completo de análisis de datos que incluyó:

- Limpieza y preparación de datos.
- Análisis Exploratorio de Datos (EDA).
- Integración de múltiples conjuntos de datos.
- Cálculo de métricas operativas.
- Identificación de operadores con bajo desempeño.
- Visualización de resultados mediante un dashboard interactivo en Tableau.

---

## 🎯 Objetivo

Identificar operadores ineficaces utilizando métricas de desempeño como:

- Tiempo promedio de espera.
- Duración de llamadas.
- Cantidad de llamadas perdidas.
- Llamadas entrantes y salientes.
- Rendimiento general del operador.

Los resultados permiten detectar oportunidades de mejora para optimizar la atención al cliente.

---

## 🛠️ Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook
- Tableau Public

---

## 📂 Estructura del proyecto

```
├── Telecom - Churn.ipynb      # Notebook principal del análisis
├── README.md
└── datasets/
```

---

## 📊 Proceso del análisis

### 1. Carga de datos

Se importaron los conjuntos de datos de telecomunicaciones y clientes.

### 2. Análisis Exploratorio de Datos (EDA)

Se realizó:

- Revisión de tipos de datos.
- Identificación de valores nulos.
- Eliminación de duplicados.
- Corrección de inconsistencias.
- Estadística descriptiva.
- Visualización de distribuciones.

### 3. Preparación de datos

Se integraron ambos conjuntos de datos para obtener una base consolidada de operadores y llamadas.

### 4. Ingeniería de características

Se calcularon indicadores como:

- Tiempo de espera.
- Duración promedio de llamadas.
- Número de llamadas atendidas.
- Número de llamadas perdidas.
- Cantidad de llamadas entrantes y salientes.

### 5. Identificación de operadores ineficaces

Se definieron criterios para clasificar a los operadores según su desempeño y se compararon sus métricas mediante análisis estadístico y visualizaciones.

---

## 📈 Dashboard interactivo

Puedes explorar el dashboard desarrollado en Tableau Public en el siguiente enlace:

🔗 **https://public.tableau.com/views/DashboardTelecomunicaciones_17821513335520/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link**

---

## 📌 Principales hallazgos

- Se identificaron operadores con tiempos de espera considerablemente superiores al promedio.
- Algunos operadores presentan una mayor proporción de llamadas perdidas.
- Existen diferencias importantes en la duración promedio de las llamadas entre operadores.
- Las métricas obtenidas permiten establecer criterios objetivos para evaluar el desempeño operativo.

---

## 🚀 Cómo ejecutar el proyecto

1. Clonar el repositorio:

```bash
git clone (https://github.com/diegoverclock/telecom-operator-performance-analysis.git
```

2. Instalar las dependencias:

```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

3. Abrir el notebook:

```bash
jupyter notebook
```

4. Ejecutar el archivo:

```
Telecom.ipynb
```

---

## 📁 Fuente de datos

Los datos utilizados corresponden a registros de llamadas y operadores de un centro de atención telefónica con fines académicos para el desarrollo de este proyecto.

---

## 👤 Autor

**Ing. Diego Alonso Morales Salazar**

Proyecto desarrollado como parte de un análisis de datos enfocado en la evaluación del desempeño de operadores de telecomunicaciones utilizando Python y Tableau.

