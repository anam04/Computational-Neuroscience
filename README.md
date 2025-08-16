Hello,
I am Anam Ahamed, a sophomore studying at the Ashoka University.
This is my final project for the Computational Neuroscience ISM(Independent Study Module).
This project simulates how the **primary visual cortex (V1)** in the brain detects **edges** and **orientations** in a visual scene using biologically inspired **Gabor filters**.

## 🔍 Project Overview

- Models **simple and complex cells** in V1 using 2D Gabor filters
- Applies a Gabor filter bank across orientations
- Visualizes **orientation-specific responses** and computes **V1 energy**
- Demonstrates **contrast invariance** by comparing original vs contrast-inverted images
- Uses a grayscale image of a **cat** for demonstration

## 🧰 Tech Stack

- Google Colab
- `numpy`, `matplotlib`, `scikit-image`, `tensorflow` (all the libraries that have been used to build this project)
- Custom module: [`gwp`](https://www.johancarlin.com/gabor-filter-models-for-visual-neuroscience.html) (by Johan Carlin)


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
I am thankful to Professor Bittu for providing all the students with a platform and an opportunity to deeply engage with the course. It truly helped shaped the intellectual and thought-provind conversations in the room, truly helped gain even a nunaced understanding of this course.
I am also thankful to Aryan and Manas for helping initiate fruitful classroom discussion via coversations and presentations throughout this ISM.

