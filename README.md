# Taller 2 - Análisis y Predicción de Precios de Apartamentos

**Autores:**
- Santiago Martínez Novoa - 202112020
- David Alejandro Fuquen Florez - 202021113

---

## Estructura del Proyecto

```
Uniandes-Ciencia-Datos-Taller2/
│
├── data/
│   ├── apartamentos.csv
│   └── Diccionario de datos - apartamentos (1).html
│
├── docs/
│   ├── despliegue.png
│   └── Informe_ejecutivo.pdf
│
├── .gitignore
├── README.md
├── requirements.txt
└── taller_2.ipynb
```

## Instrucciones de Instalación y Ejecución

### Prerrequisitos
- Python 3.8 o superior
- pip (gestor de paquetes de Python)

### Paso 1: Clonar el repositorio

```bash
git clone https://github.com/SantiagoM99/Uniandes-Ciencia-Datos-Taller2.git
cd Uniandes-Ciencia-Datos-Taller2
```

### Paso 2: Crear y activar el entorno virtual

**En Windows (PowerShell):**
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

**En Windows (CMD):**
```cmd
python -m venv .venv
.venv\Scripts\activate.bat
```

**En macOS/Linux:**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### Paso 3: Instalar las dependencias

```bash
pip install -r requirements.txt
```

### Paso 4: Ejecutar el notebook

```bash
jupyter notebook taller_2.ipynb
```

O si prefieres usar JupyterLab:

```bash
jupyter lab taller_2.ipynb
```


## Descripción del Proyecto

Este proyecto implementa un análisis completo de datos y modelos de machine learning para la predicción de precios de apartamentos. Incluye:

- Exploración y limpieza de datos
- Ingeniería de características
- Entrenamiento de múltiples modelos de regresión
- Análisis de interpretabilidad con SHAP y LIME
- Evaluación de desempeño y generación de insights

## Notas

- El entorno virtual (`.venv`) no está incluido en el repositorio
- Asegúrate de tener todas las dependencias instaladas antes de ejecutar el notebook
- El dataset se encuentra en la carpeta `data/`
- Los resultados y análisis se encuentran documentados en el notebook `taller_2.ipynb`
- El informe ejecutivo (respuesta al punto 6) se encuentra en `docs/Informe_ejecutivo.pdf`


