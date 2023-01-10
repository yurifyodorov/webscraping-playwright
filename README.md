# Web scrapping using playwright
Source: https://github.com/CodeWithOsvaldas/webscraping-playwright-flight-tickets

This script scrapes https://kiwi.com website for cheap weekend flights to any destination and saves the screenshots with the flight details.

### Install dependencies

```
npm install
```

### Modify index.js constants:
```
const DEPARTURE_CITY = 'Yerevan';
const DEPARTURE_CITY_URL_PARAM = 'yerevan-armenia';
const DESTINATION_CITY = 'Istanbul';
const DESTINATION_CITY_URL_PARAM = 'istanbul-turkey';
const DEFAULT_TIMEOUT = 5000;
const PRICE_THRESHOLD = 300;
const NUMBER_OF_WEEKENDS_TO_SEARCH = 10;
```

### Run the script

```
npm run start
```
