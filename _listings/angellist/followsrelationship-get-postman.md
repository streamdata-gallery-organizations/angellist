{
  "info": {
    "name": "AngelList Get Follows Relationship",
    "_postman_id": "a34f8b7a-6d7a-41b5-8235-e837c88cbf8a",
    "description": "Gets the relationships for followers",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "0d0e0f67-630d-43cb-921b-6b2c58c89244",
          "name": "followsRelationship",
          "request": {
            "url": "http://api.angel.co/1/follows/relationship?source_id=%7B%7D&target_id=%7B%7D&target_type=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the relationships for followers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bccd881b-8eb4-423d-a0bf-6ebc0d3941bc"
            }
          ]
        }
      ]
    }
  ]
}