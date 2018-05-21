{
  "info": {
    "name": "AngelList User Search",
    "_postman_id": "b106b82d-fbcd-467a-943c-b68f2642116a",
    "description": "User Search",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "c1d1d76c-0827-4869-9481-0a5df1cb09f6",
          "name": "users",
          "request": {
            "url": "http://api.angel.co/1/users/search?slug=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "User Search"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ce9f904e-da0e-41fe-866b-77bf1f9b5ffe"
            }
          ]
        }
      ]
    }
  ]
}