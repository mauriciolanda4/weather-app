# 5-Day Weather Forecast

A simple application to display 5-day weather forecast using the OpenWeatherMap API showing the overall weather for the day as an image, along with the expected High and Low temperature for the day and the average humidity of that day by percentage.

it asks for permission to get the weather for your current location and offers the user the possibility to search by city name.

weather images comes from the API itself.

other icons/images are being retrieved from a bucket in AWS S3.

## Pre-requisites

- Node.js 10.16.0 and above
- npm 6.9.2 and above

## Run

```
git clone https://github.com/MauricioLanda/weather-app
cd weather-app
npm i
```

## Start the dev server

```

npm run start:dev

```

## Build

```

npm run build

```

#### Notes:

- Running the build bundles all your updates to `bundle.js` and `bundle.css` in dist folder.
- If you insist to automate the build upon appending changes to files, use `webpack --watch`
- Project runs at http://localhost:8080/
- Webpack output comes from /
- Content that is not related to webpack comes from ./public/

## Test

```

npm run test

```

#### Notes:

- Unit testing can be done manually by executing the above command.
- It will be done automatically prior committing the updates to the repo as a pre-commit hook.

### Tech Stack

- React (16.2.0)
- Redux (5.0.7)
- JavaScript (ES6)
- HTML5
- SASS/SCSS
- Jest + Enzyme
- AWS
- Webpack (3.11.0)
- Axios (0.19.0)
- Prettier (for code formatting; personalized file for react code)
