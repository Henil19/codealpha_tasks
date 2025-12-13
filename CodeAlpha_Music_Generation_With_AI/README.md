# 🎵 Music Generation with AI

This project implements an end-to-end **AI-based music generation system** using **symbolic MIDI data** and **deep learning**.  
A Recurrent Neural Network (LSTM) is trained on MIDI files to learn musical patterns and generate new music, which is then converted back to MIDI and audio formats.

---

## 🚀 Project Objectives

This project fulfills **Task 3: Music Generation with AI**, with the following goals:

- Collect and use MIDI music data (classical / instrumental)
- Preprocess MIDI files into note sequences using `music21`
- Train a deep learning model (LSTM-based RNN) to learn musical structure
- Generate new music sequences from the trained model
- Convert generated sequences into MIDI and audio (WAV/MP3)

---

## 🧠 Technologies Used

- **Python**
- **TensorFlow / Keras**
- **music21** – MIDI parsing and note extraction
- **pretty_midi** – MIDI reconstruction
- **NumPy** – numerical processing
- **Matplotlib** – training visualization
- **timidity & ffmpeg** – audio rendering

---

## 📁 Project Structure

```text
.
├── Music_Generation_With_AI.ipynb
├── requirements.txt
├── token_to_int.json
├── int_to_token.json
├── best_music_model.h5
├── generated.mid
├── generated.wav
├── generated.mp3
└── environment_versions.txt

