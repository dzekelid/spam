swagger: "2.0"
x-collection-name: Shopify
x-complete: 1
info:
  title: Shopify API
  description: todo-add-description
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/comments/2941387470/spam.json:
    post:
      summary: Mark a comment as Spam
      description: Mark a comment as spam.
      operationId: postAdminComments2941387470Spam.json
      x-api-path-slug: admincomments2941387470spam-json-post
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Mark
      - Comment
      - As
      - Spam
  /admin/comments/2941387470/not_spam.json:
    post:
      summary: Mark a comment as not spam
      description: Mark a comment as not spam.
      operationId: postAdminComments2941387470NotSpam.json
      x-api-path-slug: admincomments2941387470not-spam-json-post
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Mark
      - Comment
      - As
      - Not
      - Spam