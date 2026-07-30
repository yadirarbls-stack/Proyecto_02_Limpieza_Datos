# 🧹 Proyecto 02 - Limpieza de Datos

## Descripción

Este proyecto forma parte de mi portafolio de Análisis de Datos con Python y se centra en la evaluación y mejora de la calidad de un conjunto de datos abiertos publicos.

A través de técnicas de limpieza de datos se revisó la integridad del dataset, identificando valores faltantes, registros duplicados, consistencia de la información y tipos de datos, con el objetivo de obtener un conjunto de datos confiable para las siguientes etapas del análisis.

---

## Problema

Antes de realizar cualquier análisis de datos, es fundamental asegurar que la información sea consistente, completa y esté correctamente estructurada. El equipo necesita preparar el conjunto de datos para garantizar que los análisis posteriores se realicen sobre información de calidad.

---

## Objetivos

- Evaluar la calidad del conjunto de datos.
- Identificar valores faltantes.
- Detectar registros duplicados.
- Verificar la consistencia de las variables categóricas.
- Corregir los tipos de datos cuando sea necesario.
- Obtener un conjunto de datos limpio y listo para futuros análisis.

---

## Dataset

**Fuente:** Catálogo Nacional de Datos Abiertos de Uruguay .

El Catálogo Nacional de Datos Abiertos permite acceder a datos abiertos de organismos públicos, academia, organizaciones de sociedad civil y empresas privadas. Cualquier persona puede utilizar los datos publicados libremente para contar historias, desarrollar investigaciones, visualizaciones, aplicaciones cívicas y emprendimientos.
https://catalogodatos.gub.uy/

> **Nota:** El dataset no se incluye en este repositorio. Para ejecutar el proyecto deberá descargarse desde el portal oficial de Datos Abiertos de Uruguay y colocarse dentro de la carpeta `datos/`.

---

## Herramientas utilizadas

- Python 3
- Pandas
- Visual Studio Code
- Git
- GitHub

---

## Principales resultados

Durante el proceso de limpieza se obtuvo un conjunto de datos con un alto nivel de calidad.

Se realizaron las siguientes actividades:

- Evaluación de valores faltantes.
- Identificación de registros duplicados.
- Revisión de la consistencia de variables categóricas.
- Conversión de la variable `fechainicioorganismo` al tipo `datetime`.
- Validación final del conjunto de datos.

Como resultado:

- No se encontraron registros duplicados.
- Solo se identificaron dos valores nulos, cuyo impacto es insignificante sobre el total de registros.
- No fue necesario normalizar las variables categóricas.
- El conjunto de datos quedó preparado para las siguientes etapas del proceso analítico.

---

## Estructura del proyecto

```
Proyecto_02_Limpieza_Datos/
│
├── notebooks/
│   └── Proyecto02_Limpieza_Datos.ipynb
│
├── datos/                 # No incluido en el repositorio
├── resultados/            # No incluido en el repositorio
├── imagenes/
├── docs/
├── src/
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

## Cómo ejecutar el proyecto

1. Clonar el repositorio.

```bash
git clone https://github.com/yadirarbls-stack/Proyecto_02_Limpieza_Datos.git
```

2. Crear un entorno virtual.

```bash
python -m venv .venv
```

3. Activar el entorno virtual.

**Windows**

```bash
.venv\Scripts\activate
```

4. Instalar las dependencias.

```bash
pip install -r requirements.txt
```

5. Descargar el dataset desde el portal de Datos Abiertos de Uruguay y colocarlo en la carpeta:

```
datos/
```

6. Abrir el notebook ubicado en:

```
notebooks/Proyecto02_Limpieza_Datos.ipynb
```

y ejecutar las celdas en orden.

---

## Competencias desarrolladas

Durante este proyecto se aplicaron competencias relacionadas con:

- Evaluación de la calidad de los datos.
- Limpieza y preparación de datos.
- Manejo de valores faltantes.
- Detección de registros duplicados.
- Validación de consistencia de datos.
- Conversión de tipos de datos.
- Manipulación de datos con Pandas.
- Documentación de procesos analíticos.
- Uso de Git y GitHub para el control de versiones.

---

## Autor

**Yadira Robles Aranda**

Project Manager | Analista de Datos | Python | SQL | Power BI

GitHub: https://github.com/yadirarbls-stack
