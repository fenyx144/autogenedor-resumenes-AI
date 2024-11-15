# Generador de Resúmenes Automáticos con IA

Este proyecto utiliza el modelo preentrenado **BART** de Hugging Face para generar resúmenes automáticos de textos largos. La herramienta toma un texto largo como entrada y devuelve un resumen conciso y coherente.

## 🚀 Cómo usar

 #### 1. Clona el repositorio:

    ```bash
   git clone https://github.com/fenyx144/autogenedor-resumenes-AI.git
   cd autogenedor-resumenes-AI
    ```

#### 2.Instala las dependencias:

    ```bash
    pip install transformers torch
    ```

#### 3.Abre el archivo Jupyter Notebook autogenedor-resumenes-AI.ipynb en tu entorno de Jupyter:
```bash
    jupyter notebook autogenedor-resumenes-AI.ipynb
```

## 🧠 ¿Cómo funciona?
Carga del Modelo: Se carga el modelo preentrenado BART para resúmenes.
Entrada de Texto: Proporcionas un texto largo que deseas resumir.
Generación del Resumen: El modelo procesa el texto y genera un resumen breve.
Resultado: El resumen se imprime en la consola.
## 🤖 ¿Tecnologías usadas?
Transformers (Hugging Face)
Torch (Backend de Machine Learning)
Python (Lenguaje de Programación)
## 📝 Ejemplo de uso

```python

texto_largo = """
    La inteligencia artificial (IA) es un campo de estudio que se ocupa de crear sistemas que imitan la inteligencia humana.
    La IA puede aprender y tomar decisiones por sí misma...
"""

resumen = generar_resumen(texto_largo)
print(resumen)
```
## 🌟 Contribuye
Si deseas contribuir al proyecto, puedes hacerlo haciendo un fork y creando un pull request con nuevas ideas, mejoras o correcciones.