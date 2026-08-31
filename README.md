# 🚀 OptiRuta - Sistema de Recomendación de Rutas Óptimas

![Banner del Proyecto](https://img.shields.io/badge/Estado-En%20Desarrollo-blue?style=for-the-badge)
![Licencia](https://img.shields.io/badge/Licencia-CC%20BY%204.0-green?style=for-the-badge)
![Asignatura](https://img.shields.io/badge/Asignatura-Algoritmia-orange?style=for-the-badge)
![Facultad](https://img.shields.io/badge/Facultad-Ingeniería%20Industrial-red?style=for-the-badge)

<p align="center">
  <svg width="200" height="100" xmlns="http://www.w3.org/2000/svg">
    <rect width="200" height="100" fill="#2c3e50" rx="10"/>
    <text x="20" y="40" fill="#ecf0f1" font-size="16" font-family="Arial">OptiRuta</text>
    <text x="20" y="65" fill="#bdc3c7" font-size="11" font-family="Arial">Rutas inteligentes</text>
    <circle cx="160" cy="50" r="15" fill="#3498db"/>
    <polygon points="155,45 155,55 165,50" fill="white"/>
  </svg>
</p>

---

## 1. Integrantes del Equipo

| Nombres y Apellidos | Rol dentro del proyecto |
|----------------------|--------------------------|
| **Angie Marisel Higuita Londoño** | Líder de Proyecto / Especialista en Optimización Logística |
| **Dair Manuel Martinez Arrieta** | Analista de Datos y Modelado de Redes |
| **Santiago Alvarez Guresso** | Desarrollador de Interfaz y Experiencia de Usuario (UX) |
| **Juan Manuel Gomez Morales** | Analista de Pruebas, Calidad y Documentación Técnica |

---

## 2. Vínculos Académicos y Descripción de Habilidades

| Integrante | Programa Académico | Habilidades y Fortalezas Técnicas |
|------------|--------------------|------------------------------------|
| **Angie Marisel Higuita Londoño** | Ingeniería Industrial | Dominio en optimización de procesos y cadena de suministro. Manejo avanzado de herramientas estadísticas y de simulación. Capacidad para traducir problemas logísticos del mundo real en modelos matemáticos (grafos y redes). Liderazgo y planificación estratégica. |
| **Dair Manuel Martinez Arrieta** | Ingeniería Industrial | Experto en investigación de operaciones y análisis de datos. Manejo de bases de datos (SQL/Excel avanzado) y lenguajes de programación aplicados a la ingeniería (Python enfocado a datos). Habilidad para estructurar grandes volúmenes de información georreferenciada. |
| **Santiago Alvarez Guresso** | Ingeniería Industrial | Enfoque en ingeniería de métodos y ergonomía cognitiva. Experiencia en diseño de tableros de control (Dashboards) e interfaces funcionales para la toma de decisiones. Conocimientos en visualización de datos y herramientas de prototipado rápido (Streamlit, Power BI). |
| **Juan Manuel Gomez Morales** | Ingeniería Industrial | Especialista en gestión de calidad y mejora continua (Six Sigma). Habilidad para la redacción de documentos técnicos, manuales de usuario y especificaciones de requisitos. Experiencia en pruebas de estrés de procesos y validación de modelos operativos. |

---

## 3. Nombre del Proyecto y Detalles

**Nombre del proyecto:** `OptiRuta`

**Descripción ejecutiva:**  
OptiRuta es un sistema de software que modela una red de transporte o distribución (público o de mercancías) como un grafo dirigido y ponderado. Su objetivo es calcular la ruta más eficiente entre dos puntos, permitiendo al usuario elegir entre minimizar el **tiempo de viaje**, la **distancia recorrida** o la **cantidad de transbordos (paradas)**. 

El proyecto aplica los algoritmos de búsqueda en grafos (Dijkstra y A*) vistos en la asignatura Algoritmia, pero con un enfoque práctico de la Ingeniería Industrial: **optimización de rutas logísticas**, reducción de costos operativos y mejora de la eficiencia en la distribución de recursos.

---

## 4. Licencia del Software

Este proyecto está protegido bajo la licencia **Creative Commons Attribution 4.0 International (CC BY 4.0)**.  
Esto permite que cualquier persona comparta, adapte y use el software, incluso con fines comerciales, siempre que se otorgue el crédito adecuado al equipo desarrollador.

Para más información, consulte el archivo [`LICENSE`](./LICENSE) en la raíz del repositorio o visite:  
[https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)

---

## 📁 Estructura del Repositorio

```plaintext
proyecto-algoritmia/
├── README.md          # Este archivo (portada del proyecto)
├── LICENSE            # Texto completo de la licencia CC BY 4.0
├── docs/              # Carpeta de documentación interna
│   ├── vision.md      # Visión general, objetivos y beneficios
│   ├── requisitos.md  # Requisitos funcionales y no funcionales
│   └── plan-proyecto.md # Cronograma (Gantt) y presupuesto detallado
└── src/               # (Próximamente) Código fuente del proyecto
    ├── grafo.py
    ├── dijkstra.py
    ├── estrella.py
    └── main.py

--

