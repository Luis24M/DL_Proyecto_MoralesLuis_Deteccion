# Detección de Pólipos en Colonoscopia con YOLOv8

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Luis24M/DL_Proyecto_MoralesLuis_Deteccion/blob/main/Deteccion_polipos.ipynb)

## Ruta elegida y Dataset
- **Ruta:** Detección de objetos (pólipos en imágenes de colonoscopia).
- **Dataset:** [Kvasir-SEG](https://universe.roboflow.com/lettuce-test/kvasir-seg-d0wwf)  
  - **Fuente:** Roboflow Universe  
  - **Licencia:** CC BY 4.0
  - 
- **Acceso:** Para utilizar el dataset, crea una API Key en [Roboflow](https://roboflow.com), la api key seteada esta revocada, se dejo como ejemplo.

## Estructura de Carpetas que genera
- **proyecto_dl/**
    - **datasets/**: Dataset descargado
        - **kvasir-seg/**
    - **models/**: Modelos entrenados (best.pt)
    - **checkpoints/**: Checkpoints de entrenamiento
    - **runs/**: Ejecuciones de YOLO, pesos, graficos de los entrenamientos e imagenes de prueba
    - **results/**: Tablas, gráficos y resumen
    - **proyecto_deteccion.py**

## Cómo ejecutar
1. Clonar el repositorio o abrir el notebook en Google Colab / Jupyter.  
2. Seleccionar **entorno GPU** (ej. Tesla T4 en Colab).  

## Entrenamiento y Evaluación
1. Descargar el dataset desde Roboflow con tu **API Key (mantener privada)**.  
2. Entrenar el modelo YOLOv8 con

## Resultados de la sesión
[Drive](https://drive.google.com/file/d/1cdAOIls0vLnhI_KK4iQ6zp1qaJ4hx6IV/view?usp=sharing)
