# <p align="center"> <b>💻 LLM Evaluation Dashboard 📈</b> </p>

<p align="center"> <img width="1500" img height="500" src="https://github.com/SouravD-Me/LLM-Evaluation-Dashboard/blob/main/LLM%20Evaluation%20Dashboard.png"> </p> 
<p align="center"> <em>🌟 An interactive dashboard for benchmarking and visualizing the performance of large language models across several datasets. 🌟</em> </p>

<p align="center"> <a href="https://github.com/Sourav-Das1996/llm_evaluation_dashboard/blob/main/LICENSE"> <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="MIT License"> </a> 
    <a href="https://github.com/SouravD-Me/LLM-Evaluation-Dashboard"> <img src="https://img.shields.io/github/issues-pr/Sourav-Das1996/llm_evaluation_dashboard.svg" alt="Pull Requests"> </a> 
    <a href="https://github.com/SouravD-Me/LLM-Evaluation-Dashboard"> <img src="https://img.shields.io/github/stars/Sourav-Das1996/llm_evaluation_dashboard.svg" alt="Stars"> </a> 
    <a href="https://github.com/SouravD-Me/LLM-Evaluation-Dashboard"> <img src="https://img.shields.io/github/forks/Sourav-Das1996/llm_evaluation_dashboard.svg" alt="Forks"> </a> </p> 
    
<p align="center">
    <a href="## key-features">Key Features</a> •
    <a href="## demo">Demo</a> •
    <a href="## installation">Installation</a> •
    <a href="## usage">Usage</a> •
    <a href="## contributing">Contributing</a> •
    <a href="## license">License</a>
</p>

## 🟡 Key Features: ✨

    🏃‍♂️ Multi-process benchmarking for faster evaluation of multiple models,
    📊 Interactive visualizations for model performance metrics,
    🔢 Numerical summary statistics for each model,
        🔍 Average generation time,
        🔍 Token length,
        🔍 Proportionality between token and generation,
        🔍 Runtime complexity of each model,
    🌈 Customizable selection of models, datasets, and token length range,
    🎨 Polished UI with a dark-themed Bootstrap style,
    🌐 Cross-platform compatibility with Dash.

## Corpora: 📑 

The evaluation is done on GLUE benchmark datasets: 𝗚𝗟𝗨𝗘, 𝗦𝗦𝗧𝟮, and 𝗬𝗲𝗹𝗽 𝗣𝗼𝗹𝗮𝗿𝗶𝘁𝘆.

## 🟡 Limitations: ❗

🔶 Why haven't I used more recent SoTA models like Llama-2, Mistral, MPT, Phi-2, XGLM, and others?

<p align="justify">
<b>1.</b> The entire dashboard is developed and run from my laptop (i7 12th Gen + 24 GB RAM + NVIDIA RTX 3060 - 6GB GDDR6) using VS Code (with NVIDIA Nsight CUDA development framework integrated). Choosing such SoTA models would crash the VSCode in my native machine. I tried to fine-tune the lower parameter versions above-mentioned models for deployment, but they were too much for my machine to handle. Also, Google Colab (or Pro and Pro+) does not allow users to open another tab or browser to display any interactive window from the current notebook session. There are workarounds with third-party authenticators like ngrock, but that did not work for my project.
</p>

<p align="justify">
<b>2.</b> For the same reason, I could not benchmark the models on standard metrics for LLM evaluations like BLEU, METEOR, ROUGE, BERTScore, or incorporate RAG-based mechanisms or fine-tuning.
</p>

## 🟡 Demo: 🎥
<p align="center"> <img src="https://github.com/SouravD-Me/LLM-Evaluation-Dashboard/blob/main/LLM%20Evaluation%20-%20MiniDemo.gif" alt="Demo GIF"> </p>

## 🟡 Installation: 🚀

### 🔶 Clone the repository:

```bash
git clone https://github.com/SouravD-Me/LLM-Evaluation-Dashboard.git
```

### 🔶 Change to the project directory:

```bash
cd llm_evaluation_dashboard
```

### 🔶 Install the required packages:

```bash
pip install -r requirements.txt
```

## 🟡 Usage: 🕹️

### 🔶 Run the application:

```bash
python app.py (LLM Evaluation - Main.ipynb)
```
    1. Open your web browser and navigate to http://localhost:8050/ to access the dashboard.
    2. Customize the models, datasets, and token length range using the interactive controls.
    3. Explore the various visualizations to analyze the performance of the selected models.

## 🟡 Contributing: 🤝

### I welcome contributions and further modifications of the project from the community! If you'd like to contribute, please follow these steps:

    1. Fork the repository.
    2. Create a new branch for your feature or bug fix: git checkout -b my-new-feature.
    3. Make your changes and commit them: git commit -am 'Add new feature'.
    4. Push your changes to your branch: git push origin my-new-feature.
    5. Submit a pull request.

## 🟡 License: ⚖️

---

<p align="center"> This project is licensed under MIT. See the LICENSE file for more details. </p>

---

#### <p align="center"> Made with 🙏🏻 by Sourav Das • 2024 </p>
