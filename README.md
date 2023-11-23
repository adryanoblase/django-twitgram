# Django Twitgram Website

## Description

Django Twitgram is a web application designed for social networking and sharing posts.
Users can enjoy features such as uploading images, searching for posts, liking posts, viewing profiles, and more. 
The project follows the Django framework for the backend and is styled using Bootstrap for a responsive and visually appealing user interface.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Documentation](#documentation)
- [Docker Container](#docker-container)
- [Contributing](#contributing)
- [Credits](#credits)
- [Contact](#contact)
- [License](#license)

## Installation

To install and run this Django project locally, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/adryanoblase/django-twitgram.git
Navigate to the project directory:

bash
Copy code
cd django-twitgram
Create and activate a virtual environment:

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows, use "venv\Scripts\activate"
Install project dependencies:

bash
Copy code
pip install -r requirements.txt
Apply migrations:

bash
Copy code
python manage.py migrate
Run the development server:

bash
Copy code
python manage.py runserver
Open your web browser and navigate to http://127.0.0.1:8000/ to view the app.

## Usage
After installing the project, you can access the web application by running the development server and navigating to the provided URL.

## Documentation
For detailed documentation, refer to the docs folder.

## Docker Container
To run the app in a Docker container, follow these steps:

Build the Docker image:

bash
Copy code
docker build -t django-twitgram .
Run the Docker container:

bash
Copy code
docker run -p 8000:8000 django-twitgram
Access the app in your browser at http://127.0.0.1:8000/.

## Contributing
If you want to contribute to this project, do so with ease.

## Credits
This project was created by:

Adriano Mama
GitHub: AdrianoMama
Contact
If you have any questions or feedback regarding this project, feel free to contact the author:

Name: Adriano Mama
Email: adrianoblase99@gmail.com
License
© 2023 Adriano Mama. All rights reserved.
