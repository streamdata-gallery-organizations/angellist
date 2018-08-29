{
  "info": {
    "name": "AngelList Get Comments",
    "_postman_id": "17678eba-24f2-42b9-9721-5e3d49750d28",
    "description": "Pulls the comments for given object.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "41beb35e-1c52-4372-9b0c-30c6bbc76652",
          "name": "comments",
          "request": {
            "url": "http://api.angel.co/1/comments?commentable_id=%7B%7D&commentable_type=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Pulls the comments for given object"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "37d75c51-bb8a-4039-bfe7-7b9c0e6e0d90"
            }
          ]
        }
      ]
    }
  ]
}