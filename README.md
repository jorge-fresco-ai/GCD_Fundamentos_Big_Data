# Fundamentos de Big Data

Repositorio docente dedicado a introducir los principales conceptos, tecnologías y patrones de trabajo relacionados con **Big Data**, procesamiento distribuido y análisis de grandes volúmenes de datos.

El objetivo es disponer de un espacio común para materiales, ejemplos prácticos, ejercicios y código utilizado durante la asignatura.

## Objetivos

A lo largo del repositorio se trabajarán conceptos relacionados con:

* Fundamentos y características de los sistemas Big Data.
* Procesamiento de grandes volúmenes de información.
* Almacenamiento distribuido.
* Procesamiento batch y distribuido.
* Preparación y transformación de datos.
* Análisis de datos mediante Python.
* Uso de herramientas habituales dentro del ecosistema Big Data.
* Diseño de pipelines de procesamiento de datos.
* Buenas prácticas para trabajar con datasets de gran tamaño.

El enfoque combina los conceptos teóricos con ejemplos prácticos que permitan entender cómo se aplican estas técnicas sobre datos reales.

## Estructura del repositorio

La estructura del proyecto irá organizándose por temas y actividades. Una posible organización es:

```text
fundamentos_big_data/
│
├── notebooks/          # Notebooks con ejemplos y ejercicios
├── datasets/           # Datos utilizados en las prácticas
├── src/                # Código Python reutilizable
├── exercises/          # Actividades propuestas
├── docs/               # Material complementario
│
├── requirements.txt    # Dependencias del proyecto
└── README.md
```

La estructura puede evolucionar a medida que se incorporen nuevos contenidos.

## Entorno de trabajo

Se recomienda utilizar:

* Python 3.10 o superior
* Jupyter Notebook o JupyterLab
* Visual Studio Code
* Git
* Un entorno virtual de Python

Para clonar el repositorio:

```bash
git clone https://github.com/jorge-fresco-ai/fundamentos_big_data.git
cd fundamentos_big_data
```

Es recomendable crear un entorno virtual antes de instalar las dependencias:

```bash
python -m venv .venv
```

Activación en Linux o macOS:

```bash
source .venv/bin/activate
```

En Windows:

```bash
.venv\Scripts\activate
```

Cuando el repositorio incluya un fichero `requirements.txt`, las dependencias podrán instalarse mediante:

```bash
pip install -r requirements.txt
```

## Uso de los notebooks

Los notebooks pueden ejecutarse desde Jupyter:

```bash
jupyter lab
```

o directamente desde Visual Studio Code utilizando la extensión de Jupyter.

Se recomienda revisar cada notebook en orden y ejecutar las celdas de forma secuencial, prestando atención tanto al código como a los comentarios y resultados obtenidos.

## Trabajo con datos

Los datasets utilizados en los ejercicios pueden almacenarse dentro de `datasets/` o descargarse desde las fuentes indicadas en cada actividad.

Cuando se utilicen datasets grandes, estos podrán quedar excluidos del repositorio mediante `.gitignore` o gestionarse mediante mecanismos específicos para ficheros de gran tamaño.

En esos casos, el propio ejercicio indicará cómo obtener los datos necesarios.

## Metodología

Los ejercicios están planteados para trabajar de forma práctica sobre problemas relacionados con ingeniería y análisis de datos.

En general, el flujo de trabajo será:

```text
Datos
  ↓
Carga
  ↓
Exploración
  ↓
Limpieza
  ↓
Transformación
  ↓
Procesamiento
  ↓
Análisis
  ↓
Resultados
```

Además de obtener un resultado correcto, se valorará que el código sea legible, reproducible y esté razonablemente estructurado.

## Recomendaciones

Antes de comenzar una actividad:

1. Lee el enunciado completo.
2. Revisa las características del dataset.
3. Comprueba los tipos de datos y los valores ausentes.
4. Evita realizar transformaciones sin entender primero su efecto.
5. Documenta las decisiones relevantes dentro del notebook.
6. Comprueba que el código puede ejecutarse desde el principio hasta el final.

Cuando trabajemos con volúmenes grandes de información, también será importante analizar el coste computacional de las operaciones y evitar cargar o procesar datos innecesariamente.

## Git y control de versiones

Para descargar los últimos cambios:

```bash
git pull
```

Para trabajar sobre una copia propia del repositorio puede utilizarse un *fork* o una rama independiente.

Ejemplo:

```bash
git checkout -b mi-rama
```

Después de realizar cambios:

```bash
git add .
git commit -m "Añade ejercicio de procesamiento de datos"
git push
```

## Autor

**Jorge Fresco**

Data Scientist | Machine Learning | Deep Learning | Artificial Intelligence

GitHub: [@jorge-fresco-ai](https://github.com/jorge-fresco-ai)

---

Este repositorio tiene finalidad educativa.

