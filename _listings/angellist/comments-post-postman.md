{
  "info": {
    "name": "AngelList Add Comment",
    "_postman_id": "c8b92fd1-a498-4f0d-b942-a86d90202ace",
    "description": "Adds a comment for given object",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "5dbf7898-4f6b-4c85-8929-6f74cc750db0",
          "name": "comment",
          "request": {
            "url": "http://api.angel.co/1/comments?comment=%7B%7D&commentable_id=%7B%7D&commentable_type=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Adds a comment for given object"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ce28999e-aef4-4a85-9314-dd086f0e72fc"
            }
          ]
        }
      ]
    }
  ]
}