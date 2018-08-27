swagger: "2.0"
x-collection-name: Atlassian
x-complete: 1
info:
  title: Stride API
  description: this-service-provides-public-api-for-the-stride-
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
  /api/2/version/{id}/unresolvedIssueCount:
    get:
      summary: Get version's unresolved issues count
      description: 'Returns counts of the issues and unresolved issues for the project
        version. [Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:
        _Browse projects_ project permission'
      operationId: com.atlassian.jira.rest.v2.issue.VersionResource.getVersionUnresolvedIssues_get
      x-api-path-slug: api2versionidunresolvedissuecount-get
      parameters:
      - in: path
        name: id
        description: The ID of the version
      responses:
        200:
          description: OK
      tags:
      - Versions
      - Unresolved
      - Issues
      - Count