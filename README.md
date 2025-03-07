# Clasificador de Basuras - EcoBot IA

Este proyecto implementa un modelo de inteligencia artificial para clasificar distintos tipos de residuos y proporcionar recomendaciones sobre cómo desecharlos adecuadamente.

## Características
- Clasificación de residuos mediante un modelo de aprendizaje profundo.
- Interfaz basada en Google Colab para facilitar su uso.
- Procesamiento automático de imágenes.
- Instrucciones sobre el manejo adecuado de los residuos.

## Requisitos
Para ejecutar este proyecto en Google Colab, es necesario contar con los siguientes paquetes:
- Python 3
- Pillow (v9.1.0)
- Keras (v2.12.0)
- TensorFlow (v2.12.0)
- OpenCV

## Uso
### 1. Acceder al proyecto en Google Colab
Haz clic en el siguiente enlace para abrir el proyecto en Google Colab:
[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cdavidbm/Kodland-PyPro-6.4---IA_Para_EcoBot/blob/main/M6L4_Proyecto_clasificador_de_Basuras_EcoBot_IA.ipynb)

### 2. Descargar el Dataset (opcional)
Puedes mejorar el modelo utilizando este conjunto de datos inicial:
[Descargar Dataset](https://drive.google.com/drive/folders/15hOgrRNDlvNg9APX_PG-4LB4H7MgDBBF)

### 3. Configuración inicial
Sigue estos pasos en Colab:
1. Ejecuta el bloque de código para verificar la versión de Python.
2. Instala las bibliotecas necesarias ejecutando el bloque correspondiente.
3. Ejecuta el bloque de código para cargar los recursos del proyecto.

### 4. Cargar y analizar una imagen
1. Sube una imagen de un residuo.
2. Ejecuta el bloque de código para analizar la imagen.
3. El modelo clasificará el residuo y mostrará un procedimiento recomendado para su disposición adecuada.

## Funcionamiento del modelo
El modelo carga una imagen y la procesa de la siguiente manera:
- Ajusta el tamaño de la imagen a 224x224 píxeles.
- Normaliza los valores de los píxeles.
- Predice la clase del residuo utilizando un modelo preentrenado en Keras.
- Devuelve la categoría del residuo y su nivel de confianza.
- Proporciona instrucciones para su correcta disposición.

## Contacto
Para cualquier consulta o mejora en el modelo, puedes contribuir al repositorio o ponerte en contacto con los desarrolladores.


