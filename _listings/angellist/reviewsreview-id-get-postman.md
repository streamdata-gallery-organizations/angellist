{
  "info": {
    "name": "AngelList Get Review",
    "_postman_id": "32f6e922-a4bb-4bf7-b402-41d712f0d5e0",
    "description": "Get Review",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "ce76f14b-45df-4172-9538-6d3864d61e3c",
          "name": "reviews",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.angel.co",
              "path": [
                "1",
                "reviews/:review_id"
              ],
              "query": [
                {
                  "key": "startup_id",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "review_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Review"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "90cca9a5-b55a-4244-9a0e-6b6ffb8b182d"
            }
          ]
        }
      ]
    }
  ]
}