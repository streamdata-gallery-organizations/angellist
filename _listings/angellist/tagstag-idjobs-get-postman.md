{
  "info": {
    "name": "AngelList Get Jobs by Tag",
    "_postman_id": "1c9ed6f9-b385-418f-a821-d0a951e5388a",
    "description": "Get Jobs by Tag",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "28c90762-7895-48c7-a2d4-f2f7011eefc3",
          "name": "jobs",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.angel.co",
              "path": [
                "1",
                "tags/:tag_id/jobs"
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
            "description": "Get Jobs by Tag"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f49472df-39b7-408e-88d1-f5a5a792fca6"
            }
          ]
        }
      ]
    }
  ]
}