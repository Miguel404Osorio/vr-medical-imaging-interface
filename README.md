# Interfaz de Usuario de Realidad Virtual para Visualización Radiológica 3D

Este repositorio contiene la memoria y los detalles de mi Trabajo Fin de Grado (TFG) para el Grado en Ingeniería Informática. El proyecto se centra en el desarrollo de una interfaz de usuario inmersiva para la manipulación y visualización avanzada de imágenes médicas tridimensionales en un entorno de Realidad Virtual (RV).

[**➡️ Descargar TFG (TFG.pdf)**](TFG.pdf)

---

## Resumen del Proyecto

El objetivo principal de este proyecto es desarrollar un conjunto de herramientas interactivas para visualizar y manipular datos médicos 3D (como Tomografías Computarizadas - TC) dentro de un entorno de RV, utilizando un Head-Mounted Display (HMD).

Las herramientas desarrolladas permiten:
* **Manipular una fuente de luz de área:** Modificar su posición, color e intensidad para mejorar la visualización.
* **Ajustar la función de transferencia:** Controlar la apariencia (opacidad y color) de los datos volumétricos para resaltar diferentes tejidos o estructuras.
* **Utilizar planos de corte:** Seccionar el volumen 3D para descartar datos no deseados y explorar el interior de las estructuras anatómicas.

El proyecto parte de un prototipo de investigación preexistente llamado **Exposure Render**, que fue adaptado para su uso en RV.

---

## Marco Tecnológico

El desarrollo se ha realizado sobre una base tecnológica robusta y moderna para gráficos y realidad virtual:

* **Lenguaje de Programación:** C++.
* **API de Realidad Virtual:** **OpenXR**, un estándar abierto que proporciona una API unificada para interactuar con hardware de múltiples fabricantes.
* **Motor Gráfico 3D:** **OpenSceneGraph (OSG)**, una librería de alto nivel que abstrae la complejidad de OpenGL.
* **Técnica de Renderizado:** El sistema utiliza **Volumetric Path Tracing** para conseguir una visualización fotorrealista de los datos, simulando la interacción de la luz con los tejidos biológicos.
* **Hardware:** Las pruebas y el desarrollo se realizaron con un HMD **HTC Vive Pro 2**.

---

## Competencias Demostradas

Este proyecto me ha permitido adquirir y consolidar competencias en:
* Desarrollo avanzado en **C++** y gestión de proyectos con **CMake**.
* Programación de gráficos 3D con **OpenSceneGraph** y librerías como **GLM**.
* Integración de hardware de **Realidad Virtual** a través del estándar **OpenXR**.
* Comprensión y aplicación de técnicas de visualización científica como el **Volume Rendering**.
