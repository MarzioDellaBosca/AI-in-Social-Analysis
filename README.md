# AI in Social Analysis

# AI in Social Analysis

This is a research and demonstration project focused on the application of Artificial Intelligence to the analysis of social media comments—primarily from Facebook and YouTube. Its main purpose is to showcase how AI models can extract meaningful insights from user interactions and compare different user populations engaging with the same content across platforms. Through this analysis, the project aims to highlight patterns, contrasts, and similarities in online behavior and expression, using real-world data in a controlled, illustrative context.


## Analysis Objectives

The analyses cover a wide range of linguistic and behavioral dimensions. Specifically, we investigate:

- **Sentiment Analysis:** Assessing the emotional tone of comments (positive, negative, or neutral).
- **Zero-Shot Classification:** Classifying comments into predefined categories without the need for task-specific training data, enabling flexible and scalable annotation.
- **Language Proficiency:** Evaluating the quality, complexity, and variation in the language used by users.
- **Tone and Style Analysis:** Detecting stylistic and rhetorical patterns, such as formality, directness, or aggression.
- **Additional Features:** Depending on data availability, the analysis may also explore communicative subtleties like irony, sarcasm, and markers of implicit education or sociolectal variation.

---

## Methodology and Tools

We use pre-trained Natural Language Processing (NLP) models available via the [Hugging Face Transformers](https://huggingface.co/models) library to process, classify, and interpret user-generated text. The main models employed are:

### 1. Sentiment Analysis  
We use [`tabularisai/multilingual-sentiment-analysis`](https://huggingface.co/tabularisai/multilingual-sentiment-analysis), a multilingual model fine-tuned for sentiment classification. It effectively identifies the polarity of comments in various languages, classifying them as positive, negative, or neutral.

### 2. Zero-Shot Classification  
For category-based analysis without prior annotated data, we use [`MoritzLaurer/mDeBERTa-v3-base-mnli-fever-anli`](https://huggingface.co/MoritzLaurer/mDeBERTa-v3-base-xnli-multilingual-nli-2mil7). This powerful multilingual model enables classification based on custom labels by leveraging zero-shot learning through natural language inference (NLI).

---

This framework provides a flexible and scalable foundation for analyzing discourse across platforms and uncovering meaningful socio-linguistic insights through AI and NLP, with the support of models hosted and served via Hugging Face.




