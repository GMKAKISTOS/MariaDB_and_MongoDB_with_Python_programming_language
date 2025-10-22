# MariaDB and MongoDB with python

This project is a Python program designed to interact with both MariaDB and MongoDB databases providing a user-friendly menu interface to answer various questions derived from the Yelp dataset. The application facilitates data manipulation, querying and integration between different database systems.

## Features

-   **Database Connectors**: Establishes connections with both MariaDB and MongoDB databases.
-   **Data Conversion**: Converts SQL data to CSV format for data migration purposes.
-   **Data Insertion**: Inserts datasets into MariaDB and MongoDB, handling data loading and integration.
-   **Complex Queries**: Executes a variety of complex queries to extract meaningful information from the databases.
-   **User Interface**: Provides a menu-driven interface for easy navigation and query execution.

## Table of Contents

-   [Installation](#installation)
-   [Usage](#usage)
-   [Dependencies](#dependencies)

## Installation

To set up the project, follow these steps:

1.  Clone the repository:

    ```bash
    git clone https://github.com/panoschron97/MariaDB_and_MongoDB_with_Python_programming_language.git
    cd MariaDB_and_MongoDB_with_Python_programming_language
    ```

2.  Install the required Python packages:

    ```bash
    pip install mariadb pymongo pandas python-dateutil
    ```

## Usage

1.  Run the `myapp.py` script:

    ```bash
    python myapp.py
    ```

2.  Follow the menu options to interact with the databases and execute predefined queries.
    Enter the number corresponding to the desired action and press Enter.

## Dependencies

-   **mariadb**: For connecting to and interacting with MariaDB databases.
-   **pymongo**: For connecting to and interacting with MongoDB databases.
-   **pandas**: For data manipulation and CSV file handling.
-   **python-dateutil**: For parsing and working with date formats.
-   The dataset is on the website: **https://www.kaggle.com/datasets/yelp-dataset/yelp-dataset**
