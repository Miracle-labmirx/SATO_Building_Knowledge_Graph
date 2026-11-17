# SATO Building Knowledge Graph

The **SATO Building Knowledge Graph** is a web of established *building entities* and
*computational entities*, together with their interconnectedness. It forms a semantic
layer that supports a wide range of building tasks — including the autonomous discovery
of computational tasks that can be instantiated and operationalised, building predictive
analytics, and control applications driven by Reinforcement Learning.

## Overview

Modern buildings generate rich, heterogeneous data, but this data is rarely organised in
a way that machines can reason over. The SATO Building Knowledge Graph bridges this gap by
explicitly modelling:

- **Building entities** — the physical and conceptual components of a building (spaces,
  devices, sensors, systems, measurements, etc.).
- **Computational entities** — the tasks, models, and applications that can operate on
  building data (predictive models, control policies, analytics routines).
- **Interconnections** — the semantic relationships that link building entities to the
  computational entities that can consume or act upon them.

By capturing these relationships explicitly, the graph enables autonomous discovery of
which computational tasks are applicable to a given building context, and how they can be
instantiated and operationalised.

## Key Capabilities

- **Semantic layer** over building data to support interoperable, machine-readable
  reasoning.
- **Autonomous task discovery** — identify computational tasks that can be instantiated
  and operationalised for a given building configuration.
- **Predictive tasks** — support data-driven forecasting applications.
- **Control applications** — enable Reinforcement Learning–based control strategies.

## Tech Stack

- **Neo4j** — graph database for storing and querying the knowledge graph.
- **Python** — core implementation and data processing.
- **Semantic Web technologies:**
  - **SAREF** (Smart Applications REFerence ontology) — for modelling smart devices and
    their functions.
  - **NGSI-LD** (New Generation Services Interface – Linked Data) — for linked-data
    context information and interoperability.

## Getting Started

> _Work in progress — setup and usage instructions to be added._

## License

> _To be added._
