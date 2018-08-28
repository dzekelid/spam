swagger: "2.0"
x-collection-name: Twitter
x-complete: 1
info:
  title: Twitter
  description: the-twitter-api-gives-you-programmatic-control-over-any-twitter-account-and-most-aspect-of-the-platform--allowing-developers-to-build-social-applications-that-use-the-platform-and-automate-interactions-between-users-
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