
# 🤖 TechSaksham Chatbot

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

Welcome to the **TechSaksham Chatbot** project! This chatbot is built using **Natural Language Processing (NLP)** techniques and the **Streamlit** framework. It uses machine learning to classify intents and generate accurate responses while logging conversations for further analysis.

---

## 🌟 Features

- **Intent Recognition**: Classifies user input into predefined intents using NLP and machine learning.
- **Interactive Web UI**: Built with **Streamlit** for a smooth and user-friendly chatbot experience.
- **Conversation Logging**: Captures user inputs and chatbot responses in a `chat_log.csv` file for analysis.
- **Scalable Design**: Easily extendable for new intents, languages, or advanced AI models.

---

## 🧠 Technologies Used

- **Python**: Programming language.
- **Natural Language Toolkit (nltk)**: For tokenization and text preprocessing.
- **Scikit-learn**: Logistic Regression for intent classification.
- **Streamlit**: Framework for building a web-based interface.
- **TfidfVectorizer**: Converts text into numerical features for classification.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- Install required libraries:
   ```bash
   pip install streamlit sklearn nltk
   ```

### Steps to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/harish-3/techsaksham-chatBot.git
   cd techsaksham-chatBot
   ```

2. Ensure your `intents.json` file (containing training data) is in the project root directory.

3. Run the application:
   ```bash
   streamlit run app.py
   ```

4. Access the chatbot in your browser using the URL provided by Streamlit.

---

## 📂 Project Structure

```plaintext
.
├── app.py               # Main chatbot script
├── intents.json         # Training data for chatbot intents
├── chat_log.csv         # Logs user inputs and bot responses
├── README.md            # Project documentation
```

---

## 📊 Dataset Details

The chatbot uses `intents.json` for training, which includes:

- **Tag**: Intent of the query (e.g., "greeting", "goodbye").
- **Patterns**: Example user queries for each intent.
- **Responses**: Possible replies from the chatbot.

### Example JSON Snippet:
```json
[
    {
        "tag": "greeting",
        "patterns": ["Hi", "Hello", "Hey"],
        "responses": ["Hello! How can I assist you?", "Hi there!"]
    }
]
```

---

## 🛠️ Future Enhancements

- Add **Deep Learning** models like LSTM or Transformers for improved accuracy.
- Enable **multilingual support** for a wider audience.
- Deploy the chatbot on **cloud platforms** like AWS or Google Cloud.
- Integrate data visualization for user interactions using analytics tools.

---

## 🤝 Contributing

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/YourFeatureName
   ```
5. Open a pull request.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## ✉️ Contact

For inquiries or collaborations, feel free to reach out:

- **Email**: [harish.m3137@gmail.com](mailto:harish.m3137@gmail.com) | [harish.m3122@gmail.com](mailto:harish.m3122@gmail.com)  
- **GitHub**: [Harish M](https://github.com/harish-3/techsaksham-chatBot)  
- **LinkedIn**: [Harish M](https://www.linkedin.com/in/harish-m-59461a289/)

---
