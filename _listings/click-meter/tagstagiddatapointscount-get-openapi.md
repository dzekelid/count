---
swagger: "2.0"
x-collection-name: Click Meter
x-complete: 0
info:
  title: Click Meter Count the datapoints associated to the user filtered by this
    tag
  description: Count the datapoints associated to the user filtered by this tag.
  contact:
    name: Api Support
    url: http://www.clickmeter.com/api
    email: api@clickmeter.com
  version: v2
host: apiv2.clickmeter.com:80
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account/guests/count:
    get:
      summary: Retrieve count of guests
      description: Retrieve count of guests.
      operationId: getAccountGuestsCount
      x-api-path-slug: accountguestscount-get
      parameters:
      - in: query
        name: textSearch
        description: Filter fields by this pattern
      responses:
        200:
          description: OK
      tags:
      - Account
      - Guests
      - Count
  /account/guests/{guestId}/permissions/count:
    get:
      summary: Retrieve count of the permissions for a guest
      description: Retrieve count of the permissions for a guest.
      operationId: getAccountGuestsGuestPermissionsCount
      x-api-path-slug: accountguestsguestidpermissionscount-get
      parameters:
      - in: query
        name: entityId
        description: Optional id of the datapoint/group entity to filter by
      - in: query
        name: entityType
        description: Can be datapoint or group
      - in: path
        name: guestId
        description: Id of the guest
      - in: query
        name: type
        description: Can be w or r
      responses:
        200:
          description: OK
      tags:
      - Account
      - Guests
      - GuestId
      - Permissions
      - Count
  /conversions/count:
    get:
      summary: Retrieve a count of conversions
      description: Retrieve a count of conversions.
      operationId: getConversionsCount
      x-api-path-slug: conversionscount-get
      parameters:
      - in: query
        name: createdAfter
        description: Exclude conversions created before this date (YYYYMMDD)
      - in: query
        name: createdBefore
        description: Exclude conversions created after this date (YYYYMMDD)
      - in: query
        name: status
        description: Status of conversion (deleted/active)
      - in: query
        name: textSearch
        description: Filter fields by this pattern
      responses:
        200:
          description: OK
      tags:
      - Conversions
      - Count
  /conversions/{conversionId}/datapoints/count:
    get:
      summary: Retrieve a count of datapoints connected to this conversion
      description: Retrieve a count of datapoints connected to this conversion.
      operationId: getConversionsConversionDatapointsCount
      x-api-path-slug: conversionsconversioniddatapointscount-get
      parameters:
      - in: path
        name: conversionId
        description: Id of the conversion
      - in: query
        name: createdAfter
        description: Exclude datapoints created before this date (YYYYMMDD)
      - in: query
        name: createdBefore
        description: Exclude datapoints created after this date (YYYYMMDD)
      - in: query
        name: status
        description: Status of datapoint (deleted/active/paused/spam)
      - in: query
        name: tags
        description: Filter by this tag name
      - in: query
        name: textSearch
        description: Filter fields by this pattern
      - in: query
        name: type
        description: Type of datapoint (tl/tp)
      responses:
        200:
          description: OK
      tags:
      - Conversions
      - ConversionId
      - Datapoints
      - Count
  /datapoints/count:
    get:
      summary: Count the datapoints associated to the user
      description: Count the datapoints associated to the user.
      operationId: getDatapointsCount
      x-api-path-slug: datapointscount-get
      parameters:
      - in: query
        name: createdAfter
        description: Exclude datapoints created before this date (YYYYMMDD)
      - in: query
        name: createdBefore
        description: Exclude datapoints created after this date (YYYYMMDD)
      - in: query
        name: onlyFavorites
        description: Filter fields by favourite status
      - in: query
        name: status
        description: Status of the datapoint
      - in: query
        name: tags
        description: A comma separated list of tags you want to filter with
      - in: query
        name: textSearch
        description: Filter fields by this pattern
      - in: query
        name: type
        description: Type of the datapoint (tp/tl)
      responses:
        200:
          description: OK
      tags:
      - Datapoints
      - Count
  /domains/count:
    get:
      summary: Retrieve count of domains
      description: Retrieve count of domains.
      operationId: getDomainsCount
      x-api-path-slug: domainscount-get
      parameters:
      - in: query
        name: name
        description: Filter domains with this anmen
      - in: query
        name: type
        description: Type of domain (system/go/personal/dedicated)
      responses:
        200:
          description: OK
      tags:
      - Domains
      - Count
  /groups/count:
    get:
      summary: Count the groups associated to the user.
      description: Count the groups associated to the user..
      operationId: getGroupsCount
      x-api-path-slug: groupscount-get
      parameters:
      - in: query
        name: createdAfter
        description: Exclude groups created before this date (YYYYMMDD)
      - in: query
        name: createdBefore
        description: Exclude groups created after this date (YYYYMMDD)
      - in: query
        name: status
        description: Status of the datapoint
      - in: query
        name: tags
        description: A comma separated list of tags you want to filter with
      - in: query
        name: textSearch
        description: Filter fields by this pattern
      - in: query
        name: write
        description: Write permission
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Count
  /groups/{id}/datapoints/count:
    get:
      summary: Count the datapoints associated to the user in this group.
      description: Count the datapoints associated to the user in this group..
      operationId: getGroupsDatapointsCount
      x-api-path-slug: groupsiddatapointscount-get
      parameters:
      - in: query
        name: createdAfter
        description: Exclude datapoints created before this date (YYYYMMDD)
      - in: query
        name: createdBefore
        description: Exclude datapoints created after this date (YYYYMMDD)
      - in: path
        name: id
        description: Id of the group
      - in: query
        name: onlyFavorites
        description: Filter fields by favourite status
      - in: query
        name: status
        description: Status of the datapoint
      - in: query
        name: tags
        description: A comma separated list of tags you want to filter with
      - in: query
        name: textSearch
        description: Filter fields by this pattern
      - in: query
        name: type
        description: Type of the datapoint (tp/tl)
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Id
      - Datapoints
      - Count
  /retargeting/count:
    get:
      summary: Retrieve count of retargeting scripts
      description: Retrieve count of retargeting scripts.
      operationId: getRetargetingCount
      x-api-path-slug: retargetingcount-get
      responses:
        200:
          description: OK
      tags:
      - Retargeting
      - Count
  /retargeting/{id}/datapoints/count:
    get:
      summary: Count the datapoints associated to the retargeting script.
      description: Count the datapoints associated to the retargeting script..
      operationId: getRetargetingDatapointsCount
      x-api-path-slug: retargetingiddatapointscount-get
      parameters:
      - in: query
        name: createdAfter
        description: Exclude datapoints created before this date (YYYYMMDD)
      - in: query
        name: createdBefore
        description: Exclude datapoints created after this date (YYYYMMDD)
      - in: path
        name: id
        description: Id of the group
      - in: query
        name: onlyFavorites
        description: Filter fields by favourite status
      - in: query
        name: status
        description: Status of the datapoint
      - in: query
        name: tags
        description: A comma separated list of tags you want to filter with
      - in: query
        name: textSearch
        description: Filter fields by this pattern
      responses:
        200:
          description: OK
      tags:
      - Retargeting
      - Id
      - Datapoints
      - Count
  /tags/count:
    get:
      summary: List of all the groups associated to the user filtered by this tag.
      description: List of all the groups associated to the user filtered by this
        tag..
      operationId: getTagsCount
      x-api-path-slug: tagscount-get
      parameters:
      - in: query
        name: datapoints
        description: Comma separated list of datapoints id to filter by
      - in: query
        name: groups
        description: Comma separated list of groups id to filter by
      - in: query
        name: name
        description: Name of the tag
      - in: query
        name: type
        description: Type of entity related to the tag
      responses:
        200:
          description: OK
      tags:
      - Tags
      - Count
  /tags/{tagId}/datapoints/count:
    get:
      summary: Count the datapoints associated to the user filtered by this tag
      description: Count the datapoints associated to the user filtered by this tag.
      operationId: getTagsTagDatapointsCount
      x-api-path-slug: tagstagiddatapointscount-get
      parameters:
      - in: query
        name: createdAfter
        description: Exclude datapoints created before this date (YYYYMMDD)
      - in: query
        name: createdBefore
        description: Exclude datapoints created after this date (YYYYMMDD)
      - in: query
        name: status
        description: Status of the datapoint
      - in: path
        name: tagId
        description: Id of the tag
      - in: query
        name: textSearch
        description: Filter fields by this pattern
      - in: query
        name: type
        description: Type of the datapoint (tp/tl)
      responses:
        200:
          description: OK
      tags:
      - Tags
      - TagId
      - Datapoints
      - Count
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