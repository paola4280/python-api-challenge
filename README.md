# python-api-challenge
This challenge includes some API handling.

-The code for this activity is found under the WeatherPy folder. There are two notebook files ("VacationPY" and "WeatherPY") with the code and an "output_data" folder with pictures and data files.

-The activity aimed to use APIs to acquire data from outside sources by using an API URL and the respective key. Another activity was to transform the JSON () response into data frames to visualize it on scatter plots and into maps. 

-The tools to complete this challenge included class notes, Jupyter notebooks, the geoViews Python Catalog, the Geoapify API Catalog, the  OpenWeatherMap API Catalog, AskBCS Learning, and ChatGPT.

-Due to debugging, some of the code used from outside sources such as ChatGPT and other online resources is listed below:
  -"city_data_df['scaled_humidity'] = np.interp(city_data_df['Humidity'],   
   (city_data_df['Humidity'].min(), city_data_df['Humidity'].max()), (min_size, max_size))"
  -"city_data_df['color'] = np.random.choice(['red', 'green', 'blue', 'orange', 'purple', 'brown', 
    'pink', 'cyan'], len(city_data_df))"
  - "params["filter"] = f"circle:{longitude},{latitude},{radius}"" (Geoapify catalog)
  - "params["bias"] = f"proximity:{longitude},{latitude}""


