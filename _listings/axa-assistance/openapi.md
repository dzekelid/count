---
swagger: "2.0"
x-collection-name: AXA Assistance
x-complete: 1
info:
  title: AXA Assistance
  description: axa-assistance-is-a-worldwide-specialist-for-car-insurance-travel-health-and-home-services--trust-in-axa-assistance-for-your-insurance
  version: 1.0.0
host: sandbox.api.axa-assistance.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /information/v1/countries:
    get:
      summary: Retrieve all countries
      description: Retrieve all countries
      operationId: getInformationV1Countries
      x-api-path-slug: informationv1countries-get
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Retrieve
      - all
      - countries
  /information/v1/countries/{country_id}:
    get:
      summary: Retrieve a country detail
      description: Retrieve a country detail
      operationId: getInformationV1CountriesCountry_id
      x-api-path-slug: informationv1countriescountry-id-get
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      - in: path
        name: country_id
        description: country id
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Retrievecountry
      - detail
  /information/v1/countries/{country_id}/security_cards:
    get:
      summary: Retrieve security information for a country
      description: Retrieve security information for a country
      operationId: getInformationV1CountriesCountry_idSecurity_cards
      x-api-path-slug: informationv1countriescountry-idsecurity-cards-get
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      - in: path
        name: country_id
        description: country id
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Retrieve
      - security
      - informationa
      - country
  /information/v1/countries/{country_id}/health_cards:
    get:
      summary: Retrieve health information for a country
      description: Retrieve health information for a country
      operationId: getInformationV1CountriesCountry_idHealth_cards
      x-api-path-slug: informationv1countriescountry-idhealth-cards-get
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      - in: path
        name: country_id
        description: country id
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Retrieve
      - health
      - informationa
      - country
  /information/v1/countries/{country_id}/alerts:
    get:
      summary: Retrieve the latest alerts for a specified country
      description: Retrieve the latest alerts for a specified country
      operationId: getInformationV1CountriesCountry_idAlerts
      x-api-path-slug: informationv1countriescountry-idalerts-get
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      - in: path
        name: country_id
        description: country id
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Retrieve
      - the
      - latest
      - alertsa
      - specified
      - country
  /user/v1/identities/register/confirm/resend:
    post:
      summary: Resends the confirmation email to an identity account
      description: Resends the confirmation email to an identity account
      operationId: postUserV1IdentitiesRegisterConfirmResend
      x-api-path-slug: userv1identitiesregisterconfirmresend-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - ResendAssistance
      - the
      - confirmation
      - email
      - toidentity
      - account
---