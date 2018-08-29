{
  "info": {
    "name": "AngelList Get Status Updates",
    "_postman_id": "2fb02585-1cc0-47d7-a138-d3c37e45124d",
    "description": "Get Status Updates",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "c1880eb6-8a0f-490b-bfb3-e7a2ad318b4e",
          "name": "1Status_updates",
          "request": {
            "url": "http://api.angel.co/1/status_updates?startup_id=%7B%7D&user_id=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Status Updates"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ae199700-27cb-49dd-a446-c0abe14e4d46"
            }
          ]
        }
      ]
    }
  ]
}