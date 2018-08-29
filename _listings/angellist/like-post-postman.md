{
  "info": {
    "name": "AngelList Add Like",
    "_postman_id": "326e0cb5-ae63-46cc-8f7e-9ad15acadefc",
    "description": "Add like.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "6fe3a8fb-8f82-46c2-9d54-679bcd3dcd5b",
          "name": "like",
          "request": {
            "url": "http://api.angel.co/1/like?likable_id=%7B%7D&likable_type=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add like"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "98f80bbe-e0ec-4245-9c12-595b2e389345"
            }
          ]
        }
      ]
    }
  ]
}