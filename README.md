# Tree Species Classification using Convolutional Neural Networks (CNN)

## Author

**Vishakha Ghatole**

## Project Overview

This project focuses on building a Machine Learning model that can classify different tree species using image data. Leveraging Convolutional Neural Networks (CNN), the model learns to recognize visual patterns unique to each species, enabling automated tree identification which can assist in environmental monitoring and botanical research.

---

## Project Structure

```
Tree-Species-Classification/
├── code/
│   ├── data_preprocessing.py
│   ├── model_training.py
│   └── prediction_visualization.py
├── notebooks/
│   └── Tree_Species_Classification_Colab.ipynb
├── README.md
└── tree_species_model.h5 (Optional, if <100MB)
```

---

## Dataset Access

Due to GitHub's file size limitations, the dataset is hosted externally.

* [Download Dataset from Google Drive](https://drive.google.com/drive/folders/1yT-drQPDpXb-uOYBQM_bkZz72XWF3E5b?usp=drive_link)

> **Instructions:** Download the dataset manually or use the following command in Google Colab to automate it:

```python
!pip install -U -q gdown
!gdown --folder[ https://drive.google.com/drive/folders/your_folder_id_here](https://drive.google.com/drive/folders/1yT-drQPDpXb-uOYBQM_bkZz72XWF3E5b?usp=drive_link
```

---

## Tools & Technologies Used

* Python
* TensorFlow / Keras
* Google Colab
* OpenCV
* Matplotlib / Seaborn
* ImageDataGenerator (for augmentation)

---

## Problem Statement

Manual identification of tree species is labor-intensive and prone to inaccuracies. An automated solution using AI can streamline this process, providing rapid and reliable species identification based on image data.

---

## Methodology

1. **Dataset Preparation:**

   * Organized images in folders per species.
   * Cleaned corrupted images and visualized class distributions.
2. **Data Preprocessing:**

   * Rescaling, augmentation (rotation, zoom, brightness adjustment).
3. **Model Building:**

   * Built a CNN model using Keras with Conv2D, MaxPooling, BatchNormalization, Dropout layers.
4. **Training & Evaluation:**

   * Trained on 80% of data, validated on 20%.
   * Visualized Accuracy/Loss plots to evaluate model performance.
5. **Predictions Visualization:**

   * Created grid of sample images showing Actual vs Predicted labels.
6. **Model Saving:**

   * Saved trained model as `.h5` for future deployment.

---

## Results

* Achieved Validation Accuracy of **88%** after training.
* Model effectively classified tree species with high precision.
* Visualization of sample predictions showcased model's ability to generalize.

---

## Future Enhancements

* Expand dataset with more diverse species images.
* Implement Transfer Learning (e.g., MobileNetV2, ResNet50) for higher accuracy.
* Deploy as a web/mobile app using Streamlit or Flask.

---

## Acknowledgements

* Dataset Source: [Vidit Gandhi - Tree Species Identification Dataset on Kaggle](https://www.kaggle.com/datasets/viditgandhi/tree-species-identification-dataset)
* Freepik.com for design templates.

---

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/yourusername/Tree-Species-Classification.git
```

2. Open the `Tree_Species_Classification_Colab.ipynb` in Google Colab.
3. Download the dataset using the provided Google Drive link.
4. Run the notebook cells sequentially to train and evaluate the model.
5. View results and visualizations.

---

## Commit Message Guidelines

* Initial commit
* Added data preprocessing script
* Added CNN model training script
* Added prediction visualization script
* Uploaded Colab notebook for full workflow
* Updated README with dataset link
* Saved trained model (.h5)
* Finalized project structure and documentation

---

## Contact

For any queries, reach out to:

* Vishakha Ghatole
* Contact: vishakhaghatole27@gmail.com
---

*This project was developed as part of an AI & ML Virtual Internship.*
