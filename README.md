![license](https://img.shields.io/badge/license-Apache--2.0-blue)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1vtpXwzC1h4xkxp47wXspfkWR5yuodIAv?usp=sharing)

I Curated a a Computational Neuroscience Project which shows the **Simulation of Visual Cortex Edge Detection with Gabor Filters**.
This project simulates how the primary visual cortex (V1) detects edges and orientations using biologically inspired Gabor filters. It demonstrates edge/orientation detection through interactive visualizations.

<img width="466" height="389" alt="image" src="https://github.com/user-attachments/assets/513f8c61-7e09-4809-9c3c-efb43e8c3e69" />
<img width="515" height="350" alt="image" src="https://github.com/user-attachments/assets/18359298-ddc8-474f-8774-dff9fe43681b" />
<img width="515" height="376" alt="image" src="https://github.com/user-attachments/assets/a91b48f0-6d7d-486f-908a-896cc638616b" />


## 🔍 Project Overview

- Modeled V1 simple & complex cells with 2D Gabor filters.
- Applied a multi-orientation filter bank for edge detection.
- Computed orientation-specific energy & combined responses.
- Demonstrated **contrast invariance** on natural images (cat sample).
- Produced interactive visualizations of orientation maps.


## 🚀 Quickstart

### Run in Colab 
This project was built and tested entirely on **Google Colab**.  
To reproduce results, open the notebook below:
[![Open In Colab](https://colab.research.google.com/drive/1vtpXwzC1h4xkxp47wXspfkWR5yuodIAv?usp=sharing)

### Run locally
To run it locally follow the instructions below:
```bash
git clone https://github.com/<your-username>/<repo-name>
cd <Compuational-Neuroscience>
pip install -r requirements.txt
python comp_neuro_finalproject.py
**Replace `cat1.jpeg` with any grayscale image to test orientation detection.**
```

## 🧰 Tech Stack
- Google Colab ->reproducibility & prototyping
  `requirements.txt`
- `numpy`, `matplotlib`, `scikit-image`, `tensorflow`-> filter ops, visualization, and computation
- Custom module: [`gwp`](https://www.johancarlin.com/gabor-filter-models-for-visual-neuroscience.html) (by Johan Carlin)


## 📊 Outputs

- Gabor filter visualizations

  
  <img width="466" height="389" alt="image" src="https://github.com/user-attachments/assets/6438cf6f-218a-4568-afcc-3bf2271d7ace" />
- Orientation-specific energy maps

  
  <img width="515" height="188" alt="image" src="https://github.com/user-attachments/assets/24901374-ffd3-4c80-808f-732b3cc33801" />
- Combined orientation energy map

  
  <img width="274" height="1274" alt="image" src="https://github.com/user-attachments/assets/e862c677-07cb-4043-9317-528753af1a6e" />
- V1 response to contrast-inverted input

  
  <img width="515" height="376" alt="image" src="https://github.com/user-attachments/assets/6f50d650-0fb6-4a1b-ba01-1dabb769b078" />


## 📂 Files
- `comp_neuro_finalproject.py` — main script, run preprocessing and visualization.
- `cat1.jpeg` — sample input used(replacebale)
- `gwp.py`- John Carlin's customized Module implement Gabor Filter to Images.


## 🤝 Acknowledgments
Based on Johan Carlin's Gabor filter model(https://www.johancarlin.com/). I am grateful to Professor Bittu for guidance throughout the course, which fostered engaging discussions and a deeper understanding of the subject. I would also like to thank Aryan and Manas for their valuable contributions to classroom discussions and presentations during this ISM.
