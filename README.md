# 🚀 Proyecto #1: Práctica de Rendimiento — Sistema de Procesamiento de Imágenes para Control de Calidad

<p align="center">
  <img src="https://img.shields.io/badge/Universidad-Pontificia%20Bolivariana-red?style=for-the-badge" alt="UPB">
  <img src="https://img.shields.io/badge/Materia-Arquitectura de Computadores-blue?style=for-the-badge" alt="Arquitectura de Computadores">
  <img src="https://img.shields.io/badge/Estado- %25100 Desarrollo-green?style=for-the-badge" alt="Status">
</p>

Repositorio oficial para el desarrollo del **Proyecto 1: Experimentación y análisis de prestaciones**, enfocado en evaluar el comportamiento del rendimiento y la identificación de cuellos de botella bajo una carga de trabajo orientada al control de calidad industrial mediante procesamiento de imágenes.

---

## 👥 Equipo de Trabajo

| Estudiante | Rol Principal |
| :--- | :--- |
| **Esteban Présiga Posada** | Rol 1: Diseño Experimental / Rol 3: Análisis de Prestaciones |
| **Daniel Alberto Montiel** | Rol 2: Benchmarking y Medición / Rol 3: Análisis de Prestaciones |

* **Docente:** Claudia Stella Carmona Rodriguez  
* **Institución:** Universidad Pontificia Bolivariana (UPB)  
* **Semestre:** 4° Semestre — Ingeniería en Sistemas e Informática  

---

## 🎯 Descripción del Escenario (Grupo 1)

Una empresa manufacturera requiere implementar un sistema de inspección automática de productos mediante procesamiento de imágenes. El flujo de trabajo recibe entradas heterogéneas en cantidad y resolución (desde pocas imágenes de baja resolución hasta grandes volúmenes de alta resolución). El objetivo de esta práctica es analizar empíricamente cómo evoluciona el tiempo de procesamiento y la saturación de los recursos de hardware ante incrementos progresivos de la carga.

---

## 🔬 Diseño Experimental Resumido

* **Pregunta de Investigación:** ¿Cómo cambia el rendimiento de un sistema de procesamiento de imágenes al aumentar la cantidad y resolución de las imágenes, y qué recurso presenta mayores evidencias de convertirse en un factor limitante?
* **Variables Independientes:** 
  * Cantidad de imágenes procesadas simultáneamente.
  * Resolución de las imágenes de entrada (píxeles).
* **Variables Dependientes:** 
  * Tiempo de procesamiento total e individual.
  * Imágenes procesadas por segundo (Throughput).
  * Porcentaje de utilización de la CPU.
  * Porcentaje de utilización de la Memoria RAM.
* **Herramienta / Benchmark:** Script automatizado desarrollado por el equipo en Python utilizando librerías de procesamiento de imágenes y monitoreo de hardware.

---

## 🛠️ Organización del Repositorio

```text
├── script/               # Código fuente del benchmark desarrollado por el equipo
├── resultados_script/    # Archivos de datos, métricas crudas y registros de las pruebas
├── informe_final.docx    # Documento final consolidado con la experimentación y análisis
└── README.md             # Documentación principal del repositorio
```
## 💯 Muchas Gracias Por su atención al Repositorio 
