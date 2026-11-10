# Análisis del mercado global de videojuegos (Ice)

## Descripción del proyecto

Proyecto de análisis exploratorio y estadístico de datos históricos de la industria de los videojuegos. El objetivo es identificar patrones de ventas, tendencias de mercado y preferencias de los consumidores para formular recomendaciones comerciales orientadas a la campaña publicitaria de 2017.

El análisis utiliza información de videojuegos lanzados hasta 2016 y se enfoca especialmente en el período 2014-2016 para identificar las tendencias más relevantes del mercado reciente.

## Objetivos

- Explorar y preparar los datos históricos de ventas de videojuegos.
- Identificar las plataformas con mayor volumen de ventas y analizar sus ciclos de vida.
- Evaluar la relación entre las calificaciones de usuarios y críticos y las ventas.
- Comparar el desempeño comercial de los distintos géneros.
- Identificar diferencias en las preferencias de los consumidores de Norteamérica, Europa y Japón.
- Realizar pruebas de hipótesis para evaluar diferencias en las calificaciones promedio de usuarios.
- Formular recomendaciones para la planificación comercial de 2017.

## Dataset

Archivo utilizado: `games.csv`

El conjunto de datos contiene información sobre:

- Nombre del videojuego.
- Plataforma.
- Año de lanzamiento.
- Género.
- Ventas en Norteamérica, Europa, Japón y otras regiones.
- Calificaciones de críticos.
- Calificaciones de usuarios.
- Clasificación ESRB.

Se calcula una variable adicional, `total_sales`, que representa las ventas globales por videojuego, expresadas en millones de unidades.

## Herramientas y tecnologías

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

## Estructura del proyecto

```text
5 Proyecto Integrado/
│
├── Datasets/
│   └── games.csv
│
├── Notebook/
│   └── 5 Proyecto Integrado de Análisis del mercado global de videojuegos Ice).ipynb
│
├── .gitignore
└── README.md
```

## Etapas del análisis

1. **Exploración de datos:** inspección inicial del dataset, dimensiones, tipos de datos y valores ausentes.
2. **Preparación de datos:** estandarización de columnas, conversión de tipos de datos y cálculo de ventas globales.
3. **Análisis exploratorio:** tendencias históricas, evolución de plataformas, distribución de ventas, reseñas y géneros.
4. **Análisis regional:** comparación de plataformas, géneros y clasificaciones ESRB en Norteamérica, Europa y Japón.
5. **Pruebas de hipótesis:** comparación de las calificaciones promedio de Xbox One y PC, así como de los géneros Action y Sports.
6. **Conclusiones y recomendaciones:** identificación de oportunidades comerciales para la planificación de 2017.

## Principales hallazgos

- PS4 y Xbox One destacan entre las plataformas con mayores ventas durante el período reciente, mientras que Nintendo 3DS mantiene una presencia importante, especialmente en Japón.
- Action registra el mayor volumen total de ventas, mientras que Shooter presenta la mediana de ventas más alta por videojuego.
- Las reseñas de críticos muestran una correlación positiva moderada con las ventas de PS4, mientras que las calificaciones de usuarios presentan una correlación prácticamente nula.
- Norteamérica y Europa muestran preferencias relativamente similares, mientras que Japón presenta diferencias importantes en plataformas y géneros.
- Las pruebas estadísticas no encontraron evidencia suficiente de una diferencia significativa entre las calificaciones de Xbox One y PC, pero sí identificaron una diferencia significativa entre Action y Sports.

## Cómo ejecutar el proyecto

1. Clonar o descargar este repositorio.
2. Abrir la carpeta del proyecto en Visual Studio Code.
3. Instalar las bibliotecas necesarias:

```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

4. Abrir el notebook ubicado en la carpeta `Notebook/`.
5. Ejecutar las celdas en orden.

El notebook localiza automáticamente `games.csv` dentro de la estructura de carpetas del proyecto, por lo que no es necesario configurar una ruta absoluta.

## Conclusión

El análisis permite identificar patrones relevantes en el mercado global de videojuegos y demuestra la importancia de considerar las particularidades regionales, las plataformas y los géneros al formular estrategias comerciales. Los resultados proporcionan una referencia basada en datos históricos para orientar las decisiones de marketing y planificación de cara a 2017.