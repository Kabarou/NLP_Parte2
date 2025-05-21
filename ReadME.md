# Trabajo Práctico: Procesamiento de Lenguaje Natural (NLP)

Este proyecto implementa diferentes técnicas de procesamiento de lenguaje natural (NLP) aplicadas sobre textos extensos. Se exploraron modelos de embeddings semánticos para fragmentación y vectorización, análisis de similitud textual, técnicas de POS tagging (extracción de sustantivos) y NER (reconocimiento de entidades nombradas), clasificación de idioma, análisis de sentimientos y clasificación de consultas usando regresión logística.

## 📌 Descripción de los ejercicios

- Fragmentación de textos y vectorización usando modelos de embeddings semánticos.
- Comparación de métricas de distancia para búsquedas semánticas.
- Extracción de sustantivos y entidades nombradas con técnicas de POS tagging y NER.
- Clasificación de idioma y organización de textos en un dataframe.
- Análisis de sentimientos con modelo pre-entrenado, integrado a un sistema de recuperación de información.
- Clasificación de consultas por tipo de información mediante regresión logística.

## 🐍 Requisitos

- **Python 3.11 o superior** (recomendado)
- Las dependencias están listadas en `requirements.txt`.

## 🔧 Instalación

1. Cloná el repositorio:

   ```bash
   git clone https://github.com/usuario/repositorio.git
   cd repositorio

2. (Opcional pero recomendado) Crea un entorno virtual
python -m venv venv
source venv/bin/activate        # En Linux/macOS
.\venv\Scripts\activate         # En Windows

3. Instala las dependencias
pip install -r requirements.txt

### Archivos importantes
main.ipynb o el script principal del proyecto.

Informe TP 2 NLP Franco Caballero.pdf: Documento explicativo del trabajo práctico.

requirements.txt: Lista completa de librerías usadas.