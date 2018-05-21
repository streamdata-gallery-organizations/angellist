{
  "info": {
    "name": "AngelList Get Tag",
    "_postman_id": "1e9633ca-9f26-423c-8773-edca1e21bdf7",
    "description": "Get Tag",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "f458c8dc-adec-4cec-8681-6a2348fe15b6",
          "name": "tags",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.angel.co",
              "path": [
                "1",
                "tags/:tag_id"
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
            "description": "Get Tag"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bfdb703b-c9b2-40cc-9eb3-66d1530e82e1"
            }
          ]
        }
      ]
    }
  ]
}