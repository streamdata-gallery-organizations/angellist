{
  "info": {
    "name": "AngelList Add Status Update",
    "_postman_id": "742ecd35-c785-4fd6-a940-74d8044fdffd",
    "description": "Add Status Update",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "01955629-428c-4fb9-b4df-f8b965d3ffae",
          "name": "statusUpdate",
          "request": {
            "url": "http://api.angel.co/1/status_updates?message=%7B%7D&startup_id=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add Status Update"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a839d9cb-6fc0-4078-ae5c-df66e3ef69c5"
            }
          ]
        }
      ]
    }
  ]
}