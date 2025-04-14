# Handwritten Letter and Person Recognition

This project was developed as part of the **YZV303E Deep Learning Course**. It is designed to recognize **handwritten letters** of the **Turkish alphabet** and uniquely **identify individuals** based on their handwriting styles. The system leverages deep learning techniques to not only detect characters but also use those characters as biometric indicators for person recognition.

## 📌 Project Overview

- Recognize handwritten uppercase and lowercase Turkish letters.
- Identify individuals based on their unique handwriting patterns.
- Utilize a custom-collected dataset from 56 participants.
- Apply deep learning methods for classification and recognition tasks.

## 📁 Dataset

The dataset consists of handwritten letters collected from **56 individuals** using **3 different phone cameras**. Each participant wrote all **126 letters** (uppercase and lowercase) of the Turkish alphabet.

- Each participant folder (e.g., `beyza`, `ezgi`, `zeynep`) contains subfolders numbered `1` to `56`.
- Each subfolder includes the images of handwritten letters from one person.
- Participants also provided signature consent in accordance with **KVKK (Turkish Data Protection Law)**.

📥 [Download the Dataset](https://drive.google.com/drive/folders/1x8znRCDLU_i7m5WmKqC_xjEyDXnNW3yR?usp=sharing)
![Dataset Structure](assets/dataset_structure.png)

Below are examples of how the same letter can appear differently when written by different individuals. These variations highlight the diversity in handwriting styles and the importance of a robust recognition model capable of handling such differences.

![Samples from Dataset](assets/data_sample.png)

## 🔧 Installation

Clone the repository and install the dependencies:

```bash
git clone https://github.com/beyzanurkeskin/YZV303E_TermProject_BEEB.git
cd YZV303E_TermProject_BEEB
pip install tensorflow scikit-learn keras Pillow numpy matplotlib seaborn visualkeras opencv-python joblib
