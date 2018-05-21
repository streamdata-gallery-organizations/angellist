{
  "info": {
    "name": "AngelList Get Accreditation",
    "_postman_id": "dc71e413-8188-4729-92a3-95df833a1ed4",
    "description": "Pulls the accreditation for a startup and users.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "2000efde-5047-48fa-90b4-da1518ef6134",
          "name": "accreditation",
          "request": {
            "url": "http://api.angel.co/1/accreditation",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Pulls the accreditation for a startup and users"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6bc0d716-4b5b-47f9-9b17-b8cf875e2272"
            }
          ]
        }
      ]
    }
  ]
}