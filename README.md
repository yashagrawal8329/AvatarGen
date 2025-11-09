# 🤖 AvatarGen: AI-Powered Avatar Generator

![AvatarGen_Demo_Screenshot](assets/app_screenshot.png) 
*(Note: Replace this with an actual screenshot of your Gradio application)*

> **Position:** AI/ML Intern
> **Objective:** Design, implement, and deploy a simple AI-powered avatar creation system using generative models and a user-friendly interface.
> **Duration:** 3 Days

---

## 🌟 Project Overview

AvatarGen is a simple, web-based application designed to generate customizable digital avatars from text prompts. Built as a proof-of-concept during an AI/ML internship, this system leverages state-of-the-art **Stable Diffusion** technology to create high-quality, stylized images across various themes (e.g., Realistic, Anime, Cyberpunk).

**Key Features:**

* **Text-to-Image Generation:** Convert detailed text prompts into unique avatars.
* **Style Control:** Select from pre-defined styles using prompt templates for consistent results.
* **Batch Generation:** Generate 4 variations simultaneously using different random seeds.
* **Gradio UI:** Simple, interactive interface for easy use and sharing.

---

## 🛠️ Setup Instructions

This project is designed to run primarily in a **Google Colab** environment, which provides the necessary GPU resources.

### Prerequisites

* A **Google Account** to access Colab.
* **GPU runtime** is required for model inference (Runtime -> Change runtime type -> T4 or V100 GPU).
* The **`app.py`** script and **`requirements.txt`** must be accessible (cloned) in the Colab environment.

### 1. Clone the Repository

Open a new code cell in your Colab notebook and run the following commands to clone the project and navigate into the directory:

```bash
# Clone the project from GitHub
!git clone [https://github.com/](https://github.com/)[your-github-username]/AvatarGen.git

# Change into the project directory
%cd AvatarGen
