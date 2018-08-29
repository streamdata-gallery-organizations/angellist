{
  "info": {
    "name": "AngelList Get Tag Parents",
    "_postman_id": "a4f2b7e1-b43d-4cfa-bec3-329448fe66fb",
    "description": "Get Tag Parents",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "b1296bbf-3fbe-4812-a554-a8d562eab1d3",
          "name": "tagParents",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.angel.co",
              "path": [
                "1",
                "tags/:tag_id/parents"
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
            "description": "Get Tag Parents"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d87e692d-b82e-4855-879f-6f50b3d3f14c"
            }
          ]
        }
      ]
    }
  ]
}