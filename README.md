# Machine Learning: Animal Taxonomy Classification with Decision Trees

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1eM9-c1rEOkKEahnCnQypvigo1E9AghQ6?usp=sharing)

## 📌 Project Overview
This repository features a **Machine Learning** implementation designed to classify animals into seven distinct taxonomic categories (e.g., Mammals, Birds, Reptiles). Developed as part of my advanced studies and research in **Informatics Engineering at the Polytechnic Institute of Bragança (IPB)**, the project utilizes **Decision Tree Classifiers** to predict animal groups based on physical and biological characteristics.

## 🚀 Key Features
* **Multiclass Classification**: Categorizes animals into 7 groups, including Mammals, Birds, Fish, and Invertebrates.
* **Feature Engineering**: Processes 14 distinct biological markers such as presence of hair, feathers, backbone, and limb count.
* **Imbalance Handling**: Implements custom `class_weights` within the model to ensure accurate detection of minority classes like Amphibians and Insects.
* **Model Persistence**: Includes automated exporting of the trained model and class mappings using `pickle` for seamless integration.
* **Interactive CLI**: Features a built-in prediction interface that allows users to input animal traits manually to get real-time classifications.

## 🛠️ Tech Stack
* **Language**: Python
* **Primary Library**: Scikit-learn (`sklearn`)
* **Data Manipulation**: Pandas
* **Serialization**: Pickle
* **Platform**: Google Colab

## 📊 Technical Insights
The implementation focuses on optimizing a tree-based architecture for categorical biological data:
* **Tree Regularization**: Uses `max_depth=5` and `min_samples_split=10` to prevent overfitting and ensure the model generalizes well.
* **Data Partitioning**: Employs a 70/30 train-test split to rigorously validate accuracy and model performance.
* **Weighted Learning**: Specifically penalizes errors in less frequent classes (Amphibians/Insects) with a higher weight factor during the training phase.

## 📂 Repository Structure
* `trabalhoml_pedroegustavo.py`: Core script containing data loading, model training, and the interactive prediction interface.
* `model.pkl`: The serialized Decision Tree model.
* `names.pkl`: Serialized dictionary containing the mapping between numerical IDs and taxonomic names.

---

## 👤 About the Author
**Pedro Ferreira Franco**
Brazilian Researcher in Bragança | MSc Student in Informatics Engineering at **IPB** 🇵🇹

I am a software developer, researcher, and triathlete with a passion for Robotics, IoT, and Artificial Intelligence. Currently researching AI-driven calibration for industrial robots at the **Polytechnic Institute of Bragança**.

🔗 **Connect with me:**
* **LinkedIn**: [pedro-ferreira-franco](https://www.linkedin.com/in/pedro-ferreira-franco/)
* **GitHub**: [PedroFerreiraFranco](https://github.com/PedroFerreiraFranco)
* **Instagram**: [@pedrofranco_11](https://www.instagram.com/pedrofranco_11/)

---
*Developed in Bragança, Portugal.*
