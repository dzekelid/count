swagger: "2.0"
x-collection-name: AWS Route 53
x-complete: 1
info:
  title: AWS Route 53 API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /2013-04-01/geolocation?continentcode=ContinentCode&amp;countrycode=CountryCode&amp;subdivisioncode=SubdivisionCode:
    get:
      summary: Get Geo Location
      description: 'Retrieves a single geo location. Send a GET request to the/2013-04-01/geolocation
        resource with one of these options: continentcode |countrycode | countrycode
        and subdivisioncode.'
      operationId: getgeolocation
      x-api-path-slug: 20130401geolocationcontinentcodecontinentcodeampcountrycodecountrycodeampsubdivisioncodesubdivisioncode-get
      parameters:
      - in: path
        name: continentcode
        description: 'Amazon Route 53 supports the following continent codes:                        AF:
          Africa                        AN: Antarctica                        AS:
          Asia                        EU: Europe                        OC: Oceania                        NA:
          North America                        SA: South AmericaLength Constraints:
          Fixed length of 2'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Locations
  ? /2013-04-01/geolocations&amp;maxitems=MaxItems?startcontinentcode=StartContinentCode&amp;startcountrycode=StartCountryCode&amp;startsubdivisioncode=StartSubdivisionCode
  : get:
      summary: List Geo Locations
      description: Retrieves a list of supported geo locations. Send a GET request
        to the/2013-04-01/geolocations resource. The response to this request includes
        aGeoLocationDetailsList element for each location that Amazon Route 53 supports.Countries
        are listed first, and continents are listed last. If Amazon Route 53 supportssubdivisions
        for a country (for example, states or provinces), the subdivisions for thatcountry
        are listed in alphabetical order immediately after the corresponding country.
      operationId: listgeolocations
      x-api-path-slug: 20130401geolocationsampmaxitemsmaxitemsstartcontinentcodestartcontinentcodeampstartcountrycodestartcountrycodeampstartsubdivisioncodestartsubdivisioncode-get
      parameters:
      - in: path
        name: maxitems
        description: (Optional) The maximum number of geolocations to be included
          in the response body forthis request
        type: string
      responses:
        200:
          description: OK
      tags:
      - Locations
  /2013-04-01/healthcheckcount:
    get:
      summary: Get Health Check Count
      description: To retrieve a count of all your health checks, send a GET request
        to the/2013-04-01/healthcheckcount resource.
      operationId: gethealthcheckcount
      x-api-path-slug: 20130401healthcheckcount-get
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Health
  /2013-04-01/hostedzonecount:
    get:
      summary: Get Hosted Zone Count
      description: Retrieves a count of all your hosted zones. Send a GET request
        to the/2013-04-01/hostedzonecount resource.
      operationId: gethostedzonecount
      x-api-path-slug: 20130401hostedzonecount-get
      responses:
        200:
          description: OK
      tags:
      - Hosted Zones
  /2013-04-01/trafficpolicyinstancecount:
    get:
      summary: Get Traffic Policy Instance Count
      description: Gets the number of traffic policy instances that are associated
        with the current AWSaccount.To get the number of traffic policy instances,
        send a GET request to the/2013-04-01/trafficpolicyinstancecount resource.
      operationId: gettrafficpolicyinstancecount
      x-api-path-slug: 20130401trafficpolicyinstancecount-get
      responses:
        200:
          description: OK
      tags:
      - Traffic Policies