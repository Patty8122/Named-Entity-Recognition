# Named Entity Recognition (NER) for Astrophysical Data

---

## Overview

This project focuses on implementing a **Named Entity Recognition (NER)** system to analyze astrophysical datasets. The goal is to identify and extract named entities and relationships between scientific entities within the data, enabling better organization and interpretation of complex astrophysical information.

The project was applied to the **WIESP2022 dataset**, which contains astrophysical data, to enhance document structure understanding and provide meaningful insights into scientific research.

---

## Features

- Extract named entities from astrophysical datasets.
- Identify relationships between scientific entities for better data organization.
- Facilitate the interpretation of complex astrophysical documents by applying NER techniques.

---

## Technologies Used

- **Python**: Core programming language for implementation.
- **Natural Language Processing (NLP)**: Techniques for entity recognition and relationship extraction.
- **Libraries/Frameworks**:
    - `spaCy` or `NLTK` (for NER processing)
    - `pandas` (for data manipulation)
    - `scikit-learn` or other ML libraries (if machine learning models are used)

---

## Dataset

The project uses the **WIESP2022 dataset**, which contains astrophysical documents. This dataset is structured to include scientific terms, relationships, and contextual information relevant to the field of astrophysics.

---

## Usage

1. **Prepare the Dataset**:
    ### Place the WIESP2022 dataset in the appropriate directory (`content/`). The dataset is divided into four components:
      - Development Dataset: Contains 20 text fragments for model development.
      - Training Dataset: Includes 1,741 text fragments (887 from full-text sections and 854 from acknowledgment sections).
      - Testing Dataset: Contains 2,495 text fragments for evaluation.
      - Validation Dataset: Used for fine-tuning and model validation.


2. **Run the NER Script**:
      - Run the script in Univ_ner_Bilstm.ipynb

---

## Future Improvements

- Incorporate advanced machine learning models like BERT or spaCy's transformer-based pipelines for improved accuracy.
- Add support for multilingual datasets.
- Visualize entity relationships using tools like `NetworkX` or `D3.js`.

---

