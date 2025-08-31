# 🤖 AI Financial Advisor

> An intelligent financial advisory system that provides personalized investment advice through AI-powered voice responses.

## 🎯 Project Overview

This project creates an AI-powered financial advisor that:
- ✅ Collects user financial information through a simple form
- ✅ Processes data using Google Gemini AI for personalized advice
- ✅ **Converts recommendations to natural speech using Murf.ai**
- ✅ Delivers comprehensive financial guidance in under 2 minutes

### 🎵 Murf.ai Integration
This project leverages **Murf.ai's text-to-speech API** to transform written financial advice into engaging, natural-sounding audio responses, making financial planning accessible and user-friendly.

## 🛠️ Tech Stack

- **Workflow Engine**: n8n (No-code automation)
- **AI Engine**: Google Gemini API
- **Voice Synthesis**: **Murf.ai Text-to-Speech API** 🎤

## ✨ Key Features

### 🎙️ Voice-First Experience
- Professional voice narration powered by Murf.ai
- Multiple voice options (bn-IN-arnab featured)
- Audio length optimization (~90-120 seconds)

### 📊 Comprehensive Financial Analysis
- Emergency fund calculations
- Investment portfolio recommendations
- Insurance gap analysis
- Tax-saving strategies (Indian market focus)

### 🇮🇳 India-Specific Advice
- PPF, ELSS, NSC recommendations
- Indian tax implications (80C, LTCG)
- INR-based calculations
- Local investment products

### 🎬 Video Demo
![Workflow Demo](workflow-demo-video (1).mp4)

### 🎵 Sample Audio Output
[🎵 Listen to Sample Financial Advice](sample-financial-advice.wav)

## 🔧 Setup Instructions

### Prerequisites
- n8n installed locally or cloud instance
- API Keys:
  - Google Gemini API
  - **Murf.ai API Key** (Get from [murf.ai](https://murf.ai))

### 1. Clone Repository
```bash
git clone https://github.com/yourusername/ai-financial-advisor.git
cd ai-financial-advisor
