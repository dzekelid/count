---
swagger: "2.0"
x-collection-name: Fire Browse Beta API
x-complete: 1
info:
  title: Fire Browse Beta API
  description: a-simple-and-elegant-way-to-explore-cancer-data
  version: 1.1.35 (2016-09-27 10:12:23 6a47e74011281b2aa
host: firebrowse.org
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Metadata/Counts:
    get:
      summary: Retrieve sample counts.
      description: |-
        Returns the aliquot counts for each disease cohort, per sample
        type and data type.  The sample type designation of "Tumor"
        may be used to aggregate the count of all tumor aliquots into
        a single number per disease and data type. See the SampleTypes
        function for a complete description of sample types.
      operationId: getMetadataCounts
      x-api-path-slug: metadatacounts-get
      parameters:
      - in: query
        name: cohort
        description: Narrow search to one or more TCGA disease cohorts from the scrollable
          list
      - in: query
        name: data_type
        description: Narrow search to one or more TCGA data types from the scrollable
          list
      - in: query
        name: date
        description: Select one or more date stamps
      - in: query
        name: format
        description: Format of result
      - in: query
        name: sample_type
        description: Narrow search to one or more TCGA sample types from the scrollable
          list
      - in: query
        name: sort_by
        description: Which column in the results should be used for sorting paginated
          results?
      - in: query
        name: totals
        description: Output an entry providing the totals for each data type
      responses:
        200:
          description: OK
      tags:
      - Metadata
      - Counts
---