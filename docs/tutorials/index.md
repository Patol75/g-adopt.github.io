# Tutorials

The diagram below illustrates the set of notebook tutorials available
in G-ADOPT and how they relate to each other. These notebooks demonstrate
how to use G-ADOPT to set up (forward and inverse) geodynamical simulations.

```mermaid
--8<-- "docs/tutorials/.diagram.mermaid"
```

We start with the most basic problem — isoviscous, incompressible
convection, in an enclosed 2-D Cartesian box (base) — and
systematically build complexity, initially moving into more realistic
physical approximations (compressibility — ALA, TALA; visco-plastic
rheology), subsequently to multi-material simulations, and finally to
different dimensions and to spherical shell geometries that are more
representative of Earth's mantle.

These pages are all rendered from Jupyter notebooks included in the
G-ADOPT source code. You can find them under the directory `demos/`.

To run these notebooks, you will need a working installation of
Firedrake and G-ADOPT and a Jupyter kernel for Firedrake. See the
[install page](../install.md) for instructions.

Note that Firedrake includes its own tutorials to get you started. If
you are not familiar with Firedrake, we strongly recommend that you
start with their [introductory tutorials](https://www.firedrakeproject.org/documentation.html).
