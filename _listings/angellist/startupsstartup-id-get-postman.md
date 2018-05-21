{
  "info": {
    "name": "AngelList Get Startup",
    "_postman_id": "6925525e-20f5-4a52-8c93-c4736f64b4cd",
    "description": "Get Startup",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "e3669cb0-cfe2-4eaa-a168-995c89440708",
          "name": "startups",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.angel.co",
              "path": [
                "1",
                "startups/:startup_id"
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
            "description": "Get Startup"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cd68f515-99a9-42e3-8e00-e6e35cac51b6"
            }
          ]
        }
      ]
    }
  ]
}