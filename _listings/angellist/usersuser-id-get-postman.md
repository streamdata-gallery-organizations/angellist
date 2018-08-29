{
  "info": {
    "name": "AngelList Get User",
    "_postman_id": "e7639361-52e3-43e2-b5b4-0ca53cb030c7",
    "description": "Get User",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "11ade300-7d50-45cb-9889-eacc45283811",
          "name": "user",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.angel.co",
              "path": [
                "1",
                "users/:user_id"
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
            "description": "Get User"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "910b17af-355c-45e1-8fab-9dcb16686e85"
            }
          ]
        }
      ]
    }
  ]
}