---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Jira Cloud API Get version's related issues count
  description: |-
    Returns the following counts for a version:

    *   Number of issues where the `fixVersion` is set to the version.
    *   Number of issues where the `affectedVersion` is set to the version.
    *   Number of issues where a version custom field is set to the version.

    [Permissions](https://confluence.atlassian.com/x/FQiiLQ) required: _Browse projects_ project permission
  termsOfService: http://atlassian.com/terms/
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/2/component/{id}/relatedIssueCounts:
    get:
      summary: Get component issues count
      description: Returns the counts of issues assigned to the component. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
        required:** Permission to access Jira.
      operationId: com.atlassian.jira.rest.v2.issue.ComponentResource.getComponentRelatedIssues_get
      x-api-path-slug: api2componentidrelatedissuecounts-get
      parameters:
      - in: path
        name: id
        description: The ID of the component
      responses:
        200:
          description: OK
      tags:
      - Component
      - Issues
      - Count
  /api/2/version/{id}/relatedIssueCounts:
    get:
      summary: Get version's related issues count
      description: |-
        Returns the following counts for a version:

        *   Number of issues where the `fixVersion` is set to the version.
        *   Number of issues where the `affectedVersion` is set to the version.
        *   Number of issues where a version custom field is set to the version.

        [Permissions](https://confluence.atlassian.com/x/FQiiLQ) required: _Browse projects_ project permission
      operationId: com.atlassian.jira.rest.v2.issue.VersionResource.getVersionRelatedIssues_get
      x-api-path-slug: api2versionidrelatedissuecounts-get
      parameters:
      - in: path
        name: id
        description: The ID of the version
      responses:
        200:
          description: OK
      tags:
      - Versions
      - Related
      - Issues
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