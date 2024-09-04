# NeuroCalm

NeuroCalm is a cutting-edge AI-powered application designed to help you manage stress through personalized recipe suggestions and management techniques. By analyzing your unique stress signals, NeuroCalm crafts customized recipes and provides actionable stress relief strategies.

## Features
Personalized Recipe Suggestions: Utilizes physiological signals and deep learning techniques to craft personalized recipes for stress relief.
Efficient Management Techniques: Provides management techniques based on stress levels, age, and chronic diseases.
Interactive Chatbot: Allows users to express preferences for stress-busting recipe ideas through a chatbot built with LLM.

## Technologies Used
Python 3.x: Programming language used for the project.
scikit-learn: For machine learning models (RandomForestClassifier, SelectKBest).
pandas: Data manipulation and analysis.
joblib: For model serialization.
Chatbot: Built using LLM for interactive user engagement.

## Installation
### 1. Clone the Repository
bash
Copy code
git clone https://github.com/yourusername/NeuroCalm.git
cd NeuroCalm
### 2. Create a Virtual Environment
bash
Copy code
python -m venv venv
### 3. Activate the Virtual Environment

### On Windows:

bash
Copy code
venv\Scripts\activate
On macOS/Linux:

bash
Copy code
source venv/bin/activate
### 4. Install Required Packages
bash
Copy code
pip install -r requirements.txt

## Usage
### 1. Prepare Your Data
Ensure you have the input data source in CSV format (e.g., SaYoPillow.csv) containing physiological signals for stress prediction.

### 2. Run the Application
To start the application, execute:

bash
Copy code
python main.py
Follow the prompts to input your data (e.g., age, stress level, chronic diseases).

### 3. Interact with the Chatbot
Use the chatbot interface to express your preferences for stress-busting recipe ideas.

## Data Source
Input Data: The input data should be in CSV format, with columns corresponding to physiological signals used for stress prediction.
Machine Learning Models
Stress Level Prediction: Uses RandomForestClassifier from scikit-learn.
Feature Selection: Utilizes SelectKBest with mutual_info_classif.
Contributing
### 1. Fork the Repository
Create a personal copy of the repository on GitHub.

### 2. Create a New Branch
bash
Copy code
git checkout -b feature/your-feature-name
### 3. Make Your Changes
Edit the code, documentation, or add new features.

### 4. Commit Your Changes
bash
Copy code
git add .
git commit -m "Add your message"
### 5. Push Your Changes
bash
Copy code
git push origin feature/your-feature-name
### 6. Create a Pull Request
Go to the GitHub repository and create a pull request to merge your changes.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
''' For any questions or issues, please contact:

Advika Gupta: advikag3009@gmail.com
Project Repository: https://github.com/advika30/miniproject_Neurocalm '''
