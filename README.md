# 🧠 AlgoritmicaYProgramacion2

Este proyecto simula una red de computadoras conectadas a través de routers. Su objetivo principal es **detectar errores en redes** y aplicar algoritmos clásicos para **optimizar las conexiones**, incluyendo el cálculo del camino más corto entre equipos y la generación del árbol de expansión mínima.

Esta fue la **primera versión** del sistema, desarrollado exclusivamente en Java, utilizando estructuras de datos y lectura desde archivos como mock de entrada.

---

## 🚀 Funcionalidades principales

- 📄 Lectura de datos desde archivos planos simulando una red real
- 🧱 Modelado de nodos (equipos y routers) y sus conexiones
- 🕵️ Validación de errores lógicos en la red
- 📡 Cálculo del **camino más corto** entre dos equipos con el algoritmo de Dijkstra
- 🌐 Generación del **Árbol de Expansión Mínima (MST)** para conectar toda la red con costo mínimo
- 🧠 Uso de patrones de diseño como Singleton y DAO
- 🧪 Separación clara de responsabilidades: modelo, algoritmo, lógica y entrada/salida

---

## 🛠️ Tecnologías y conceptos

- 🧠 **Lenguaje:** Java (POO)
- 🧮 **Algoritmos:** Dijkstra, MST Kruskal
- 📚 **Estructuras:** Grafos, listas enlazadas, árboles
- 🧰 **Patrones:** DAO (mock en archivos), Singleton
- 📂 **Entrada:** Archivos `.txt` simulando equipos y conexiones

---

## 📁 Estructura del proyecto
red/
├── aplicacion/ # Encargada de ejecutar la aplicacion, por teminal o UI
├── datos/ # Clases encargadas de cargar los datos almacenados en los archivos
├── interfaz/ # clases de la Interfaz grafica
├── logica/ # Todo lo relacionado con la logica del negocio y los algoritmo
└── modelo/ # Clases de dominio: Equipo, Router, Conexion, etc.

## 🖼️Imagenes
![Captura de pantalla 2025-06-28 192031](https://github.com/user-attachments/assets/ae08d954-d419-4589-91b4-aa2785fd97cc)
![Captura de pantalla 2025-06-28 192016](https://github.com/user-attachments/assets/3e13f210-268b-430f-8433-fd7b5d35f93f)
![Captura de pantalla 2025-06-28 192127](https://github.com/user-attachments/assets/3f07b8d9-f08a-4c76-8b63-a2bf7515311a)
![Captura de pantalla 2025-06-28 192138](https://github.com/user-attachments/assets/824f2758-d002-4dd1-ae9b-32490c5a2598)

