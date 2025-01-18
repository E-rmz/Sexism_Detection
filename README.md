# Sexism Detection

This project, developed as part of the **Natural Language Processing (NLP)** course at the **University of Bologna (UniBo)**, addresses the problem of **sexism detection in text**. The goal is to classify whether a given text (tweets) contains or describes sexist expressions or behaviors. The project explores a range of **modern NLP techniques**, including **LSTM-based models**, **Transformer-based models**, and **Large Language Models (LLMs)**.

---

## Table of Contents
1. [Introduction](#introduction)
3. [Approaches](#approaches)
    - [LSTM-Based Models](#lstm-based-models)
    - [Transformer-Based Models](#transformer-based-models)
    - [LLM-Based Models](#llm-based-models)
7. [Contributors](#contributors)
8. [License](#license)

---

## Introduction
This project tackles the challenge of **sexism detection** using a variety of **modern NLP techniques**. It is divided into two main assignments:

1. **Assignment 1**: Focuses on **LSTM-based models** and **Transformer-based models** for sexism detection.

    **Dataset:** A small version of EXIST dataset [Github repository](https://github.com/lt-nlp-lab-unibo/nlp-course-material/tree/main/2024-2025/Assignment%201/data).


2. **Assignment 2**: Explores **Large Language Models (LLMs)** for zero-shot and few-shot prompting for sexism detection.

    **Dataset:** A small test set version of EDOS [Github repository](https://github.com/lt-nlp-lab-unibo/nlp-course-material).


---

## Approaches

### Assignment 1: LSTM and Transformer-Based Models

#### LSTM-Based Models
Three LSTM-based models were implemented:
1. **Baseline Model**: A Bidirectional LSTM with a Dense layer on top.
2. **Model 1**: Extends the Baseline by adding an additional LSTM layer.
3. **Model 2**: Uses two LSTM layers with the same hidden dimension.

#### Transformer-Based Models
The project fine-tuned the **Twitter-roBERTa-base for Hate Speech Detection** model, available on [Hugging Face](https://huggingface.co/cardiffnlp/twitter-roberta-base-hate), for sexism detection. This model leverages the power of pre-trained transformer architectures to achieve state-of-the-art performance.

---

### Assignment 2: LLM-Based Models

This part of the project focuses on **Large Language Models (LLMs)** for sexism detection using **Zero-shot** and **Few-shot** prompting.

The following LLMs were used:
- **Mistral-7B-Instruct-v0.3**
- **Phi-3.5-mini-instruct**
---

### Contributors
- **Habib Kazemi**
- **Hesam Sheikh Hassani**
- **Ehsan Ramezani**

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

