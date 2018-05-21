{
  "info": {
    "name": "AngelList Get Users Following",
    "_postman_id": "55840127-76d1-4c83-93da-6f516df60d98",
    "description": "Get Users Following",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "aae3350e-a4db-480d-bf8f-f347e5452d48",
          "name": "usersFollowing",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.angel.co",
              "path": [
                "1",
                "users/:user_id/following"
              ],
              "variable": [
                {
                  "id": "user_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Users Following"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "13b66c21-8f11-47b5-8e70-3864110049aa"
            }
          ]
        }
      ]
    }
  ]
}