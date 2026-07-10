# Real-and-fake-face-distinction

This repository contains two separate binary image classifiers built with TensorFlow/Keras CNNs, both trained via `tf.keras.utils.image_dataset_from_directory`:

- `model13.ipynb` — classifies faces as **real** or **fake** (matches the repo name), reading images from `data/real/` and `data/fake/`.
- `Happy and Sad face distinction.ipynb` — a separate exercise that classifies faces as **happy** or **sad**, reading images from `data/happy/` and `data/sad/`.

## Note on data

The training image folders themselves are not included in this repository (the checked-in `data` path is a placeholder, not the dataset) — only the notebook code and its saved outputs are here. To re-run either notebook, supply your own labeled images in the corresponding folder structure. Two sample JPEGs used for ad-hoc inference testing are included in the repo root.

## How to run

```bash
git clone https://github.com/bharat3645/Real-and-fake-face-distinction.git
cd Real-and-fake-face-distinction
pip install tensorflow opencv-python matplotlib
jupyter notebook
```
