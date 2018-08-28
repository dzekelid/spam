---
swagger: "2.0"
x-collection-name: Twitter
x-complete: 0
info:
  title: Twitter Report User Spam
  description: Returna users report spam
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
  /users/report_spam:
    post:
      summary: Report User Spam
      description: Returna users report spam
      operationId: returna-users-report-spam
      x-api-path-slug: usersreport-spam-post
      parameters:
      - in: query
        name: screen_name
        description: The ID or screen_name of the user you want to report as a spammer
      - in: query
        name: user_id
        description: The ID of the user you want to report as a spammer
      responses:
        200:
          description: OK
      tags:
      - Social
      - Users
      - Spam
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