# Flipcart Reviews Scrapper

Flipcart Reviews Scrapper is a Flask web application designed to extract reviews of products listed on Flipkart. It provides details such as ratings, comments, customer names, etc., in the form of a table. The project utilizes web scraping techniques to retrieve reviews from Flipkart and integrates with a custom web portal, REST API, and MongoDB for easy data retrieval and storage.

## Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Features

- Extracts product reviews from Flipkart.
- Displays review details in a tabular format.
- Integrates with a custom web portal.
- Provides a REST API for easy data retrieval.
- Utilizes MongoDB for storing and managing reviews.

## Project Structure

The project is structured as follows:

- `.github/workflows`: GitHub Actions workflow for continuous integration (if applicable).
- `static/css`: CSS stylesheets for the web portal.
- `templates`: HTML templates for rendering the web pages.
- `app.py`: Main application file.

## Getting Started

To get started with the Flipcart Reviews Scrapper, follow these steps:

1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the application using `python app.py`.
4. Access the web portal at [http://localhost:5000](http://localhost:5000).

## Usage

Once the application is running, you can access the web portal and use the REST API to retrieve and manage product reviews.

- Web Portal: [http://localhost:5000](http://localhost:5000)
- REST API: [http://localhost:5000/api](http://localhost:5000/api)

## Dependencies

The project relies on the following Python dependencies:

- Flask
- Flask-CORS
- requests
- BeautifulSoup
- pymongo

Install these dependencies using `pip install -r requirements.txt`.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the [MIT License](LICENSE).
