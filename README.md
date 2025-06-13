# super-duper-spork-weather-app


 # **☀️ The Awesome Weather Teller! 🌡️**
 
Ever wondered what the weather's up to in your dream destination (or just your backyard)? Look no further! This snazzy Weather App is here to give you the lowdown on local conditions with just a few keystrokes.

## 🌟 What's the Forecast for Fun?
This app is designed to be your quick and easy weather buddy. Here's what it can do:

City Search: Simply type in any city name, hit Enter, and poof! Instant weather updates.

Real-time Data: Get current temperature, "feels like" conditions, and today's high/low.

Dynamic Displays: See the weather conditions presented clearly and stylishly.

Date Display: Always know what day it is, alongside your weather info.


<img width="1718" alt="Screen Shot 2020-02-25 at 12 25 57 AM" src="https://user-images.githubusercontent.com/31016815/75218407-37a50b80-5768-11ea-9444-20020d17e3d0.png">




## 🛠️ Under the Hood: The Techy Bits
Crafted with the web's foundational trio, this app keeps things snappy and straightforward:

HTML (HyperText Markup Language): The sturdy backbone, structuring all the weather information you see.

CSS (Cascading Style Sheets): The artist, making everything look cool (pun intended!). It handles the layout, fonts, and that awesome background image effect.

JavaScript: The brain, fetching the weather data from the OpenWeatherMap API and making the search box interactive.

## 🚀 Getting Started (It's a Breeze!)
Want to run this weather wizard on your own machine? It's super simple!

Clone or Download: Grab this project from its repository.

Open index.html: Just open the index.html file in your favorite web browser. Seriously, that's it!

API Key Note: The app uses an API key for OpenWeatherMap. If you're planning on deploying this or making significant changes, you might want to consider getting your own API key from OpenWeatherMap for consistent performance and to avoid rate limits. The current key is configured in main.js.

## 📸 A Little Peek at the Sky!

<!-- index.html snippet -->
<div class="app-wrap">
  <header>
    <input type="text" autocomplete="off" class="search-box" placeholder="Search for a city..." />
  </header>
  <main>
    <section class="location">
      <div class="city">Columbus, Ohio</div>
      <div class="date">Tuesday, 25th February 2020</div>
    </section>
    <div class="current">
      <div class="temp">42<span>°c</span></div>
      <div class="weather">Snowy</div>
      <div class="hi-low">13°c / 16°c</div>
    </div>
  </main>
</div>



Got questions? Want to add a new feature like a sun dance? Feel free to reach out! Happy weather watching!
