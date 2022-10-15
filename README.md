# Weather App for US Only - ReactJS + Firebase

<a href='https://weather-app-us-ad60a.web.app/'>
<img src="https://github.com/michal9108/weather-app-US/blob/9d10b7c393e01d6bcd71b8ab615c512c96e38929/Weather-app-US.jpg" onClick="https://weather-app-us-ad60a.web.app/" width="100%" height="100%"/> 
</p>
</a>

## Link

[https://weather-app-us-ad60a.web.app/](https://weather-app-us-ad60a.web.app/)

After entering US city, the weather data are going to be transfered through API.


## Requirements

Before using this project, you will need to have installed [Node.js](https://nodejs.org/en/), npm and [git](https://git-scm.com/) or [yarn](https://yarnpkg.com/).  For accessing API you need to have installed [axios](https://axios-http.com/docs/intro).

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Usage

```
$ git clone https://github.com/michal9108/weather-app-US.git
$ cd weather-app-US.git
$ npm install or yarn install
$ npm i qrcode or yarn add qrcode
$ yarn run dev
```

The application will be listening on port 3000. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

https://openweathermap.org/api

## OpenWeather API

After signing up to [https://openweathermap.org](https://openweathermap.org/) you can subscribe to access the free version of <b>Current Weather Data API</b>. Then  you will receive your own API key. More in information about how to make the API calls and how to choose optional parameters are here: [https://openweathermap.org/current](https://openweathermap.org/current).

To make sure that your API is working propresly you can put it your browser with specified location. For example: `https://api.openweathermap.org/data/2.5/weather?q=Miami&units=metric&appid=API` (instead of API choose your specific API). 

Created response - Your API response - JSON file with all of its weather parameters is very helpfull for setting up App.js 


## Build Setup

```
# install dependencies
$ npm install or yarn install

# serve with hot reload at localhost:3000
$ yarn run dev

# build for production and launch/deploy on Firebase server
$ firebase login
$ yarn run build
$ firebase init

Choose `build` as a public dir

$ firebase deploy
```

For detailed explanation on how things work, check out the [react.js](https://reactjs.org/), [axios](https://axios-http.com/docs/intro) and [Firebase](https://firebase.google.com/docs?authuser=0&hl=en) documentation.

