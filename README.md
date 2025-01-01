# DEVELOP-A-WEBPAGE-THAT-FETCHES-AND-DISPLAYS-DATA-FROM-A-PUBLIC-API-WEATHER-NEWS-R-

***COMPANY** CODETECH IT SOLUTIONS

***NAME*** APEKSHA MOHAN ZANZANE

*** INTERN ID*** CTO8FYM

***DOMAIN NAME*** FULLSTACK WEBDEVLOPMENT 

***BATCH DURATION*** DECEMBER 25TH,2024 TO JANUARY 25TH,2025
*** MENTOR NAME*** NEELA SANTOSH KUMAR

#DESCRIPTION 
1.Get the API Key from OpenWeatherMap:
Sign up on OpenWeatherMap at OpenWeatherMap API.
Obtain an API key after logging in.
2.Create the Webpage:
HTML for structure.
CSS for styling and responsiveness.
JavaScript to fetch and display weather data dynamically.
Key Features:
Responsive Layout:
The page automatically adjusts its layout depending on the screen size. On mobile devices, the input field and button become more compact.
Dynamic Content Loading:
Weather data is fetched dynamically and displayed without reloading the page. This is done using the JavaScript fetch() function.
Error Handling:
If the user inputs an invalid city or there’s an issue with the API call, an error message is shown. This improves the user experience by providing feedback.
How It Works:
User Interface (UI):
The page has a simple search bar where users can enter the name of a city and click on the "Get Weather" button.
The weather information will be dynamically displayed below the search bar.
API Integration (OpenWeatherMap):
The JavaScript function getWeather() is called when the user clicks the button.
It fetches the weather data for the city entered by the user using the OpenWeatherMap API.
The API key is included in the request URL. Replace 'YOUR_API_KEY' with your actual API key obtained from OpenWeatherMap.
Keywords and Concepts
API Key:

A unique code provided by OpenWeatherMap after signing up, used to authenticate and authorize requests to the OpenWeatherMap API.
OpenWeatherMap:

A popular public API service that provides weather data globally, including current weather, forecasts, and historical data.
HTML (HyperText Markup Language):

The standard markup language used to structure content on the web, such as headings, paragraphs, forms, and buttons.
CSS (Cascading Style Sheets):

A style sheet language used to control the appearance of the webpage. It defines things like colors, fonts, layouts, and responsiveness for different screen sizes.
JavaScript:

A programming language used to create dynamic and interactive web pages. It allows the webpage to fetch weather data from an API and display it without reloading the page.
Fetch API:

A JavaScript method used to make HTTP requests to external resources, such as fetching data from OpenWeatherMap. It enables asynchronous data retrieval without reloading the page.
Responsive Layout:

A design technique that ensures the webpage adjusts to various screen sizes, such as desktops, tablets, and mobile devices. This makes the webpage mobile-friendly and improves user experience on all devices.
Dynamic Content Loading:

The process of updating webpage content in real-time without requiring the page to reload. In this case, weather data is loaded dynamically when the user searches for a city.
Error Handling:

A method for managing potential issues like invalid user input or API call failures. In the example, an error message is shown if the city entered doesn't exist or if there’s a problem with the API.
User Interface (UI):

The space where users interact with the webpage. The search bar for entering the city name, the "Get Weather" button, and the displayed weather details are all part of the UI.
API Integration:

The process of connecting the webpage with the OpenWeatherMap API, allowing the webpage to send requests and retrieve weather data based on the user's input.
getWeather() function:

A JavaScript function that gets called when the user clicks the "Get Weather" button. This function makes a request to the OpenWeatherMap API and displays the fetched weather data on the page.
Request URL:

The URL used in the API call that includes parameters like the city name and API key. The URL specifies the data to be fetched from the OpenWeatherMap API.
'YOUR_API_KEY':

A placeholder that should be replaced with the actual API key you obtain from OpenWeatherMap to make the API call functional.
This webpage utilizes HTML for structure, CSS for design and responsiveness, and JavaScript to fetch and display weather data dynamically using the OpenWeatherMap API. The fetch() function is used to get the data without refreshing the page, while the UI includes a simple search bar and button for users to input the city name. Error handling is implemented to manage invalid inputs or API issues, improving the user experience. The API Key is essential for authenticating the requests made to OpenWeatherMap.
