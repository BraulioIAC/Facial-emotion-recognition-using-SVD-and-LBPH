# Facial Emotion Recognition using SVD and LBPH

This project delves into the development of an algorithm aimed at recognizing and categorizing emotions based on facial patterns studied through Singular Value Decomposition (SVD) and Binary Patterns of LBP Histograms (LBPH). The primary objective is to derive a representative mask for specific emotions—such as joy or anger—referred to as the 'ghost face.' The generation of this mask involves the extraction of singular left vectors (U), singular values from the main diagonal (S), and singular right vectors (VT) from the stored image database. By selecting a specific number of singular values, it becomes possible to reconstruct the desired mask with varying levels of definition. Additionally, the LBPH of the final image is studied to identify unique characteristics for each emotion.

## Overview

The complexity of the project lies in obtaining the necessary databases for each emotion. After initial research, it was observed that existing databases contain numerous images of individuals displaying different facial expressions. However, these databases are seemingly non-standardized for the purpose of this project. To address this, the creation of a dedicated database is envisioned through a facial tracking algorithm. While not a defined objective of this project, this database creation will serve as a Machine Learning tool essential to achieving the project's goals.

The outcome of this program allows users to capture a photograph of themselves, and the implemented classifier associates it with one of the pre-trained emotions, indicating whether the person appears happy or angry.

## Key Challenges

- **Database Acquisition:** Finding or creating standardized databases for distinct emotions.
- **Facial Tracking Algorithm:** Developing a tool to create a specific database for emotion recognition.

## Installation

### Prerequisites

- Python 3.11
- Specific packages are not required.

### Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/facial-emotion-recognition.git
