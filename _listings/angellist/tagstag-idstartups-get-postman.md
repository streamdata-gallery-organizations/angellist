{
  "info": {
    "name": "AngelList Get Startups by Tag",
    "_postman_id": "3f697166-54df-43e4-bacd-86dbf1408cef",
    "description": "Get Startups by Tag",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "28b71b8f-2a82-4f66-a8d8-f52b38a385d9",
          "name": "tagStartups",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.angel.co",
              "path": [
                "1",
                "tags/:tag_id/startups"
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
            "description": "Get Startups by Tag"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "08dde130-fa63-4975-8274-eebb37a9de4a"
            }
          ]
        }
      ]
    }
  ]
}