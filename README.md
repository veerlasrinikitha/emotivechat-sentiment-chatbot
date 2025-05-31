# Emotivechat-sentiment-chatbot
EmotiveChat is an advanced conversational AI that combines deep learning and sentiment analysis to deliver emotionally intelligent and context-aware responses. It utilizes a hybrid neural network architecture, integrating convolutional and recurrent layers for robust emotion detection from text. Pre-processing steps like tokenization and lemmatization enhance input quality for accurate classification. Detected emotions and sentiments directly guide the chatbot’s response generation, ensuring empathetic and relevant replies. This methodology enables EmotiveChat to provide natural, engaging, and emotionally adaptive user interactions.
# Features
- Emotion Detection: Uses a BERT-based classifier to recognize 28 fine-grained emotions and map them to broader sentiment categories (positive, negative, ambiguous, neutral).
- Sentiment-Aware Responses: Generates chatbot replies tailored to the detected emotion group.
- Interactive UI: Demo interface using IPython widgets for conversational testing.
-Evaluation Tools: Includes scripts for NLP and HCI evaluation, with metrics and visualizations.
# Dataset
This project uses the [GoEmotions dataset](https://www.kaggle.com/datasets/niklassaerens/goemotions) available on Kaggle.
- **Kaggle Dataset Link:**  
  [https://www.kaggle.com/datasets/niklassaerens/goemotions](https://www.kaggle.com/datasets/niklassaerens/goemotions)
**Instructions:**
- Download the dataset from the Kaggle link above.
- Place the CSV files in the `data/` directory or update the file paths in your code as needed.
# Install dependencies
```bash
!pip install -r requirement.txt
```
# Usage
1. **Train the Emotion Model**  
   The notebook will guide you through loading data, preprocessing, and training the BERT emotion classifier.
2. **Initialize the Chatbot**  
   After training, MotiveChat is initialized with the trained model and tokenizer.
3. **Demo UI**  
   Run the provided `setup_demo_ui(chatbot)` function to interact with the chatbot in a conversational interface.
4. **Evaluation**  
   Use the included evaluation cells to assess NLP and HCI performance.


