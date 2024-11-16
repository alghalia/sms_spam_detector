his repository contains a Python-based SMS Spam Classifier application. The project utilizes machine learning to classify SMS messages as either "Spam" or "Not Spam." The app is built using the `scikit-learn` library for model training and `Gradio` for the user interface.

---

## Features

- **Machine Learning Model**: Trained using `TfidfVectorizer` and `LinearSVC` to classify SMS messages.
- **Gradio Interface**: A user-friendly web app for real-time predictions.
- **Public Sharing**: The app generates a public link for testing and sharing.

---

## Installation Instructions

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/sms-spam-classifier.git
   ```
2. Navigate to the project directory:
   ```
   cd sms-spam-classifier
   ```
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

---

## Usage

1. Run the Python script to launch the app:
   ```
   python sms_classifier.py
   ```
2. Access the app in your browser. If `share=True`, a public link will be provided.
3. Enter an SMS text in the input box and click **Submit** to see the classification result.

---

## File Structure

- `sms_classifier.py`: Main script for training the model and launching the Gradio app.
- `Resources/SMSSpamCollection.csv`: Dataset for training the machine learning model.
- `requirements.txt`: List of Python dependencies.
- `README.txt`: Project overview and usage instructions.

---

## Example

1. **Input**: "Congratulations! You've won a free ticket."
2. **Output**: "The text message: 'Congratulations! You've won a free ticket.', is spam."

---

## Technologies Used

- **Python**: Core programming language.
- **scikit-learn**: For model training and evaluation.
- **Gradio**: For building the user interface.

---

## Author

Developed by [Alghalia](https://github.com/alghalia).

---

## License

This project is licensed under the CU License.
