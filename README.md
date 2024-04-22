# Proyecto Distribución de Sobrantes 🚗⚽️✈️

Este proyecto proporciona un conjunto de scripts en Python para gestionar la distribución de sobrantes de inventario en tiendas. Utiliza datos de inventario, despachos, ventas y consultas SQL para calcular y asignar la distribución óptima de los sobrantes a las diferentes ubicaciones.

## Archivos y Funcionalidades

### distribucion_sobrantes.py

Este archivo contiene el código principal del proyecto. Aquí se realizan las siguientes operaciones:

1. 📊 Lectura de archivos Excel que contienen datos de inventario, despachos, ventas, y consultas SQL.
2. 📋 Organización de tablas de datos para su procesamiento.
3. 🔀 Fusionado de tablas y cálculo de métricas relevantes.
4. 🔄 Generación de una matriz de rotación para determinar la asignación óptima de sobrantes a las tiendas.
5. 🎯 Asignación de destinos basados en criterios como rotación y disponibilidad en otras ubicaciones.
6. 💾 Exportación de los resultados finales a un nuevo archivo Excel.

### Funcionalidades Adicionales

- **Lector de Rutas:** Esta sección lee las rutas de archivos necesarios para la ejecución del script.
- **Organizar Tablas:** Funciones para ordenar y estructurar las tablas de datos de manera consistente.
- **Matriz:** Generación de una matriz de rotación para evaluar las ventas y asignar sobrantes de manera óptima.

## Dependencias

Este proyecto requiere las siguientes bibliotecas de Python:

- pandas
- numpy
- xlsxwriter
- tqdm

Además, se utiliza un módulo personalizado `consultas_sql` para acceder a los datos de la base de datos.

## Uso

Para ejecutar el script `distribucion_sobrantes.py`, asegúrate de tener los archivos de datos necesarios en las rutas especificadas y todas las dependencias instaladas. Luego, simplemente ejecuta el script y sigue las instrucciones que proporciona.

## Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar este proyecto, por favor, crea una solicitud de extracción con tus sugerencias.

## ✍️ Autor ✍️

Este proyecto fue desarrollado por [David Gonzalez](https://github.com/DeiviGT1).
