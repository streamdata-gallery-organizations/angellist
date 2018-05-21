{
  "info": {
    "name": "AngelList Get Startup Followers IDs",
    "_postman_id": "90f54eca-13e6-434c-96f7-9179fc32dce1",
    "description": "Get Startup Followers IDs",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "0397e163-aa78-41c5-8e26-7531821bf639",
          "name": "startupFollowersIDs",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.angel.co",
              "path": [
                "1",
                "startups/:startup_id/followers/ids"
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
            "description": "Get Startup Followers IDs"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d062e52e-1d3f-4164-94cf-0c1b3a3e5455"
            }
          ]
        }
      ]
    }
  ]
}