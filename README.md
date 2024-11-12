# Decoding the Brain through Machine Learning

This repository contains materials for the workshop **"Decoding the Brain through Machine Learning"**, a hands-on introduction to using machine learning techniques for analyzing neural electrophysiological data, including local field potentials (LFPs) and spike trains. Participants will learn how to apply dimensionality reduction, clustering, and classification to identify latent patterns within high-dimensional neural data.

---

## Workshop Instructors
Lucas CS Tavares (lucastavares@neuro.ufrn.br), Rodrigo MM Santiago (rsantiago@neuro.ufrn.br)

## Workshop Overview

This workshop offers a blend of theory and practice in machine learning for neural data analysis. By the end, participants will have a foundational understanding of neural coding principles and practical skills in using Python-based tools to decode brain activity.

### Topics Covered

- **Introduction to Neural Coding and Signal Types**  
  Understand neural signal scales (macro, meso, micro), key electrophysiological data types (LFPs and spikes), and coding schemes such as rate coding and tuning curves.

- **High-Dimensional Neural Data Challenges**  
  Explore the complexities involved in handling large and complex datasets in neuroscience.

- **Machine Learning Toolkit**  
  Overview of essential tools and packages, including:
  - **Programming Languages**: Python
  - **Interactive Environments**: Jupyter Notebooks, Colab
  - **Python IDEs**: VSCode, Colab
  - **Key Libraries**: Scikit-learn, PyTorch, Pynapple

- **Dimensionality Reduction and Latent Patterns**  
  Learn methods like **PCA**, **t-SNE**, and **UMAP** for dimensionality reduction and explore latent patterns with **CEBRA**.

- **Clustering and Classification of Neural Data**  
  Dive into supervised learning methods such as logistic regression, SVMs, and random forests, and use K-means clustering for unsupervised learning. Includes case studies on behavioral decoding with real neural data.

- **Model Evaluation and Validation**  
  Understand metrics like accuracy, ROC-AUC, and F1 score, and perform cross-validation techniques (K-fold, repeated, stratified) for model validation.

---

## Getting Started

### Prerequisites

- **Python** (3.7 or higher)
- **Jupyter Notebook** or **Google Colab** for running the notebook interactively
- **Python Libraries**: Install required packages using:
  ```bash
  pip install -r requirements.txt

### Files in this Repository

- `notebooks/Decoding_the_Brain_Workshop.ipynb` - The main workshop notebook, containing theory, code exercises, and practical examples.
- `README.md` - Workshop overview and instructions.
- `requirements.txt` - List of required Python packages.

---

## Workshop Structure

1. **Introduction to Neural Coding and Signals**  
   Basics of neural data and why decoding brain signals is essential in neuroscience.

2. **Machine Learning Toolkit**  
   Brief overview of tools for data manipulation, model building, and neural analysis.

3. **Dimensionality Reduction and Latent Patterns**  
   Learn PCA, t-SNE, UMAP, and apply **CEBRA** for exploring neural patterns.

4. **Clustering and Classification**  
   Apply clustering and classification techniques to neural datasets, understanding different use cases and methods.

5. **Model Evaluation and Interpretation**  
   Learn best practices for validating models and interpreting results in the context of neural decoding.

6. **Conclusion and Future Directions**  
   Summary of key takeaways, suggestions for further analysis, and additional resources.

---


## Contributing
We welcome contributions to improve the workshop materials! If you find any issues or have suggestions, feel free to open an issue or a pull request.

## License
This workshop material is under the MIT License, so you can freely reproduce, modify and distribute it. See LICENSE for more details.

## Contact
For questions or feedback, please reach out via the GitHub Issues page, or contact the workshop organizers directly via email.

Happy learning and decoding!