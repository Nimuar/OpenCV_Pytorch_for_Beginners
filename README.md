# PyTorch Bootcamp with OpenCV

This repository contains my personal code, notes, and experiments while going through the PyTorch Bootcamp with OpenCV course.

While the course recommends Google Colab for running notebooks, I’m using Jupyter Notebooks via Anaconda in VS Code for local development and GPU experimentation (where supported).

## 💻 Setup

I'm working locally with the following stack:

- Python 3.10+

- PyTorch (CPU version, since I use an AMD GPU on Windows)

- OpenCV

- Jupyter Notebooks via Anaconda

- VS Code (as the main IDE)

⚠️ AMD GPUs are not currently supported for PyTorch acceleration on Windows, so all models are trained on CPU.

To set up the environment:

```bash
# Create conda environment
conda create -n opencv_dl python=3.10
conda activate opencv_dl

# Install required packages
pip install torch torchvision torchaudio
pip install opencv-python matplotlib numpy jupyter wget
pip install torchviz
```

⚙️ Graphviz Setup (Required for torchviz)

Torchviz requires Graphviz system binaries, not just the Python package.

- Windows:

    - Download Graphviz from https://graphviz.org/download/

    - Install it and add the bin/ folder (e.g., C:\Program Files\Graphviz\bin) to your system PATH

- macOS:
```bash
brew install graphviz
```

- Linux:
```bash
sudo apt install graphviz
```

## 📁 Folder Structure

Each section/module from the course will have its own folder.

## 🚀 Goals

Gain hands-on experience with PyTorch fundamentals.

Practice image classification and computer vision workflows using OpenCV.

Build small but complete projects using best practices.

Adapt examples from Google Colab to run locally on a Jupyter setup.

## 🧠 Notes

All notebooks are documented with comments and visualizations.

Some image download links may throw errors (403 Forbidden) when accessed without browser headers — I use Python’s requests instead of wget for those.

Code will evolve and be cleaned up over time — this is a live learning repo.

This document was generated with the help of ChatGPT.

## 📜 License

This repository contains educational work based on OpenCV’s course materials. All code here is for personal learning and open sharing, under the MIT License.

## 🔍 Sources

- Jupyter Notebook: [Jupyter for VS Code](https://code.visualstudio.com/docs/datascience/jupyter-notebooks)
- Anaconda: [Working with Conda](https://www.anaconda.com/docs/tools/working-with-conda/main)
