# 🌾 AgroVisionGPT

AgroVisionGPT is an end-to-end AI system that detects plant diseases from images, generates treatment recommendations using a fine-tuned LLM, and translates the solution into any language using the Google Translate API.

## 🚀 Features
- 📸 Plant disease detection (EfficientNet + transfer learning)  
- 🧠 LLM-generated treatment guidance  
- 🌍 Multilingual output (Google Translate API)  
- 🔗 Full pipeline from image → diagnosis → solution → translation  

## 📦 Project Pipeline
1. Image classification → predicted disease  
2. LLM generates treatment steps  
3. Google Translate API converts the result to any language  

## 🧠 Model Overview

```mermaid
flowchart LR
A[Leaf Image] --> B[Disease Classifier]
B --> C[LLM Treatment Generator]
C --> D[Google Translate API]
D --> E[Translated Output]
