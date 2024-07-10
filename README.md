## Inteliver Documentation

Inteliver is an open-source image management framework that allows you to store, modify, and deliver optimized images. 

This README provides instructions to set up and build the documentation for Inteliver using MkDocs.

### Installation

1. Create a new Conda environment with Python 3.11:
    ```bash
    conda create -n mkdocs python=3.11
    ```

2. Activate the environment:
    ```bash
    conda activate mkdocs
    ```

3. Install MkDocs Material and MkDocs Macros Plugin:
    ```bash
    pip install mkdocs-material mkdocs-macros-plugin
    ```

### Serving the Documentation

To serve the documentation locally:

```bash
mkdocs serve
```

### Building the Static Website

To build the static website:

```bash
mkdocs build
```

This will create a `site` directory with your static documentation website ready to be hosted.

### Notes
1. Use relative links for internal navigation.

> Example:
    You can find out more examples at `[inteliver Examples](../examples/index.md)`