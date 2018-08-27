---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 0
info:
  title: Shopify Get a count of all articles from a certain blog
  description: Get a count of all articles from a certain blog.
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/pages/count.json:
    get:
      summary: Count all pages for a shop
      description: Count all pages for a shop.
      operationId: getAdminPagesCount.json
      x-api-path-slug: adminpagescount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Pagesa
      - Shop
  /admin/orders/4554953422/transactions/count.json:
    get:
      summary: Get a count of transactions for an order
      description: Get a count of transactions for an order.
      operationId: getAdminOrders4554953422TransactionsCount.json
      x-api-path-slug: adminorders4554953422transactionscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Transactionsan
      - Order
  /admin/gift_cards/count.json:
    get:
      summary: Retrieve a count of all gift cards
      description: Retrieve a count of all gift cards.
      operationId: getAdminGiftCardsCount.json
      x-api-path-slug: admingift-cardscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - Count
      - Gift
      - Cards
  /admin/blogs/62581763/articles/count.json:
    get:
      summary: Get a count of all articles from a certain blog
      description: Get a count of all articles from a certain blog.
      operationId: getAdminBlogs62581763ArticlesCount.json
      x-api-path-slug: adminblogs62581763articlescount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Articles
      - From
      - Certain
      - Blog
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