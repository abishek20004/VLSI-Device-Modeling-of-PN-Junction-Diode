# VLSI-Device-Modeling-of-PN-Junction-Diode
Synopsys Sentaurus TCAD project demonstrating PN junction diode modeling, mesh generation, and electrical characterization.

---

## 📌 Executive Summary

This repository presents a complete **2D TCAD (Technology Computer-Aided Design)** device modeling and numerical characterization suite for an advanced **Silicon $P^+ N N^+$ Power Diode** utilizing the **Synopsys Sentaurus TCAD** toolset. 

The project covers structural generation, mesh refinement, physical transport model configuration, static DC forward/reverse IV analysis, high-voltage breakdown, junction capacitance dynamics ($C\text{--}V$), and transient reverse recovery ($t_{rr}$) switching performance.

##  TCAD Tool Flow
```text
========================================================================================
                                 TCAD SIMULATION FLOW
  +------------------+    +------------------+    +------------------+    +------------------+
  |    Sentaurus     |    |   SNMESH Mesh    |    | Sentaurus Device |    | Sentaurus Visual |
  | Structure Editor |--->|    Generator     |--->| Numerical Solver |--->|   Data & Plot    |
  |      (SDE)       |    |   (n1_msh.tdr)   |    |    (sdevice)     |    |   Extraction     |
  +------------------+    +------------------+    +------------------+    +------------------+
========================================================================================
