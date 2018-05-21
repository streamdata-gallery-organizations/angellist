{
  "info": {
    "name": "AngelList Get Users by Tag",
    "_postman_id": "bfc3d761-336d-4dca-839d-b960241f80be",
    "description": "Get Users by Tag",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "7a79fbbc-7a5b-4f06-a1e1-c99fb68d9844",
          "name": "tagUsers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.angel.co",
              "path": [
                "1",
                "tags/:tag_id/users"
              ],
              "variable": [
                {
                  "id": "tag_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Users by Tag"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3a671735-b45e-4a25-b8c0-a758438b40bf"
            }
          ]
        }
      ]
    }
  ]
}