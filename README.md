# Python-Flask-Template


This is a template for a Python-Flask web application. It includes a basic file structure and configuration files to get you started quickly.

## Requirements

* Python 3
* Flask
* SQLAlchemy

## Installation

1. Clone the repository:

`git clone https://github.com/berkebozaci/Python-Flask-Template.git`


2. Install the dependencies:

`pip install -r requirements.txt`

3. Run the application:

`python run.py`


## File Structure

* `app/__init__.py` - Initializes the Flask application
* `app/models.py` - Defines the database models
* `app/routes.py` - Defines the application routes
* `app/static/` - Directory for static files (CSS, JS, images)
* `app/templates/` - Directory for Jinja2 templates
* `config.py` - Application configuration file
* `requirements.txt` - List of dependencies for the application
* `run.py` - Runs the Flask application

## Configuration

The `config.py` file contains the configuration settings for the application, such as the database URI, secret key, and debug mode.

## Usage

The application routes are defined in `app/routes.py`. You can add new routes and views to this file to create new pages or functionality.

The database models are defined in `app/models.py`. You can modify these models or add new models to suit your application's needs.

Static files (CSS, JS, images) can be placed in the `app/static/` directory, and templates can be placed in the `app/templates/` directory.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
