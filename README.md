# Neural-Bag-of-Words-Sentiment-Analysis
Neural Bag of Words (NBoW) sentiment analysis using PyTorch. Explores text classification, word embeddings, model evaluation, and trustworthy AI, achieving 86% validation accuracy while examining bias, contextual limitations, and responsible AI applications.

# Neural Bag of Words (NBoW) | Sentiment Analysis

## Project Overview

This project explores Natural Language Processing (NLP) through
the implementation of a Neural Bag of Words (NBoW) model for
binary sentiment classification.

The model processes movie reviews and predicts whether the
expressed sentiment is positive or negative.

Beyond model performance, the project examines trustworthy
AI considerations, including data bias, contextual understanding,
model reliability, and ethical limitations.

## Research Objectives

- Develop a neural network for text sentiment classification.
- Implement tokenization and vocabulary construction.
- Explore word embeddings and mean pooling.
- Evaluate model performance using training and validation data.
- Investigate trustworthy AI challenges in sentiment analysis.
- Examine the limitations of interpreting emotional distress
  through automated text classification.

## Technologies & Concepts

**Programming:** Python

**Framework:** PyTorch

**Artificial Intelligence:**
- Natural Language Processing (NLP)
- Neural Networks
- Word Embeddings
- Sentiment Classification
- Supervised Learning

**Machine Learning Techniques:**
- Tokenization
- Vocabulary Construction
- Mean Pooling
- Cross-Entropy Loss
- Backpropagation
- Model Evaluation

**Trustworthy AI:**
- Data Quality & Bias
- Model Reliability
- Generalization
- Contextual Understanding
- Ethical AI

## Model Architecture

The Neural Bag of Words model uses:

1. Tokenization to convert text into individual words.
2. Vocabulary construction to map words to numerical IDs.
3. An embedding layer representing each word using
   a 300-dimensional vector.
4. Mean pooling to combine word representations.
5. A linear layer to classify sentiment as positive or negative.

## Dataset

The project uses movie review data for binary
sentiment classification.

| Dataset | Number of Reviews |
|---------|------------------:|
| Training | 18,750 |
| Validation | 6,250 |
| Testing | 25,000 |

## Model Performance

The model was trained for 10 epochs.

| Metric | Result |
|--------|--------|
| Training Accuracy | 90.7% |
| Validation Accuracy | 86.0% |
| Training Loss | 0.285 |
| Validation Loss | 0.357 |
| Vocabulary Size | 38,428 |
| Model Parameters | 11,529,002 |

These results demonstrate the model's ability to learn
sentiment-related patterns in text.

The reported accuracy is validation accuracy, not an
independently reported test-set accuracy.

## Trustworthy AI Considerations

The project examines several limitations of automated
sentiment analysis:

**Data Bias:**
Training data may not represent different communication
styles, cultural expressions, or emotional contexts.

**Loss of Context:**
NBoW ignores word order, making it difficult to distinguish
phrases such as "good" and "not good."

**Human Emotional Complexity:**
Sarcasm, humor, metaphors, and indirect expressions of
distress may be misinterpreted.

**Model Reliability:**
Incorrect sentiment predictions can create risks when
automated systems are applied to sensitive situations.

This model is a sentiment classification research prototype,
not a clinically validated mental health assessment tool.

## Project Documentation

The repository includes:

- Research report detailing methodology, implementation,
  challenges, and experimental results.
- PowerPoint presentation explaining the project,
  architecture, and research findings.

## Team & Contributions

Nathaniel Osborn
- Model coding and implementation.

Popy Halder
- PowerPoint presentation and communication of
  research findings.

Dayvon King
- Project report development and documentation.

## Research Significance

This project demonstrates how neural networks can process
human language while highlighting the importance of
responsible AI development.

It connects machine learning implementation with broader
considerations of transparency, reliability, bias,
and responsible technology deployment.
