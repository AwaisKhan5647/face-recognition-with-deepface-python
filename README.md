# Face Recognition with DeepFace (Python)

A simple, beginner-friendly notebook demonstrating **face recognition and verification** using the [DeepFace](https://github.com/serengil/deepface) library in Python.  
This project compares two images and checks whether they belong to the same person, all in just a few lines of code.

---

## Overview

This notebook uses **DeepFace**, an open-source deep learning facial recognition framework, to perform **face verification** between two input images.


DeepFace supports several pre-trained models for facial recognition:
You can choose from pre-trained models like:
- **VGG-Face** : Deep CNN model trained on large-scale face data
- **Facenet** : Google’s face recognition model based on triplet loss
- **OpenFace** : Lightweight open-source model for embedding generation
- **DeepID** : One of the earliest deep learning models for faces
- **ArcFace** : Modern high-accuracy model for facial verification


The notebook displays both images and prints whether they are the same person or not, along with model confidence.

---

## Requirements
You only need a few Python libraries:
```bash
pip install deepface opencv-python matplotlib
