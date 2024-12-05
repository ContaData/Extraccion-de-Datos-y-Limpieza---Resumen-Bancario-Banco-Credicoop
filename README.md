# Extracción y Limpieza de Datos del Resumen Bancario - Banco Credicoop
  # Descripción
Este proyecto se dedica a la extracción y limpieza de datos de extractos bancarios del Banco Credicoop. 
El objetivo es transformar los datos de los extractos bancarios en formato PDF a un archivo Excel limpio y estructurado, facilitando así su análisis posterior.

  # Requisitos
Para llevar a cabo este proyecto, necesitarás las siguientes librerías de Python junto con sus versiones:

- OpenCV (cv2): Utilizada para la preprocesamiento de imágenes, versión 4.10.0.

- NumPy: Empleada para operaciones numéricas y manejo de matrices, versión 1.26.4.

- pytesseract: Utilizada para la extracción de texto de imágenes, versión 0.3.13.

- pandas: Empleada para la manipulación y análisis de datos, versión 2.2.3.

- re: Usada para el manejo de expresiones regulares, versión 2.2.1.

- pdf2image: Manipulacion de imagenes en archivos pdf, version 1.17.0

Este codigo tiene un funcionamiento en:

- Python: Versión 3.12.7 (packaged by conda-forge)

- Sistema Operativo: Windows 10, versión 10.0.19045

  # Instalación
Para instalar las librerías necesarias, puedes usar el siguiente comando de pip:

sh
pip install opencv-python-headless==4.10.0 numpy==1.26.4 pytesseract==0.3.13 pandas==2.2.3
Nota: re es un módulo incorporado en Python y no necesita instalación adicional.

  # Uso
El flujo del proyecto sigue estos pasos:

Convertir PDF a imágenes: La primera página del PDF se convierte en una imagen utilizando la librería pdf2image.

Preprocesamiento de la imagen: La imagen se convierte a escala de grises, se binariza, se elimina el ruido y se aumenta el contraste utilizando OpenCV.

Extracción de texto: Se usa pytesseract para extraer texto del área de interés especificada en la imagen procesada.

Limpieza y transformación de datos: Los datos extraídos se limpian y transforman utilizando pandas.

Guardar en Excel: Los datos limpios se guardan en un archivo Excel para su análisis posterior.

  # Contribuciones
Las contribuciones al proyecto son bienvenidas. Puedes enviar un pull request con una descripción detallada de los cambios propuestos.

  # Licencia
Este proyecto está licenciado bajo los términos de la licencia MIT.

  # Contacto
Para cualquier consulta, por favor contacta a [condadata.info@gmail.com].

Esta estructura del README proporciona una guía clara y completa sobre el propósito y uso del proyecto, incluyendo las dependencias, la instalación y el flujo de trabajo. 
Puedes personalizarlo según tus necesidades específicas. Si tienes más preguntas o necesitas ayuda adicional, ¡estoy aquí para ayudarte! 😊


****
