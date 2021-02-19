# apex_getweather
Dynamic Action APEX plugin to get weather data

Use this Plugin to fetch weather data from https://openweathermap.org/ and show this in APEX page items.

At the moment the selected location will be localized by geographic coordinates (lat, lon). The results are the temperature, conditions and weather icon.

[Here](https://apex.oracle.com/pls/apex/cc13/r/getweather/show-building) you can see an example page. Select a building and the weather data will fetched live in the backround.


### Installation

Before you start you have to create an account on https://openweathermap.org/. For the first steps and for testing there is a possibility to use it for free. After creating the account and sign in, you have to create the API key to use it in the plugin later.

1. Download the file "dynamic_action_plugin_com_cc13_getweather.sql"
2. Install this plugin in your APEX application
3. Add the needed APEX fields on your page (see picture)
4. Create a Dynamic Action "GetWeather"

### The parameters of this plugin are:

| Parameter        | Description           | Field           |
| ------------- |:-------------:| :-------------:|
| API_KEY      | your OpenWeathermap API_KEY | TEXT |
| LATITUDE      | APEX_Field with the Latitude      | PAGE ITEM |
| LONGITUDE | APEX_Field with the Longitude     | PAGE ITEM |
| TEMPERATURE ITEM | APEX_Field for setting the temperature value      | PAGE ITEM |
| CONDITIONS | APEX_Field for setting the condition value     | PAGE ITEM |
| ICON | APEX_Field for the conditions icon      | PAGE ITEM |

![Image of needed Page Items](https://cc13.com/bilder/GetWeather_Items.png)


### How it looks at the end

![Image of needed Page Items](https://cc13.com/bilder/GetWeather_Result.png)

### ToDos

* localization via City and/or ZIP Code
* adding more details like min/max temp, wind speed, humidity and pressure
