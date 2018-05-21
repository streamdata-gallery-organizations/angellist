{
  "info": {
    "name": "AngelList Get Startup Comments",
    "_postman_id": "67ccf319-2e54-4e67-bd88-2cfe23bd5536",
    "description": "Get Startup Comments",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "67fb3636-e479-4f41-a66d-8f7254ab7fc2",
          "name": "startupComments",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.angel.co",
              "path": [
                "1",
                "startups/:startup_id/comments"
              ],
              "variable": [
                {
                  "id": "startup_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Startup Comments"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4282edf5-aed6-4e2a-aed4-ab184596d073"
            }
          ]
        }
      ]
    }
  ]
}