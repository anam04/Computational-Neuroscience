Hello,
I am Anam Ahamed, a sophomore studying at the Ashoka University.
This is my final project for the Computational Neuroscience ISM.
This project simulates how the **primary visual cortex (V1)** in the brain detects **edges** and **orientations** in a visual scene using biologically-inspired **Gabor filters**.

## 🔍 Project Overview

- Models **simple and complex cells** in V1 using 2D Gabor filters
- Applies a Gabor filter bank across multiple orientations (0° to 157.5°)
- Visualizes **orientation-specific responses** and computes **V1 energy**
- Demonstrates **contrast invariance** by comparing original vs contrast-inverted images
- Uses a grayscale image of a **cat** for demonstration

## 🧰 Tech Stack

- Python 3
- Google Colab
- `numpy`, `matplotlib`, `scikit-image`, `tensorflow`
- Custom module: [`gwp`](https://www.johancarlin.com/gabor-filter-models-for-visual-neuroscience.html) (by Johan Carlin)

## 🧠 Biological Motivation

This model is inspired by how neurons in the **visual cortex (V1)** respond to specific edge orientations and spatial frequencies. Gabor functions closely resemble the receptive fields of V1 simple cells (Jones & Palmer, 1987). The energy model used mimics complex cells, which are phase-invariant.

## 📊 Outputs

- Gabor filter visualizations
- Orientation-specific energy maps
- Combined orientation energy map
- V1 response to contrast-inverted input

## 📂 Files

- `comp_neuro_finalproject.py` — full code
- `cat1.jpeg` — input image used
- `gwp.py`- John Carlin's customized Module implement Gabor Filter to Images.

## 🤝 Acknowledgments

Thanks to [Johan Carlin](https://www.johancarlin.com/) for the original Gabor filter model.

