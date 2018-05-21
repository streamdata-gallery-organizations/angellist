{
  "info": {
    "name": "AngelList Search Startups",
    "_postman_id": "5804b90f-eec5-42c3-80fe-b697f4ec8de6",
    "description": "Search Startups",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "d78f2c83-5dbe-4e99-880c-8c7f554f3790",
          "name": "startups",
          "request": {
            "url": "http://api.angel.co/1/startups?filter=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Search Startups"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4e5f28cd-ea32-474e-a344-9e44d02df278"
            }
          ]
        }
      ]
    }
  ]
}