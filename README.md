# Natural-Disaster-Prediction-in-R

<div align="center">
  <img src="https://github.com/ABHIJATSARARI/Natural-Disaster-Prediction-in-R/blob/main/logo.png" alt="Project Logo">
</div>

## Overview
This project leverages an earthquake dataset from the U.S. Geological Survey (USGS) to predict natural disasters. The application features a GUI that allows users to interact with the model and observe immediate outcomes. The `shiny` package in R is used to develop a straightforward web application, resulting in an interactive web application for earthquake prediction.

## Features
- **Interactive GUI**: Engage with the model and observe predictions in real-time.
- **USGS Earthquake Dataset**: Utilizes comprehensive earthquake data for accurate predictions.
- **Shiny Package**: Develops a user-friendly web application in R.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/ABHIJATSARARI/natural-disaster-prediction.git
    cd natural-disaster-prediction
    ```
2. Install the required packages:
    ```R
    install.packages(c("shiny", "dplyr", "ggplot2"))
    ```

## Usage
1. Run the Shiny app:
    ```R
    library(shiny)
    runApp("app.R")
    ```
2. Access the application in your web browser at `http://localhost:3838`.

## Dataset
The earthquake dataset is sourced from the U.S. Geological Survey (USGS).

## Live Demo
<div align="center">
  <a href="https://abhijat-rapiz.shinyapps.io/project/" target="_blank">
    <img src="https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge&logo=appveyor" alt="Live Demo">
  </a>
</div>

## Screenshots
<div align="center">
  <img src="https://github.com/ABHIJATSARARI/Natural-Disaster-Prediction-in-R/blob/main/Preset1.jpg" alt="Screenshot 1" width="400" hight='600'>
  <img src="https://github.com/ABHIJATSARARI/Natural-Disaster-Prediction-in-R/blob/main/Preset2.jpg" alt="Screenshot 2" width="400" hight='600>
</div>

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.
