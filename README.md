# Art Style Recognition Web Application

This project is a web application designed to automatically recognize and classify art styles in images using deep learning techniques. The application leverages convolutional neural networks (CNNs) for image classification, providing an efficient and user-friendly tool for art analysis.

Template credits: https://github.com/app-generator/flask-black-dashboard

## Data

**Dataset:** https://www.wikiart.org/, Repository: https://github.com/cs-chan/ArtGAN/tree/master/WikiArt%20Dataset

Download the images:

```sh
wget http://web.fsktm.um.edu.my/~cschan/source/ICIP2017/wikiart.zip
```

Download the csv files:

```sh
wget http://web.fsktm.um.edu.my/~cschan/source/ICIP2017/wikiart_csv.zip
```

Unzip the folders, and move them to the ... folder of the package.

## Jupyter notebooks

TBA

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

2. Set Up for `Unix`, `MacOS`:

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
   
3. Set Up for `Windows`:

- Install modules via `VENV`:

   ```sh
   $ virtualenv env
   $ .\env\Scripts\activate
   $ pip3 install -r requirements.txt
   ```

- Set Up Flask Environment:

   ```sh
   # CMD
   $ set FLASK_APP=run.py
   $ set FLASK_ENV=development
   
   # Powershell
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

![image](https://github.com/vicmir/ArtStyleRecognitionApp/assets/79836020/50a43483-da02-45fb-b340-8111e7e9c403)

![image](https://github.com/vicmir/ArtStyleRecognitionApp/assets/79836020/c03a3e1c-a948-4600-be94-6e9a63217914)

![image](https://github.com/vicmir/ArtStyleRecognitionApp/assets/79836020/8f8367d2-040a-41d1-b0a2-e59e949134ce)

![image](https://github.com/vicmir/ArtStyleRecognitionApp/assets/79836020/a8a0bbc7-4f4b-41fa-97b5-8b1a0a8f12c3)

## Live Demo
