---
name: AWS Identity and Access Management
x-slug: aws-identity-and-access-management
description: AWS Identity and Access Management (IAM) enables you to securely control
  access to AWS services and resources for your users. Using IAM, you can create and
  manage AWS users and groups, and use permissions to allow and deny their access
  to AWS resources.IAM is a feature of your AWS account offered at no additional charge.
  You will be charged only for use of other AWS services by your users.To get started
  using IAM, orif you have already registered with AWS, go to theAWS Management Consoleand
  get started with theseIAM Best Practices.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Count
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/aws-identity-and-access-management/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Identity and Access Management API Create Account Alias
  x-api-slug: aws-identity-and-access-management-api
  description: Creates an alias for your AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=CreateAccountAlias
  tags: Account Alias
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/aws-identity-and-access-management/actioncreateaccountalias-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/aws-identity-and-access-management/actioncreateaccountalias-get-openapi.md
- name: AWS Identity and Access Management API Delete Account Alias
  x-api-slug: aws-identity-and-access-management-api
  description: Deletes the specified AWS account alias.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteAccountAlias
  tags: Account Alias
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/aws-identity-and-access-management/actiondeleteaccountalias-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/aws-identity-and-access-management/actiondeleteaccountalias-get-openapi.md
- name: AWS Identity and Access Management API Delete Account Password Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Deletes the password policy for the AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteAccountPasswordPolicy
  tags: Account Password Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/aws-identity-and-access-management/actiondeleteaccountpasswordpolicy-get-openapi.md
- name: AWS Identity and Access Management API Get Account Authorization Details
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Retrieves information about all IAM users, groups, roles, and policies in your AWS
          account, including their relationships to one another.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetAccountAuthorizationDetails
  tags: Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/aws-identity-and-access-management/actiongetaccountauthorizationdetails-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/aws-identity-and-access-management/actiongetaccountauthorizationdetails-get-openapi.md
- name: AWS Identity and Access Management API Get Account Password Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Retrieves the password policy for the AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetAccountPasswordPolicy
  tags: Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/aws-identity-and-access-management/actiongetaccountpasswordpolicy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/aws-identity-and-access-management/actiongetaccountpasswordpolicy-get-openapi.md
- name: AWS Identity and Access Management API Get Account Summary
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Retrieves information about IAM entity usage and IAM quotas in the AWS
          account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetAccountSummary
  tags: Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/aws-identity-and-access-management/actiongetaccountsummary-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/aws-identity-and-access-management/actiongetaccountsummary-get-openapi.md
- name: AWS Identity and Access Management API List Account Aliases
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Lists the account alias associated with the AWS account (Note: you can have only
          one).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListAccountAliases
  tags: Account Aliases
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/aws-identity-and-access-management/actionlistaccountaliases-get-openapi.md
- name: AWS Identity and Access Management API Update Account Password Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Updates the password policy settings for the AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=UpdateAccountPasswordPolicy
  tags: Account Password Policy
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/aws-identity-and-access-management/actionupdateaccountpasswordpolicy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/aws-identity-and-access-management/actionupdateaccountpasswordpolicy-get-openapi.md
- name: AWS Identity and Access Management API
  x-api-slug: aws-identity-and-access-management-api
  description: AWS Identity and Access Management (IAM) enables you to securely control
    access to AWS services and resources for your users. Using IAM, you can create
    and manage AWS users and groups, and use permissions to allow and deny their access
    to AWS resources.IAM is a feature of your AWS account offered at no additional
    charge. You will be charged only for use of other AWS services by your users.To
    get started using IAM, orif you have already registered with AWS, go to theAWS
    Management Consoleand get started with theseIAM Best Practices.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/aws-identity-and-access-management/openapi.md
x-common:
- type: x-change-log
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=323
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/sts/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/IAM/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/iam/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=76
- type: x-getting-started
  url: https://aws.amazon.com/iam/getting-started/
- type: x-partners
  url: https://aws.amazon.com/iam/partners/
- type: x-tools
  url: http://aws.amazon.com/cli
- type: x-website
  url: https://aws.amazon.com/iam/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---