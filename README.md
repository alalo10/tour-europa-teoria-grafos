# 🚆 Tour por Europa — Optimización de Rutas con Teoría de Grafos

> Proyecto Final · Matemáticas Discretas (22954) · Grupo E1  
> Escuela de Ingeniería de Sistemas e Informática · Universidad Industrial de Santander

---

## 🎥 Video de presentación

[![Ver video de presentación](https://img.youtube.com/vi/IU31Z_dlD0w/0.jpg)](https://youtu.be/IU31Z_dlD0w?si=SkRChU3vbgsIyXPJ)

---

## 📌 Descripción del problema

La agencia **AlasExplorer** recibió a un grupo de estudiantes universitarios con buen presupuesto económico, pero con tiempo muy limitado. Su objetivo: recorrer las **capitales de los países más grandes de Europa en tren**, con el menor tiempo de desplazamiento posible.

Para resolverlo, se modeló el problema usando **Teoría de Grafos**, representando las ciudades como nodos y los tiempos de viaje en tren (en horas) como los pesos de las aristas. Luego se aplicó el **algoritmo de Kruskal** para encontrar el **Árbol Recubridor Mínimo (ARM)**, es decir, la ruta que conecta todas las ciudades en el menor tiempo total.

---

## 🗺️ Ciudades incluidas en el grafo

Bélgica · Países Bajos · UK · Irlanda · Francia · España · Portugal · Italia · Suiza · Noruega · Alemania · República Checa · Croacia · Suecia · Finlandia · Polonia · Rumania · Macedonia · Grecia

---

## ⚙️ ¿Cómo funciona el algoritmo de Kruskal?

1. Se construye una **matriz de pesos** con los tiempos de viaje entre ciudades conectadas.
2. El algoritmo ordena todas las aristas de **menor a mayor peso** (horas de viaje).
3. Va seleccionando aristas una por una, **evitando ciclos**, hasta conectar todos los nodos.
4. El resultado es el árbol que conecta todas las ciudades con la **mínima duración total del viaje**.

---

## 🛠️ Tecnologías utilizadas

| Herramienta | Uso |
|---|---|
| `Python` | Lenguaje principal |
| `NetworkX` | Representación y manipulación del grafo |
| `Matplotlib` | Visualización gráfica del grafo y del ARM |
| Google Colab | Entorno de desarrollo |

---

## 🚀 ¿Cómo ejecutar el proyecto?

1. Abre el archivo `.ipynb` en [Google Colab](https://colab.research.google.com/) o Jupyter Notebook.
2. Ejecuta primero la celda de **importación de librerías** (`networkx` y `matplotlib`).
3. Ejecuta las celdas en orden: Matriz de Pesos → Algoritmo de Kruskal → Visualización.
4. ¡Verás el grafo completo de Europa y la ruta óptima calculada! 🗺️

---

## 📊 Resultados

El algoritmo encontró el **árbol recubridor mínimo** del grafo, entregando como resultado la ruta ferroviaria de menor duración que conecta las 19 ciudades. Esta solución permite al grupo de estudiantes recorrer el mayor número de destinos europeos **gastando el menor tiempo posible en desplazamientos**.

---

## 👩‍💻 Autores

| Nombre | Correo |
|---|---|
| Daniel Esteban Rueda | daniel2221927@correo.uis.edu.co |
| Andrea Bernal | andrea2201827@correo.uis.edu.co |
| Angela Lozano | angelalozano2017@gmail.com |
| Johnathan Ramos | jonramos@correo.uis.edu.co |

---

## 📚 Referencias

- The Train Line. (2023). *Tiempos de viaje en tren por Europa*. https://www.thetrainline.com/es/
- Alves, A. D. S. (2016). *Teoria dos grafos: algoritmo de Kruskal e Prim aplicado em análise de dados*. https://repositorio.ufc.br/handle/riufc/32800
- Galvis, L. (2023). *Capítulo 3: Estructuras de datos lineales y no lineales*. Universidad Industrial de Santander.

---

<p align="center">
  Hecho con ❤️ en la Universidad Industrial de Santander · 2023
</p>
