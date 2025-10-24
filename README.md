# SISTEMA DE RUC.


Una aplicacion web de Django en subes un archivo txt, lo lee y lo ordena usando algoritmos de ordenamiento, tiene a su disposicion tambien un reporte PDF.



## ✨ Caracteristicas Principales

Este proyecto demuestra el uso de Django funciones de negocio: 1. CRUD de Clientes. 2. Almacenamiento de Coordenadas (Lat/Lon). 3. Visualizacion de Mapa Interactivo. 4. Enlace Directo a Google Maps.

* **Carga Segura de Archivos:** Permite la subida de archivos de texto delimitados (CSV, TXT).
* **Procesamiento Inteligente:** Utiliza la librería Pandas para leer archivos con delimitadores variables (| o tabulador \t), limpiar datos (dropna) y cargarlos a la base de datos.
* **Implementación Algorítmica:** Muestra la implementación de algoritmos de ordenamiento como TimSort y Quicksort sobre los datos cargados.
* **Generación de Reportes PDF:** Crea reportes dinámicos y formateados en PDF utilizando la librería ReportLab, listos para descargar.
* **Historial de Cargas:** Mantiene un registro de los archivos subidos (nombre y número de registros).



## 🛠️ Tecnologías Utilizadas

* **Lenguaje:** Python 3.12.3
* **Framework Web:** **Django**



---

## 🚀 Instalación y Puesta en Marcha

Sigue estos pasos para configurar y ejecutar el servidor de desarrollo de Django en tu máquina local.

### 1. Clonar el Repositorio

```bash
git clone <URL de tu repositorio en GitHub>
cd weather_project




# Crear el entorno virtual
python3 -m venv env

# Activar el entorno virtual
# En Linux/macOS:
source env/bin/activate
# En Windows (CMD):
# .\env\Scripts\activate
