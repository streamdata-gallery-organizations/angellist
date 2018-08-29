{
  "info": {
    "name": "AngelList Get Job",
    "_postman_id": "27d06d1c-80f4-44cd-8047-a3d796b026dc",
    "description": "Get job.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "737bc042-24f5-4118-a1ae-737bd421f83c",
          "name": "job",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.angel.co",
              "path": [
                "1",
                "jobs/:job_id"
              ],
              "variable": [
                {
                  "id": "job_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get job"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9b2564a5-acd2-454c-a1a2-44c51a93d9bb"
            }
          ]
        }
      ]
    }
  ]
}