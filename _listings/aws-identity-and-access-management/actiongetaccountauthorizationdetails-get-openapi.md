---
swagger: "2.0"
x-collection-name: AWS Identity and Access Management
x-complete: 0
info:
  title: AWS Identity and Access Management API Get Account Authorization Details
  version: 1.0.0
  description: |-
    Retrieves information about all IAM users, groups, roles, and policies in your AWS
          account, including their relationships to one another.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateAccountAlias:
    get:
      summary: Create Account Alias
      description: Creates an alias for your AWS account.
      operationId: createAccountAlias
      x-api-path-slug: actioncreateaccountalias-get
      parameters:
      - in: query
        name: AccountAlias
        description: The account alias to create
        type: string
      responses:
        200:
          description: OK
      tags:
      - Account Alias
  /?Action=DeleteAccountAlias:
    get:
      summary: Delete Account Alias
      description: Deletes the specified AWS account alias.
      operationId: deleteAccountAlias
      x-api-path-slug: actiondeleteaccountalias-get
      parameters:
      - in: query
        name: AccountAlias
        description: The name of the account alias to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Account Alias
  /?Action=DeleteAccountPasswordPolicy:
    get:
      summary: Delete Account Password Policy
      description: Deletes the password policy for the AWS account.
      operationId: deleteAccountPasswordPolicy
      x-api-path-slug: actiondeleteaccountpasswordpolicy-get
      parameters:
      - in: query
        name: LimitExceeded
        description: The request was rejected because it attempted to create resources
          beyond the current      AWS account limits
        type: string
      - in: query
        name: NoSuchEntity
        description: The request was rejected because it referenced an entity that
          does not exist
        type: string
      - in: query
        name: ServiceFailure
        description: The request processing has failed because of an unknown error,
          exception or      failure
        type: string
      responses:
        200:
          description: OK
      tags:
      - Account Password Policies
  /?Action=GetAccountAuthorizationDetails:
    get:
      summary: Get Account Authorization Details
      description: |-
        Retrieves information about all IAM users, groups, roles, and policies in your AWS
              account, including their relationships to one another.
      operationId: getAccountAuthorizationDetails
      x-api-path-slug: actiongetaccountauthorizationdetails-get
      parameters:
      - in: query
        name: Filter.member.N
        description: A list of entity types used to filter the results
        type: string
      - in: query
        name: Marker
        description: Use this parameter only when paginating results and only after     you
          receive a response indicating that the results are truncated
        type: string
      - in: query
        name: MaxItems
        description: (Optional) Use this only when paginating results to indicate
          the     maximum number of items you want in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Accounts
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