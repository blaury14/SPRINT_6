# Proyecto Integrado 1 (sprint 6): Análisis de Datos de Ventas de Videojuegos

## Descripción del Proyecto

Trabajas para la tienda online Ice, que vende videojuegos por todo el mundo. Las reseñas de usuarios y expertos, los géneros, las plataformas (por ejemplo, Xbox o PlayStation) y los datos históricos sobre las ventas de juegos están disponibles en fuentes abiertas. Tu objetivo es identificar patrones que determinen si un juego tiene éxito o no. Esto te permitirá detectar proyectos prometedores y planificar campañas publicitarias.

## Objetivos del Proyecto

- Identificar patrones que determinen el éxito de un juego.
- Detectar proyectos prometedores para planificar campañas publicitarias.

## Pasos Realizados en el Proyecto

### Paso 1: Abrir el Archivo de Datos y Estudiar la Información General

- Ruta del archivo: `/datasets/games.csv`
- Se cargaron los datos y se realizó una revisión inicial de su contenido y estructura.

### Paso 2: Preparación de los Datos

- Reemplazo de los nombres de las columnas a minúsculas para consistencia.
- Conversión de los datos a los tipos necesarios (por ejemplo, fechas, números).
- Tratamiento de valores ausentes, reemplazo de valores "TBD" (to be determined) y eliminación de valores duplicados.
- Cálculo de las ventas totales sumando las ventas en todas las regiones para cada juego.

### Paso 3: Análisis de los Datos

- Análisis del número de juegos lanzados por año y su relevancia.
- Observación de la variación de las ventas por plataforma.
  - Identificación de plataformas con mayores ventas y análisis de tendencias a lo largo del tiempo.
  - Construcción de diagramas de caja para visualizar la distribución de ventas por plataforma.
- Análisis de la influencia de las reseñas de usuarios y críticos en las ventas de una plataforma popular (ejemplo: Xbox 360).
  - Creación de gráficos de dispersión y cálculo de correlaciones entre reseñas y ventas.
- Estudio de la distribución de juegos por género y determinación de los géneros más rentables.

### Paso 4: Creación de un Perfil de Usuario para Cada Región

- Determinación de las cinco principales plataformas y géneros en cada región (NA, EU, JP).
- Análisis de las diferencias en cuotas de mercado y preferencias de género entre regiones.
- Evaluación del impacto de las clasificaciones ESRB en las ventas regionales.

### Paso 5: Prueba de Hipótesis

- Hipótesis 1: Las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son las mismas.
- Hipótesis 2: Las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son diferentes.
- Formulación de hipótesis nula y alternativa.
- Selección y aplicación del criterio de prueba de hipótesis adecuado.

### Paso 6: Conclusión General

- Resumen de los hallazgos clave del análisis.
- Evaluación de la influencia de las reseñas, las preferencias regionales y las diferencias en las ventas por plataforma y género.
- Sugerencias para futuras campañas publicitarias basadas en los datos analizados.

## Descripción de Datos

- `Name`: Nombre del juego.
- `Platform`: Plataforma (ejemplo: Xbox, PlayStation).
- `Year_of_Release`: Año de lanzamiento.
- `Genre`: Género del juego.
- `NA_sales`: Ventas en Norteamérica (millones de dólares).
- `EU_sales`: Ventas en Europa (millones de dólares).
- `JP_sales`: Ventas en Japón (millones de dólares).
- `Other_sales`: Ventas en otras regiones (millones de dólares).
- `Critic_Score`: Puntuación de los críticos (máximo 100).
- `User_Score`: Puntuación de los usuarios (máximo 10).
- `Rating`: Clasificación ESRB.

Es posible que los datos de 2016 estén incompletos.

## Contribución

Si deseas contribuir a este proyecto, realiza un fork del repositorio y crea una pull request con tus mejoras. Asegúrate de que tu código sigue los lineamientos del proyecto y está bien comentado.

## Licencia

Este proyecto está bajo la licencia MIT. Para más detalles, consulta el archivo LICENSE.
