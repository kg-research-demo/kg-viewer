# Grafo de Conocimiento Legislativo — Visualizador Interactivo
# Legislative Knowledge Graph — Interactive Visualizer


## Español

### ¿Qué es este repositorio?

Este repositorio contiene el material suplementario de un artículo científico presentado en la **SEPLN (Sociedad Española para el Procesamiento del Lenguaje Natural)**. Incluye un visualizador interactivo del grafo de conocimiento construido a partir de textos legislativos y proposiciones parlamentarias.

### 🔍 Visualizador

👉 **[Abrir visualizador interactivo](https://kg-research-demo.github.io)**

El visualizador permite explorar las relaciones entre entidades legislativas: proposiciones de ley, mociones, temáticas y resultados de votación, entre otras.

### ¿Qué contiene?

| Fichero | Descripción |
|--------|-------------|
| `index.html` | Visualizador interactivo autocontenido del grafo de conocimiento |

### Sobre el grafo

El grafo de conocimiento fue construido a partir de textos legislativos mediante técnicas de Procesamiento del Lenguaje Natural (PLN). Contiene:

- **~1.687 nodos** — entidades legislativas (proposiciones, mociones, temáticas…)
- **~10.301 aristas** — relaciones semánticas entre entidades (`trata_sobre`, `resultado_votacion`, etc.)
- **Comunidades** detectadas automáticamente mediante el algoritmo de Louvain

### Cómo usar el visualizador

El visualizador se ejecuta directamente en el navegador, sin instalación:

1. Abre el enlace de arriba
2. **Haz clic en un nodo** para ver sus relaciones (tripletas salientes y entrantes)
3. **Haz clic en una comunidad** en el panel izquierdo para mostrarla u ocultarla
4. **Haz clic en el fondo** del grafo para restablecer la vista
5. Usa la rueda del ratón o el gesto de pellizco para hacer zoom

### Sobre el artículo

Este visualizador es material suplementario de un artículo enviado a revisión en la **SEPLN**. Los detalles de autoría no se incluyen en este repositorio para preservar el anonimato durante el proceso de revisión por pares ciega. Una vez aceptado el trabajo, este README se actualizará con la referencia completa.

---

## English

### What is this repository?

This repository contains the supplementary material for a scientific paper submitted to **SEPLN (Spanish Society for Natural Language Processing)**. It includes an interactive visualizer of the knowledge graph built from legislative texts and parliamentary propositions.

### 🔍 Open the visualizer

👉 **[Open interactive visualizer](https://kg-research-demo.github.io)**

The visualizer allows exploration of relationships between legislative entities: bills, motions, topics, and voting outcomes, among others.

### Contents

| File | Description |
|------|-------------|
| `index.html` | Self-contained interactive knowledge graph visualizer |

### About the graph

The knowledge graph was constructed from legislative texts using Natural Language Processing (NLP) techniques. It contains:

- **~1,687 nodes** — legislative entities (bills, motions, topics…)
- **~10,301 edges** — semantic relationships between entities (`trata_sobre`, `resultado_votacion`, etc.)
- **Communities** automatically detected using the Louvain algorithm

### How to use the visualizer

The visualizer runs directly in the browser, no installation required:

1. Open the link above
2. **Click on a node** to see its relationships (outgoing and incoming triples)
3. **Click on a community** in the left panel to show or hide it
4. **Click on the background** to reset the view
5. Use the mouse wheel or pinch gesture to zoom

### About the paper

This visualizer is supplementary material for a paper currently under review at **SEPLN**. Author details are not included in this repository to preserve anonymity during the double-blind peer review process. Once the paper is accepted, this README will be updated with the full citation.

---

## Tecnologías / Technologies

- [Cytoscape.js](https://js.cytoscape.org/) — graph rendering
- [NetworkX](https://networkx.org/) — graph analysis & layout (Python)
- [python-louvain](https://github.com/taynaud/python-louvain) — community detection

---

*Repositorio creado como material suplementario anónimo para revisión científica.*  
*Repository created as anonymous supplementary material for scientific review.*