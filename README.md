🛰️ Overview

This project applies a multi-model AI pipeline for land cover classification using high-resolution satellite imagery from the DeepGlobe Land Cover Challenge.
By combining traditional ML models (MLP, Random Forest) with deep learning (CNN), the system classifies terrain types—urban, agricultural, forest, water, rangeland, and barren—with high precision.

🎯 Objectives

Compare multiple AI approaches (MLP, Random Forest, CNN) for supervised classification.

Explore unsupervised clustering (KMeans, DBSCAN) to uncover latent spatial patterns.

Evaluate performance trade-offs between interpretability, computational cost, and accuracy.

🧠 Dataset

Source: DeepGlobe Land Cover Classification Dataset

Total Tiles: 65,043 (256×256 pixels each)

Classes: Agriculture, Rangeland, Urban, Forest, Water, Barren, Unknown

| Category          | Tools                                                      |
| ----------------- | ---------------------------------------------------------- |
| **Languages**     | Python                                                     |
| **Libraries**     | scikit-learn, TensorFlow, Keras, NumPy, Pandas, Matplotlib |
| **Clustering**    | KMeans, DBSCAN                                             |
| **Visualization** | Matplotlib, Seaborn                                        |
| **Hardware**      | GPU-enabled environment for CNN training                   |

🔗 Resources

GitHub Repository: https://github.com/AditiHans/LandCover_Classification

Dataset: DeepGlobe Land Cover Classification (Kaggle)

Author: Aditi Hans
