# 📊 Sentiment Analysis

A Python-based sentiment analysis project that classifies text data into positive, negative, or neutral sentiments using machine learning techniques. Built with Support Vector Machine (SVM) classifier and TF-IDF vectorization for accurate text sentiment prediction.

---

## 🚀 Features

- 🔤 **Text Preprocessing**: Advanced text cleaning and normalization
- 🤖 **SVM Classification**: Support Vector Machine with optimized parameters
- 📈 **TF-IDF Vectorization**: Efficient text-to-numerical feature conversion
- 💾 **Model Persistence**: Pre-trained models saved for quick deployment
- 🎯 **Real-time Prediction**: Fast sentiment analysis for new text inputs
- 📊 **Visualization**: Sentiment analysis results with visual insights

---

## 🛠️ Tech Stack

- **Language**: Python 3.7+
- **Machine Learning**: scikit-learn
- **Data Processing**: pandas, numpy
- **Text Processing**: TF-IDF Vectorizer
- **Model**: Support Vector Machine (SVM)
- **Serialization**: pickle

---

## 📁 Project Structure

```
Sentiment_Analysis/
├── deployment.py               # Main deployment script
├── requirements.txt            # Project dependencies
├── svm_model.pkl              # Trained SVM model
├── tfidf_vectorizer.pkl       # TF-IDF vectorizer
├── Sentiment-Analysis1.jpg.webp  # Project visualization
└── README.md                  # Documentation
```

---

## 🔧 Setup & Installation

### Prerequisites
- Python 3.7 or higher
- pip package manager

### Installation Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Pranavi1609/Sentiment_Analysis.git
   ```

2. **Navigate to project directory:**
   ```bash
   cd Sentiment_Analysis
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the sentiment analyzer:**
   ```bash
   python deployment.py
   ```

---

## 💻 Usage

### Quick Start
```bash
# Run the deployment script
python deployment.py

# Follow the prompts to input text for sentiment analysis
# Output: Sentiment classification (Positive/Negative/Neutral)
---

## 📊 Model Details

- **Algorithm**: Support Vector Machine (SVM)
- **Feature Extraction**: TF-IDF (Term Frequency-Inverse Document Frequency)
- **Text Preprocessing**: Tokenization, lowercasing, stop word removal
- **Output Classes**: Positive, Negative, Neutral
- **Model Storage**: Serialized using pickle for deployment

---

## 🎯 Applications

- **Social Media Analysis**: Monitor brand sentiment on platforms
- **Product Reviews**: Classify customer feedback
- **Market Research**: Analyze consumer opinions
- **Content Moderation**: Filter and categorize user content
- **Customer Service**: Automated sentiment detection in support tickets

---

## 📋 Dependencies

```txt
scikit-learn
pandas
numpy
nltk
matplotlib
seaborn
```

---

## 🚀 How It Works

1. **Text Input**: User provides text for analysis
2. **Preprocessing**: Text is cleaned and normalized
3. **Vectorization**: TF-IDF converts text to numerical features
4. **Classification**: SVM model predicts sentiment category
5. **Output**: Returns sentiment label with confidence

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Create a Pull Request

---

## 🐛 Troubleshooting

### Common Issues

- **Import Errors**: Ensure all dependencies are installed via `requirements.txt`
- **Model Loading**: Verify `.pkl` files are in the correct directory
- **Encoding Issues**: Use UTF-8 encoding for text inputs
- **Memory Issues**: Process large datasets in smaller batches

---

## 📈 Future Enhancements

- [ ] Multi-language sentiment analysis
- [ ] Deep learning models (LSTM, BERT)
- [ ] Web-based interface
- [ ] REST API development
- [ ] Real-time streaming analysis
- [ ] Emotion detection capabilities

---

## 🙏 Acknowledgments

- scikit-learn community for machine learning tools
- NLTK project for natural language processing
- Open source community for inspiration and resources

---

**Built with ❤️ for Natural Language Processing and Machine Learning**
