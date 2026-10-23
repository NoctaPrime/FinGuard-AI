# FinGuard-AI
FinGuard AI is a multi-agent compliance auditor (CrewAI + Streamlit) that eliminates LLM math hallucinations. Using a strict "Zero-Math Policy," it routes financial data through deterministic Python tools rather than LLM logic. It features a Gemini model cascade for high availability and a Human-in-the-Loop safety gate for enterprise reliability.


Setup Instructions
Option 1: Running via Google Colab (Recommended)
Open the Ziro_Project_Final.ipynb file directly in Google Colab.
Add your Gemini API Key to Colab's built-in Secrets manager (the key icon on the left sidebar) and name it GOOGLE_API_KEY.
Click Runtime > Run all.
The final cell will generate a secure ngrok public web link. Click that link to open the Streamlit dashboard in your browser.
Option 2: Running Locally
Clone this repository to your local machine using git clone [https://github.com/NoctaPrime/FinGuard-AI.git](https://github.com/NoctaPrime/FinGuard-AI.git).
Navigate to the project directory in your terminal.
Install the necessary dependencies by running pip install -r requirements.txt.
Set your Google Gemini API key as a local environment variable (e.g., export GOOGLE_API_KEY="your_api_key" on Mac/Linux or set GOOGLE_API_KEY="your_api_key" on Windows).
If you exported the project as a standard Python file, launch the interface by running streamlit run app.py.



Pitch Deck: https://docs.google.com/presentation/d/1OmNQmi5x92q43bGJYngnRQmZXNEOIJhM496E8ktj4co/edit?usp=sharing
Demo Video: https://drive.google.com/file/d/1T-mBseaC0F8I9ue1XA3ZgZMmJP5HPtWV/view?usp=sharing
