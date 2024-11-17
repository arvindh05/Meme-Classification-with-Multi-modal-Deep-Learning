# Detection of Persuasion Techniques in Texts and Images

## Project Overview

### Problem Description:
The internet and social media have significantly amplified the reach of disinformation campaigns. Many of these campaigns use **memes**, which combine both **visual cues** and **text** to convey persuasive or manipulative messages. In this project, we focus on **detecting persuasion techniques** in memes, leveraging a deep learning approach to automatically classify these techniques.

This project utilizes the **SemEval-2021 Task 6** dataset, which includes memes annotated with 22 possible propaganda techniques. The task involves identifying which of these techniques are present in a given meme, considering both the **text** and **image** data.

### Task Description:
- **Main Task**: Given a meme, identify which techniques (out of **22 possible ones**) are used in the meme. This is a **multi-label classification** problem, where the model must predict multiple labels for each meme.
- **Enhancement Task**: In addition to the main task, the enhancement requires identifying the span(s) of text in the meme that correspond to each technique. This is a **multi-label sequence tagging** task, which is an advanced version of **Named Entity Recognition (NER)**.

### Warning:
This project contains meme examples and wording that might be offensive to some readers. If you are concerned, please skip this project and attempt the other option.

## Models Used
- **DistilBERT**: For textual feature extraction.
- **ResNet50**: For image processing.

## Key Metrics
- **Accuracy**: 87.5%
- **Precision**: 0.84 (average)
- **Recall**: 0.78 (average)
- **F1 Score**: 0.81 (average)
- **AUC**: 0.5178

## Requirements
- Python 3.x
- TensorFlow
- Keras
- Matplotlib
- NumPy
- Pandas

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/meme-classification-with-Multi-modal-Deep-Learning.git




## Author

Arvindh Bharadwaj Venkatesan

Running the Code:

1. Open Jupyter Notebook in your terminal or command prompt:

    ```bash
    jupyter notebook
    ```

2. Navigate to the file `MemeClassification.ipynb` in the Jupyter interface.

3. Open the notebook and select "Cell" > "Run All" from the menu to execute all cells.
