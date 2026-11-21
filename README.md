# Machine Learning: Animal Taxonomy Classification with Decision Trees

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1eM9-c1rEOkKEahnCnQypvigo1E9AghQ6?usp=sharing)

## 📌 Project Overview
This repository features a **Machine Learning** model that classifies animals into seven taxonomic groups (Mammals, Birds, Reptiles, Fish, Amphibians, Insects and Invertebrates). Developed as a pair project during my Master's in Informatics at the **Polytechnic University of Bragança (IPB)**, it uses a **Decision Tree Classifier** to predict an animal's group from its physical and biological characteristics.

## 🚀 Key Features
* **Multiclass Classification**: Predicts one of 7 taxonomic groups.
* **Biological Features**: Uses 14 input attributes, such as hair, feathers, backbone, number of legs and whether the animal is aquatic.
* **Imbalance Handling**: Applies custom `class_weight` values to improve detection of minority classes (Amphibians, Insects and Invertebrates).
* **Model Persistence**: Exports the trained model and class mapping with `pickle` for reuse.
* **Interactive CLI**: Lets users enter an animal's traits and get a prediction in real time.

## 🛠️ Tech Stack
* **Language**: Python
* **Primary Library**: Scikit-learn (`sklearn`)
* **Data Manipulation**: Pandas
* **Serialization**: Pickle
* **Platform**: Google Colab

## 📊 Technical Insights
* **Tree Regularization**: `max_depth=5` and `min_samples_split=10` limit tree growth to reduce overfitting.
* **Data Partitioning**: A 70/30 train-test split is used to evaluate accuracy on unseen data.
* **Weighted Learning**: Minority classes receive double weight during training, so errors on them are penalized more.

## 📂 Repository Structure
* `trabalhoml_pedroegustavo.py`: Data loading, training, evaluation and the interactive prediction interface.
* `model.pkl`: The serialized Decision Tree model.
* `names.pkl`: Mapping between numeric IDs and taxonomic group names.

## 🤝 Contributors
* **Pedro Ferreira Franco**
* **Gustavo** — co-author

---

## 👤 About the Author
**Pedro Ferreira Franco**
Full Stack Developer | MSc Student in Informatics at the **Polytechnic University of Bragança (IPB)** 🇵🇹

I am a software developer, researcher and triathlete with a passion for Robotics, IoT and Artificial Intelligence. My Master's research focuses on anomaly detection for a Universal Robots UR3 industrial robot.

🔗 **Connect with me:**
* **Portfolio**: [pedroffranco.com](https://www.pedroffranco.com)
* **LinkedIn**: [pedro-ferreira-franco](https://www.linkedin.com/in/pedro-ferreira-franco/)
* **GitHub**: [PedroFerreiraFranco](https://github.com/PedroFerreiraFranco)
* **Instagram**: [@pedrofranco_11](https://www.instagram.com/pedrofranco_11/)

---
*Developed in Machado, Brazil.*
