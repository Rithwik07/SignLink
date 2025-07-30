SignLink: Real-time British Sign Language Interpreter

SignLink is a real-time British Sign Language (BSL) recognition and translation system that leverages deep learning to improve accessibility and communication for the Deaf and Hard of Hearing community. It uses a combination of Convolutional Neural Networks (CNN) and Bi-directional LSTM (BiLSTM) to interpret hand gestures and translate them into English text.
📌 Features

Real-time sign language detection using webcam
Frame extraction and hand landmark tracking
CNN + BiLSTM model for sequence learning
Translation of gestures to English text
Jupyter Notebook-based implementation for step-by-step understanding

🧠 Technologies Used

Python 3.10+
OpenCV
MediaPipe
TensorFlow / Keras
NumPy / Pandas / Matplotlib
Jupyter Notebook

📂 Repository Structure
.
├── BSL.ipynb              # Main Jupyter Notebook
├── models/                # (Optional) Trained model weights
├── data/                  # (Optional) Dataset or sample gesture sequences
├── README.md              # Project overview
├── requirements.txt       # Python dependencies
🚀 Getting Started
1. Clone the Repository
bashgit clone https://github.com/Rithwik07/SignLink.git
cd SignLink
2. Create Virtual Environment (Optional but recommended)
bashpython -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install Dependencies
bashpip install -r requirements.txt
4. Run the Notebook
Launch the Jupyter Notebook environment:
bashjupyter notebook BSL.ipynb
Follow the cells sequentially to see the model pipeline in action.
🧪 Dataset
You can use publicly available datasets such as RWTH-BOSTON-50 or create your own using MediaPipe and OpenCV to capture custom sign sequences.
Make sure data is preprocessed into sequences of hand landmarks.
🎓 Academic Context
This project was developed as part of my Master's dissertation in Computing at the University of East London. It demonstrates how deep learning can be applied to solve real-world accessibility challenges.
📈 Future Improvements

Integration with speech synthesis (text-to-speech)
Expanded vocabulary with more complex signs
Mobile or web-based deployment
User personalization for higher accuracy


🤝 Acknowledgements

University of East London – Dissertation Support
TensorFlow and MediaPipe teams
OpenCV and Python community


Let's break the communication barrier, one sign at a time.
