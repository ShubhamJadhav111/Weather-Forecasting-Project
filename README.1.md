
# Weather Forecasting Project


This project uses the OpenWeatherMap API to fetch real-time weather data for multiple cities and store the data in a CSV file. The data includes information like temperature, humidity, wind speed, and cloudiness. It also provides functionality to visualize the collected data using different types of charts.




## Prerequisites
1) Python 3.x installed on your system.

2) Required Python packages:

• requests

• pandas

• matplotlib

You can install them using :








## How It Works
1) Weather Data Collection :
The script fetches weather data for a list of cities. For each city, the following data is collected.

• Name of the city

• Longitude and Latitude

• Temperature (°C) and "Feels Like" temperature (°C)

• Humidity (%)

• Wind speed and gusts (m/s)

• Cloud cover (%)

• Weather description

• Date and Time of the
 data

2) Data Storage :
The collected data is stored in a CSV file named weather_Collect_new_data.csv. If the file already exists, the new data will be appended to it.

3) Data Visualization :
The script allows the user to visualize the weather data for selected cities and parameters using line charts, bar charts, or pie charts.




## Setup Instructions

## Deployment

To deploy this project run

```bash
  pip install requests pandas matplotlib
```

1) Clone the repository (or copy the code):


https://github.com/ShubhamJadhav111/Weather-Forecasting-Project/blob/main/README.md#weather-forecasting-project

2) Install the required libraries :

pip install requests pandas matplotlib

3) Update the API key :

• Replace your_actual_api_key_here in the script with your        OpenWeatherMap API key :

api_key = 'your_actual_api_key_here'...

4) Run the Script :
You can run the script to fetch the latest weather data :

python weather_forecast.py





## Features

- Real-Time Data Fetching :-> Fetches current weather data from OpenWeatherMap API for multiple cities.
- CSV Data Logging :-> Automatically logs the fetched data in a CSV file, and appends new data if it already exists.
- Data Visualization :-> Allows you to create line, bar, or pie charts for various weather parameters.




## Usage Instructions 
Collecting Weather Data :->

• The script collects weather data for the following cities by default:
Indore, Bhopal, Jabalpur, Balaghat, Dewas, Seoni, Ujjain, Ratlam,
Saugor, Morena,Chhatarpur, Rewa, Pachmarhi, Gwalior.

• You can modify the list of cities in the script by updating the cities .


## Visualizing Data
• To visualize the data, the user will be prompted to :

1) Enter the cities they want to visualize (comma-separated).

2) Enter the columns (weather parameters) they want to visualize.

3) Choose the type of chart (line, bar, or pie).


## Future Improvements
• Add support for more detailed weather statistics.

• Include forecast data (multiple days) of only current weather.

• Expand visualization options with more chart types or filters.


## License

[MIT](https://choosealicense.com/licenses/mit/)

This project is open-source and available under the MIT License.

Feel free to contribute or suggest improvements.

## Contact Information
For any questions or feedback, feel free to reach out via:

Email: shubhamajadhav1306@gmail.com 

GitHub: https://github.com/ShubhamJadhav111
