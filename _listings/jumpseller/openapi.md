swagger: "2.0"
x-collection-name: Jumpseller
x-complete: 1
info:
  title: Jumpseller
  description: explore-all-our-endpoints-with-your-own-set-of-of-access-tokens--all-changes-affect-your-production-jumpseller-store-
  version: "1"
host: api.jumpseller.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /products/category/{category_id}/count.json:
    get:
      summary: Get Products Category Category Count
      description: ""
      operationId: getProductsCategoryCategoryCount.json
      x-api-path-slug: productscategorycategory-idcount-json-get
      parameters:
      - in: path
        name: category_id
        description: Category ID of the Product used as filter
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
      - Category
      - Category
      - Id
      - Count
      - Json
  /products/count.json:
    get:
      summary: Get Products Count
      description: ""
      operationId: getProductsCount.json
      x-api-path-slug: productscount-json-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
      - Count
      - Json
  /products/status/{status}/count.json:
    get:
      summary: Get Products Status Status Count
      description: ""
      operationId: getProductsStatusStatusCount.json
      x-api-path-slug: productsstatusstatuscount-json-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: status
        description: Status of the Product used as filter
      responses:
        200:
          description: OK
      tags:
      - Products
      - Status
      - Status
      - Count
      - Json
  /products/{id}/fields/count.json:
    get:
      summary: Get Products Fields Count
      description: ""
      operationId: getProductsFieldsCount.json
      x-api-path-slug: productsidfieldscount-json-get
      parameters:
      - in: path
        name: id
        description: ID of the Product
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
      - Id
      - Fields
      - Count
      - Json
  /products/{id}/images/count.json:
    get:
      summary: Get Products Images Count
      description: ""
      operationId: getProductsImagesCount.json
      x-api-path-slug: productsidimagescount-json-get
      parameters:
      - in: path
        name: id
        description: ID of the Product
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
      - Id
      - Images
      - Count
      - Json
  /products/{id}/options/count.json:
    get:
      summary: Get Products Options Count
      description: ""
      operationId: getProductsOptionsCount.json
      x-api-path-slug: productsidoptionscount-json-get
      parameters:
      - in: path
        name: id
        description: ID of the Product
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
      - Id
      - Options
      - Count
      - Json
  /products/{id}/options/{option_id}/values/count.json:
    get:
      summary: Get Products Options Option Values Count
      description: ""
      operationId: getProductsOptionsOptionValuesCount.json
      x-api-path-slug: productsidoptionsoption-idvaluescount-json-get
      parameters:
      - in: path
        name: id
        description: ID of the Product
      - in: query
        name: No Name
      - in: path
        name: option_id
        description: ID of the Product Option
      responses:
        200:
          description: OK
      tags:
      - Products
      - Id
      - Options
      - Option
      - Id
      - Values
      - Count
      - Json
  /products/{id}/variants/count.json:
    get:
      summary: Get Products Variants Count
      description: ""
      operationId: getProductsVariantsCount.json
      x-api-path-slug: productsidvariantscount-json-get
      parameters:
      - in: path
        name: id
        description: ID of the Product
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
      - Id
      - Variants
      - Count
      - Json