---
swagger: "2.0"
x-collection-name: Eventbrite
x-complete: 0
info:
  title: Eventbrite Get System Countries
  description: |-
    Returns a single page response with a key of countries,
    containing a list of countries.
  version: 1.0.0
host: www.eventbrite.com
basePath: /%7Bdata-type%7D/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /checkout_settings/countries_currencies/:
    get:
      summary: Get Checkout Settings Countries Currencies
      description: Get the countries and currencies which are supported by Eventbrite
        for ticket payment
      operationId: getCheckoutSettingsCountriesCurrencies
      x-api-path-slug: checkout-settingscountries-currencies-get
      responses:
        200:
          description: OK
      tags:
      - Checkout
      - Settings
      - Countries
      - Currencies
  /discounts/:discount_id/:
    get:
      summary: Get Discounts Discount
      description: Returns the cross_event_discount with the specified :discount_id.
      operationId: getDiscountsDiscount
      x-api-path-slug: discountsdiscount-id-get
      responses:
        200:
          description: OK
      tags:
      - Discounts
      - :discount
    post:
      summary: Post Discounts Discount
      description: Updates the discount with the specified :discount_id. Returns the
        updated cross_event_discount. The fields sent are the ones that are going
        to be updated, the fields that are not sent will be unchanged. The same conditions
        and notes for the discount creation apply.
      operationId: postDiscountsDiscount
      x-api-path-slug: discountsdiscount-id-post
      parameters:
      - in: query
        name: discount.amount_off
        description: Fixed reduction amount
        type: query
      - in: query
        name: discount.code
        description: Code used to activate discount
        type: query
      - in: query
        name: discount.end_date
        description: Allow use until this date
        type: query
      - in: query
        name: discount.end_date_relative
        description: Allow use until this number of seconds before the event starts
        type: query
      - in: query
        name: discount.hold_ids
        description: IDs of holds this discount can unlock
        type: query
      - in: query
        name: discount.percent_off
        description: Percentage reduction
        type: query
      - in: query
        name: discount.quantity_available
        description: Number of discount uses
        type: query
      - in: query
        name: discount.start_date
        description: Allow use from this date
        type: query
      - in: query
        name: discount.start_date_relative
        description: Allow use from this number of seconds before the event starts
        type: query
      - in: query
        name: discount.ticket_class_ids
        description: IDs of tickets to limit discount to
        type: query
      responses:
        200:
          description: OK
      tags:
      - Discounts
      - :discount
    delete:
      summary: Delete Discounts Discount
      description: |-
        Deletes the cross_event_discount with the specified :discount_id.
        Only unused discounts can be deleted.
      operationId: deleteDiscountsDiscount
      x-api-path-slug: discountsdiscount-id-delete
      responses:
        200:
          description: OK
      tags:
      - Discounts
      - :discount
  /discounts/:
    post:
      summary: Post Discounts
      description: Creates a discount. Returns the created cross_event_discount.
      operationId: postDiscounts
      x-api-path-slug: discounts-post
      parameters:
      - in: query
        name: discount.amount_off
        description: Fixed reduction amount
        type: query
      - in: query
        name: discount.code
        description: Code used to activate discount
        type: query
      - in: query
        name: discount.end_date
        description: Allow use until this date
        type: query
      - in: query
        name: discount.end_date_relative
        description: Allow use until this number of seconds before the event starts
        type: query
      - in: query
        name: discount.event_id
        description: ID of the event
        type: query
      - in: query
        name: discount.hold_ids
        description: IDs of holds this discount can unlock
        type: query
      - in: query
        name: discount.percent_off
        description: Percentage reduction
        type: query
      - in: query
        name: discount.quantity_available
        description: Number of discount uses
        type: query
      - in: query
        name: discount.start_date
        description: Allow use from this date
        type: query
      - in: query
        name: discount.start_date_relative
        description: Allow use from this number of seconds before the event starts
        type: query
      - in: query
        name: discount.ticket_class_ids
        description: IDs of tickets to limit discount to
        type: query
      - in: query
        name: discount.ticket_group_id
        description: ID of the ticket group
        type: query
      - in: query
        name: discount.type
        description: The type of discount
        type: query
      responses:
        200:
          description: OK
      tags:
      - Discounts
  /events/{id}/discounts/:
    get:
      summary: Get Events Discounts
      description: Please use https://www.eventbrite.com/developer/v3/endpoints/users/#ebapi-get-users-user-id-discounts
      operationId: getEventsDiscounts
      x-api-path-slug: eventsiddiscounts-get
      responses:
        200:
          description: OK
      tags:
      - Events
      - Discounts
    post:
      summary: Post Events Discounts
      description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-post-discounts
      operationId: postEventsDiscounts
      x-api-path-slug: eventsiddiscounts-post
      responses:
        200:
          description: OK
      tags:
      - Events
      - Discounts
  /events/{id}/discounts/:discount_id/:
    get:
      summary: Get Events Discounts Discount
      description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-get-discounts-discount-id
      operationId: getEventsDiscountsDiscount
      x-api-path-slug: eventsiddiscountsdiscount-id-get
      responses:
        200:
          description: OK
      tags:
      - Events
      - Discounts
      - :discount
    post:
      summary: Post Events Discounts Discount
      description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-post-discounts-discount-id
      operationId: postEventsDiscountsDiscount
      x-api-path-slug: eventsiddiscountsdiscount-id-post
      responses:
        200:
          description: OK
      tags:
      - Events
      - Discounts
      - :discount
    delete:
      summary: Delete Events Discounts Discount
      description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-delete-discounts-discount-id
      operationId: deleteEventsDiscountsDiscount
      x-api-path-slug: eventsiddiscountsdiscount-id-delete
      responses:
        200:
          description: OK
      tags:
      - Events
      - Discounts
      - :discount
  /events/{id}/public_discounts/:
    get:
      summary: Get Events Public Discounts
      description: Please use https://www.eventbrite.com/developer/v3/endpoints/users/#ebapi-get-users-user-id-discounts
      operationId: getEventsPublicDiscounts
      x-api-path-slug: eventsidpublic-discounts-get
      responses:
        200:
          description: OK
      tags:
      - Events
      - Public
      - Discounts
    post:
      summary: Post Events Public Discounts
      description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-post-discounts
      operationId: postEventsPublicDiscounts
      x-api-path-slug: eventsidpublic-discounts-post
      responses:
        200:
          description: OK
      tags:
      - Events
      - Public
      - Discounts
  /events/{id}/public_discounts/:discount_id/:
    get:
      summary: Get Events Public Discounts Discount
      description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-get-discounts-discount-id
      operationId: getEventsPublicDiscountsDiscount
      x-api-path-slug: eventsidpublic-discountsdiscount-id-get
      responses:
        200:
          description: OK
      tags:
      - Events
      - Public
      - Discounts
      - :discount
    post:
      summary: Post Events Public Discounts Discount
      description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-post-discounts-discount-id
      operationId: postEventsPublicDiscountsDiscount
      x-api-path-slug: eventsidpublic-discountsdiscount-id-post
      responses:
        200:
          description: OK
      tags:
      - Events
      - Public
      - Discounts
      - :discount
    delete:
      summary: Delete Events Public Discounts Discount
      description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-delete-discounts-discount-id
      operationId: deleteEventsPublicDiscountsDiscount
      x-api-path-slug: eventsidpublic-discountsdiscount-id-delete
      responses:
        200:
          description: OK
      tags:
      - Events
      - Public
      - Discounts
      - :discount
  /system/countries/:
    get:
      summary: Get System Countries
      description: |-
        Returns a single page response with a key of countries,
        containing a list of countries.
      operationId: getSystemCountries
      x-api-path-slug: systemcountries-get
      responses:
        200:
          description: OK
      tags:
      - System
      - Countries
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---