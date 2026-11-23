# IITM2026

Python basics for image analysis.

## Setup

The environment is managed with [pixi](https://pixi.sh) and works on Windows, Linux, and macOS (Intel and Apple Silicon).

1. Install pixi, then restart your terminal:
   - **Windows:** `winget install prefix-dev.pixi`
   - **macOS / Linux:** `curl -fsSL https://pixi.sh/install.sh | sh`

2. Clone this repository and install the environment:

   ```bash
   git clone <repo-url>
   cd IITM2026
   pixi install
   ```

3. Start JupyterLab and open the notebooks in the `notebooks` folder:

   ```bash
   pixi run jupyter lab
   ```

## Notebooks

| Notebook | Topics |
|---|---|
| [01_python_basics](notebooks/01_python_basics.ipynb) | Variables, strings, lists, dictionaries, loops, functions, modules, errors, NumPy arrays |
| [02_image_analysis_basics](notebooks/02_image_analysis_basics.ipynb) | Loading and displaying images, data types, contrast, filtering, thresholding, morphology, labelling, measurement, saving results |
