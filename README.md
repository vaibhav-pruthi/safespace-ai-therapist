# 🧠 AI Mental Health Therapist Project
The AI Mental Health Therapist project is a comprehensive application designed to provide users with a conversational interface to interact with an AI agent trained to offer mental health support and guidance. The project leverages the power of natural language processing (NLP) and machine learning to create a personalized and empathetic experience for users. The core features of the project include a user-friendly frontend built with Streamlit, a FastAPI backend that handles API requests and integrates with the AI agent, and a sophisticated AI agent that utilizes tools from the LangChain library to process user queries and generate responses.

## 🚀 Key Features
- **Conversational Interface**: A user-friendly chat interface built with Streamlit that allows users to interact with the AI agent.
- **AI-Powered Responses**: The AI agent uses NLP and machine learning to generate personalized and empathetic responses to user queries.
- **Integration with External Services**: The project integrates with external services such as the Groq API to leverage their capabilities and provide a more comprehensive experience.
- **Configurable**: The project allows for easy configuration of API keys and other sensitive information through the `config.py` file.
- **Modular Design**: The project follows a modular design, with separate files for the frontend, backend, AI agent, and configuration, making it easy to maintain and extend.

## 🛠️ Tech Stack
- **Frontend**: Streamlit
- **Backend**: FastAPI
- **AI Agent**: LangChain library
- **Database**: Not applicable (uses external services for data storage and retrieval)
- **Build Tools**: Uvicorn for running the FastAPI server
- **AI Tools**: Groq API, LangChain tools
- **Dependencies**: Pydantic for request validation, requests for making HTTP requests

## 📦 Getting Started / Setup Instructions
### Prerequisites
- Python 3.8 or higher
- Streamlit
- FastAPI
- Uvicorn
- Pydantic
- Requests
- LangChain library

### Installation
1. Clone the repository using `git clone`.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Configure the API keys and other sensitive information in the `config.py` file.

### Running Locally
1. Run the FastAPI server using `uv run backend/main.py`.
2. Run the Streamlit frontend using ` uv run streamlit run frontend.py`.

## 📂 Project Structure
```markdown
.
├── backend
│   ├── main.py
│   ├── config.py
│   ├── ai_agent.py
│   └── ...
├── frontend.py
├── main.py
├── requirements.txt
└── ...
```



## 🤝 Contributing
Contributions are welcome! Please submit a pull request with your changes and a brief description of what you've added or modified.

## 📝 License
This project is licensed under the MIT License.

## 💖 Thanks Message
We hope you find this project helpful! If you have any suggestions or ideas for improvement, please don't hesitate to reach out.
