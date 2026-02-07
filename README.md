## 📂 Project Structure

### 📄 Documentation & Reports

**`ML Final Project Report - Leaf Disease Detection.pdf`**
> A comprehensive technical report detailing the **hierarchical machine learning pipeline** for leaf disease detection. It covers dataset curation (OLID-I), image preprocessing methodologies, and the architecture of the **two-stage classification system** (Plant Type $\to$ Disease Status).

**`Project PPT.pdf`**
> Presentation slides outlining the problem statement, proposed solution architecture, and experimental results. Visualizes the **dual-stage model approach** and highlights key performance metrics and ablation studies achieved during testing.

---

### 💻 Jupyter Notebooks & Source Code

#### **Exploratory Analysis & Preprocessing**
**`eda-notebook.ipynb`**
> Performs **Exploratory Data Analysis (EDA)** to derive statistical insights into the dataset structure. Includes visualizations of class distributions, pixel intensity analysis, and image resolution checks to inform **preprocessing and augmentation strategies**.

**`auto-encoder.ipynb`**
> Implements an **autoencoder architecture** for unsupervised feature learning and dimensionality reduction. This module is designed to extract **latent features** and detect anomalies to support downstream supervised classification tasks.

#### **Modeling Pipeline**
**`Stage 1 Models (1).ipynb`**
> Implements the **first tier** of the hierarchical classification system, targeting the identification of **plant species** (e.g., Gourd, Tomato) from raw images. This model acts as a router, filtering data to the appropriate disease-specific classifiers.

**`Combining Data + Stage 2 Models (1).ipynb`**
> Focuses on the **second stage**: specific disease classification. Contains code for merging disparate datasets, handling class imbalance via **SMOTE/augmentation**, and training the final **disease status classifiers**.
