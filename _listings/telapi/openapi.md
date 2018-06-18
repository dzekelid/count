---
swagger: "2.0"
x-collection-name: TelAPI
x-complete: 1
info:
  title: hetras Hotel API Version 0
  version: v0
host: api.hetras-certification.net
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/hotel/v0/hotels/{hotelId}/rateplans/$count:
    get:
      summary: Get the count of all rateplans in the hotel matching the given filter
        criteria.
      description: Get the count of all rateplans in the hotel matching the given
        filter criteria..
      operationId: RatePlans_GetRateplansCount
      x-api-path-slug: apihotelv0hotelshotelidrateplanscount-get
      parameters:
      - in: header
        name: App-Id
        description: Application identifier
      - in: header
        name: App-Key
        description: Application key
      - in: query
        name: baseRateplan
        description: Return all rateplans having the specified rateplan as base rateplan
      - in: query
        name: channelCode
        description: Return all rateplans sold through the specified channel
      - in: query
        name: channelGroup
        description: Return all rateplans that are sold through at least one channel
          out of the specified channel group
      - in: query
        name: commissionable
        description: Return all rateplans having commisionable status
      - in: query
        name: group
        description: Return all rateplans belonging to the specified rateplan group
      - in: path
        name: hotelId
        description: The hotel you are counting the rateplans for
      - in: query
        name: includedServices
        description: Return all rateplans having at least one of the specified services
          included
      - in: query
        name: marketCodes
        description: Return all rateplans having one of the specified values as a
          market code
      - in: query
        name: roomTypes
        description: Return all rateplans by which at least one of the specified room
          types are sold
      - in: query
        name: sellingStatus
        description: Specify which rateplans to return
      responses:
        200:
          description: OK
      tags:
      - Count
      - Of
      - ""
      - Rateplans
      - In
      - Hotel
      - Matching
      - Given
      - Filter
      - Criteria
  /api/hotel/v0/hotels/{hotelId}/rateplans/{rateplanCode}/rates/$count:
    get:
      summary: Get the count of all active and loaded daily rates for the defined
        rateplan in a specified time period.
      description: Get the count of all active and loaded daily rates for the defined
        rateplan in a specified time period..
      operationId: RatePlans_GetRatesCount
      x-api-path-slug: apihotelv0hotelshotelidrateplansrateplancoderatescount-get
      parameters:
      - in: header
        name: App-Id
        description: Application identifier
      - in: header
        name: App-Key
        description: Application key
      - in: query
        name: from
        description: Defines the last business day you would like to get rates for
      - in: path
        name: hotelId
        description: The hotel id the rateplan belongs to
      - in: path
        name: rateplanCode
        description: The code of the rateplan you want to count daily rates for
      - in: query
        name: to
        description: Defines the first business day you would like to get rates for
      responses:
        200:
          description: OK
      tags:
      - Count
      - Of
      - ""
      - Active
      - Loaded
      - Daily
      - Ratesthe
      - Defined
      - Rateplan
      - In
      - Specified
      - Time
      - Period
  /api/hotel/v0/hotels/{hotelId}/rooms/$count:
    get:
      summary: Get the count of all rooms in the hotel matching the given filter criteria.
      description: Get the count of all rooms in the hotel matching the given filter
        criteria..
      operationId: Rooms_GetRoomsCount
      x-api-path-slug: apihotelv0hotelshotelidroomscount-get
      parameters:
      - in: query
        name: amenities
        description: Return result only for rooms having all of the given amenities
      - in: header
        name: App-Id
        description: Application identifier
      - in: header
        name: App-Key
        description: Application key
      - in: query
        name: conditions
        description: Return results only for rooms that have the given room condition
          status
      - in: path
        name: hotelId
        description: The hotel you are counting the rooms for
      - in: query
        name: locations
        description: Return result only for rooms having at least one of the specified
          locations
      - in: query
        name: maintenances
        description: Return results only for rooms that have the given maintenance
          status
      - in: query
        name: occupancy
        description: Return results only for rooms that have the given frontdesk ocuppancy
          status
      - in: query
        name: roomTypes
        description: Return result only for rooms for the given room types
      - in: query
        name: views
        description: Return result only for rooms having at least one of the specified
          views
      responses:
        200:
          description: OK
      tags:
      - Count
      - Of
      - ""
      - Rooms
      - In
      - Hotel
      - Matching
      - Given
      - Filter
      - Criteria
---