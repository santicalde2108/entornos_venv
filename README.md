# Trabajos Prácticos - Python (Semana 11)

**Estudiante:** Santiago Calderón  
**Asignatura:** Nuevas Tecnologías  

---

## Contenido del Repositorio

Este repositorio contiene los dos ejercicios prácticos desarrollados para la semana 11:

### 1. Entornos Virtuales (`semana_11/analisis_pinguinos/`)
Configuración de un entorno de trabajo reproducible para análisis de datos con Python:
* Creación y activación de entorno virtual `.venv`.
* Dependencias fijadas en `requirements.txt` (`pandas`, `matplotlib`, `seaborn`).
* Script inicial de verificación `analisis.py`.
* Guía de replicación en su respectivo `README.md`.

### 2. Taller Práctico Excel (`semana_11/taller_excel/`)
Lectura y consulta interactiva de datos desde un archivo Excel (`personas.xlsx`):
* Carga de datos con `openpyxl` y visualización profesional con `tabulate`.
* Script principal: `TallerExcel_Python_SantiagoCalderon.py`.
* **Retos implementados:**
  1. Mostrar únicamente Nombre y Correo.
  2. Conteo total de registros.
  3. Filtrar personas cuya empresa contenga "Group".
  4. Búsqueda individual de persona por ID.
  5. Menú interactivo en consola con validaciones.

---

## Ejecución del Taller de Excel

1. Instalar requerimientos:
   ```bash
   pip install openpyxl tabulate
   ```
2. Ejecutar el script:
   ```bash
   python semana_11/taller_excel/TallerExcel_Python_SantiagoCalderon.py
   ```
