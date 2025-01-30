<div align="center">
  <img src="https://github.com/user-attachments/assets/33a064fb-9ce6-4b58-9add-61b8bed05196" alt="DeepSeek Logo">

  <h1>Chat with DeepSeek-R1 Models using Ollama on Colab</h1>

  <a href="https://colab.research.google.com/drive/1JASFR5EJdh5drBXm7XnsoLwGb8CurPfn">
    <img src="https://github.com/user-attachments/assets/753339e6-7d01-455a-907f-4fd9caa28644" alt="Open In Colab" width="200px"/>
  </a>
</div>

## 🔮 Overview

Inside the notebook, you will find:
1. **Environment Setup**: Get `Ollama` and required dependencies
2. **GPU Check**: Ensures you are running on a GPU-enabled runtime (T4 is typical in Colab)
3. **Model Download**: Choose from five different DeepSeek R1 models based on your GPU capacity
4. **Model Listing**: View currently installed models
5. **Chat Interface**: Interact with your selected DeepSeek model directly in Colab

## ⚡ Features

- **Simple Setup**: Run a few cells in sequence to have all dependencies ready
- **Multiple Model Variants**: Choose from 1.5B, 7B, 8B, 14B, or 32B parameters
- **Responsive Chat**: A convenient `prompt` cell to chat with DeepSeek-R1

## 🚀 Quick Start

1. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1JASFR5EJdh5drBXm7XnsoLwGb8CurPfn)
3. Execute cells in order

## 📊 Available Models

| Model | Size | Notes |
|-------|------|-------|
| ⚡ 1.5b | ~1.1 GB | Fastest and lightest |
| ⚡ 7b | ~4.8 GB | Balanced performance |
| ⚡ 8b | ~4.9 GB | Fast with recommended performance |
| 🐢 14b | ~9.0 GB | Slower but more capable |
| 🐢 32b | ~20 GB | Most capable, requires large GPU RAM |

> After selecting a model size, it will download (if not already present) and prepare for inference.

## 🚨 Limitations

### Runtime Disconnections and Storage
- Free Google Colab GPU runtime typically lasts up to **1 hour 20 minutes**
- Available disk storage is **~112.6 GB** (usage varies based on installed models)
- Runtime automatically disconnects after the time limit or period of inactivity

### GPU Availability
- T4 GPU is typically provided for **free-tier users**
- GPU access may be limited during high-demand periods
- Change runtime: `Runtime → Change Runtime Type → GPU → Save`

### Model Performance
- Larger models `(32b)` may not run efficiently on free Colab instances
- Recommended models for free accounts: **1.5b and 8b**

---

<div align="center">
  <strong>Happy DeepSeeking! 🚀</strong>
</div>
