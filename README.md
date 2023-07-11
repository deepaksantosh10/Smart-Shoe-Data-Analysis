# Smart-Shoe-Data-Analysis
The SmartShoe Data Anlysis Project is designed to collect sensor data from a smart shoe and perform various analyses, including gait analysis and weather prediction. This README file provides an overview of the project and instructions on how to run it.

# Table of Contents
Introduction
Model Analysis
Installation
Usage
Datasets
Contributing
License
Introduction
The SmartShoe is equipped with sensors that collect various data points while the user is walking or running. The collected data is stored in a CSV file for further analysis. This project utilizes machine learning techniques to perform gait analysis and predict weather conditions based on the collected data.

Model Analysis
Gait Analysis
Gait analysis involves analyzing the user's walking or running pattern to derive insights about their body condition and exertion level. The following parameters are considered for gait analysis:

Step count
Stride length
Distance
Estimated time
Walking speed
Calories burned
Average heart rate
Fatigue
The project provides a Python notebook, GaitAnalysis.ipynb, which utilizes Support Vector Machines (SVM) and Artificial Neural Network (ANN) models to predict the exertion level and body condition of the user based on the gait analysis.

Weather Prediction
The SmartShoe project also incorporates weather prediction based on the collected data. The following parameters are used for weather prediction:

Temperature
Humidity
Heat index
Heat index message
Dew temperature
The project provides a Python notebook, WeatherPrediction.ipynb, which utilizes SVM and ANN models to predict the chances of precipitation and provide weather information based on the collected data.

Installation
To run the SmartShoe project, follow these steps:

Clone the repository: git clone https://github.com/your-username/SmartShoe.git
Install the required dependencies: pip install -r requirements.txt
Usage
Navigate to the project directory: cd SmartShoe
Open the GaitAnalysis.ipynb notebook in Jupyter or any compatible environment for gait analysis. Upload the dataset Dataset1.csv (for gait analysis) to the notebook. Follow the instructions and code comments in the notebook to analyze the gait data and generate predictions.
Open the WeatherPrediction.ipynb notebook in Jupyter or any compatible environment for weather prediction. Upload the dataset Dataset.csv (for weather prediction) to the notebook. Follow the instructions and code comments in the notebook to analyze the weather data and generate predictions.
Datasets
The project includes two datasets in CSV format:

Dataset.csv: This dataset is used for weather prediction.
Dataset1.csv: This dataset is used for gait analysis.
Ensure that you have the appropriate dataset for the analysis you wish to perform.

Contributing
Contributions to the SmartShoe project are welcome! If you encounter any issues or have suggestions for improvement, please feel free to submit a pull request or open an issue.

License
This project is licensed under the MIT License.

Feel free to modify and use this README template according to your specific project requirements.
