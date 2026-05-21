# Final-Project-Sports-Analytics-using-Deep-Learning

**Descripción del proyecto:**

Este proyecto implementa un pipeline de visión computacional para análisis deportivo utilizando un modelo de deep learning YOLOv11. El sistema procesa un video aéreo de un partido de fútbol capturado con un dron DJI Mavic Pro y detecta:

- Jugadores de fútbol
- Balón de fútbol

Además, el proyecto genera métricas visuales en tiempo real durante el partido, incluyendo:

- Jugadores en el lado izquierdo de la cancha
- Jugadores en el lado derecho de la cancha
- Jugadores fuera del campo
- Jugadores dentro de cada área penal
- Posición del balón (lado izquierdo, lado derecho o fuera del campo)

El modelo fue entrenado utilizando transfer learning y un dataset personalizado anotado manualmente en CVAT.

Debido a temas de privacidad, no se agregará ni los frames de entrenamiento del modelo ni el video de salida. En su lugar se agregará al repositorio una captura de pantalla del video de salida.

**Pipeline del Proyecto**

El proyecto sigue las siguientes etapas principales:

1. Extracción de frames del video aéreo
2. Anotación manual de jugadores y balón usando CVAT
3. Organización del dataset en entrenamiento, validación y prueba
4. Entrenamiento de un modelo YOLOv11 utilizando transfer learning
5. Procesamiento completo del video
6. Generación de analytics visuales y overlays
7. Exportación del video final procesado

**Instalación**
1. Clonar el repositorio
2. Instalar dependencias

**Cómo ejecutar el proyecto**
1. Colocar el video del dataset, las anotaciones y las imágenes de entrenamiento dentro de la carpeta principal del proyecto. Algunos de estos archivos no se incluyen en el repositorio debido a temas de seguridad.
2. Ejecutar el notebook principal o el script del proyecto para comenzar el entrenamiento y procesamiento del video.
