# <Creating Weather Dashboard: Week-6-Challenge (Server-side APIs)>

## Description

The primary aim of this project was to develop a weather dashboard application, enabling users to search for current and future weather conditions in cities worldwide. Leveraging my knowledge of server-side APIs, I implemented real-time data extraction to provide up-to-date weather information for any user-specified city. The application furnishes users with both the current day forecast and a 5-day forecast, each day represented by a unique icon indicating the prevailing weather. Additionally, temperature (in degrees Fahrenheit), wind speed (MPH), and humidity (%) details are presented for each day. It's worth noting that upon page load, the default city displayed is Austin, TX.
Through the construction of this application, I gained insights into the proper retrieval of data from a server-side API. I learned the significance of utilizing query parameters when making API calls and how to reformat the obtained data for seamless integration into my page, all accomplished using JavaScript. Furthermore, I acquired proficiency in effectively incorporating the Materialize CDN framework within the application, utilizing its grid layout and button functionality to achieve the desired visual aesthetics. This project underscored the intricacies of function reusability and its importance in creating a cohesive and efficient application.

## Live URL

## Screenshot

![Screenshot-week-6-challenge](https://user-images.githubusercontent.com/120127903/226476502-3a8bce9e-6816-4d7a-a7b6-10dd59a2cd8a.png)

## Technologies Used

This project utilizes HTML, CSS, JavaScript, Materialize, and OpenWeather API (server-side API).

## Installation

1. Clone the repo:
   git clone https://github.com/Parvathyaravin/Weather-Dash-board

2. Open in VS Code. If you do not have VS code you must install it.

## Features

This page offers users the capability to load weather data for any city they select, providing real-time current conditions and a 5-day forecast. Upon searching for a city, the associated data is stored in local storage. Subsequently, users can conveniently re-append this stored information to the page using the recent search buttons. This approach minimizes the need to fetch data from the API repeatedly, optimizing the user experience and reducing the number of API calls.
