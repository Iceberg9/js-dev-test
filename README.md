# Prueba Técnica - JS full Stack
## Justificación
Las siguientes pruebas buscan probar los conocimiento intermedios sobre:
- JavaScript 
- HTML
- CSS
- SASS


## Prueba técnica - App del Clima
### Brief

Construir una app web que permita mostrar información relevante sobre el clima de una ciudad  en concreto.

La información a mostrar es:
- Temperatura
- Condición climatica
- Velocidad del viento
- % de humedad

### Requerimientos

Consumir mediante JS el API de [Weather API - OpenWeatherMap](https://openweathermap.org/api) (versión gratuita, necesitas registrarte para obtener credenciales [How to start to work with Openweather API - OpenWeatherMap](https://openweathermap.org/appid)) y solo utilizar el método para tiempo actual (current) y hacer la petición por ciudad:
[Current weather data - OpenWeatherMap](https://openweathermap.org/current)
`api.openweathermap.org/data/2.5/weather?q={city name}`

De la respuesta usar los nodos de:
- weather.description
- weather.icon (Leer requerimientos)
- main.temp
- main.temp_min
- main.temp_max
- wind.speed

Para las estados/ciudades, usar [Mexican Dropdown Maker | INEGI fácil](http://inegifacil.com/dropdowns) para generar los dos inputs select (uno para estado y otro para ciudad).

Los iconos deben de ser de la siguiente librería: [Weather Icons - 222 font icons inspired by Font Awesome and designed for Bootstrap](https://erikflowers.github.io/weather-icons/)

Cambiando la lista oficial de OpenWeather por la siguiente relación:
[Weather Conditions - OpenWeatherMap](https://openweathermap.org/weather-conditions)
Day icons
01d.png  clear sky ---> wi-day-sunny
02d.png  few clouds ---> wi-day-cloudy
03d.png  scattered clouds ---> wi-cloud
04d.png  broken clouds ---> wi-cloudy
09d.png  shower rain ---> wi-showers
10d.png  rain ---> wi-rain
11d.png  thunderstorm ---> wi-thunderstorm
13d.png  snow ---> wi-snowflake-cold
50d.png  mist ---> wi-dust

Night icons
01n.png  	clear sky ---> wi-night-clear
02n.png  	few clouds --->	wi-night-alt-cloudy		
03n.png  	scattered clouds ---> wi-cloud
04n.png  	broken clouds ---> wi-cloudy
09n.png  	shower rain ---> wi-showers
10n.png  	rain ---> wi-rain
11n.png  	thunderstorm ---> wi-thunderstorm
13n.png  	snow ---> wi-snowflake-cold
50n.png  	mist ---> wi-dust

Visualmente debemos poder intercambiar mediante un toggle entre un theme light y otro dark.

La aplicación de clima debe poder recordar al recargar la ultima ciudad seleccionada así como el theme.


### Maqueta
Todos los elementos los encuentras en las librerías previamente mencionadas. Para accesar a la maqueta puedes usar el siguiente enlace:
 [https://sketch.cloud/s/OWqrm](https://sketch.cloud/s/OWqrm) 


### Entrega
Enviar una URL pública para testear la app así como el repositorio en GitHub para la revisión de código a alan@iceberg9.mx



