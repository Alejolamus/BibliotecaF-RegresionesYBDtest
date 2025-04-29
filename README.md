# BibliotecaF-RegresionesYBDtest

**Librería en F# para estimadores de regresión lineal y análisis de datos de ventas**

Este proyecto contiene una colección de funciones matemáticas desarrolladas en **F#** para calcular una regresión lineal (MAE, RMSE, R¨2)y realizar pruebas sobre conjuntos de datos de ventas simulados o reales. Es parte de un sistema más amplio que conecta modelos matemáticos con bases de datos y análisis predictivo.

# Estructura del Proyecto
# Funcionalidades implementadas

- Cálculo Regresion por medio de Arrays de types{producto, fecha y cantidad}
- ecuacion, pendiente y eje Y
- Cálculo de métricas:
  - MAE (Error absoluto medio)
  - RMSE (Raíz del error cuadrático medio)
  - R² (Coeficiente de determinación)
- Estructuras de datos para almacenar y procesar resultados

# Datos de prueba

El sistema permite el uso de registros simulados (por ejemplo, ventas por día) para probar los estimadores sin necesidad de conectarse aún a una base de datos real. (no incluye datos de comparativos de precciones, dado que estos requieren cargar datos de ventas anterior y seran datos que se llenen en automatico para unicamente ser consutlados desde la BD"Esto lo desarrolla la app de consola C# para la cual se diseño la Biblioteca f#"
