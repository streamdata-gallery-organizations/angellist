{
  "info": {
    "name": "AngelList Search Slugs",
    "_postman_id": "f656a9d0-f7b8-4b24-bfde-5df2948501d7",
    "description": "Search by slug",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "1374c201-c99e-4de4-9e0e-a357cea10eac",
          "name": "search",
          "request": {
            "url": "http://api.angel.co/1/search/slugs?query=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Search by slug"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "74e157d3-d7c2-4ccf-b450-cbe85ad29b30"
            }
          ]
        }
      ]
    }
  ]
}