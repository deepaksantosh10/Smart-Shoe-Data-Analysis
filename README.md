# Smart-Shoe-Data-Analysis
The SmartShoe Data Anlysis Project is designed to collect sensor data from a smart shoe and perform various analyses, including gait analysis and weather prediction. This README file provides an overview of the project and instructions on how to run it.

# Table of Contents
1.Introduction<br>
2.Model Analysis<br>
3.Installation<br>
4.Usage<br>
5.Datasets<br>
6.Contributing<br>
7.License<br>
# Introduction
The SmartShoe is an innovative IoT device designed to revolutionize the way we track and analyze human movement. Equipped with a wide array of sensors, the SmartShoe collects various data points while the user is wearing the device, providing valuable insights into their walking or running patterns and environmental conditions.The SmartShoe captures various parameters including step count, stride length, distance, estimated time, walking speed, calories burned, average heart rate, and fatigue levels. By analyzing this data using Support Vector Machines (SVM) and Artificial Neural Network (ANN) models, the SmartShoe predicts exertion levels and body conditions, offering valuable insights.Additionally, the SmartShoe monitors environmental factors such as temperature, humidity, heat index, and dew temperature. By combining this information with weather prediction models, it provides real-time weather forecasts and personalized weather information.<br>
This README file serves as a guide for anyone interested in using the SmartShoe project. It provides installation instructions, usage guidelines, and information about the datasets and contributions. By following the instructions provided, users can easily set up the project, run the analyses, and gain valuable insights from the SmartShoe's sensor data.

# Model Analysis
<h3>Gait Analysis</h3><br>
Gait analysis involves analyzing the user's walking or running pattern to derive insights about their body condition and exertion level. The following parameters are considered for gait analysis:<br>
&#x2022; Step count<br>
&#x2022; Stride length<br>
&#x2022; Distance<br>
&#x2022; Estimated time<br>
&#x2022; Walking speed<br>
&#x2022; Calories burned<br>
&#x2022; Average heart rate<br>
&#x2022; Fatigue<br>
The project provides a Python notebook,<b>gait-analysis-svm-ann-model.ipynb</b>, which utilizes Support Vector Machines (SVM) and Artificial Neural Network (ANN) models to predict the exertion level and body condition of the user based on the gait analysis.<br>
<h3>Weather Prediction</h3><br>
The SmartShoe project also incorporates weather prediction based on the collected data. The following parameters are used for weather prediction:<br>
&#x2022; Temperature<br>
&#x2022; Humidity<br>
&#x2022; Heat index<br>
&#x2022; Heat index message<br>
&#x2022; Dew temperature<br>
The project provides a Python notebook,<b>weather-prediction-svm-ann-models.ipynb</b>, which utilizes SVM and ANN models to predict the chances of precipitation and provide weather information based on the collected data.

# Installation
To run the SmartShoe project, follow these steps:<br>
Clone the repository: https://github.com/deepaksantosh10/Smart-Shoe-Data-Analysis<br>
Install the required dependencies

# Datasets
The project includes two datasets in CSV format:
<br>
&#x2022; Dataset.csv: This dataset is used for weather prediction.<br>
&#x2022; Dataset1.csv: This dataset is used for gait analysis.<br>
Ensure that you have the appropriate dataset for the analysis you wish to perform.<br>

# Contributing
Contributions to the SmartShoe project are welcome! If you encounter any issues or have suggestions for improvement, please feel free to submit a pull request or open an issue.

