---
swagger: "2.0"
x-collection-name: PredictHQ
x-complete: 1
info:
  title: PredictHQ API
  description: todo-add-description
  version: 1.0.0
host: api.predicthq.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/events/count/:
    get:
      summary: Retrieve Events Count
      description: This endpoint accepts the same parameters as the ones described
        in Retrieve All Events and can be used to get aggregated counts of all matching
        events that are available to your account.
      operationId: V1EventsCountGet
      x-api-path-slug: v1eventscount-get
      responses:
        200:
          description: OK
      tags:
      - Events
      - Count
---