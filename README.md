# 🧠 EEG Motor Imagery Classification

This project applies signal processing and machine learning to classify **motor imagery EEG signals**.  
It is based on the **BCI Competition III Dataset IIIa** (e.g., subject l1b), focusing on 4 motor tasks:  
- Left hand  
- Right hand  
- Feet  
- Tongue

## 📊 Dataset

The EEG signals come from the **BCI Competition IIIa** dataset. The data were preprocessed using:

- Bandpass filtering: **7–35 Hz**
- Temporal window: **2–5 seconds**
- Electrode system: **10-20 system**
- Channels: **60 electrodes**


## 📁 Project Structure

- `EEG_MI.ipynb` – Main notebook (Google Colab)
- `requirements.txt` – Python dependencies
- `README.md` – This file
- `LICENSE` – MIT License for reuse

## 📦 Required Libraries

| Library        | Purpose                                      |
|----------------|----------------------------------------------|
| `mne`          | EEG signal processing                        |
| `numpy`        | Numerical computations                       |
| `pandas`       | Data manipulation                            |
| `matplotlib`   | Visualizations                               |
| `scikit-learn` | Machine learning     |

