{
  "info": {
    "name": "AngelList Delete Follow",
    "_postman_id": "19997a5c-2f58-4656-8cd0-d46209b4acfc",
    "description": "Delete the follow for given user or startup.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "fa50d7ed-8b4d-4353-8d51-ae917b1e10ac",
          "name": "follows",
          "request": {
            "url": "http://api.angel.co/1/follows?id=%7B%7D&type=%7B%7D",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete the follow for given user or startup"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "290442b2-3674-4c37-9858-c734f778de38"
            }
          ]
        }
      ]
    }
  ]
}