# apex_getweather
Dynamic Action APEX plugin to get weather data

Use this Plugin to fetch weather data from https://openweathermap.org/ and show this in APEX page items.

At the moment the selected location will be localized by geographic coordinates (lat, lon). The results are the temperature, conditions and weather icon.

### The parameters of this plugin are:

| Parameter        | Description           | Field           |
| ------------- |:-------------:| :-------------:|
| API_KEY      | your OpenWeathermap API_KEY | TEXT |
| LATITUDE      | APEX_Field with the Latitude      | PAGE ITEM |
| LONGITUDE | APEX_Field with the Longitude     | PAGE ITEM |
| TEMPERATURE ITEM | APEX_Field for setting the temperature value      | PAGE ITEM |
| CONDITIONS | APEX_Field for setting the condition value     | PAGE ITEM |
| ICON | APEX_Field for the conditions icon      | PAGE ITEM |
