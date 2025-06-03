

---

```markdown
# 📊 Análisis Exploratorio de Salarios y Procesos de Secuenciadores en Ciencia de Datos

## 🧠 Descripción del Proyecto

Este repositorio contiene un proyecto de Análisis Exploratorio de Datos (EDA) desarrollado para el curso *Fundamentos de Ciencia de Datos*. Su objetivo es analizar la base de datos `ds_salaries.csv` para:

- Explorar tendencias salariales globales en roles de ciencia de datos.
- Mapear procesos relacionados con los secuenciadores, de acuerdo con las instrucciones de trabajo.

El análisis se desarrolla en Google Colab utilizando herramientas como **Pandas**, **NumPy**, **Matplotlib**, **Seaborn** y **Plotly**.

---

## 🎯 Objetivo

Proporcionar una visión clara sobre:

- Expectativas salariales globales en ciencia de datos.
- Distribución de roles y niveles de experiencia.
- Carga de trabajo desde la perspectiva de secuenciadores.

---

## 📑 Tabla de Contenidos

1. [Estructura del Proyecto](#estructura-del-proyecto)
2. [Requisitos](#requisitos)
3. [Instalación y Configuración](#instalación-y-configuración)
4. [Uso](#uso)
5. [Estructura del Notebook](#estructura-del-notebook)
6. [Resultados Clave](#resultados-clave)
7. [Contribuciones](#contribuciones)
8. [Licencia](#licencia)

---

## 🗂️ Estructura del Proyecto

```

├── ds\_salaries.csv           # Dataset utilizado para el análisis
├── proyecto\_eda.ipynb        # Notebook con el EDA completo
├── README.md                 # Este archivo

````

---

## 📋 Requisitos

- Python >= 3.8
- Google Colab (recomendado)
- Acceso a internet para cargar dependencias

### 🧪 Librerías necesarias

```bash
pandas >= 2.0.0  
numpy >= 1.24.0  
matplotlib >= 3.7.0  
seaborn >= 0.12.0  
plotly >= 5.14.0  
````

---

## ⚙️ Instalación y Configuración

### 🔁 Clonar el repositorio

```bash
git clone https://github.com/<tu-usuario>/fundamentos-ciencia-datos-eda.git
cd fundamentos-ciencia-datos-eda
```

### ☁️ Si usas Google Colab

1. Sube `proyecto_eda.ipynb` a Google Colab.
2. Sube `ds_salaries.csv` al entorno (`/content/`).
3. Ejecuta las celdas secuencialmente.

### 💻 Si usas Jupyter local

```bash
pip install pandas numpy matplotlib seaborn plotly
jupyter notebook proyecto_eda.ipynb
```

---

## 🚀 Uso

1. Abre el notebook en Colab o localmente.
2. Asegúrate de que el archivo `ds_salaries.csv` esté en la ruta correcta.
3. Ejecuta las celdas en orden.
4. Lee los *insights* incluidos en las celdas Markdown.

---

## 📓 Estructura del Notebook

| Sección                   | Contenido                                                         |
| ------------------------- | ----------------------------------------------------------------- |
| Introducción              | Objetivo del análisis y contexto                                  |
| Carga de Datos            | Importación de librerías y dataset                                |
| Descripción de Columnas   | Tabla en Markdown con descripciones y tipos                       |
| Análisis de Completitud   | Revisión de nulos y estructura del dataset                        |
| Estadísticas Descriptivas | Valores promedio, mínimos, máximos, etc.                          |
| Correlación               | Matriz de correlación de Pearson con mapa de calor                |
| Visualizaciones           | Barras, histogramas, boxplots, etc.                               |
| Mapeo de Secuenciadores   | Interpretación de columnas como procesos (cliente, usuario, etc.) |
| Insights                  | Interpretaciones explicativas en cada sección                     |
| Conclusiones              | Hallazgos principales y limitaciones del análisis                 |

---

## 📈 Resultados Clave

* **Salarios por año**: Crecimiento progresivo entre 2020 y 2023.
* **EE.UU. lidera** los salarios promedio (> \$99,000 USD).
* **Roles más comunes**: Data Scientist y Data Engineer.
* **Nivel predominante**: Senior (SE), asociado a procesos críticos.
* **Correlaciones débiles**: Las variables numéricas muestran baja correlación, destacando la importancia de variables categóricas.
* **Limitación**: Falta de datos horarios impide analizar la carga de trabajo por hora.

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas:

1. Abre un *issue* para reportar problemas o sugerencias.
2. Envía un *pull request* con tus mejoras.
3. Sigue el estilo PEP8 para Python.

---

## 📜 Licencia

Este proyecto está bajo la licencia MIT. Puedes usar, modificar y distribuir el código, citando al autor original.

---

⭐ **¡Explora el análisis y descubre las tendencias en ciencia de datos!** ⭐

```

---

Si quieres, también puedo ayudarte a crear la **tabla en Markdown para la descripción de columnas** o generar un índice navegable para Google Colab con enlaces internos. ¿Te gustaría eso?
```

