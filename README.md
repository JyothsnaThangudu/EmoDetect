# VisageDetect

**VisageDetect** is an end-to-end computer vision project that integrates machine learning for face and emotion recognition. This web application allows users to upload a photo, processes the image, and detects emotions using deep learning techniques. The system is built using the Django framework and incorporates several advanced machine learning algorithms.

## Features

- **Photo Upload**: Users can upload their photos to detect emotions.
- **Face and Emotion Recognition**: Utilizes deep neural networks and image processing techniques to accurately detect faces and analyze emotions such as happiness, sadness, anger, surprise, and more.
- **Machine Learning Integration**: The system leverages multiple machine learning models for emotion detection, including Logistic Regression, Support Vector Machines (SVM), and Random Forest classifiers.
- **End-to-End System**: Complete pipeline from image upload to emotion detection and result display.

## Technology Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Django (Python) - MVT Framework
- **Image Processing**: OpenCV
- **Machine Learning Models**: Logistic Regression, Support Vector Machines, Random Forest
- **Deep Learning**: Deep Neural Networks for face and emotion recognition
- **Database**: SQLite (or any preferred database)
- **Deployment**: Deployed on (mention your hosting platform here)

## Installation and Setup

1. **Clone the repository**:
   git clone https://github.com/JyothsnaThangudu/VisageDetect.git
   cd VisageDetect
2. **Create and activate a virtual environment**:
    python3 -m venv venv
    source venv/bin/activate

3. **Install dependencies**:
    pip install -r requirements.txt

4. **Run database migrations**:
    python manage.py migrate
5. **Create a superuser (for admin purposes)**:
    python manage.py createsuperuser

6. **Start the development server**:
    python manage.py runserver

7. **Access the system**:
    Go to http://127.0.0.1:8000/ to access the application.

**Machine Learning Workflow**
 - Image Processing: The uploaded images are processed using OpenCV to detect faces and prepare them for emotion analysis.
 - Model Training: Machine learning models, including Logistic Regression, SVM, and Random Forest, were trained on large emotion datasets.
 - Deep Learning: A deep neural network is used for facial emotion recognition, improving accuracy and robustness across different images.

**Future Improvements**
 - Advanced Models: Further enhance accuracy using advanced deep learning models like Convolutional Neural Networks (CNNs).
 - User Authentication: Enable user login and history tracking for previous emotion detections.
 - API Integration: Develop an API for third-party developers to integrate face and emotion recognition into their applications.

**Contributing**
   Contributions, issues, and feature requests are welcome! Feel free to open a pull request or submit an issue.
    
