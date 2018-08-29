{
  "info": {
    "name": "AngelList Delete Like",
    "_postman_id": "7f9c33d8-3acb-4ffa-80a4-8ac1b7077c69",
    "description": "Delete Like",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "0837224f-28df-4b58-940c-9a026e787160",
          "name": "likes",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.angel.co",
              "path": [
                "1",
                "likes/:like_id"
              ],
              "query": [
                {
                  "key": "likable_type",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "like_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete Like"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9203a889-a7b7-4e3b-bb2f-206be6bd2730"
            }
          ]
        }
      ]
    }
  ]
}