---
swagger: "2.0"
x-collection-name: Datumbox
x-complete: 0
info:
  title: Datumbox Classifies the Document as spam or nospam
  description: The Spam Detection function labels documents as spam or nospam by taking
    into account their context. It can be used to filter out spam emails and comments.
  version: 1.0.0
host: api.datumbox.com
basePath: 1.0/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /SpamDetection.json:
    post:
      summary: Classifies the Document as spam or nospam
      description: The Spam Detection function labels documents as spam or nospam
        by taking into account their context. It can be used to filter out spam emails
        and comments.
      operationId: SpamDetection
      x-api-path-slug: spamdetectionjson-post
      parameters:
      - in: formData
        name: text
        description: The text that you want to analyze
      responses:
        200:
          description: OK
      tags:
      - Spam
      - Detection
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