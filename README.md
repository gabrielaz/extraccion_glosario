# **Extracción de Términos para Glosarios en Especificaciones de Requisitos**

Este repositorio contiene todos los módulos y el código necesarios para la **extracción inicial de términos clave** destinados a la creación de glosarios que faciliten la generación automática de documentación para especificaciones de requisitos. El proyecto utiliza técnicas de **procesamiento de lenguaje natural (NLP)** y **algoritmos de clustering** para automatizar la identificación y organización de conceptos relevantes.

---

## **Descripción del Proyecto**

El objetivo principal de este proyecto es mejorar la precisión y eficiencia en la elaboración de glosarios técnicos mediante:
- Identificación de términos clave a partir de documentos de requisitos.
- Agrupamiento semántico de términos relacionados.
  

Esta metodología aborda desafíos como la diversidad lingüística en los documentos y la necesidad de una organización coherente y automatizada de términos técnicos.

---

## **Estructura del Repositorio**

El repositorio está organizado en módulos que cubren todo el pipeline de procesamiento:

1. **Preprocesamiento de Texto**
   - Limpieza, tokenización y lematización del texto.
   - Identificación de términos candidatos usando herramientas como **spaCy**.

2. **Extracción de Términos Candidatos**
   - Basada en reglas gramaticales (por ejemplo, frases nominales).
   - Filtrado de términos irrelevantes mediante listas de stopwords específicas.

3. **Representación Vectorial**
   - Uso de modelos de embeddings como **FastText** o **Word2Vec** para representar términos en un espacio semántico.

4. **Clustering Semántico**
   - Agrupamiento mediante **K-Means**, **EM**, o **Clusterización Jerárquica**.
---

## **Instalación y Uso**

### **1. Clonar el Repositorio**
Clona este repositorio en tu máquina local:
```bash
git clone <URL_DEL_REPOSITORIO>
pip install -r requirements.txt
