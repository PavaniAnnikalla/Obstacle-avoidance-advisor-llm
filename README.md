# 🚗 Obstacle Avoidance Advisor using LLMs

A real-time road scene analysis system that uses **OpenCV** for video frame extraction 
and the **Groq LLM API (LLaMA Vision)** to generate intelligent, context-aware 
navigation guidance from driving footage.

## 🔍 What It Does

- Uploads any driving video directly in Google Colab
- Extracts frames at regular intervals using **OpenCV**
- Encodes each frame to base64 and sends it to **Groq's vision LLM**
- Generates real-time advice per frame:
  - Identifies vehicles, barriers, and road hazards
  - Recommends lane discipline and safe following distance
  - Suggests collision avoidance actions
- Displays extracted frames inline with LLM advice
- Exports a full **obstacle_report.txt** with timestamped analysis

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| OpenCV (`opencv-python-headless`) | Video processing & frame extraction |
| Groq API | Vision-Language Model inference |
| Pillow (PIL) | Image handling |
| Google Colab | Runtime environment |

## 🚀 How to Run

1. Open the notebook in **Google Colab**
2. Run Cell 1 to install dependencies:
