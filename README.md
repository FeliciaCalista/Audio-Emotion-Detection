# Audio Emotion Detection
Developed a speech emotion recognition model using the RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song) dataset. The project focuses on analyzing speech signals from .wav audio recordings, extracting acoustic features, and applying machine learning or deep learning techniques to identify emotional patterns. The model aims to classify multiple emotional states, including happiness, sadness, anger, fear, neutrality, and other categories, based on characteristics of the input speech signals.

---

## About Dataset

Dataset used:  
[RAVDESS Emotional Speech Audio](https://doi.org/10.1371/journal.pone.0196391)

- Total: **1440 file audio** (.wav)
- Actors: 24 (12 pria, 12 wanita)
- Emotion: 8 jenis (neutral, calm, happy, sad, angry, scared, disgusted, surprised)
- File naming format:  
  `Modality-VocalChannel-Emotion-Intensity-Statement-Repetition-Actor.wav`

### Example:
03-01-06-01-02-01-12.wav

### Explanation:
- **Modality**: 03 = audio-only
- **Vocal Channel**: 01 = speech
- **Emotion**: 06 = fearful
- **Intensity**: 01 = normal
- **Statement**: 02 = "Dogs are sitting by the door"
- **Repetition**: 01 = first
- **Actor**: 12 = female

---

## Project Features

- Automatic data extraction from `.zip` files
- Audio feature extraction using `librosa`
- Emotion classification model from audio
- Data visualization and model accuracy
- Model validation with test data

## Technologies Used

- Python 3.x
- `librosa` – for audio feature extraction (MFCC, pitch, etc.)
- `numpy`, `pandas` – data manipulation
- `matplotlib`, `seaborn` – visualization
- `scikit-learn` – machine learning pipeline

---

## How to Run

1. Download the RAVDESS (audio speech) dataset
2. Run the `HSP.ipynb` notebook in the following sequence:
- Data extraction
- Cleaning and processing
- Model training and evaluation

> Ensure all dependencies are installed.

---

## License

This project is licensed under the MIT License – you are free to use, modify, and distribute this project with attribution.
