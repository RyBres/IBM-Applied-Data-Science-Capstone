# IBM Data Science Professional Certificate Capstone Project

## Project Overview

This project is the final component of the IBM Data Science Professional Certificate on Coursera. It involves applying the skills and knowledge acquired throughout the course to a real-world data science problem. The capstone project focuses on SpaceX's Falcon 9 first-stage landing outcomes, aiming to predict whether the first stage will land successfully.

## Table of Contents

- [Project Overview](#project-overview)
- [Project Objectives](#project-objectives)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Project Objectives

- Collect and analyze data using web scraping and REST APIs.
- Conduct data wrangling and cleaning.
- Perform exploratory data analysis (EDA) to uncover patterns and insights.
- Build and evaluate machine learning models to predict landing outcomes.
- Deploy the machine learning model using IBM Watson Studio.

## Dataset

The dataset used for this project is provided by SpaceX, containing information about various launches. Key features include:

- `FlightNumber`: Number of the flight.
- `Date`: Launch date.
- `BoosterVersion`: Version of the booster.
- `PayloadMass`: Mass of the payload in kilograms.
- `Orbit`: Orbit type.
- `LaunchSite`: Launch site name.
- `Outcome`: Outcome of the landing.
- `Flights`: Number of previous flights.
- `GridFins`: Whether the flight used grid fins.
- `Reused`: Whether the flight used a reused booster.
- `Legs`: Whether the flight used landing legs.
- `LandingPad`: The landing pad used for the flight.
- `Block`: Block version of the booster.
- `ReusedCount`: Number of times the booster has been reused.
- `Serial`: Booster serial number.
- `Longitude`: Launch site longitude.
- `Latitude`: Launch site latitude.

## Usage

1. **Data Collection**: Run the `1_Data_Collection.ipynb` notebook to scrape and collect the data.
2. **Data Wrangling**: Run the `2_Data_Wrangling.ipynb` notebook to clean and preprocess the data.
3. **Exploratory Data Analysis**: Run the `3_EDA.ipynb` notebook to perform EDA.
4. **Feature Engineering**: Run the `4_Feature_Engineering.ipynb` notebook to create new features.
5. **Machine Learning**: Run the `5_Machine_Learning.ipynb` notebook to build and evaluate the machine learning models.
6. **Model Deployment**: Run the `6_Model_Deployment.ipynb` notebook to deploy the model using IBM Watson Studio.
7. **Dash Application**: Run the `spacex_dash_app.py` script to launch the Dash web application:
    ```sh
    python app/spacex_dash_app.py
    ```

## Results

The project results include:
- A detailed analysis of the SpaceX launch data.
- Predictive models to determine the success of the first-stage landing.
- A deployed machine learning model.
- An interactive dashboard to visualize the analysis and predictions.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements.

## License

This project is licensed under the MIT License.

## Acknowledgements

- IBM for providing the Data Science Professional Certificate program.
- Coursera for hosting the course.
- SpaceX for providing the launch data.
