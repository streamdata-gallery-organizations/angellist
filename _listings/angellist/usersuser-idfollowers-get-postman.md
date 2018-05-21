{
  "info": {
    "name": "AngelList Get User Followers",
    "_postman_id": "38af5896-ffc4-42d7-8127-b3fe0ce1769b",
    "description": "Get User Followers",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "1b1f24bc-e1c3-4ed1-a025-43d13a69be8e",
          "name": "userFollowers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.angel.co",
              "path": [
                "1",
                "users/:user_id/followers"
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
            "description": "Get User Followers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "845952a2-8645-4bc7-83d4-e858f8de74bc"
            }
          ]
        }
      ]
    }
  ]
}