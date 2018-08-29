{
  "info": {
    "name": "AngelList Delete Comment",
    "_postman_id": "fb5efb4e-5e6d-4c0d-bafa-7ed0880c71ad",
    "description": "Deletes a comment for given object",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "255acc7a-03a3-42b8-82c5-344380225791",
          "name": "comment",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.angel.co",
              "path": [
                "1",
                "comments/:comment_id"
              ],
              "variable": [
                {
                  "id": "comment_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a comment for given object"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3ba638bc-b963-4606-825d-5fca4554f075"
            }
          ]
        }
      ]
    }
  ]
}