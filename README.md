# Graduate Admission Predictor

## Project Overview
The **Graduate Admission Predictor** is designed to help prospective students estimate their chances of being accepted into graduate programs. The project uses historical data on admissions and several regression techniques to predict admission chances based on input features like GRE scores, TOEFL scores, university ranking, CGPA, etc.

### Main Goal
The main goal is to create a predictive model that provides an accurate estimate of admission probability for a given student profile.

## Key Features
- **GRE Score**: Graduate Record Examination score.
- **TOEFL Score**: Test of English as a Foreign Language score.
- **University Rating**: University ranking on a scale of 1-5.
- **SOP**: Statement of Purpose rating.
- **LOR**: Letter of Recommendation rating.
- **CGPA**: College GPA out of 10.
- **Research**: Research experience (1 = Yes, 0 = No).

## Installation
To run this project locally, you'll need to have Python and the required libraries installed.

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/graduate-admission-predictor.git
    cd graduate-admission-predictor
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. After setting up the environment, you can run the model training and prediction scripts.
2. The script to preprocess data, train the model, and evaluate performance is `admission_predictor.py`.

   Example usage:
   ```bash
   python admission_predictor.py
