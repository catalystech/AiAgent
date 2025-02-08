## Self-Hosted AI Medical Analysis Toolkit

This repository provides a  **self-hosted AI toolkit**  designed for evaluating and comparing AI-driven clinical decision support models. It enables seamless benchmarking of  **specialist AI agents**  against  **GPT-4o**  across various medical decision-making tasks, such as screening, diagnosis, and treatment recommendations.

The setup includes  **containerized services**  for AI model execution, data storage, and interactive analytics, making it an ideal platform for  **medical AI research**  and  **comparative performance analysis**.

Download my N8N + OpenWebUI integration [directly on the Open WebUI site.](https://openwebui.com/f/coleam/n8n_pipe/) (more instructions below)

![n8n.io - Screenshot](https://raw.githubusercontent.com/n8n-io/self-hosted-ai-starter-kit/main/assets/n8n-demo.gif)

----------

### 🚀 What’s Included?

✅ [**Self-hosted n8n**](https://n8n.io/) - Low-code platform with over 400
integrations and advanced AI components

✅ [**Ollama**](https://ollama.com/) - Cross-platform LLM platform to install
and run the latest local LLMs

✅ [**Open WebUI**](https://openwebui.com/) - ChatGPT-like interface to
privately interact with your local models and N8N agents

✅ [**Flowise**](https://flowiseai.com/) - No/low code AI agent
builder that pairs very well with n8n

✅ [**Qdrant**](https://qdrant.tech/) - Open-source, high performance vector
store with an comprehensive API

✅ [**PostgreSQL**](https://www.postgresql.org/) -  Workhorse of the Data
Engineering world, handles large amounts of data safely.

----------

### 📦 Installation

#### For NVIDIA GPU Users:

    git clone https://github.com/catalystech/AiAgent.git
    cd AiAgent
    docker compose --profile gpu up


#### For Apple Silicon (M1/M2) or CPU-Only Users:

    git clone https://github.com/catalystech/AiAgent.git
    cd AiAgent
    docker compose --profile cpu up 

> ⚠  **Note**: Ensure you have Docker installed and configured for GPU acceleration if applicable.

----------

### 📊 Running the Evaluation Workflow

1.  **Launch the Web Interface:**
    
    -   Open  **http://localhost:8501/**  to access the Streamlit dashboard.
2.  **Upload Clinical Data:**
    
    -   Upload anonymized clinical notes for AI analysis.
3.  **Run Model Evaluations:**
    
    -   Execute both the  **specialist AI agent**  and  **GPT-4o**  for comparative assessment.
4.  **View Analytics & Results:**
    
    -   Compare model performance across key metrics like  **accuracy, specificity, and usefulness.**

----------

### 📈 Analysis & Interpretation

-   **Automated Statistical Evaluation:**
    
    -   One-way  **ANOVA**  and  **paired t-tests**  to assess performance differences.
    -   Mean and standard deviation calculations for each evaluation metric.
-   **High-Disagreement Case Identification:**
    
    -   Highlighting cases where AI models produce  **conflicting recommendations**.
-   **Clinical Guideline Adherence Scoring:**
    
    -   Evaluating AI outputs based on structured medical guidelines.

----------

### 🛠 Customizing the AI Models

-   Modify the  **Docker Compose**  configuration to integrate custom  **LLMs**.
-   Replace  **GPT-4o**  with other  **foundation models**  like Mistral or Llama3.
-   Adjust  **vector search parameters**  to fine-tune retrieval-based AI models.

----------

### 📜 License

This project is licensed under  **Apache License 2.0**. See the  [LICENSE](LICENSE)  file for details.