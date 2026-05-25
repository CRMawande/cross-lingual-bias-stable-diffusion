# Cross-Lingual Occupational Gender Bias in Stable Diffusion 2.1

This repository contains the code, statistical analysis scripts, datasets, and supplementary materials used for the thesis:

> **Cross-Lingual Analysis of Occupational Gender Bias in Stable Diffusion 2.1: A Comparative Study of English and Afrikaans Prompts Against South African Labour Statistics**

---

# Study Overview

This study investigates occupational gender representation in Stable Diffusion 2.1 using multilingual prompt conditions in English and Afrikaans. Generated image outputs were compared against South African labour-force distributions derived from the Quarterly Labour Force Survey (QLFS).

The study evaluates:

- occupational gender representation,
- bias amplification,
- cross-lingual variation,
- inter-annotator reliability,
- and statistical significance of observed distributions.

---

# Generated Image Dataset

Due to repository storage limitations, the complete generated image dataset is hosted separately on Google Drive:

https://drive.google.com/drive/folders/1RXFYdHKEdbp9GxGURryW3sCfO2fmo2BQ?usp=sharing

The dataset includes:
- English prompt outputs,
- Afrikaans prompt outputs,
- occupation-level generated images,
- and selected supplementary examples used in the thesis.

---

# Statistical Analysis

The repository includes implementation code for:

- descriptive statistics,
- Cohen’s Kappa inter-annotator reliability,
- chi-square goodness-of-fit testing,
- chi-square tests of independence,
- Cramér’s V effect-size calculations,
- and visualization generation.

---

# Model Information

- Model: Stable Diffusion 2.1-base
- Framework: Hugging Face Diffusers
- Language Conditions:
  - English
  - Afrikaans
- Image Resolution: 512 × 512
- Generation Environment: Python / Google Colab

---

# Reproducibility

The repository was developed to support reproducibility and transparency in multilingual generative AI bias auditing research.

The included scripts reproduce:
- image generation procedures,
- annotation processing,
- statistical testing,
- and visualization outputs reported in the thesis.

---
# License

This repository is distributed under the MIT License.
