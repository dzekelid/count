---
name: Weatherbit.io
x-slug: weatherbit-io
description: Our Weather API is the most powerful Weather data API on the web. Sign
  up for our free Weather API, and upgrade as your weather data needs grow!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
x-kinRank: "8"
x-alexaRank: "1016253"
tags: Count
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/weatherbit-io/apis.md
specificationVersion: "0.14"
apis:
- name: Weatherbit Get Bulk History Daily City Country
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a city in the format of City,ST
    or City. The state, and country parameters can be provided to make the search
    more accurate.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/daily?city={city}&country={country}
  tags: Weather,Bulk, History, Daily, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/weatherbit-io/bulkhistorydailycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/weatherbit-io/bulkhistorydailycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get Bulk History Hourly City & Country
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a city in the format of City,ST
    or City. The state, and country parameters can be provided to make the search
    more accurate.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/hourly?city={city}&country={country}
  tags: Weather,Bulk, History, Hourly, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/weatherbit-io/bulkhistoryhourlycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/weatherbit-io/bulkhistoryhourlycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get Forecast 3hourly City & Country
  x-api-slug: weatherbit
  description: Returns a 3-hourly forecast, where each point represents a three hour   period.
    Every point has a datetime string in the format "YYYY-MM-DD:HH". Time is UTC.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/3hourly?city={city}&country={country}
  tags: Weather,Forecast, 3hourly, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/weatherbit-io/forecast3hourlycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/weatherbit-io/forecast3hourlycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get Forecast Daily City & Country
  x-api-slug: weatherbit
  description: '**(REQUIRED: Basic Plan or Higher)** Returns a daily forecast, where
    each point represents one day (24hr) period. Every point has a datetime string
    in the format "YYYY-MM-DD". One day begins at 00:00 UTC, and ends at 23:59 UTC.
    Accepts a city in the format of City,ST or City. The state, and country parameters
    can be provided to make the search more accurate.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/daily?city={city}&country={country}
  tags: Weather,Forecast, Daily, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/weatherbit-io/forecastdailycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/weatherbit-io/forecastdailycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get Forecast Hourly City & Country
  x-api-slug: weatherbit
  description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
    where each point represents a one hour   period. Every point has a datetime string
    in the format "YYYY-MM-DD:HH". Time is UTC. Accepts a city in the format of City,ST
    or City. The state, and country parameters can be provided to make the search
    more accurate.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/hourly?city={city}&country={country}
  tags: Weather,Forecast, Hourly, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/weatherbit-io/forecasthourlycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/weatherbit-io/forecasthourlycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get History Daily City & Country
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a city in the format of City,ST
    or City. The state, and country parameters can be provided to make the search
    more accurate. **(LIMIT 1 day for Low Volume plans. LIMIT 7 days for Basic/Developer.
    LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/daily?city={city}&country={country}
  tags: Weather,History, Daily, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/weatherbit-io/historydailycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/weatherbit-io/historydailycitycitycountrycountry-get-openapi.md
- name: Weatherbit Get History Hourly City & Country
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a city in the format of City,ST
    or City. The state, and country parameters can be provided to make the search
    more accurate. **(LIMIT 1 day for Low Volume plans. LIMIT 7 days for Basic/Developer.
    LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/hourly?city={city}&country={country}
  tags: Weather,History, Hourly, City, City, &country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/weatherbit-io/historyhourlycitycitycountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/weatherbit-io/historyhourlycitycitycountrycountry-get-openapi.md
- name: Weatherbit
  x-api-slug: weatherbit
  description: Our Weather API is the most powerful Weather data API on the web. Sign
    up for our free Weather API, and upgrade as your weather data needs grow!
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28119-weatherbit.jpg
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/weatherbit-io/openapi.md
x-common:
- type: x-blog
  url: https://www.weatherbit.io/blog
- type: x-contact-form
  url: https://www.weatherbit.io/contact
- type: x-crunchbase
  url: https://crunchbase.com/organization/product/weather-it-
- type: x-documentation
  url: https://www.weatherbit.io/api
- type: x-email
  url: support@weatherbit.io
- type: x-github
  url: https://github.com/weatherbit
- type: x-pricing
  url: https://www.weatherbit.io/pricing
- type: x-twitter
  url: https://twitter.com/weatherbitio
- type: x-website
  url: http://weatherbit.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---