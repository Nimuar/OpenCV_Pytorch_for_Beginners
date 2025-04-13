# PyTorch Bootcamp: Deep Learning with OpenCV

This repository contains my personal code, notes, and experiments while going through the PyTorch Bootcamp: Deep Learning with OpenCV course.

While the course recommends Google Colab for running notebooks, I’m using Jupyter Notebooks via Anaconda in VS Code for local development and GPU experimentation (where supported).

## 💻 Setup

I'm working locally with the following stack:

Python 3.10+

PyTorch (CPU version, since I use an AMD GPU on Windows)

OpenCV

Jupyter Notebooks via Anaconda

VS Code (as the main IDE)

AMD GPUs are not currently supported for PyTorch acceleration on Windows, so all models are trained on CPU.

To set up the environment:

```bash
# Create conda environment
conda create -n opencv_dl python=3.10
conda activate opencv_dl

# Install required packages
pip install torch torchvision torchaudio
pip install opencv-python matplotlib numpy jupyter wget
```

## 📁 Folder Structure

Each section/module from the course will have its own folder.

## 🚀 Goals

Gain hands-on experience with PyTorch fundamentals.

Practice image classification and computer vision workflows using OpenCV.

Build small but complete deep learning projects using best practices.

Adapt examples from Google Colab to run locally on a Jupyter setup.

## 🧠 Notes

All notebooks are documented with comments and visualizations.

Some image download links may throw errors (403 Forbidden) when accessed without browser headers — I use Python’s requests instead of wget for those.

Code will evolve and be cleaned up over time — this is a live learning repo.

## 📜 License

This repository contains educational work based on OpenCV’s course materials. All code here is for personal learning and open sharing, under the MIT License.
