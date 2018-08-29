{
  "info": {
    "name": "AngelList Get Press",
    "_postman_id": "4c0a9f42-8aa4-4ed6-98bf-a6fcdab20dd3",
    "description": "Get Press",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "af3b9544-ae5f-4ab4-95e1-5fae4fdee7c1",
          "name": "press",
          "request": {
            "url": "http://api.angel.co/1/press?startup_id=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Press"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "95117f92-4abd-44c0-a58d-bc568daf1c67"
            }
          ]
        }
      ]
    }
  ]
}