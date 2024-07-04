### Day Weather Forecast App

Welcome to the **Day Weather Forecast App**! This project is a simple yet powerful weather forecasting tool built using Streamlit and PyOWM (Python wrapper for OpenWeatherMap API). It allows users to get a 5-day weather forecast for any city, with options to view the data in either Celsius or Fahrenheit and display it as a line or bar graph.

#### Features
- **City Weather Forecast**: Get a 5-day weather forecast for any city.
- **Temperature Units**: Choose between Celsius and Fahrenheit.
- **Graph Types**: Display the forecast as a line graph or a bar graph.
- **Additional Weather Information**: Provides details on impending weather changes, cloud coverage, wind speed, and sunrise/sunset times.

#### Installation

1. **Clone the repository**:
    ```bash
    git clone git clone https://github.com/Karthik-GigaByte/Day-Weather-Forecast-App.git
    cd day-weather-forecast-app
    ```

2. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Get an OpenWeatherMap API Key**:
    - Sign up at [OpenWeatherMap](https://home.openweathermap.org/users/sign_up) to get a free API key.
    - Replace `'your_api_key_here'` in the code with your actual API key.

#### Usage

1. **Run the Streamlit app**:
    ```bash
    streamlit run app.py
    ```

2. **Interact with the app**:
    - Enter the name of the city.
      ![Interface](https://github.com/Karthik-GigaByte/Image/blob/main/Screenshot%202024-07-04%20180215.png)
    - Select the temperature unit (Celsius or Fahrenheit).
      ![Temperature](https://github.com/Karthik-GigaByte/Image/blob/main/Temperature.png)
    - Choose the type of graph (Line Graph or Bar Graph).
      ![Graph](https://github.com/Karthik-GigaByte/Image/blob/main/Graph.png)
    - View the Graphs.
      - Line Graph
        ![Graph](https://github.com/Karthik-GigaByte/Image/blob/main/Line%20Graph.png)
      - Bar Graph
        ![Graph](https://github.com/Karthik-GigaByte/Image/blob/main/Bar%20Graph.png)
    - View the forecast and additional weather information.
      ![Forecast](https://github.com/Karthik-GigaByte/Image/blob/main/Weather%20info.png)
