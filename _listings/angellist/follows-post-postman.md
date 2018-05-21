{
  "info": {
    "name": "AngelList Add Follow",
    "_postman_id": "f58455d1-c14e-4cc1-bb6b-f1e1a68aef17",
    "description": "Add a follow for user or startup on AngelList.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "6e899f1d-5748-4dc3-b652-28c820a685da",
          "name": "follows",
          "request": {
            "url": "http://api.angel.co/1/follows?id=%7B%7D&type=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add a follow for user or startup on AngelList"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0448c755-8b9d-4b95-b2c4-437ffb711395"
            }
          ]
        }
      ]
    }
  ]
}