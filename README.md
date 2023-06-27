# VirtualDoctor
The Medical Diagnosis and Recommendation System is a web application that utilizes machine learning techniques to diagnose medical conditions based on user-provided symptoms and extracted text from uploaded images. It provides recommendations for treatment and computes a health score based on the severity of the predicted diagnosis.

Medical Diagnosis and Recommendation System
This is a web application that utilizes machine learning to diagnose medical conditions based on user-provided symptoms and extracted text from uploaded images. It provides recommendations for treatment and computes a health score based on the severity of the predicted diagnosis.

Prerequisites
Before running the application, ensure that you have the following dependencies installed:

Python 3.x
Flask
NumPy
Pandas
NLTK (Natural Language Toolkit)
scikit-learn
OpenCV (cv2)
Tesseract OCR (installed separately)
You can install the required dependencies by running the following command:

Copy code
pip install -r requirements.txt
Additionally, you need to download NLTK resources. You can do this by running the following commands in a Python shell or script:

python
Copy code
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
Getting Started
Clone the repository or download the code files.

Open a terminal or command prompt and navigate to the project directory.

Run the following command to start the application:

Copy code
python app.py
The application will start running locally at http://localhost:5000.
Usage
Access the application using a web browser at http://localhost:5000.

Upload an image containing relevant medical information or enter symptoms manually.

Click the "Get Diagnosis" button to retrieve the diagnosis, treatment recommendations, and health score based on the provided symptoms and extracted text (if any).

The application will display the diagnosis, recommendations, and health score.

Contributing
Contributions to this project are welcome. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

License
This project is licensed under the MIT License. Feel free to use and modify the code according to your needs.
