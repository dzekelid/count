---
swagger: "2.0"
x-collection-name: Dropbox
x-complete: 1
info:
  title: Dropbox Core API v1
  description: the-dropbox-core-api-is-the-underlying-interface-for-all-of-our-official-dropbox-mobile-appshttpswww-dropbox-commobileand-our-sdkshttpswww-dropbox-comdeveloperscoresdk--its-the-most-direct-way-to-access-the-api--thisreference-document-is-designed-for-those-interested-in-developing-for-platforms-not-supported-by-the-sdks-or-forthose-interested-in-exploring-api-features-in-detail-
  termsOfService: https://www.dropbox.com/developers/reference/tos
  contact:
    name: Dropbox
    url: https://www.dropbox.com/developers
  version: 1.0.0
host: api.dropbox.com
basePath: /1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account/info:
    get:
      summary: Retrieves information about the user's account.
      description: Retrieves information about the user's account.
      operationId: retrieves-information-about-the-users-account
      x-api-path-slug: accountinfo-get
      parameters:
      - in: query
        name: locale
        description: Use to specify language settings for user error messages and
          other language specific text
      responses:
        200:
          description: OK
      tags:
      - Storage
      - Documents
      - Account
      - Info
---