# Agriculture Portal

- Agriculture Portal is a machine learning-based project designed to provide predictions and recommendations for farmers. The system uses different algorithms to predict crops, recommend fertilizers, and provide rainfall and yield predictions to help farmers make informed decisions about their crops.
- IT also has direct crop sales to customer with real payment interface using Stripe API.
- Other supporting features are Chatbot using OPENAI's gpt-3.5-turbo model, Weather Forecast upto 4 days using Weather API, Agriculture realetd news using News API.

## Pre Requisites
### Get Below API Keys
- [News API](https://newsapi.org/)
- [OpenWeatherMap API](https://openweathermap.org/api)
- [Stripe API](https://dashboard.stripe.com/account/apikeys)
- [OpenAI API](https://platform.openai.com/account/api-keys)


## Installation

1. Clone the repository to your local machine.
```bash
git clone https://github.com/Mikedire/Agroweather-Management-System.git
```
2. Goto Farmers folder and Install the required packages using pip.
```
pip install -r requirements.txt
```

4. Add API Keys to respective files.
- News API Key to `fnewsfeed.php`
- OpenWeatherMap API Key to `fweather_forecast.php`
- Stripe API Key to `customer/stripePayment/config.php`
- OpenAI API Key to `index.php` and `fchatgpt.php`
5. Import database from db folder.
6. Run Apache web server using XAMPP.

## Features
- Crop Prediction
- Crop Recommendation
- Fertilizer Recommendation
- Rainfall Prediction
- Yield Prediction
- OTP Verification through mail
- Agriculture realetd news using News API
- Chatbot using OpenAI's gpt-3.5-turbo model
- Dynamically changing quotes using OpenAI's API
- Weather Forecast upto 4 days using OpenWeatherMap API
- Direct crop sales to customer with real time payment interface using Stripe API


## Technologies Used
- Python
- PHP
- Pandas
- NumPy
- JavaScript
- HTML/CSS
- Bootstrap4
- Scikit-learn

## Dataset
The Crop Management System dataset includes the following features:

### Crop Prediction Dataset
- State_Name
- District_Name
- Season
- Crop

### Crop Recommendation Dataset
- N
- P
- K
- Temperature
- Humidity
- pH
- Rainfall
- Label

### Fertilizer Recommendation Dataset
- Temparature
- Humidity
- Soil Moisture
- Soil Type
- Crop Type
- Nitrogen
- Phosphorous
- Potassium
- Fertilizer Name

### Rainfall Prediction Dataset
- SUBDIVISION
- YEAR
- JAN
- FEB
- MAR
- APR
- MAY
- JUN
- JUL
- AUG
- SEP
- OCT
- NOV
- DEC
- ANNUAL
- Jan-Feb
- Mar-May
- Jun-Sep
- Oct-Dec

### Yield Prediction Dataset
- State_Name
- District_Name
- Crop_Year
- Season
- Crop
- Area
- Production

## How to Use
- Crop Prediction: Input `State_Name`, `District_Name`, and `Season` to get the predicted crop for that location.
- Crop Recommendation: Input `N`, `P`, `K`, `Temperature`, `Humidity`, `pH`, and `Rainfall` for that location to get recommended crops for that location.
- Fertilizer Recommendation: Input `Temperature`, `Humidity`, `Soil Moisture`, `Soil Type`, `Crop Type`, `Nitrogen`, `Phosphorous`, and `Potassium` to get recommended fertilizer for that crop and location.
- Rainfall Prediction: Input `Subdivision` and `Year` to get rainfall prediction for that year.
- Yield Prediction: Input `State_Name`, `District_Name`, `Crop_Year`, `Season`, `Crop`, `Area`, `Production` to get predicted yields for that crop and location.

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
