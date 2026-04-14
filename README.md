# Facial Emotion Recognition

**MIT Applied AI & Data Science Program — Capstone Project**

By **Kinn Coelho Julião**

🌐 **[View the paper as a web page](https://kinncj.github.io/mit-applied-ai-and-data-sience/)**

---

## Overview

This is the capstone project for the MIT Applied AI & Data Science Program. It presents a deep learning pipeline for **4-class facial expression classification** (happy, sad, surprise, neutral) from 48×48 pixel grayscale facial images.

The project explores and compares multiple architectures — from a fully connected ANN baseline through progressively deeper CNNs, transfer learning with ResNet50V2 and EfficientNetB0, to a custom complex CNN — evaluating each on a perfectly balanced test set.

## Project Files

| File | Description |
|------|-------------|
| [🌐 Paper (web)](https://kinncj.github.io/mit-applied-ai-and-data-sience/) | Full paper as a static web page |
| [📓 Capstone Notebook (HTML)](https://github.com/kinncj/mit-applied-ai-and-data-sience/blob/main/facial_emotion_recognition_capstone.html) | Full Jupyter notebook export with code, visualizations, and analysis |
| [📄 Research Paper (PDF)](https://github.com/kinncj/mit-applied-ai-and-data-sience/blob/main/facial_emotion_recognition_paper.pdf) | 8-page research paper |
| [📊 Presentation (PDF)](https://github.com/kinncj/mit-applied-ai-and-data-sience/blob/main/facial_emotion_recognition_presentation.pdf) | 13-slide presentation |

### Direct Download Links (Raw Files)

Use these links to download or share the files directly:

- 📓 **Capstone Notebook** — [Download HTML](https://raw.githubusercontent.com/kinncj/mit-applied-ai-and-data-sience/main/facial_emotion_recognition_capstone.html)
- 📄 **Research Paper** — [Download PDF](https://raw.githubusercontent.com/kinncj/mit-applied-ai-and-data-sience/main/facial_emotion_recognition_paper.pdf)
- 📊 **Presentation** — [Download PDF](https://raw.githubusercontent.com/kinncj/mit-applied-ai-and-data-sience/main/facial_emotion_recognition_presentation.pdf)

## Highlights

- **Problem:** Supervised multi-class image classification of facial emotions
- **Dataset:** Train/validation/test splits with 4 balanced classes (happy, sad, surprise, neutral)
- **Models Built & Compared:**
  - ANN Baseline (Fully Connected Network)
  - CNN Model 1 — Baseline Architecture (2 Convolutional Blocks)
  - ResNet50V2 (Transfer Learning)
  - EfficientNetB0 (Transfer Learning)
  - Complex CNN (5 Convolutional Blocks) — Final Model
- **Evaluation:** Test accuracy, per-class F1-score, and confusion matrix analysis

## License

This project is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)** — see the [LICENSE](LICENSE) file for details.
