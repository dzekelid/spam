---
swagger: "2.0"
x-collection-name: Datumbox
x-complete: 1
info:
  title: DatumBox
  description: datumbox-offers-a-machine-learning-platform-composed-of-14-classifiers-and-natural-language-processing-functions-functions-include-sentiment-analysis-topic-classification-readability-assessment-language-detection-and-much-more
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
---