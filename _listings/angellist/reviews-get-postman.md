{
  "info": {
    "name": "AngelList Get Reviews",
    "_postman_id": "3f8be934-83b8-4cb1-83fd-88ab29e2892d",
    "description": "Get Reviews",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "0e658f74-7a4d-485c-98f4-c6fc48a6f251",
          "name": "reviews",
          "request": {
            "url": "http://api.angel.co/1/reviews?user_id=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Reviews"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c60aa796-689c-41de-b31b-4e5dd8815c51"
            }
          ]
        }
      ]
    }
  ]
}