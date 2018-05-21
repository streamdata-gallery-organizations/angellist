{
  "info": {
    "name": "AngelList Get Likes",
    "_postman_id": "47839e36-6137-4098-9c19-c6e427f3fee5",
    "description": "Get likes",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "8f9caab4-9779-4a77-b920-bffa593840b9",
          "name": "likes",
          "request": {
            "url": "http://api.angel.co/1/likes?likable_id=%7B%7D&likable_type=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get likes"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2ff51fda-deb0-4c0e-ad7f-a41f391d894e"
            }
          ]
        }
      ]
    }
  ]
}