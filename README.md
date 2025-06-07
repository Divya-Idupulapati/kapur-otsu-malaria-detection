
#  Malaria Parasite Classification using Kapur & Otsu Thresholding

A computer vision and machine learning project for segmenting and classifying *Plasmodium* species in blood smear images. By integrating Kapur and Otsu multilevel thresholding strategies with a Random Forest classifier, this project aims to automate and improve the diagnostic process for malaria detection.

---

##  Table of Contents

* [Project Overview](#project-overview)
* [Problem Statement](#problem-statement)
* [Key Objectives](#key-objectives)
* [Tools & Technologies](#tools--technologies)
* [Methodology](#methodology)
* [Key Insights](#key-insights)
* [Results](#results)
* [Impact of This Research](#impact-of-this-research)
* [Authors](#authors)

---

##  Project Overview

Accurate and timely diagnosis of malaria is critical for treatment and control. This project focuses on using image segmentation and machine learning to classify different *Plasmodium* species (P. falciparum, P. malariae, P. vivax) from blood smear images. We use advanced multilevel thresholding techniques — **Kapur’s entropy-based** and **Otsu’s method** — followed by classification using the **Random Forest** algorithm.

---

##  Problem Statement

Manual diagnosis of malaria from blood smear images is time-consuming and prone to error. Automating the segmentation and classification of *Plasmodium* species can speed up diagnosis, reduce error, and make expert-level diagnostics accessible in low-resource settings.

---

##  Key Objectives

* Apply Kapur and Otsu thresholding to segment RGB blood smear images.
* Extract Histogram of Oriented Gradients (HOG) features from segmented images.
* Classify segmented images into three *Plasmodium* species using Random Forest.
* Evaluate the entropy and segmentation quality of each method.

---

## Tools & Technologies

| Tool           | Purpose                            |
| -------------- | ---------------------------------- |
| Python         | Core programming language          |
| OpenCV         | Image preprocessing & segmentation |
| scikit-learn   | Machine Learning (Random Forest)   |
| NumPy / Pandas | Data manipulation                  |
| Matplotlib     | Visualization                      |
| Kaggle Dataset | Malaria image dataset              |

---

## Methodology

###  Segmentation Techniques

* **Kapur’s Entropy Thresholding**
  Maximizes the entropy of histogram-based segmented regions.

* **Otsu’s Thresholding**
  Minimizes intra-class variance to find optimal binary segmentation.

###  Classification

* HOG feature extraction from segmented images.
* Classification using **Random Forest Classifier**.

###  Classes

* **Plasmodium falciparum**
* **Plasmodium malariae**
* **Plasmodium vivax**

---

##  Key Insights

* **Kapur’s method** is better for entropy-rich, detailed segmentation.
* **Otsu’s method** performs better for high-contrast binary segmentation.
* **Random Forest** effectively classifies species using extracted HOG features.
* Automated segmentation and classification increase accuracy and scalability.

---

##  Results

* **Input**: Raw RGB blood smear images
* **Process**:

  * Convert to grayscale
  * Segment using Kapur and Otsu
  * Extract HOG features
  * Classify with Random Forest
* **Output**: Accurate classification of malaria species
* **Evaluation**: Entropy comparison confirms Kapur’s method yields more information-rich segmentation in most cases.

---

##  Impact of This Research

This research contributes toward:

* Accelerated malaria diagnosis through automation
* Higher diagnostic accuracy using AI-based techniques
* Enabling low-cost solutions for rural healthcare
* Building a foundation for future medical imaging ML models

---

##  Authors

* **Idupulapati Divya** – Nitte Meenakshi Institute of Technology
* **Dr. Ramachandra A. C** – Nitte Meenakshi Institute of Technology

---

##  Contact

**Divya Idupulapati**

📍 San Marcos, TX

📧 [idupulapatidivya@gmail.com](mailto:idupulapatidivya@gmail.com)

🔗 [www.linkedin.com/in/divyaidupulapati](https://www.linkedin.com/in/divyaidupulapati)


