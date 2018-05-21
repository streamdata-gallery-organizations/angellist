{
  "info": {
    "name": "AngelList Get Jobs",
    "_postman_id": "625a13b6-1c86-4489-a631-239b582f283c",
    "description": "Get jobs.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "1bc57679-cf1b-48e4-a01e-fa2c4414dc56",
          "name": "jobs",
          "request": {
            "url": "http://api.angel.co/1/jobs",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get jobs"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "61023170-eada-4774-abf7-d3c496904c31"
            }
          ]
        }
      ]
    }
  ]
}