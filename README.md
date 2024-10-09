# Weather Forecasting Projects
This Python project uses Pandas for data manipulation and Matplotlib for visualization. The user is prompted to enter the names of cities, the columns they wish to visualize (e.g., temperature, humidity), and the type of chart (line, bar, or pie). The project then generates the requested charts, showing data trends across different cities.
# Table of Content
  - [Features](#Features)
  - [Project Structure](#ProjectStructure)
  - [Dependencies](#Dependencies)
  - [How to Use the Project](#HowtoUsetheProject)
  - [Improvements](#Improvements)
  - [Conclusion](#Conclusion)
  - [License](#License)
  - [Contact Information](#ContactInformation)

# Features
  - Multiple Chart Types: Line, bar, and pie charts for visualizing weather data.

  - User Input: Users can input the cities and columns they want to visualize.

  - Data Filtering: The project filters the data based on user-selected cities and columns.

  - CSV Input: Reads weather data from a CSV file.
 # Project Structure  
  - weather_forecasting.py: The main Python script that contains the logic for reading the CSV and generating the visualizations.
  
  - Weather_Data_CSV_File.csv: The CSV file containing the weather data. You should place this file in the directory where you run the script.
 # Dependencies
  - This project uses the following Python libraries:
      - Pandas: For data manipulation and filtering.
      - Matplotlib: For creating visualizations (line, bar, pie charts).
   ## Install Dependencies
   To install the required libraries, run:
   
     [pip install pandas matplotlib]
# How to Use the Project
  - Clone the repository or download the weather_forecasting.py script and the weather data CSV file.
   
  - Modify the file path in the script to match the location of your CSV file:
   
          - [data = pd.read_csv("path_to_your_file/Weather_Data_CSV_File.csv")]

   - Run the Python script:
     
          - [python weather_forecasting.py]
   - Enter input when prompted:
      - Cities: Provide a comma-separated list of cities you want to visualize.
     
      - Columns: Specify the columns (e.g., temperature, humidity Clouds) you want to visualize.
      - Chart Type: Choose between 'line', 'bar', or 'pie' to visualize the data.
    
     ## Example
         - Enter the cities you want to visualize (comma-separated): Mumbai, Jaipur
     
         - Enter the columns you want to visualize (comma-separated): Temperature, Humidity, Clouds
     
         - Enter the chart type (line, bar,pie): 
## 1. Temperature Over Time   
![Line Chart123](https://github.com/user-attachments/assets/48cb717c-80ca-49d0-81b8-bd758c332e4b)

## 2. Clouds Over Time
![Bar chart 12345](https://github.com/user-attachments/assets/a06e5c37-2f71-4c5e-bf1d-acd10f24f6b4)


## 3. Humidity Over Time
![Pie Chart123](https://github.com/user-attachments/assets/b0d535d8-1679-4982-a7c5-d9caa947f1bf)

# Improvements
  - Add error handling for incorrect city names or columns.

  - Allow users to dynamically select the CSV file.

  - Implement more chart types, like scatter plots or histograms, for advanced data analysis.

# Conclusion
This project provides a simple interface for visualizing weather data across multiple cities. By allowing users to customize their chart preferences, it offers flexibility in analyzing data trends and comparisons.

# License
  - This project is open-source and available under the MIT License.

  - Feel free to contribute or suggest improvements.

# Contact Information
  - For any questions or feedback, feel free to reach out via:

       - Email: shubhamajadhav1306@gmail.com 

       - GitHub: https://github.com/ShubhamJadhav111


    
          
 
