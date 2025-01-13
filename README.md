# Nrog Bangla Chatbot

The **Nrog Bangla Chatbot** is a professional, data-driven conversational AI designed to provide intelligent responses to queries in Bangla. Built with Streamlit and Groq's API, this chatbot is tailored to your specific organizational needs, leveraging your own data for accurate, context-aware answers.

---

## Features

- **Custom Data Integration**: Utilizes your organization's data to provide relevant, domain-specific answers.
- **Bangla Language Support**: Fully supports user input and responses in Bangla for better accessibility.
- **Dynamic Query Matching**: Matches user queries with the most relevant information from your dataset.
- **Session-Based Interaction**: Retains chat history within a session for a smooth conversational flow.
- **Clear and Focused Responses**: Ensures concise, high-quality answers aligned with the input query.

---

## Installation

### Prerequisites
- Python 3.9 or later.
- An active Groq API Key.

### Step 1: Clone the Repository
```bash
git clone https://github.com/<your-username>/nrog-bangla-chatbot.git
cd nrog-bangla-chatbot
```

### Step 2: Install Dependencies
Install the required Python libraries:
```bash
pip install -r requirements.txt
```

### Step 3: Configure the Application
Create a `config.json` file in the root directory with the following content:
```json
{
  "GROQ_API_KEY": "your_groq_api_key"
}
```

### Step 4: Add Your Data
Place your Bangla content file (e.g., `data.txt`) in the appropriate directory and ensure the file path is correctly referenced in the code.

---

## Running the Application

Start the chatbot application using Streamlit:
```bash
streamlit run app.py
```

This will launch the chatbot interface in your default web browser.

---

## Usage

1. **Enter a Question**: Input your query in Bangla in the chat interface.
2. **Get a Response**: The chatbot retrieves and displays the most relevant answer based on your data.
3. **Review Chat History**: View previous messages in the same session for continuity.

---

## File Structure

```plaintext
nrog-bangla-chatbot/
|
├── app.py                 # Main application code
├── config.json            # API configuration file
├── requirements.txt       # Python dependencies
└── data/
    └── data.txt           # Custom Bangla dataset (update the file path in the code if needed)
```

---

## Custom Data Format

The chatbot uses a Bangla text file as its data source. Ensure the following for optimal performance:

- Use proper sentence boundaries (e.g., `।` for Bangla).
- Structure the data clearly for better chunking and query matching.

---

## Benefits

- **Tailored to Your Needs**: Provides responses specific to your organization’s domain and data.
- **User-Friendly**: Offers a native Bangla interface for better engagement with your audience.
- **Versatile**: Adaptable for various use cases, including customer support and knowledge sharing.

---

## Requirements

- **Python 3.9+**
- **Libraries**:
  - Streamlit
  - Groq
  - re
  - JSON

Install all required dependencies via the `requirements.txt` file.

---

## License

This project is licensed under the MIT License.

---

## Future Enhancements

- **Multilingual Support**: Expand the chatbot’s capability to support additional languages.
- **Advanced Query Matching**: Integrate NLP techniques for improved semantic search.
- **Analytics Dashboard**: Provide insights into user interactions and query trends.

---

Deliver intelligent, context-aware responses in Bangla with the **Nrog Bangla Chatbot** – your organization’s trusted conversational assistant.

