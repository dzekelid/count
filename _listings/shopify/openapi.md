swagger: "2.0"
x-collection-name: Shopify
x-complete: 1
info:
  title: Shopify API
  description: todo-add-description
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
  /admin/metafields/count.json:
    get:
      summary: Get a count of all metafields for a store
      description: Get a count of all metafields for a store.
      operationId: getAdminMetafieldsCount.json
      x-api-path-slug: adminmetafieldscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Metafieldsa
      - Store
  /admin/products/7990943555/metafields/count.json:
    get:
      summary: Get a count of all metafields that belong to a product
      description: Get a count of all metafields that belong to a product.
      operationId: getAdminProducts7990943555MetafieldsCount.json
      x-api-path-slug: adminproducts7990943555metafieldscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Metafields
      - That
      - Belong
      - To
      - Product
  /admin/webhooks/count.json:
    get:
      summary: Get a count of all webhooks for your shop.
      description: Get a count of all webhooks for your shop..
      operationId: getAdminWebhooksCount.json
      x-api-path-slug: adminwebhookscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Webhooksyour
      - Shop
  /admin/products/7990943555/variants/count.json:
    get:
      summary: Get a count of variants for a product
      description: Get a count of variants for a product.
      operationId: getAdminProducts7990943555VariantsCount.json
      x-api-path-slug: adminproducts7990943555variantscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Variantsa
      - Product
  /admin/countries/261414723/provinces/count.json:
    get:
      summary: Get a count of all provinces
      description: Get a count of all provinces.
      operationId: getAdminCountries261414723ProvincesCount.json
      x-api-path-slug: admincountries261414723provincescount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Provinces
  /admin/customer_saved_searches/count.json:
    get:
      summary: Get a count of all customer saved searches
      description: Get a count of all customer saved searches.
      operationId: getAdminCustomerSavedSearchesCount.json
      x-api-path-slug: admincustomer-saved-searchescount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Customer
      - Saved
      - Searches
  /admin/products/count.json:
    get:
      summary: Count all products
      description: Count all products.
      operationId: getAdminProductsCount.json
      x-api-path-slug: adminproductscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Products
  /admin/orders/count.json:
    get:
      summary: Count all orders
      description: Count all orders.
      operationId: getAdminOrdersCount.json
      x-api-path-slug: adminorderscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Orders
  /admin/products/7990943555/images/count.json:
    get:
      summary: Get a count of all product images
      description: Get a count of all product images.
      operationId: getAdminProducts7990943555ImagesCount.json
      x-api-path-slug: adminproducts7990943555imagescount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Product
      - Images
  /admin/customers/count.json:
    get:
      summary: Get a count of all customers
      description: Get a count of all customers.
      operationId: getAdminCustomersCount.json
      x-api-path-slug: admincustomerscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Customers
  /admin/orders/4528049998/fulfillments/count.json:
    get:
      summary: Count all the total number of fulfillments for an order.
      description: Count all the total number of fulfillments for an order..
      operationId: getAdminOrders4528049998FulfillmentsCount.json
      x-api-path-slug: adminorders4528049998fulfillmentscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Total
      - Number
      - Fulfillmentsan
      - Order
  /admin/smart_collections/count.json:
    get:
      summary: Get a count of all collections
      description: Get a count of all collections.
      operationId: getAdminSmartCollectionsCount.json
      x-api-path-slug: adminsmart-collectionscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Collections
  /admin/custom_collections/count.json:
    get:
      summary: Get a count of all custom collections
      description: Get a count of all custom collections.
      operationId: getAdminCustomCollectionsCount.json
      x-api-path-slug: admincustom-collectionscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Custom
      - Collections
  /admin/events/count.json:
    get:
      summary: Count all the events
      description: Count all the events.
      operationId: getAdminEventsCount.json
      x-api-path-slug: admineventscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Events
  /admin/comments/count.json:
    get:
      summary: Get a count of all comments
      description: Get a count of all comments.
      operationId: getAdminCommentsCount.json
      x-api-path-slug: admincommentscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Comments
  /admin/script_tags/count.json:
    get:
      summary: Get a count of all script tags
      description: Get a count of all script tags.
      operationId: getAdminScriptTagsCount.json
      x-api-path-slug: adminscript-tagscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Script
      - Tags
  /admin/collects/count.json:
    get:
      summary: Get a count of all collects
      description: Get a count of all collects.
      operationId: getAdminCollectsCount.json
      x-api-path-slug: admincollectscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Collects
  /admin/blogs/count.json:
    get:
      summary: Get a count of all blogs
      description: Get a count of all blogs.
      operationId: getAdminBlogsCount.json
      x-api-path-slug: adminblogscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Blogs
  /admin/countries/count.json:
    get:
      summary: Get a count of all countries
      description: Get a count of all countries.
      operationId: getAdminCountriesCount.json
      x-api-path-slug: admincountriescount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Countries
  /admin/checkouts/count.json:
    get:
      summary: Get a count of checkouts
      description: Get a count of checkouts.
      operationId: getAdminCheckoutsCount.json
      x-api-path-slug: admincheckoutscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Checkouts
  /admin/countries/261414723.json:
    get:
      summary: Show Country
      description: Show country.
      operationId: getAdminCountries261414723.json
      x-api-path-slug: admincountries261414723-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Show
      - Country