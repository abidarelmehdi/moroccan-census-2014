# MOROCCAN CENSUS OF 2014

Python Labs for scraping data of The General Population and Housing Census of Morocco of 2014 from RGPH website
and generate some analysis

# Project Overview

### The project is divided into 4 labs:
- Building Database.ipynb: for srapping the website and building the MySql database
- Interrogating MySQL.ipynb: Generate and visualize analysis with MySql queries
- Migrate to MongoDB.ipynb: A script that helps migrate to MongoDB
- Interrogating MongoDB.ipynb: Help if you can Pleaaase 🙏

### Environment:
- Python 3.6
- Jupyter Lab
- Docker
- pandas
- requests/requests-html 
- pymongo/PyMySQL


## Installation

Clone the project

    https://github.com/abidarelmehdi/moroccan-census-2014

Make sure you are in the project directory

    cd moroccan-census-2014

Install the requirements

    pip install -r ./requirements.txt

Launch docker-compose to run the databases containers

    docker-compose up -d

# Statistics in the project

- Top 10 Populated Communes
- Province with the lowerest handicap prevalence rate
- Age Average of first meriage by gender and zones
- Provinces of The 10 Communes had the lowerest illiteracy rate
- Top school level for each region
- Nomber of Provinces uses Satellite dish more than Fridge
- ...
