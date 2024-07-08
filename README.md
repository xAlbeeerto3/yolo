# yolo
![](Imágenes/airbnb_web_euskadi.PNG)
<p align="center">
  <a href="#english">
    <img src="https://raw.githubusercontent.com/lipis/flag-icon-css/master/flags/4x3/gb.svg" alt="English" width="32" height="32">
  </a>
  <a href="#spanish">
    <img src="https://raw.githubusercontent.com/lipis/flag-icon-css/master/flags/4x3/es.svg" alt="Spanish" width="32" height="32">
  </a>
</p>

# English
### Project Description
This project uses the YOLO (You Only Look Once) model for real-time object detection in images captured from a webcam. The implementation is done in Python, using the ultralytics library for the YOLO model and cv2 for image processing and video capture.

### Requirements
Python 3.7+
Python Libraries:
ultralytics
opencv-python
math
### Usage
Ensure you have a webcam connected to your computer.
Run the script:
bash
Copiar código
python object_detection.py
A window will open showing the webcam feed with real-time object detections. To exit the capture loop and close the window, press the q key.
### Code Structure
1. Initializes the webcam and sets the image resolution.
2. Loads the YOLO model from a pre-trained file (yolov8n.pt).
3. Defines the object classes to be detected.
4. In a loop, captures images from the webcam, processes each image with the YOLO model to detect objects, draws bounding boxes and labels on the image, and displays the image in a window.
### Detected Classes
The model can detect a variety of objects, including people, vehicles, animals, appliances, and more. The full list of classes can be found in the project code.

# Spanish
### Descripción del Proyecto
Este proyecto utiliza el modelo YOLO (You Only Look Once) para la detección en tiempo real de objetos en imágenes capturadas desde una cámara web. La implementación se realiza en Python, utilizando la biblioteca ultralytics para el modelo YOLO y cv2 para el procesamiento de imágenes y la captura de video.

### Requisitos
Python 3.7+
### Bibliotecas Python:
ultralytics
opencv-python
math
### Uso
Asegúrate de tener una cámara web conectada a tu computadora.
Ejecuta el script: python object_detection.py
### Estructura del Código
1. Inicializa la cámara web y establece la resolución de la imagen.
2. Carga el modelo YOLO desde un archivo preentrenado (yolov8n.pt).
3. Define las clases de objetos que se desean detectar.
4. En un bucle, captura las imágenes de la cámara, procesa cada imagen con el modelo YOLO para detectar objetos, dibuja las cajas delimitadoras y etiquetas en la imagen, y muestra la imagen en una ventana.
### Clases Detectadas
El modelo puede detectar una variedad de objetos, incluyendo personas, vehículos, animales, electrodomésticos, y más. La lista completa de clases se puede encontrar en el código del proyecto.
