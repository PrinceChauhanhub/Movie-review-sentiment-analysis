This project uses a Recurrent Neural Network (RNN) to perform sentiment analysis on movie reviews. The model classifies reviews as positive or negative, helping understand audience feedback more effectively.

## Project Overview
- The project focuses on analyzing movie reviews to determine sentiment (positive or negative).
- It uses RNN architecture to capture sequential dependencies in text data.
- The model is trained on a labeled dataset of movie reviews.

## Features
- Text preprocessing and cleaning
- Word embedding for vector representation of words
- RNN model implementation using TensorFlow/Keras
- Accuracy and loss evaluation
- Prediction on custom movie reviews

## Technologies Used
- Python
- TensorFlow/Keras
- NumPy
- Pandas
- Matplotlib

## How to Use
1. Clone the repository:
git clone https://github.com/PrinceChauhanhub/Movie-review-sentiment-analysis.git

2. Install the required libraries:
pip install -r requirements.txt

3. Run the Streamlit app:
streamlit run app.py

## Dataset
- The model is trained on a IMDB dataset present in keras datasets of labeled movie reviews.
  
## Results
- The model achieves high accuracy in sentiment classification.

## Future Improvements
- Implementing more complex neural network architectures (e.g., LSTM, GRU)
- Experimenting with different word embedding techniques
- Expanding the dataset for better generalization

## License
This project is open-source and available under the **Public License**.

## Acknowledgments
- Inspiration from various sentiment analysis research papers
- Special thanks to open-source contributors and the machine learning community.
