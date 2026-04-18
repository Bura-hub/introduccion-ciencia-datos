# Introduccion a la Ciencia de Datos

Repositorio de talleres y soluciones del curso **Introduccion a la Ciencia de Datos**
(Maestria en Ingenieria Electronica - Universidad de Narino).

Este repositorio contiene:
- Talleres 1 a 5 (base + solucion).
- Semana 06 (retos sobre S&P 500, base + solucion).
- Semana 07 (Modelos ARMA y Filtro de Wiener, base + solucion).

## Contenido actual

| Carpeta | Tema principal | Notebook base | Notebook solucion |
|---|---|---|---|
| `Taller_1` | Python y Pandas | `icd_taller1_python_pandas.ipynb` | `Solucion_icd_taller1_Brayan_Lopez.ipynb` |
| `Taller_2` | Variables aleatorias discretas y Monte Carlo | `icd_taller2_variables_aleatorias.ipynb` | `Solucion_taller2_variables_aleatorias.ipynb` |
| `Taller_3` | Variables aleatorias continuas y analisis de retornos | `icd_taller3_va_continuas.ipynb` | `Solucion_taller3_va_continuas.ipynb` |
| `Taller_4` | Estimacion y ajuste de distribuciones | `icd_taller4_estimacion_distribuciones.ipynb` | `Solucion_taller4_estimacion_distribuciones.ipynb` |
| `Taller_5` | Limpieza de datos con Pandas | `icd_taller5_limpieza_datos.ipynb` | `Solucion_taller5_limpieza_datos.ipynb` |
| `Semana 06 - Retos S&P500` | Retos aplicados al indice S&P 500 | `Ciencia de Datos - Semana 06 - Retos S&P500.ipynb` | `BRAYAN_LOPEZ_Ciencia de Datos - Semana 06 - Retos S&P500.ipynb` |
| `Semana 07 - Arma & Filtro Wiener` | Modelado ARMA y prediccion con Filtro de Wiener | `Ciencia_de_Datos_Semana_7_Modelos_ARMA.ipynb` y `Ciencia_de_Datos_Semana_07_Filtro_de_Wiener.ipynb` | `BRAYAN_LOPEZ_Ciencia_de_Datos_Semana_7_Modelos_ARMA.ipynb` y `BRAYAN_LOPEZ_Ciencia_de_Datos_Semana_07_Filtro_de_Wiener.ipynb` |

## Estado de Semana 07

Los notebooks de solucion de Semana 07 se encuentran actualizados y consistentes:
- `BRAYAN_LOPEZ_Ciencia_de_Datos_Semana_7_Modelos_ARMA.ipynb`
- `BRAYAN_LOPEZ_Ciencia_de_Datos_Semana_07_Filtro_de_Wiener.ipynb`

## Estructura del repositorio

```text
introduccion-ciencia-datos/
|-- Taller_1/
|-- Taller_2/
|-- Taller_3/
|-- Taller_4/
|-- Taller_5/
|-- Semana 06 - Retos S&P500/
|-- Semana 07 - Arma & Filtro Wiener/
|-- env_icd/
|-- requirements.txt
`-- README.md
```

## Requisitos

- Python 3.10+ (recomendado)
- Jupyter Notebook o JupyterLab
- Opcional: Google Colab

## Instalacion de dependencias

Instalacion recomendada desde archivo de requisitos:

```bash
pip install -r requirements.txt
```

Dependencias principales declaradas:
- `matplotlib`
- `numpy`
- `pandas`
- `scipy`
- `seaborn`
- `statsmodels`
- `yfinance`

## Uso

1. Clona o descarga este repositorio.
2. Abre la carpeta del taller o semana que quieras trabajar.
3. Ejecuta primero el notebook base/enunciado.
4. Usa el notebook de solucion para comparar resultados.

## Notas

- Algunos notebooks descargan datos de internet (por ejemplo, con `yfinance`), por lo que requieren conexion.
- Se recomienda ejecutar las celdas en orden.

## Autor

**Brayan Lopez**  
Maestria en Ingenieria Electronica - Universidad de Narino

---

Material con fines educativos.
