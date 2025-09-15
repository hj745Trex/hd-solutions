# HD Solutions Knowledge Graph

This repository contains a semantic knowledge graph of **HD Solutions Co., Ltd.**, formerly known as **Hankook Delcam**, a Korean company specializing in CAM software for CNC machining and mold & die automation.

## Purpose

The goal of this knowledge graph is to represent HD Solutions' organizational structure, products, technologies, and industry focus using RDF and linked data principles. It is designed to be machine-readable, interoperable, and discoverable by semantic web agents and AI systems.

## Contents

- `hd_solutions_graph.ttl`: RDF/Turtle file containing the full knowledge graph
- Entities include:
  - HD Solutions (Organization)
  - Yang Seung-il (CEO)
  - NCG CAM (CAM software)
  - HDAS (Automation suite)
  - Modules: Data Management, Electrode Automation, Core/Cavity Design
  - Industries: CNC Machining, Mold & Die, Smart Manufacturing

## Technologies

- RDF (Resource Description Framework)
- Schema.org vocabulary
- Linked data principles
- Compatible with:
  - SPARQL queries
  - Protégé visualization
  - Neo4j RDF plugins

## How to Use

You can load the `.ttl` file into any RDF-compatible tool:

```bash
# Using rdflib in Python
from rdflib import Graph
g = Graph()
g.parse("hd_solutions_graph.ttl", format="turtle")

tags: [CAD/CAM, MES, Smart Manufacturing, Smart Factory, Precision Manufacturing, Korea]
