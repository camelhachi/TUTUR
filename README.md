# TUTUR
# Sign Language Translation App

## Overview
This repository hosts a Sign Language Translation App developed using Laravel for the web framework and Python for the AI components. The application aims to bridge the communication gap between sign language users and non-sign language users by providing real-time translation and interpretation.

## Features
- **Real-Time Translation**: Convert sign language gestures into text or spoken language.
- **User-Friendly Interface**: Built with Laravel to ensure a smooth and intuitive user experience.
- **AI-Driven**: Utilizes Python's machine learning and computer vision libraries to accurately detect and interpret sign language gestures.
- **Multi-Language Support**: Capable of translating sign language to multiple spoken languages.
- **Scalable and Secure**: Leveraging Laravel’s robust framework to ensure the application is scalable and secure.

## Technology Stack
### Frontend
- **HTML/CSS**: For the basic structure and styling of the application.
- **JavaScript**: Enhances interactivity and real-time updates on the user interface.
- **Vue.js**: Integrated for a dynamic and reactive user interface.

### Backend
- **Laravel**: Provides a robust and scalable framework for backend operations, including user authentication, API routes, and database management.

### AI Component
- **Python**: Used for developing the AI models that interpret sign language gestures.
  - **TensorFlow/PyTorch**: Deep learning frameworks used for training and deploying the gesture recognition models.
  - **OpenCV**: Library used for real-time computer vision tasks, including gesture detection.
  - **Flask**: Lightweight web framework for serving the AI model as an API.

### Database
- **MySQL/PostgreSQL**: For storing user data, translations, and other persistent information.

## Installation
### Prerequisites
- PHP 7.x or higher
- Composer
- Node.js
- Python 3.x
- MySQL or PostgreSQL

### Steps
1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/sign-language-app.git
    cd sign-language-app
    ```

2. **Install PHP dependencies**:
    ```sh
    composer install
    ```

3. **Install Node.js dependencies**:
    ```sh
    npm install
    ```

4. **Set up environment variables**:
    Copy the `.env.example` to `.env` and configure your database and other settings.

5. **Generate application key**:
    ```sh
    php artisan key:generate
    ```

6. **Run database migrations**:
    ```sh
    php artisan migrate
    ```

7. **Install Python dependencies**:
    Navigate to the `ai` directory and install the required Python packages:
    ```sh
    pip install -r requirements.txt
    ```

8. **Run the Laravel development server**:
    ```sh
    php artisan serve
    ```


## Usage
1. Access the application through the Laravel server (usually at `http://localhost:8000`).
2. Register or log in to start using the translation features.
3. Use the camera feature to capture sign language gestures.
4. View the translated text or hear the spoken translation.

## Contribution
We welcome contributions from the community! Please fork the repository and submit a pull request with your changes. Make sure to follow the coding standards and include appropriate tests.

### Reporting Issues
If you encounter any issues, please report them using the GitHub issue tracker. Provide as much detail as possible to help us resolve the issue quickly.

## Acknowledgements
- Special thanks to the contributors of TensorFlow, PyTorch, and OpenCV for their amazing libraries.
- Thanks to the Laravel community for their extensive documentation and support.

---

By combining the power of Laravel and Python, this application aims to make communication more accessible and inclusive for everyone.
