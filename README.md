# Configuración de Entorno para Generar Imágenes con Ollama

Este documento detalla los pasos necesarios para configurar un entorno de trabajo para la generación de imágenes usando Ollama, Python y Visual Studio Code (VSC).

## Herramientas Necesarias

1. **Ollama**: [ollama.com](https://ollama.com)
2. **Python 3**: [python.org](https://www.python.org)
3. **Visual Studio Code (VSC)**: [code.visualstudio.com](https://code.visualstudio.com)
4. **Terminal**: Utiliza la terminal de tu sistema operativo.
5. **Música que te gusta**: Para crear un ambiente agradable mientras trabajas (opcional).

## Paso a Paso

### 1. Crear un Entorno Virtual

1. **Abre la Terminal**:
   - **Windows**: CMD, PowerShell, o Terminal de Windows.
   - **macOS**: Aplicación "Terminal".

2. **Navega al Directorio de tu Proyecto**:
   ```bash
   cd ruta/a/tu/proyecto
Crea el Entorno Virtual:

bash
Copy code
python3 -m venv mi_entorno
Activa el Entorno Virtual:

Windows:
bash
Copy code
mi_entorno\Scripts\activate
macOS:
bash
Copy code
source mi_entorno/bin/activate
2. Abrir Visual Studio Code desde la Terminal
Asegúrate de que estás en el directorio de tu proyecto.
Ejecuta el siguiente comando para abrir VSC:
bash
Copy code
code .
3. Crear un Archivo script.py
En VSC:
Dentro de VSC, crea un nuevo archivo llamado script.py.
Por ahora, déjalo vacío o añade un comentario inicial:
python
Copy code
# Este es mi script para generar imágenes con Ollama
