# Selección de una región petrolera para OilyGiant

Proyecto del Sprint 12 de TripleTen. Utiliza regresión lineal para estimar reservas de petróleo en tres regiones y bootstrap para comparar la ganancia y el riesgo de pérdidas al seleccionar 200 pozos entre 500 candidatos.

## Contenido

- `proyecto_oilygiant.ipynb`: análisis, código, resultados y conclusiones.
- Archivos CSV: datos utilizados en el proyecto educativo de TripleTen.
- `requirements.txt`: versiones del entorno utilizado para la verificación local.

## Cómo ejecutarlo

Requiere Python 3.13, la versión utilizada en la verificación local.
Desde la carpeta raíz del repositorio:

```powershell
py -3.13 -m venv .venv
.venv\Scripts\python.exe -m pip install -r requirements.txt
.venv\Scripts\python.exe -m jupyter notebook proyecto_oilygiant.ipynb
```

Ejecuta todas las celdas en orden. Mantén los archivos de datos en sus rutas originales.
En Zuber, el notebook se ejecuta desde la carpeta `notebooks/` y consulta los CSV de `datos/`.

## Resultados verificados

Ejecutado completo desde cero el 6 de octubre de 2026 con Python 3.13.
La región 1 obtuvo una ganancia promedio simulada de 4.560 millones de USD y un riesgo de pérdidas de 1.5 %.
Es la única región que cumple el límite de riesgo inferior al 2.5 %.

## Autor

Anderson Muñoz — Chef Ejecutivo en transición a Ciencia de Datos.
[GitHub](https://github.com/aokas0)
