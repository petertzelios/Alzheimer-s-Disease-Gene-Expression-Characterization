# Alzheimer-s-Disease-Gene-Expression-Characterization
Intro to Genomic Information for Science &amp; Technology group project by Peter Tzelios, Lixia Chen Wu,and Valentina Bos. Explored biomarkers for Alzheimer's disease using scRNA-seq data and neural networks.


**Files Overview**:

**EDA.ipynb**

Exploratory Data Analysis (EDA) of the full scRNA-seq dataset.
Includes quality control, visualization, and global structure analysis such as:

UMAP embeddings

Cell-type distributions

Basic expression summaries

This notebook provides an overall understanding of the dataset before modeling.

**Model.ipynb**

Baseline modeling notebook using the full dataset (both males and females combined).
This serves as the primary reference model and establishes:

Data preprocessing for modeling

Neural network architecture

Training and evaluation pipeline

All subsequent models build upon this setup.

**model_female.ipynb**

Sex-specific modeling focused on female samples only.
The dataset is subset from the full data, and the same modeling pipeline is applied to:

Investigate female-specific gene expression patterns

Compare performance and biomarkers against the combined model

**model_male.ipynb**

Sex-specific modeling focused on male samples only.
Mirrors the female model pipeline but uses only male samples, enabling:

Direct comparison between male and female disease signatures

Analysis of sex-dependent model behavior

**Model_Patient.ipynb**

Patient-level modeling and analysis.
Rather than treating individual cells independently, this notebook aggregates or evaluates predictions at the patient level, allowing:

Patient-specific disease characterization

Comparison between cell-level and patient-level signals

**Trained Model Weight ad supplementary data and figures are available in https://drive.google.com/drive/folders/1YNw9oZH7ZOHviUjJHo-nN5fHRzsWqnVv with LionMail only**
