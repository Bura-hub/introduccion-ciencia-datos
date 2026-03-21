# Introduccion a la Ciencia de Datos

Repositorio de talleres y soluciones del curso **Introduccion a la Ciencia de Datos** (Maestria en Ingenieria Electronica - Universidad de Narino).

El material esta organizado por modulos (`Taller_1` a `Taller_5`) y cada taller incluye:
- notebook base/enunciado (`icd_...`)
- notebook de solucion (`Solucion_...`)

## Contenido del curso

| Taller | Tema principal | Notebooks |
|---|---|---|
| `Taller_1` | Primeros pasos con Python y Pandas | `icd_taller1_python_pandas.ipynb`, `Solucion_icd_taller1_Brayan_Lopez.ipynb` |
| `Taller_2` | Variables aleatorias discretas y simulacion Monte Carlo | `icd_taller2_variables_aleatorias.ipynb`, `Solucion_taller2_variables_aleatorias.ipynb` |
| `Taller_3` | Variables aleatorias continuas, metodo de la inversa, analisis de retornos (S&P 500) | `icd_taller3_va_continuas.ipynb`, `Solucion_taller3_va_continuas.ipynb` |
| `Taller_4` | Estimacion y ajuste de distribuciones (exponencial, beta, log-normal, metricas y pruebas) | `icd_taller4_estimacion_distribuciones.ipynb`, `Solucion_taller4_estimacion_distribuciones.ipynb` |
| `Taller_5` | Limpieza de datos con Pandas (duplicados, nulos, outliers y buenas practicas) | `icd_taller5_limpieza_datos.ipynb`, `Solucion_taller5_limpieza_datos.ipynb` |

## Estructura del repositorio

```text
introduccion-ciencia-datos/
|-- Taller_1/
|-- Taller_2/
|-- Taller_3/
|-- Taller_4/
|-- Taller_5/
|-- env_icd/
`-- README.md
```

## Requisitos

- Python 3.10+ (recomendado)
- Jupyter Notebook o JupyterLab
- Opcional: Google Colab

## Dependencias

Librerias usadas a lo largo de los talleres:
- `numpy`
- `pandas`
- `matplotlib`
- `scipy`
- `seaborn`
- `yfinance`

Instalacion sugerida:

```bash
pip install numpy pandas matplotlib scipy seaborn yfinance jupyter
```

Si ya tienes el entorno `env_icd`, puedes activarlo y trabajar desde ahi.

## Uso

1. Clona o descarga este repositorio.
2. Abre el taller que quieras trabajar (`Taller_1` ... `Taller_5`).
3. Ejecuta primero el notebook `icd_...` (enunciado/base).
4. Usa el notebook `Solucion_...` para comparar o validar resultados.

## Notas importantes

- Algunos talleres descargan datos de internet (por ejemplo, `yfinance` y datasets publicos), asi que requieren conexion.
- Los notebooks estan pensados para aprendizaje practico y ejecucion secuencial de celdas.

## Autor

**Brayan Lopez**  
Maestria en Ingenieria Electronica - Universidad de Narino

---

Material con fines educativos.
