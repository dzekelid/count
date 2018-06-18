---
swagger: "2.0"
x-collection-name: Twitter
x-complete: 0
info:
  title: Twitter Update Profile Colors
  description: sets one or more hex values that controls color scheme
  version: "1.1"
host: api.twitter.com
basePath: /1.1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account/settings:
    get:
      summary: Get Account Settings
      description: returns settings for user
      operationId: returns-settings-for-user
      x-api-path-slug: accountsettings-get
      responses:
        200:
          description: OK
      tags:
      - Social
      - Account
    post:
      summary: Update  Account Settings
      description: updates user's settings
      operationId: updates-users-settings
      x-api-path-slug: accountsettings-post
      parameters:
      - in: query
        name: end_sleep_time
        description: the hour that sleep time should end if enabled
      - in: query
        name: lang
        description: language which Twitter should render in for the user
      - in: query
        name: sleep_time_enabled
        description: enables/disables sleep time, silencing notifications
      - in: query
        name: start_sleep_time
        description: the hour that sleep time should begin if enabled
      - in: query
        name: time_zone
        description: timezone dates and times should be displayed in
      - in: query
        name: trend_location_woeid
        description: the Yahoo! Where On Earth ID to user as defaul tend location
      responses:
        200:
          description: OK
      tags:
      - Social
      - Account
  /account/update_delivery_device:
    post:
      summary: Update Account Deliver Service
      description: sets which device Twitter delivers updates to for user
      operationId: sets-which-device-twitter-delivers-updates-to-for-user
      x-api-path-slug: accountupdate-delivery-device-post
      parameters:
      - in: query
        name: device
        description: must be one of sms, none
      - in: query
        name: include_entities
        description: whether or not to include entities
      responses:
        200:
          description: OK
      tags:
      - Social
      - Account
  /account/update_profile:
    post:
      summary: Update Profile
      description: sets values that users ar eable to set under Account tab
      operationId: sets-values-that-users-ar-eable-to-set-under-account-tab
      x-api-path-slug: accountupdate-profile-post
      parameters:
      - in: query
        name: description
        description: a description of user owning account
      - in: query
        name: include_entities
        description: whether or not to include entities
      - in: query
        name: location
        description: city or country describing where user of account is
      - in: query
        name: name
        description: full name of profile
      - in: query
        name: skip_status
        description: whether or not to include statuses in response
      - in: query
        name: url
        description: url associated with profile
      responses:
        200:
          description: OK
      tags:
      - Social
      - Account
  /account/update_profile_background_image:
    post:
      summary: Update Profile Background Image
      description: updates user's profile background image
      operationId: updates-users-profile-background-image
      x-api-path-slug: accountupdate-profile-background-image-post
      parameters:
      - in: formData
        name: file
        description: image to replace background image of profile
      - in: query
        name: include_entities
        description: whether or not to include entities
      - in: query
        name: skip_status
        description: whether or not to include status in returned user objects
      - in: query
        name: tile
        description: whether or not to tile background image
      - in: query
        name: use
        description: display background image or not
      responses:
        200:
          description: OK
      tags:
      - Social
      - Account
  /account/update_profile_colors:
    post:
      summary: Update Profile Colors
      description: sets one or more hex values that controls color scheme
      operationId: sets-one-or-more-hex-values-that-controls-color-scheme
      x-api-path-slug: accountupdate-profile-colors-post
      parameters:
      - in: query
        name: include_entities
        description: whether or not to include entities
      - in: query
        name: profile_background_color
        description: profile background color
      - in: query
        name: profile_link_color
        description: profile link color
      - in: query
        name: profile_sidebar_border_color
        description: profile sidebars border color
      - in: query
        name: profile_sidebar_fill_color
        description: profiles sidebar background color
      - in: query
        name: profile_text_color
        description: profile text color
      - in: query
        name: skip_status
        description: whether or not to include statuses
      responses:
        200:
          description: OK
      tags:
      - Social
      - Account
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