---
swagger: "2.0"
x-collection-name: Disqus
x-complete: 0
info:
  title: Disqus Threads Spam
  description: Threads Spam
  termsOfService: https://docs.disqus.com/kb/terms-and-policies/
  version: 1.0.0
host: disqus.com
basePath: api/3.0/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /posts/spam.json:
    post:
      summary: Posts Spam
      description: Posts Spam
      operationId: posts-spam
      x-api-path-slug: postsspamjson-post
      parameters:
      - in: query
        name: post
        description: Looks up a post by ID You must be a moderator on the selected
          post&#39;s forum
        type: string
      responses:
        200:
          description: OK
      tags:
      - Comments
      - Posts
      - Spam
  /threads/spam.json:
    post:
      summary: Threads Spam
      description: Threads Spam
      operationId: threads-spam
      x-api-path-slug: threadsspamjson-post
      parameters:
      - in: query
        name: forum
        description: Defaults to null                         Looks up a forum by
          ID (aka short name)
        type: string
      - in: query
        name: thread
        description: Looks up a thread by ID You must be a moderator on the selected
          thread&#39;s forum
        type: string
      responses:
        200:
          description: OK
      tags:
      - Comments
      - Threads
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