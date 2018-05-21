{
  "info": {
    "name": "AngelList Get User Follower IDs",
    "_postman_id": "94f84a2f-2922-4ee0-9caf-4675287b6a94",
    "description": "Get User Follower IDs",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "54cc3f10-783d-48f5-a90a-9396fb9e715e",
          "name": "users",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.angel.co",
              "path": [
                "1",
                "users/:user_id/followers/ids"
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
            "description": "Get User Follower IDs"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d0328824-9827-4fbb-b01a-b77f4012fae4"
            }
          ]
        }
      ]
    }
  ]
}