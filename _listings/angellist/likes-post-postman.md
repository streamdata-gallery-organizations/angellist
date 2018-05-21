{
  "info": {
    "name": "AngelList Add Like",
    "_postman_id": "76b4153e-cff2-498e-b656-0c25aa69b24c",
    "description": "Add Like",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "f1c3f6de-e924-4168-b727-cc56f550cc68",
          "name": "likes",
          "request": {
            "url": "http://api.angel.co/1/likes?likable_id=%7B%7D&likable_type=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add Like"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c3f7cbcb-9ac1-4b36-aff0-907b1afdb826"
            }
          ]
        }
      ]
    }
  ]
}