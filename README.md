# 🗺️ APE4 - Grafos: Mapa del Campus UTA

> **Estructura de Datos** - Universidad Técnica de Ambato


## 📌 Descripción

Este proyecto implementa un **grafo no dirigido ponderado** usando **lista de adyacencia** para modelar las rutas dentro del **Campus Huachi** de la UTA. Compara dos algoritmos clásicos:

| Algoritmo | Objetivo | Resultado |
|-----------|----------|-----------|
| **BFS** | Encontrar la ruta con **menos paradas** | Camino con menos nodos intermedios |
| **Dijkstra** | Encontrar la ruta con **menor distancia** | Camino con menor peso total |

## 🎯 Objetivo del APE

- Representar un problema real mediante un grafo
- Implementar lista de adyacencia desde cero
- Comprender y aplicar BFS y Dijkstra
- Analizar diferencias entre ambos algoritmos

## 🏛️ Nodos del Grafo (Ubicaciones)

| ID | Nombre |
|----|--------|
| `uta` | Universidad |
| `fisei` | FISEI |
| `idiomas` | Idiomas |
| `biblioteca` | Biblioteca |
| `estadio` | Estadio |
| `comedor` | Comedor |

## 🔗 Conexiones (Aristas)

| Origen | → | Destino | Peso (metros) |
|--------|---|---------|---------------|
| uta | → | fisei | 50 |
| uta | → | comedor | 20 |
| fisei | → | idiomas | 40 |
| idiomas | → | biblioteca | 30 |
| biblioteca | → | estadio | 70 |
| comedor | → | estadio | 200 |

