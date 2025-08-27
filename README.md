# South-Asian-Sounds_Audio-Classification


This repository contains the code used in the research paper **"South Asian Sounds: Audio Classification"** published at C3IT 2024.  
The project focuses on classifying South Asian urban and cultural sounds using **Mel-Frequency Cepstral Coefficients (MFCCs)** and a **1D Convolutional Neural Network (1D-CNN)**.

---

## 📌 Key Highlights

- Preprocessing and segmentation of audio recordings into standardized 4-second clips.  
- Feature extraction using **MFCCs** to capture spectral characteristics of sounds.  
- Classification using **1D-CNN (SAS-CNN)** and baseline models like ResNet50V2.  
- Evaluated on both **self-collected SAS-KIIT dataset** and **UrbanSound8K dataset**.  
- Achieved high accuracy for urban sound classification:
  - SAS-KIIT: 99.78% (10-fold cross-validation)
  - UrbanSound8K: 94.26% (10-fold cross-validation)

---

## 🏆 Contribution

- Proposed a robust audio classification pipeline for **South Asian urban sounds**.  
- Introduced a **new dataset (SAS-KIIT)** for community use.  
- Demonstrated the effectiveness of combining MFCC features with a 1D-CNN model for multi-class sound recognition.  
- Performance evaluated across self-collected and benchmark datasets.

---

## 📖 Paper & Dataset Links

- **Published Paper**: [IEEE Xplore](https://ieeexplore.ieee.org/document/10829485)  
- **Dataset (SAS-KIIT)**: [https://sas-kiit.netlify.app/](https://sas-kiit.netlify.app/)

---

## 🛠️ Code

The repository contains Python scripts for:

- Audio preprocessing and feature extraction (MFCCs)  
- 1D-CNN (SAS-CNN) model implementation 
- Training, evaluation, and inference on audio datasets  

> Note: This repository contains research code and is **not a deployable system**.

---

## 📊 Model Architecture Image

You can add an image of your model (e.g., SAS-CNN) like this:

```markdown
![SAS-CNN Architecture](path/to/model_graph.png)



📄 Citation

If you find this work useful, please cite the paper:

Plain Text:
R. Chatterjee, P. Bishwas, S. Chakrabarty and T. Bandyopadhyay, "South Asian Sounds: Audio Classification," 2024 4th International Conference on Computer, Communication, Control & Information Technology (C3IT), Hooghly, India, 2024, pp. 1-6, doi: 10.1109/C3IT60531.2024.10829485. 
keywords: {Translation; Pollution; Smart cities; Biological system modeling; Surveillance; Noise; Urban planning; Feature extraction; Rail transportation; Mel frequency cepstral coefficient; Audio classification; CNN; MFCC; Sound recognition}

BibTeX (click to copy):

**BibTeX (expand and copy):**

<details>
  <summary>Click to expand BibTeX</summary>

```bibtex
@INPROCEEDINGS{10829485,
  author={Chatterjee, Rajdeep and Bishwas, Pappu and Chakrabarty, Sudip and Bandyopadhyay, Tathagata},
  booktitle={2024 4th International Conference on Computer, Communication, Control & Information Technology (C3IT)}, 
  title={South Asian Sounds: Audio Classification}, 
  year={2024},
  volume={},
  number={},
  pages={1-6},
  keywords={Translation; Pollution; Smart cities; Biological system modeling; Surveillance; Noise; Urban planning; Feature extraction; Rail transportation; Mel frequency cepstral coefficient; Audio classification; CNN; MFCC; Sound recognition},
  doi={10.1109/C3IT60531.2024.10829485}
}
</details> ```
