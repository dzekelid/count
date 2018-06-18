---
swagger: "2.0"
x-collection-name: Fire Browse Beta API
x-complete: 0
info:
  title: Fire Browse Beta API Retrieve sample counts.
  description: |-
    Returns the aliquot counts for each disease cohort, per sample
    type and data type.  The sample type designation of "Tumor"
    may be used to aggregate the count of all tumor aliquots into
    a single number per disease and data type. See the SampleTypes
    function for a complete description of sample types.
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