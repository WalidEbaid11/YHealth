 # YHealth: Smart Healthcare System Using Machine Learning

## Overview
YHealth is a web-based platform designed to predict and diagnose diseases based on symptoms reported by patients. It leverages machine learning algorithms to analyze symptom data and provide accurate disease predictions. The system connects patients with specialized doctors for further medical advice and consultation.
The project aims to develop a smart healthcare system that leverages machine learning to predict diseases based on patient symptoms. This system will enhance healthcare efficiency by enabling early disease detection and timely medical intervention. The project is focused on creating a web-based platform where users can input their symptoms, and the system will analyze the data using machine learning algorithms to predict potential diseases. Additionally, the system will facilitate online consultations, connecting patients with healthcare professionals for further guidance and treatment.


![My Image](https://github.com/WalidEbaid11/YHealth/blob/main/Screenshot/Screenshot%202024-12-03%20104854.jpg)
![My Image](https://github.com/WalidEbaid11/-YHealth-Smart-Healthcare-System-Using-ML/blob/main/Screenshot/Screenshot%202024-12-03%20104942.jpg)
![My Image](https://github.com/WalidEbaid11/-YHealth-Smart-Healthcare-System-Using-ML/blob/main/Screenshot/Screenshot%202024-12-03%20105019.jpg)
![My Image](https://github.com/WalidEbaid11/-YHealth-Smart-Healthcare-System-Using-ML/blob/main/Screenshot/Screenshot%202024-12-03%20105044.jpg)
![My Image](https://github.com/WalidEbaid11/-YHealth-Smart-Healthcare-System-Using-ML/blob/main/Screenshot/Screenshot%202024-12-03%20105100.jpg)
![My Image](https://github.com/WalidEbaid11/-YHealth-Smart-Healthcare-System-Using-ML/blob/main/Screenshot/Screenshot%202024-12-03%20105116.jpg)
![My Image](https://github.com/WalidEbaid11/-YHealth-Smart-Healthcare-System-Using-ML/blob/main/Screenshot/Screenshot%202024-12-03%20105132.jpg)


## Features
- **Disease Prediction**: Predicts diseases based on user-reported symptoms.
- **Online Consultation**: Connects users with healthcare professionals for real-time consultations.
- **User-Friendly Interface**: Intuitive design for easy navigation and symptom input.
- **Comprehensive Datasets**: Utilizes diverse datasets for accurate predictions across multiple diseases.
- **Secure and Scalable**: Ensures data privacy and scalability for a growing user base.

## Technologies Used
- **Programming Languages**: Python
- **Frameworks**: Django (Backend), Bootstrap (Frontend)
- **Machine Learning Libraries**: scikit-learn, TensorFlow
- **Data Science Tools**: Streamlit
- **Database**: PostgreSQL on Railway
- **Version Control**: Git

## Installation
## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/YHealth.git
   cd YHealth
   ```
2. **Set Up Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use \`venv\\Scripts\\activate\`
   ```
3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
4. **Database Setup**:
   - Ensure PostgreSQL is installed and running.
   - Create a new database and update the \`DATABASE_URL\` in your environment variables.
   ```bash
   createdb yhealth_db
   ```
5. **Run Migrations**:
   ```bash
   python manage.py migrate
   ```
6. **Start the Development Server**:
   ```bash
   python manage.py runserver
   ```

## Usage
1. **User Registration**:
   - Users can register and log in to the platform.
   - Users can input their symptoms to receive disease predictions.

2. **Disease Prediction**:
   - The system analyzes the input symptoms using machine learning algorithms.
   - Predicts the most likely disease and provides a confidence score.

3. **Online Consultation**:
   - Users can initiate online consultations with healthcare professionals.
   - Doctors can access patient profiles, search history, and diagnostic queries.

## Datasets
- **General Disease Dataset**: 4920 patient records with 132 symptoms and 41 disease categories.
- **Parkinson's Disease Dataset**: Data from 95 patients and 41 controls.
- **Heart Disease Dataset**: Data from 70,000 patients.
- **Diabetes Dataset**: Data from 500 diabetic patients.

## Machine Learning Models
- **Decision Tree**
- **Random Forest**
- **Gradient Boosting**
- **K-Nearest Neighbors**

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (\`git checkout -b feature-branch\`).
3. Commit your changes (\`git commit -am 'Add new feature'\`).
4. Push to the branch (\`git push origin feature-branch\`).
5. Create a new Pull Request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For more information, please contact:
- Walid Ebaid Abdel Ghaffar
- Email: walidebaid9@gmail.com

## References
- Rajalakshmi, N., et al. \"A comparative analysis of machine learning algorithms for predicting multiple diseases.\" Journal of Medical Systems 41.11 (2018): 21-36.
- Choi, J., et al. \"Development of a machine learning model for predicting multiple diseases.\" Journal of Medical Systems 41.10 (2018): 1-11.
- Chen, Y., et al. \"Transfer learning for multiple disease prediction using machine learning.\" Journal of Medical Systems 42.12 (2019): 30-38.
- Li, Z., et al. \"Deep learning for multiple disease prediction using transfer learning.\" Journal of Medical Systems 42.12 (2019): 29-37.

---
