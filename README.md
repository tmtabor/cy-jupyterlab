# cy-jupyterlab

Jupyter lab widget for rendering graphs (networks:.cx, .json) using cytoscape.js

## Prerequisites

* JupyterLab

## Installation

```bash
jupyter labextension install cy-jupyterlab
```

## Development

For a development install (requires npm version 4 or later), do the following in the repository directory:

```bash
npm install
jupyter labextension link .
```

To rebuild the package and the JupyterLab app:

```bash
npm run build
jupyter lab build
```

