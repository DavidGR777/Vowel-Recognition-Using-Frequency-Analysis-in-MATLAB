# 🎧 Frequency-Based Vowel Recognition in MATLAB

## 📌 Overview

This project implements a **vowel recognition system based on frequency analysis** using MATLAB. The system captures audio signals and extracts both **time-domain and frequency-domain features** to analyze and characterize vowel sounds.

The implementation focuses on the vowels:

- **/a/**
- **/i/**
- **/o/**

The system processes multiple recordings per vowel and computes relevant signal properties such as energy distribution and spectral behavior.

---

## 🎯 Objectives

- Analyze audio signals in both **time and frequency domains**
- Extract relevant features such as:
  - Signal energy
  - Duration
  - Frequency components
- Identify patterns associated with specific vowels
- Visualize signals and their spectral content

---

## ⚙️ Features

- 🎙️ Audio recording (3 samples per vowel)
- 📊 Time-domain signal visualization
- 📈 Frequency-domain analysis using FFT
- ⚡ Energy computation per signal
- 📉 Energy distribution in the **200–1200 Hz** range
- 💾 Automatic saving of recorded `.wav` files

---

## 🧠 Methodology

The system follows these steps:

1. Audio acquisition (user-recorded signals)  
2. Time-domain analysis  
3. Frequency-domain transformation (FFT)  
4. Feature extraction:
   - Energy  
   - Spectral content  
5. Visualization of results  

---

## 📂 Project Structure
