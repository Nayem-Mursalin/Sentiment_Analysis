
# Bangla E-commerce Review Analysis Using Deep Learning 🇧🇩

A thesis project on **topic classification and sentiment analysis of Bangla e-commerce reviews** using Convolutional Neural Networks (CNN) and Recurrent Convolutional Neural Networks (RCNN).

The project explores deep learning techniques for understanding customer feedback written in Bangla, with applications in customer opinion mining and e-commerce analytics.

## 📌 Abstract

With the growth of e-commerce, customer reviews have become an important source of information for understanding customer opinions, product experiences, and service quality.

However, analyzing Bangla customer reviews presents challenges due to the language's linguistic characteristics and the limited availability of NLP resources compared with English.

This research investigates deep learning-based approaches for classifying Bangla e-commerce reviews by topic and sentiment. CNN and RCNN models are developed and evaluated to examine their performance on these classification tasks.

The experimental results show that the CNN model achieved **87% accuracy in topic classification**, while the RCNN model achieved **90% accuracy**. For sentiment classification, both models achieved **91% accuracy**.

## 🎯 Research Objectives

- Develop deep learning models for Bangla e-commerce review classification.
- Perform topic classification to identify the subject of customer reviews.
- Perform sentiment classification to analyze customer opinions.
- Compare CNN and RCNN models using classification accuracy.
- Explore the application of Bangla NLP in customer feedback analysis.

## ✨ Key Features

- **Bangla Text Classification:** Analyze customer reviews written in Bangla.
- **Topic Classification:** Categorize reviews according to their topics.
- **Sentiment Analysis:** Classify reviews based on sentiment.
- **CNN Model:** Apply convolutional neural networks to text classification.
- **RCNN Model:** Use recurrent and convolutional neural network components to learn textual patterns.
- **Model Comparison:** Evaluate and compare the performance of both architectures.
- **Experimental Evaluation:** Report classification accuracy for both tasks.

## 🧠 Methodology

The research follows a deep learning-based text classification workflow.

### 1. Dataset Preparation

- Use a dataset containing Bangla e-commerce customer reviews.
- Prepare review text and corresponding classification labels.
- Organize the data for topic and sentiment classification.

### 2. Text Preprocessing

Prepare the review text for model training using the preprocessing steps implemented in the project.

Depending on the implemented pipeline, this may include text cleaning, normalization, tokenization, and sequence preparation.

### 3. Model Development

Two deep learning architectures are investigated:

**Convolutional Neural Network (CNN)**

CNN learns local textual patterns through convolution operations and uses these patterns to predict the class of a review.

**Recurrent Convolutional Neural Network (RCNN)**

RCNN combines recurrent contextual representations with convolution-based feature extraction to capture useful information from text sequences.

### 4. Model Training

Train the CNN and RCNN models for the topic classification and sentiment classification tasks using the prepared dataset.

### 5. Evaluation and Comparison

Compare the models using classification accuracy and analyze their performance across the two tasks.

## 🏗️ System Workflow

```text
       Bangla E-commerce Reviews
                   |
                   v
          Dataset Preparation
                   |
                   v
          Text Preprocessing
                   |
                   v
       Text Representation / Encoding
                   |
          +--------+--------+
          |                 |
          v                 v
      CNN Model         RCNN Model
          |                 |
          v                 v
   Classification     Classification
          |                 |
          +--------+--------+
                   |
                   v
        Performance Evaluation
                   |
                   v
       Model Comparison and Analysis
```

## 📊 Experimental Results

The following results were reported in this project.

| Classification Task | CNN Accuracy | RCNN Accuracy |
|---|---:|---:|
| Topic Classification | 87% | 90% |
| Sentiment Classification | 91% | 91% |

### Key Findings

- RCNN achieved higher reported accuracy than CNN for topic classification.
- Both CNN and RCNN achieved the same reported accuracy for sentiment classification.
- The results demonstrate the potential of deep learning models for Bangla e-commerce review analysis.

> **Note:** Accuracy alone does not fully describe a model's performance. Further evaluation using precision, recall, F1-score, a confusion matrix, and appropriate validation or test splits would provide a more complete assessment.

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| Programming Language | Python |
| Machine Learning | Deep Learning |
| Model Architectures | CNN, RCNN |
| Research Domain | Natural Language Processing (NLP) |
| Application Domain | Bangla E-commerce Review Analysis |

Add the specific frameworks, libraries, and development tools used in the implementation to make this section complete.

## 📂 Project Structure

```text
Sentiment_Analysis/
├── README.md
├── ...                    # Dataset files
├── ...                    # Preprocessing and training code
├── ...                    # CNN and RCNN implementations
└── ...                    # Evaluation results and notebooks
```

> Update this structure to reflect the actual files and directories in the repository.

## ⚙️ Getting Started

### Prerequisites

- Python
- Git
- The Python libraries required by the project
- Access to the dataset used in the experiments

### 1. Clone the Repository

```bash
git clone https://github.com/Nayem-Mursalin/Sentiment_Analysis.git

cd Sentiment_Analysis
```

### 2. Create a Virtual Environment

```bash
python -m venv .venv
```

Activate the environment.

**macOS / Linux**

```bash
source .venv/bin/activate
```

**Windows**

```powershell
.venv\Scripts\Activate.ps1
```

### 3. Install Dependencies

If the repository includes a `requirements.txt` file:

```bash
pip install -r requirements.txt
```

Otherwise, install the dependencies specified in the project's source code or notebook.

### 4. Run the Project

Follow the execution order used in the repository:

1. Prepare or load the dataset.
2. Run the preprocessing pipeline.
3. Train or load the CNN and RCNN models.
4. Evaluate the models on the designated evaluation dataset.
5. Compare the results.

Use the actual notebook or script filenames from the repository when running these steps.

## 🔬 Research Significance

This project contributes to the exploration of deep learning approaches for Bangla natural language processing, particularly in the domain of customer feedback analysis.

Potential applications include:

- Understanding customer satisfaction and dissatisfaction.
- Identifying common topics in e-commerce reviews.
- Supporting customer feedback analysis.
- Exploring automated analysis of Bangla user-generated content.

The reported experimental results are specific to the dataset, preprocessing pipeline, and evaluation setup used in this project. They should not be interpreted as guaranteed performance on other datasets.

## ⚠️ Limitations

- Model performance may depend on dataset size, quality, and class distribution.
- Bangla spelling variations and informal writing may affect classification.
- Accuracy alone may hide differences in performance between classes.
- Generalization to other domains requires additional evaluation.
- The reported results do not establish that either model is universally superior.

## 🔮 Future Work

- Evaluate additional metrics, including precision, recall, and macro F1-score.
- Investigate transformer-based models for Bangla text classification.
- Explore pretrained multilingual and Bangla language models.
- Improve preprocessing for spelling variations and informal Bangla text.
- Evaluate model robustness on unseen datasets.
- Investigate class imbalance and error patterns.
- Develop a user-friendly interface for analyzing customer reviews.


## 🎓 Project Type

**Undergraduate Thesis Project**

Research Area: Deep Learning, Natural Language Processing, and Bangla Sentiment Analysis.

---

*Exploring deep learning techniques for understanding Bangla customer opinions and e-commerce feedback.*
