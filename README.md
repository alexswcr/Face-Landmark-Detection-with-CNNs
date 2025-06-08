### Colab Notebooks
- Part 1: <a href="https://colab.research.google.com/github/alexswcr/Face-Landmark-Detection-with-CNNs/blob/Add-Files/Task_2_Face_Alignment_Pt_1.ipynb"><img data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" src="https://camo.githubusercontent.com/96889048f8a9014fdeba2a891f97150c6aac6e723f5190236b10215a97ed41f3/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667"></a>
- Part 2: <a href="https://colab.research.google.com/github/alexswcr/Face-Landmark-Detection-with-CNNs/blob/Add-Files/Task_2_Face_Alignment_Pt_2.ipynb"><img data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" src="https://camo.githubusercontent.com/96889048f8a9014fdeba2a891f97150c6aac6e723f5190236b10215a97ed41f3/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667"></a>
- Part 3: <a href="https://colab.research.google.com/github/alexswcr/Face-Landmark-Detection-with-CNNs/blob/Add-Files/Task_2_Face_Alignment_Pt_3.ipynb"><img data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" src="https://camo.githubusercontent.com/96889048f8a9014fdeba2a891f97150c6aac6e723f5190236b10215a97ed41f3/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667"></a>
# Face-Landmark-Detection-with-CNNs

This repository contains the multiple python notebooks containing the code used to create CNN models to locate facial landmarks. Furthermore, the notebooks contain three different CNN models (they differ in number of feature layers and network) with the intention of comparing the performance of these models. The three trained models that were evaluated in my report can be found in the *Models* folder. This was done as part of my coursework for Applied Machine Learning (Year 2 Semester 2).

## How to Run
There are three separate python notebooks designed to be run on Google Colab. It was split up due to Colab running out of RAM when consecutively running all code blocks.
- Part 1 consists of data augmentation and preprocessing
- Part 2 consists of designing, compiling and training the models
- Part 3 consists of evaluating the performance of the three models

In each python notebook, the user's google drive is mounted. As files are saved and loaded using my google drive directory, they will likely *error* when opened with another google drive account. To run the code yourself, please change the file locations to reflect where you wish to save and load files in your google drive.

