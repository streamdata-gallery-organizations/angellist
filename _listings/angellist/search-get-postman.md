{
  "info": {
    "name": "AngelList Search AngelList",
    "_postman_id": "4a51ddd0-cef5-42dc-9aa5-72c3e7a0574e",
    "description": "Search AngelList.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "8a24b4d7-ed40-47e8-87c7-830290a044e5",
          "name": "search",
          "request": {
            "url": "http://api.angel.co/1/search?query=%7B%7D&type=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Search AngelList"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cbdd48e0-6bc2-4fe8-99b4-903bbed62a09"
            }
          ]
        }
      ]
    }
  ]
}