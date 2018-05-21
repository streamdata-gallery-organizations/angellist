{
  "info": {
    "name": "AngelList Get Startup Roles",
    "_postman_id": "564470eb-df0d-40ca-a074-2ae6b390a9d8",
    "description": "Get Startup Roles",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "09e7c8ff-2e42-4703-a6f9-0f27c92bdbd7",
          "name": "startupRoles",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.angel.co",
              "path": [
                "1",
                "startups/:startup_id/roles"
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
            "description": "Get Startup Roles"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "526b0374-b20e-463b-804a-18bd7edeeb08"
            }
          ]
        }
      ]
    }
  ]
}