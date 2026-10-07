# Proyecto: Análisis de Pingüinos

Este proyecto contiene la configuración inicial del entorno de trabajo para el análisis de datos de pingüinos.

## Configuración del Entorno de Desarrollo

Sigue estos pasos para replicar el entorno de trabajo:

### 1. Crear el entorno virtual
Abre una terminal dentro de la carpeta `analisis_pinguinos` y ejecuta:

```bash
python -m venv .venv
```

### 2. Activar el entorno virtual

* **En Windows (PowerShell):**
  ```powershell
  .venv\Scripts\Activate.ps1
  ```
* **En Windows (CMD):**
  ```cmd
  .venv\Scripts\activate.bat
  ```
* **En Linux / macOS:**
  ```bash
  source .venv/bin/activate
  ```

### 3. Instalar las dependencias
Con el entorno virtual activado, instala las librerías necesarias ejecutando:

```bash
pip install -r requirements.txt
```
