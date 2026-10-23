# FinGuard-AI
FinGuard AI is a multi-agent compliance auditor (CrewAI + Streamlit) that eliminates LLM math hallucinations. Using a strict "Zero-Math Policy," it routes financial data through deterministic Python tools rather than LLM logic. It features a Gemini model cascade for high availability and a Human-in-the-Loop safety gate for enterprise reliability.


## Setup Instructions & Evaluation Guide

**Option 1: Running via Google Colab (Recommended for Judges)**
1. Open `Ziro_Project_Final.ipynb` in Google Colab.
2. Click the **Key icon (Secrets)** on the left sidebar.
3. Add a new secret named `GEMINI_API_KEY` and paste your Gemini API key. **Toggle "Notebook access" ON.**
4. Add a second secret named `NGROK_AUTH_TOKEN` and paste your ngrok authtoken. **Toggle "Notebook access" ON.**
5. Click **Runtime > Run all**. The final cell will generate a secure public web link to view the Streamlit dashboard.

**Option 2: Running Locally**
1. Clone this repository: `git clone https://github.com/NoctaPrime/FinGuard-AI.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Create a `.streamlit/secrets.toml` file in the project directory and add your Gemini API key:
   `GEMINI_API_KEY = "your_api_key_here"`
4. Run the application: `streamlit run ziro_project_final.py`
##

Pitch Deck: https://docs.google.com/presentation/d/1OmNQmi5x92q43bGJYngnRQmZXNEOIJhM496E8ktj4co/edit?usp=sharing
Demo Video: https://drive.google.com/file/d/1T-mBseaC0F8I9ue1XA3ZgZMmJP5HPtWV/view?usp=sharing
