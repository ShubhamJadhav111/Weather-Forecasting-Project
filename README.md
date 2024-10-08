# Weather Forecasting Project
<b>
Weather Forecasting Project

This project uses the OpenWeatherMap API to fetch real-time weather data for multiple cities and store the data in a CSV file. The data includes information like temperature, humidity, wind speed, and cloudiness. It also provides functionality to visualize the collected data using different types of charts.

Prerequisites
Python 3.x installed on your system.
<b>
Required Python packages:

• requests

• pandas

• matplotlib
<b>
You can install them using :
<b>
How It Works
<b>
Weather Data Collection :

The script fetches weather data for a list of cities. For each city, the following data is collected.

• Name of the city

• Longitude and Latitude

• Temperature (°C) and "Feels Like" temperature (°C)

• Humidity (%)

• Wind speed and gusts (m/s)

• Cloud cover (%)

• Weather description

• Date and Time of the data
<b>
Data Storage :

The collected data is stored in a CSV file named weather_Collect_new_data.csv. If the file already exists, the new data will be appended to it.
<b>
Data Visualization :

The script allows the user to visualize the weather data for selected cities and parameters using line charts, bar charts, or pie charts.
<b>
Setup Instructions
<b>
Deployment

To deploy this project run

  pip install requests pandas matplotlib
  
Clone the repository (or copy the code):

https://github.com/ShubhamJadhav111/Weather-Forecasting-Project/blob/main/README.md#weather-forecasting-project
<b>
Update the API key :

• Replace your_actual_api_key_here in the script with your OpenWeatherMap API key :

api_key = 'your_actual_api_key_here'...
<b>
Run the Script :

You can run the script to fetch the latest weather data :

python weather_forecast.py
<b>
Features

Real-Time Data Fetching :-> Fetches current weather data from OpenWeatherMap API for multiple cities.
CSV Data Logging :-> Automatically logs the fetched data in a CSV file, and appends new data if it already exists.
Data Visualization :-> Allows you to create line, bar, or pie charts for various weather parameters.
<b>
Usage Instructions
<b>
Collecting Weather Data :->

• The script collects weather data for the following cities by default: Indore, Bhopal, Jabalpur, Balaghat, Dewas, Seoni, Ujjain, Ratlam, Saugor, Morena,Chhatarpur, Rewa, Pachmarhi, Gwalior.

• You can modify the list of cities in the script by updating the cities .
<b>
Visualizing Data

• To visualize the data, the user will be prompted to :

Enter the cities they want to visualize (comma-separated).

Enter the columns (weather parameters) they want to visualize.

Choose the type of chart (line, bar, or pie).
<b>
Future Improvements

• Add support for more detailed weather statistics.

• Include forecast data (multiple days) of only current weather.

• Expand visualization options with more chart types or filters.
<b>
License

MIT

This project is open-source and available under the MIT License.

Feel free to contribute or suggest improvements.
<b>
Contact Information

For any questions or feedback, feel free to reach out via:

Email: shubhamajadhav1306@gmail.com

GitHub: https://github.com/ShubhamJadhav111
