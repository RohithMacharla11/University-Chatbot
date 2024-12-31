# Interactive College Information Chatbot 🎓🤖

An AI-driven chatbot designed to provide accurate and context-aware responses about SR University. This project utilizes Natural Language Processing (NLP) techniques and machine learning to offer a seamless user experience for students, parents, and university applicants.

---

## 🚀 Features
- **Intent Recognition**: Classifies user queries with ~77% accuracy using TF-IDF Vectorization and Logistic Regression.
- **Context Management**: Handles dynamic, context-aware responses for enhanced conversational quality.
- **Comprehensive Information**: Responds to queries related to:
  - Courses offered
  - Admission process
  - Hostel and canteen facilities
  - Scholarships and fees
  - College infrastructure and more.
- **Ease of Use**: 24/7 availability for instant communication.

---

## 🛠️ Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - nltk (Natural Language Toolkit) for tokenization, lemmatization, and more.
  - scikit-learn for machine learning (TF-IDF, Logistic Regression).
- **Data Storage**: JSON for intents and response mapping.


## 📂 Project Structure
 ├── SRU_DATASET.json 
### Intents file containing patterns and responses
 ├── chatbot.py 
### Main chatbot script 
├── requirements.txt 
### Python dependencies
 └── README.md 
### Project documentation


## 🧑‍💻 Getting Started

### Prerequisites
- Python 3.x
- pip (Python package manager)

### Installation
1. Clone the repository:
   git clone https://github.com/yourusername/college-info-chatbot.git
   cd college-info-chatbot

## Install the required dependencies:

pip install -r requirements.txt
## Download the necessary NLTK data:

import nltk
nltk.download('punkt')
nltk.download('wordnet')

## 📊 Accuracy
The chatbot achieves an accuracy of ~77% for intent classification.
Future improvements include the integration of deep learning models for higher accuracy.

## 🛡️ Challenges Addressed
Intent Matching: Efficient tokenization and lemmatization for better intent recognition.
Dynamic Responses: Context-aware logic to maintain conversational flow.
Scalability: Modular design for easy addition of new intents and responses.
## 🌟 Future Enhancements
Integration with advanced models (e.g., transformers) for improved NLP capabilities.
Multilingual support for a broader audience.
Deployment on messaging platforms (e.g., WhatsApp, Telegram).
## 🤝 Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any new features, bug fixes, or improvements.

## 📄 License
This project is licensed under the MIT License.

## 📞 Contact
For any inquiries or collaboration opportunities:

Email: macharlarohith111@gmail.com
