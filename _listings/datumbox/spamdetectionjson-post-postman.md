{
  "info": {
    "name": "Datumbox Classifies the Document as spam or nospam",
    "_postman_id": "17a9d6b9-27dd-4bc2-818e-f2258d0b6a19",
    "description": "The Spam Detection function labels documents as spam or nospam by taking into account their context. It can be used to filter out spam emails and comments.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Spam",
      "item": [
        {
          "id": "f8e3573c-8641-4d46-9312-04cf7b5426cf",
          "name": "SpamDetection",
          "request": {
            "url": "http://api.datumbox.com/1.0/SpamDetection.json",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "text",
                  "value": "{}",
                  "disabled": false,
                  "description": "The text that you want to analyze"
                }
              ]
            },
            "description": "The Spam Detection function labels documents as spam or nospam by taking into account their context. It can be used to filter out spam emails and comments."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f326a4b9-28af-4ffd-abe0-c5ccd557d2c4"
            }
          ]
        }
      ]
    }
  ]
}