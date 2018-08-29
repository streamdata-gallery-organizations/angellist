{
  "info": {
    "name": "AngelList Get Press",
    "_postman_id": "e2220585-5de4-4de2-8c3b-450e094484ed",
    "description": "Get Press",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "1a47f0fd-7b11-4dd8-8ce2-1a8aca937488",
          "name": "press",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.angel.co",
              "path": [
                "1",
                "press/:press_id"
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
                  "id": "press_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
              "id": "6938c4b9-57eb-4893-9c3f-79b7c534e748"
            }
          ]
        }
      ]
    }
  ]
}