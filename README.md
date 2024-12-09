
# Chatbot using NLP

## Overview
This is a chatbot that executes a project using NLP techniques. The bot uses intent identification to give correct responses to the users at appropriate times, using a set of predefined patterns with their responses. This employs `nltk` for the processing of natural language and `scikit-learn` for machine learning, as well as `streamlit` in order to build an interactive web interface.

---

## Features
-It understands different user intents like greetings, goodbyes, thankfulness, and so on.
- Provides relevant responses based on user input.
-Maintain a conversation history that can be reviewed by the user.
-Built using Python, it utilizes popular libraries in NLP and machine learning.

---

## Technologies Used
- **Python**
- **NLTK**
- **Scikit-learn**
- **Streamlit**
- **JSON** for intents data

---

## Installation

### 1. Clone the Repository
```bash
git clone <repository-url>
cd <repository-directory>
```

### 2. Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Required Packages
```bash
pip install -r requirements.txt
```

### 4. Download NLTK Data
```python
import nltk
nltk.download('punkt')
```

---

## Usage
To run the chatbot application, execute the following command:
```bash
streamlit run app.py
```

Once the application is running you can interact with the chatbot through the web interface. Type your message into the input box and press enter to see the chatbot response.

---

## Intents Data
The chatbot's behavior is defined by the `intents.json` file, which contains various tags, patterns, and responses. You can modify this file to add new intents or change existing ones.

---

## Conversation History
The chatbot saves the conversation history in a CSV file (`chat_log.csv`). You can view past interactions by selecting the "Conversation History" option in the sidebar.

---

## Contributing
Contributions to this project are welcome! If you have suggestions for improvements or features, feel free to open an issue or submit a pull request.

---

## Acknowledgments
- **NLTK** for natural language processing.
- **Scikit-learn** for machine learning algorithms.
- **Streamlit** for building the web interface.

---

Replace `<repository-url>` and `<repository-directory>` with the actual URL of your repository and the name of the directory where the project is located. Adjust any sections as necessary to better fit your project's specifics.
