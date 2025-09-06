# Blackbox

Blackbox es una herramienta para el análisis y descubrimiento de productos con potencial de rentabilidad en Amazon. Permite filtrar grandes volúmenes de datos para identificar nichos de mercado y productos que cumplen criterios específicos.

## Características principales
- Filtrado avanzado de productos por múltiples criterios (categoría, ventas, reviews, precio, etc.)
- Visualización interactiva de resultados con Plotly
- Análisis de datos a partir de archivos CSV exportados de Amazon
- Código reproducible en Jupyter Notebook

## Requisitos
- Python 3.8+
- pandas
- plotly
- ipywidgets (opcional, para interactividad avanzada)

Puedes instalar los requisitos ejecutando:
```bash
pip install -r requirements.txt
```

## Uso rápido
1. Coloca tu archivo `BLACKBOX.csv` en la raíz del proyecto.
2. Abre y ejecuta el notebook `blackbox.ipynb`.
3. Ajusta los filtros en el código según tus necesidades.
4. Visualiza los resultados y gráficas generadas.

## Visualizaciones
El notebook genera gráficas interactivas para analizar la relación entre ventas, reviews y otros atributos de los productos.

## Notas
- Si instalas nuevos paquetes desde el notebook, recuerda reiniciar el kernel para que los cambios tengan efecto.
- La funcionalidad de abrir links desde la gráfica puede requerir soporte para widgets y Javascript en tu entorno Jupyter.

## Autor
- wilmansirit
