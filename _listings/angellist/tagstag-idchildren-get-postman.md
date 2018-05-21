{
  "info": {
    "name": "AngelList Get Tags Children",
    "_postman_id": "e16c3508-c26a-4c52-9e6b-a9f746b1f86a",
    "description": "Get Tags Children",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "afab2763-a9ba-4186-a80b-34760b44cf93",
          "name": "tagsChildren",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.angel.co",
              "path": [
                "1",
                "tags/:tag_id/children"
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
            "description": "Get Tags Children"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "20d54759-645a-4c44-8784-635c82764611"
            }
          ]
        }
      ]
    }
  ]
}