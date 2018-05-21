{
  "info": {
    "name": "AngelList Get Startup Followers",
    "_postman_id": "413463b6-2740-4040-8863-1ae8d3844738",
    "description": "Get Startup Followers",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "f910a973-ac30-42fa-a859-c299fa04ff00",
          "name": "startupFollowers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.angel.co",
              "path": [
                "1",
                "startups/:startup_id/followers"
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
            "description": "Get Startup Followers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fc22af81-bf93-4edd-9bab-1949213b01f4"
            }
          ]
        }
      ]
    }
  ]
}