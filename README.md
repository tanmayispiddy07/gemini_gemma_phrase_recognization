# Phrase Recognition with Gemini Flash 

An advanced project in phrase generation that explores innovative, non-transformer approaches for phrase recognition. This repository details the development and fine-tuning of the **Phase-Generator-7** model, based on the Gemini-Flash-0.01 architecture. Through this model, we achieved a remarkable performance, pushing the boundaries of traditional phrase generation and recognition.

## Project Overview

Phrase generation and recognition are essential components in natural language processing, and this project explores a unique approach beyond standard transformer models. By using the Gemini-Flash-0.01 model, we fine-tuned it into the **Phase-Generator-7**, achieving exceptional performance in classification accuracy.

## 📊 Results and Achievements

- **Model Performance**: The Phase-Generator-7 achieved a **93% accuracy** on the classification matrix, significantly outperforming traditional Transformer-based models, such as BERT, which often achieve lower accuracy rates in similar tasks.
- **Comparative Advantage**: 
  - **Higher Accuracy**: Achieved 93% compared to BERT’s performance on the same tasks.
  - **Efficiency**: The Gemini Flash model, being optimized for speed, delivers faster phrase recognition and generation, making it ideal for real-time applications like chatbots.

## 🛠️ Tech Stack

- **Model Architecture**: Gemini-Flash-0.01, fine-tuned into Phase-Generator-7
- **Training Platform**: Google AI Studio
- **Deployment**: Chatbot integrated with Google AI Studio using the Phase-Generator-7 model

## 🔧 Key Features

- **Phrase Recognition**: Identifies and classifies phrases with a high degree of accuracy, suitable for complex phrase-based NLP tasks.
- **Real-Time Response**: Ideal for applications that require quick response times, like chatbots, due to its efficient processing capabilities.
- **Enhanced Accuracy**: Outperforms transformer models by focusing on optimized architecture and effective fine-tuning techniques.

## 🤖 Model Deployment

The model was successfully deployed as an interactive chatbot using Google AI Studio, leveraging its robust infrastructure for generative AI. This chatbot demonstrates the model’s capabilities in real-time and offers an insight into how the Gemini-Flash architecture can be applied to conversational AI.

## 📂 Project Structure

- `gemini_phrase_recognition.py`: Main script for implementing the Phase-Generator-7 model and handling phrase recognition tasks.
- `data/`: Dataset used for training and testing, with relevant phrase examples for recognition.


## 🎉 Highlights

This project exemplifies a leap forward in phrase recognition by utilizing Gemini Flash over traditional transformer methods. The Phase-Generator-7 demonstrates the effectiveness of non-transformer architectures in NLP tasks, achieving higher accuracy and efficiency.
# Phrase Generation using Gemini 2bit Model

This project demonstrates the use of the **Gemini 2bit model** for phrase generation tasks. The model is trained on tweet data and evaluated on multiple test files, including a zero-shot test file. The tokenizer used is **`AutoTokenizer`** from Hugging Face.

## Gemma Overview

The goal of this project is to generate relevant phrases based on tweet data using the **Gemini 2bit model**. The model has been evaluated on two tasks:
1. **Stance Detection**: Identifying the stance of the tweet towards a given target.
2. **Target Generation**: Generating the target (or topic) based on the tweet content.

The evaluation results for both tasks have been evaluated on several datasets, showcasing the model's performance, including zero-shot tasks.

## Evaluation Metrics

The performance of the model is evaluated using the following metrics for both tasks:

### Stance Detection
- **Case 1**: 78% accuracy
- **Case 2**: 78% accuracy
- **Zero-shot**: 60% accuracy

### Target Generation
- **Case 1**: 78% accuracy
- **Case 2**: 79% accuracy
- **Zero-shot**: 64% accuracy

## Conclusion

This project demonstrates the ability of the **Gemini 2bit model** to generate relevant phrases based on tweet data. It shows strong performance across both stance detection and target generation tasks. The zero-shot evaluation results highlight the model's ability to generalize well to unseen data.

## 🤝 Contribution

We welcome contributions! Feel free to fork this repository, submit issues, or make pull requests to enhance the model or expand its applications.

---

This project showcases the potential of the Gemini Flash,Gemma model in redefining phrase generation. By breaking away from transformer-based models, we open up new possibilities in generative AI, especially for real-time applications.
