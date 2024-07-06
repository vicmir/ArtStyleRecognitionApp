# Art Style Recognition Web Application

## Features

- **Art Style Recognition**: Automatically classify images into different art styles using a trained deep learning model.
- **Image Augmentation**: Enhance the dataset with various image transformations for robust model training.
- **User Authentication**: Secure user registration and login system.
- **Image Upload**: Users can upload images from their PC or via URL for analysis.
- **Profile Management**: Users can manage their profiles and view the history of their uploaded images.
- **Annotations and Descriptions**: Provide detailed annotations and descriptions of the recognized art styles.

## Technology Stack

- **Backend**: Flask for web development, SQLite for database management
- **Frontend**: HTML, CSS, and JavaScript for responsive UI
- **Machine Learning**: TensorFlow and Keras for deep learning models, Pillow for image processing
- **Deployment**: Docker for containerization

## Project Structure

The project is organized as follows:
- `app/`: Contains the Flask application and all backend logic.
- `static/`: Static files including CSS, JavaScript, and images.
- `templates/`: HTML templates for rendering the web pages.
- `model/`: Pre-trained models and related scripts.
- `tests/`: Unit and functional tests for the application.
- `Dockerfile`: Instructions for containerizing the application.

## Getting Started

### Prerequisites
- Python 3.6+
- Docker (optional for containerization)

### Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/vicmir/ArtStyleRecognitionApp.git
    cd ArtStyleRecognitionApp
    ```

2. Set Up for Unix, MacOS:
   - Install modules via `VENV`:
   ```sh
   $ virtualenv env
   $ source env/bin/activate
   $ pip3 install -r requirements.txt
   ```

   - Set Up Flask Environment:
   ```sh
   $ export FLASK_APP=run.py
   $ export FLASK_ENV=development
   ```

   - Start the app:
   ```sh
   $ flask run
   ```
   
3. Set Up for Windows:
   - Install modules via `VENV`:
   ```sh
   $ virtualenv env
   $ .\env\Scripts\activate
   $ pip3 install -r requirements.txt
   ```

   - Set Up Flask Environment:
   ```sh
   $ # CMD
   $ set FLASK_APP=run.py
   $ set FLASK_ENV=development
   $
   $ # Powershell
   $ $env:FLASK_APP = ".\run.py"
   $ $env:FLASK_ENV = "development"
   ```

   - Start the app:
   ```sh
   $ flask run
   ```

4. Open your web browser and go to `http://127.0.0.1:5000`.

## Usage

- **Register/Login**: Create a new account or log in to an existing account.
- **Upload Images**: Upload images from your PC or via URL for analysis.
- **View Results**: Check the recognized art style and detailed description for each uploaded image.
- **Profile Management**: Manage your profile and view the history of analyzed images.

## Codebase

The project is coded using blueprints, app factory pattern, dual configuration profile (development and production) and an intuitive structure presented bellow:

```bash
< PROJECT ROOT >
   |
   |-- apps/
   |    |
   |    |-- home/                           # A simple app that serve HTML files
   |    |    |-- routes.py                  # Define app routes
   |    |
   |    |-- authentication/                 # Handles auth routes (login and register)
   |    |    |-- routes.py                  # Define authentication routes  
   |    |    |-- models.py                  # Defines models  
   |    |    |-- forms.py                   # Define auth forms (login and register) 
   |    |
   |    |-- static/
   |    |    |-- <css, JS, images>          # CSS files, Javascripts files
   |    |
   |    |-- templates/                      # Templates used to render pages
   |    |    |-- includes/                  # HTML chunks and components
   |    |    |    |-- navigation.html       # Top menu component
   |    |    |    |-- sidebar.html          # Sidebar component
   |    |    |    |-- footer.html           # App Footer
   |    |    |    |-- scripts.html          # Scripts common to all pages
   |    |    |
   |    |    |-- layouts/                   # Master pages
   |    |    |    |-- base-fullscreen.html  # Used by Authentication pages
   |    |    |    |-- base.html             # Used by common pages
   |    |    |
   |    |    |-- accounts/                  # Authentication pages
   |    |    |    |-- login.html            # Login page
   |    |    |    |-- register.html         # Register page
   |    |    |
   |    |    |-- home/                      # UI Kit Pages
   |    |         |-- index.html            # Index page
   |    |         |-- 404-page.html         # 404 page
   |    |         |-- *.html                # All other pages
   |    |    
   |  config.py                             # Set up the app
   |    __init__.py                         # Initialize the app
   |
   |-- requirements.txt                     # App Dependencies
   |
   |-- .env                                 # Inject Configuration via Environment
   |-- run.py                               # Start the app - WSGI gateway
   |
   |-- ************************************************************************
```

## Screenshots

![image](https://github.com/vicmir/ArtStyleRecognitionApp/assets/79836020/11d09e06-7d7a-482b-9acc-dd0b2dc6cc56)

![image](https://github.com/vicmir/ArtStyleRecognitionApp/assets/79836020/96149290-db4e-4a84-937e-80a2dbcb0fd9)

![image](https://github.com/vicmir/ArtStyleRecognitionApp/assets/79836020/210e3650-69f0-435a-bbb7-963e1142b038)

![image](https://github.com/vicmir/ArtStyleRecognitionApp/assets/79836020/6f541b56-f6e8-46f6-b2a4-6b5134014181)

![image](https://github.com/vicmir/ArtStyleRecognitionApp/assets/79836020/e8b521ef-b0c4-4ab8-974f-f06c7c29e289)

![image](https://github.com/vicmir/ArtStyleRecognitionApp/assets/79836020/48978025-9107-4555-9b81-844630573f34)

![image](https://github.com/vicmir/ArtStyleRecognitionApp/assets/79836020/3605b0f1-35c8-4d43-a4df-989c1831e539)

![image](https://github.com/vicmir/ArtStyleRecognitionApp/assets/79836020/2be08500-5f0b-4287-9f15-ec876db18fba)
