# Conversation Management and Classification

A Python-based project for managing and classifying conversations using AI-powered language models through the Groq API. This project demonstrates how to integrate with Groq's LLaMA 3.3 70B model for intelligent conversation handling and analysis.

## 🚀 Features

- **AI-Powered Conversations**: Leverage Groq's LLaMA 3.3 70B model for intelligent responses
- **Environment-Based Configuration**: Secure API key management using environment variables
- **Jupyter Notebook Interface**: Interactive development and testing environment
- **Modular Design**: Clean, reusable functions for client initialization and chat interactions

## 📋 Prerequisites

- Python 3.10 or higher
- Groq API key (sign up at [console.groq.com](https://console.groq.com))
- Virtual environment (recommended)

## 🛠️ Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/conversation-management-and-classification.git
   cd conversation-management-and-classification
   ```

2. **Create and activate a virtual environment**

   ```bash
   # Windows
   python -m venv venv
   venv\Scripts\activate

   # macOS/Linux
   python -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**
   Create a `.env` file in the project root:
   ```env
   GROQ_API_KEY=your_groq_api_key_here
   ```

## 🚀 Quick Start

1. **Launch Jupyter Notebook**

   ```bash
   jupyter notebook
   ```

2. **Open the notebook**

   - Navigate to `conversation-management-and-classification.ipynb`
   - Run all cells to see the example in action

3. **Customize your conversation**
   - Modify the `message` variable in the notebook
   - Experiment with different prompts and scenarios

### Environment Variables

| Variable       | Description       | Required |
| -------------- | ----------------- | -------- |
| `GROQ_API_KEY` | Your Groq API key | Yes      |

## 📦 Dependencies

- **openai**: OpenAI API client for Groq integration
- **python-dotenv**: Environment variable management
- **jupyter**: Interactive notebook environment

**Note**: This project is for educational and research purposes. Please ensure you comply with Groq's terms of service and usage policies when using their API.
