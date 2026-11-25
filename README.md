# IITM2026

Python basics for image analysis.

## Setup

The environment is managed with [pixi](https://pixi.sh) and works on Windows, Linux, and macOS (Intel and Apple Silicon).

1. You will need to install [git](https://git-scm.com/install/). Choose the right one for your operating system.

2. Once git is installed, open a terminal. In Windows, you can press Start Button and type `PowerShell` to get access to a `terminal`. Type `git` and then press Enter to verify git is installed.

3. Once you are in your terminal, you can install pixi using the following commands:
   - **Windows:** `winget install prefix-dev.pixi`
   - **macOS / Linux:** `curl -fsSL https://pixi.sh/install.sh | sh`
   Restart the terminal after installing pixi.

4. Clone this repository and install the environment:

   ```bash
   git clone https://github.com/IBI2012/IITM2026.git
   cd IITM2026
   pixi install
   ```

5. Start JupyterLab:

   ```bash
   pixi run jupyter lab
   ```
   This will launch jupyter lab in your browser.
   Once you are in jupyter lab, open the notebooks in the `notebooks` folder

## Notebooks

| Notebook | Topics |
|---|---|
| [01_python_basics](notebooks/01_python_basics.ipynb) | Variables, strings, lists, dictionaries, loops, functions, modules, errors, NumPy arrays |
| [02_image_analysis_basics](notebooks/02_image_analysis_basics.ipynb) | Loading and displaying images, data types, contrast, filtering, thresholding, morphology, labelling, measurement, saving results |
