# [Black Dashboard Flask](https://appseed.us/product/black-dashboard/flask/)
# Art Style Recognition Web Application

# Art Style Recognition Web Application

**Features**
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
    git clone https://github.com/yourusername/art-style-recognition.git
    cd art-style-recognition
    ```
2. Install dependencies:
    ```sh
    pip install -r requirements.txt
    ```

3. Run the application:
    ```sh
    python run.py
    ```

4. Open your web browser and go to `http://127.0.0.1:5000`.

## Usage

- **Register/Login**: Create a new account or log in to an existing account.
- **Upload Images**: Upload images from your PC or via URL for analysis.
- **View Results**: Check the recognized art style and detailed description for each uploaded image.
- **Profile Management**: Manage your profile and view the history of analyzed images.


Open-source **[Flask Dashboard](https://appseed.us/admin-dashboards/flask/)** crafted on top of a modern `Bootstrap` design. Designed for those who like bold elements and beautiful websites, **Black Dashboard** is ready to help you create stunning websites and web apps. **Black Dashboard** is built with over 50 frontend individual elements, like buttons, inputs, navbars, nav tabs, cards, or alerts, giving you the freedom of choosing and combining.

- 👉 [Black Dashboard Flask](https://appseed.us/product/black-dashboard/flask/) - `product page`
- 👉 [Black Dashboard Flask](https://flask-black-dashboard.appseed-srv1.com/) - `LIVE Demo`
  
<br />

## Features

> `Have questions?` Contact **[Support](https://appseed.us/support/)** (Email & Discord) provided by **AppSeed**

| Free Version                          | [PRO Version](https://appseed.us/product/black-dashboard-pro/flask/)          | [Custom Development](https://appseed.us/custom-development/) |  
| --------------------------------------| --------------------------------------| --------------------------------------|
| ✓ **Up-to-date dependencies**             | **Everything in Free**, plus:                                        | **Everything in PRO**, plus:          |
| ✓ Best Practices                          | ✅ **Premium Bootstrap 5 Design**                                    | ✅ **1 Week** `Custom Development`  | 
| ✓ DB: SQLite, MySql                       | ✅ `OAuth` for Github                                                | ✅ **Team**: PM, Developer, Tester   |
| ✓ DB Tools: ORM, Flask-Migrate            | ✅ `Extended User Model`                                             | ✅ Weekly Sprints                    |
| ✓ Session-Based authentication            | ✅ `Users Roles`                                                     | ✅ Technical SPECS                   |
| ✓ `Docker`                                | ✅ `Private REPO Access`                                             | ✅ Documentation                     |
| ✓ `CI/CD` Flow via Render                 | ✅ **PRO Support** - [Email & Discord](https://appseed.us/support/)  | ✅ **30 days Delivery Warranty**     |
| ✓ `Free Support`                          | -                                                                    | ✅ [CI/CD for AWS, DO](https://appseed.us/terms/#section-ci-cd) **(Extra)**    |
| ---------------------------------         | ---------------------------------                                     | ---------------------------------  |
| ✓ [LIVE Demo](https://flask-black-dashboard.appseed-srv1.com/)  | 🚀 [LIVE Demo](https://flask-black-dashboard-enh.appseed-srv1.com/) `PRO` | 🛒 `Order`: **[$999](https://appseed.gumroad.com/l/rocket-package-week)** (GUMROAD) |  

![Black Dashboard Flask - Crafted by AppSeed.](https://github.com/app-generator/flask-black-dashboard/assets/51070104/0428a8aa-d095-4a49-9a6a-5466041f7cec)

<br /> 

## ✅ Start in `Docker`

> 👉 **Step 1** - Download the code from the GH repository (using `GIT`) 

```bash
$ git clone https://github.com/app-generator/flask-black-dashboard.git
$ cd flask-black-dashboard
```

<br />

> 👉 **Step 2** - Start the APP in `Docker`

```bash
$ docker-compose up --build 
```

Visit `http://localhost:5085` in your browser. The app should be up & running.

<br />

## ✅ Create/Edit `.env` file

The meaning of each variable can be found below: 

- `DEBUG`: if `True` the app runs in develoment mode
  - For production value `False` should be used
- `ASSETS_ROOT`: used in assets management
  - default value: `/static/assets`
- `OAuth` via Github
  - `GITHUB_ID`=<GITHUB_ID_HERE>
  - `GITHUB_SECRET`=<GITHUB_SECRET_HERE> 

<br />

## ✅ Manual Build

> Download the code 

```bash
$ git clone https://github.com/app-generator/flask-black-dashboard.git
$ cd flask-black-dashboard
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ export FLASK_APP=run.py
$ export FLASK_ENV=development
```

<br />

> Start the app

```bash
$ flask run
// OR
$ flask run --cert=adhoc # For HTTPS server
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ # CMD 
$ set FLASK_APP=run.py
$ set FLASK_ENV=development
$
$ # Powershell
$ $env:FLASK_APP = ".\run.py"
$ $env:FLASK_ENV = "development"
```

<br />

> Start the app

```bash
$ flask run
// OR
$ flask run --cert=adhoc # For HTTPS server
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

## ✅ Recompile SCSS  

The SCSS/CSS files used to style the Ui are saved in the `apps/static/assets` directory. 
In order to update the Ui colors (primary, secondary) this procedure needs to be followed. 

```bash
$ yarn # install modules
$ # # edit variables 
$ vi apps/static/assets/scss/black-dashboard/custom/_variables.scss 
$ gulp # SCSS to CSS translation
```

The `_variables.scss` content defines the `primary` and `secondary` colors: 

```scss
$default:       #344675 !default; // EDIT for customization
$primary:       #e14eca !default; // EDIT for customization
$secondary:     #f4f5f7 !default; // EDIT for customization
$success:       #00f2c3 !default; // EDIT for customization
$info:          #1d8cf8 !default; // EDIT for customization
$warning:       #ff8d72 !default; // EDIT for customization
$danger:        #fd5d93 !default; // EDIT for customization
$black:         #222a42 !default; // EDIT for customization
```

<br />

## ✅ Codebase

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

<br />

## ✅ [Black Dashboard Flask](https://appseed.us/product/black-dashboard-pro/flask/) `PRO Version`

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

Black Dashboard is a premium Bootstrap Design now available for download in Django. Made of hundred of elements, designed blocks, and fully coded pages, Black Dashboard PRO is ready to help you create stunning websites and web apps.

- 👉 [Black Dashboard PRO Flask](https://appseed.us/product/black-dashboard-pro/flask/) - product page
  - ✅ `Enhanced UI` - more pages and components
  - ✅ `Priority` on support

![Black Dashboard PRO - Full-Stack Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/169471630-e96cec9b-ef57-4c06-9b36-62b9bbf255f3.png)

<br />

---
[Black Dashboard Flask](https://appseed.us/product/black-dashboard/flask/) - Open-source starter generated by **[AppSeed](https://appseed.us)**.

## Screenshots

![image](https://github.com/vicmir/ArtStyleRecognitionApp/assets/79836020/11d09e06-7d7a-482b-9acc-dd0b2dc6cc56)

![image](https://github.com/vicmir/ArtStyleRecognitionApp/assets/79836020/96149290-db4e-4a84-937e-80a2dbcb0fd9)

![image](https://github.com/vicmir/ArtStyleRecognitionApp/assets/79836020/210e3650-69f0-435a-bbb7-963e1142b038)

![image](https://github.com/vicmir/ArtStyleRecognitionApp/assets/79836020/6f541b56-f6e8-46f6-b2a4-6b5134014181)

![image](https://github.com/vicmir/ArtStyleRecognitionApp/assets/79836020/e8b521ef-b0c4-4ab8-974f-f06c7c29e289)

![image](https://github.com/vicmir/ArtStyleRecognitionApp/assets/79836020/48978025-9107-4555-9b81-844630573f34)

![image](https://github.com/vicmir/ArtStyleRecognitionApp/assets/79836020/3605b0f1-35c8-4d43-a4df-989c1831e539)

![image](https://github.com/vicmir/ArtStyleRecognitionApp/assets/79836020/2be08500-5f0b-4287-9f15-ec876db18fba)
