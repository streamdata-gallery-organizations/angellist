{
  "info": {
    "name": "AngelList Get Startup Roles",
    "_postman_id": "e615e66d-852b-4b8d-976e-d0893f071b56",
    "description": "Get Startup Roles",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "3ec08175-2a62-421c-bcd2-567ca7a47d79",
          "name": "1Startup_roles",
          "request": {
            "url": "http://api.angel.co/1/startup_roles?startup_id=%7B%7D&v=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Startup Roles"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "836b1ada-c084-45bc-8986-2dfbbf0c052f"
            }
          ]
        }
      ]
    }
  ]
}