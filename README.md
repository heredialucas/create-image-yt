
# Generación de Imágenes con Ollama

Este documento detalla los pasos necesarios para configurar un entorno de trabajo para la generación de imágenes usando Ollama, Python y Visual Studio Code (VSC).

## Herramientas Necesarias
- **Ollama**: [ollama.com](https://ollama.com)
- **Python 3**: [python.org](https://www.python.org)
- **Visual Studio Code (VSC)**: [code.visualstudio.com](https://code.visualstudio.com)
- **Terminal**: Utiliza la terminal de tu sistema operativo.
- **Música que te gusta**: Para crear un ambiente agradable mientras trabajas (opcional).

## Paso a Paso

### 1. Crear un Entorno Virtual

1. Abre la Terminal:
   - **Windows**: CMD, PowerShell, o Terminal de Windows.
   - **macOS**: Aplicación "Terminal".

2. Navega al Directorio de tu Proyecto:

   ```bash
   cd ruta/a/tu/proyecto
   ```

3. Crea el Entorno Virtual:

   ```bash
   python3 -m venv mi_entorno
   ```

4. Activa el Entorno Virtual:

   - **Windows**:

     ```bash
     mi_entorno\Scripts\activate
     ```

   - **macOS**:

     ```bash
     source mi_entorno/bin/activate
     ```

### 2. Abrir Visual Studio Code desde la Terminal

1. Asegúrate de que estás en el directorio de tu proyecto.
2. Ejecuta el siguiente comando para abrir VSC:

   ```bash
   code .
   ```

### 3. Crear un Archivo script.py

1. Dentro de VSC, crea un nuevo archivo llamado `script.py`.
2. Por ahora, déjalo vacío o añade un comentario inicial:

   ```python
   # Comentario
   ```
