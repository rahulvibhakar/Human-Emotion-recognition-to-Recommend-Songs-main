﻿ # 🎵 Human Emotion Recognition - To Recommand Songs based Moods

This project is designed to help explore the relationship between human emotions and music. It includes a well-structured Python script for generating a labeled music dataset based on moods, a Jupyter notebook for analysis, and a ready-to-use CSV file.

---

## 📁 Project Structure

```
├── data_moods.py            # Python script to generate a mood-based music dataset.
├── data_moods.csv           # Pre-generated dataset of songs with mood labels.
├── Human_Emotion.ipynb      # Jupyter Notebook for exploration & visualization.
└── README.md                # Project description and usage.
```

---

## 💡 Overview

The project generates a dataset of popular songs categorized by mood — such as:

- **Happy**
- **Sad**
- **Calm**
- **Energetic**

Using this dataset, you can:

✅ Train emotion detection models.  
✅ Use it for recommendation engines.  
✅ Perform data visualization on song trends by mood, year, and artist.

---

## ⚙️ How to Use

### 1️⃣ Generate the Dataset
If you want to recreate the dataset:

```bash
python data_moods.py
```
This will generate `data_moods.csv` with structured song data including:
- `name` (Song Name)
- `artist` (Artist Name)
- `year` (Release Year)
- `popularity` (Relative Popularity Score)
- `mood` (Assigned Mood)

---

### 2️⃣ Explore the Data
Open the Jupyter notebook:

```bash
jupyter notebook Human_Emotion.ipynb
```
You can visualize:
- Distribution of moods.
- Popular artists per mood.
- Release year trends.
- Song popularity analysis.

---

## 💾 Requirements

- Python 3.x
- pandas
- numpy
- jupyter

Install dependencies:

```bash
pip install pandas numpy jupyter
```

---

## 💖 Credits

- Dataset manually curated and scripted.
- Inspired by music-based mood prediction and emotion detection tasks.

---

## 🚀 Future Ideas

- Extend to include audio feature extraction.
- Integration with Spotify / YouTube APIs for real-time mood-based recommendations.
- Use this data to train a mood-based song recommender.

---

If this project helps you, feel free to ⭐️ the repo!
#   H u m a n - E m o t i o n - r e c o g n i t i o n - t o - R e c o m m e n d - S o n g s - m a i n  
 #   H u m a n - E m o t i o n - r e c o g n i t i o n - t o - R e c o m m e n d - S o n g s - m a i n  
 