
# 🤖 ASSISTANT KAVYA : My First Chatbot Project

Welcome to my first venture into the world of OpenAI, Langchain, and open-source models! 🎉 I'm thrilled to share this project with you. Follow the steps below to get started:

## 🚀 How to Run This Project

1. **Clone the Repository**:
   ```bash
   git clone [repository-url]
   ```

2. **Set Up the Virtual Environment**:
   ```bash
   cd [repository-name]
   python -m venv env
   source env/bin/activate   # On Windows use `env\Scripts\activate`
   pip install -r requirements.txt
   ```

3. **Configure Environment Variables**:
   - Create a `.env` file in the project root (skip this if the file already exists).
   - Sign up for an OpenAI account at [platform.openai.com](https://platform.openai.com) and get your API key.
   - Add your API key to the `.env` file:
     ```env
     OPENAI_API_KEY="your-openai-api-key"
     ```

4. **Run the Chatbot**:
   - In a new terminal, run:
     ```bash
     streamlit run chatbot.py
     ```
   - If any dependencies are missing, follow the terminal suggestions to install them.

That's it! 🎊 I hope you enjoy exploring this project as much as I enjoyed creating it. Thanks for visiting!
