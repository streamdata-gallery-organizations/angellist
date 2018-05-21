{
  "info": {
    "name": "AngelList Get Batch of Follows",
    "_postman_id": "662b1f9b-afd0-4ac3-b0e7-a2cbffe19c82",
    "description": "Returns a batched lists of follows",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "27f44c84-6f4f-4090-a4b4-0d32c290515f",
          "name": "followsBatch",
          "request": {
            "url": "http://api.angel.co/1/follows/batch?ids=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a batched lists of follows"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "23609ee6-ba91-42e7-aff2-d3c2a6e5f003"
            }
          ]
        }
      ]
    }
  ]
}