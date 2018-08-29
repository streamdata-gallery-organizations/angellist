{
  "info": {
    "name": "AngelList Delete Status Update",
    "_postman_id": "e38972f3-4951-4714-a860-6d77197fa14c",
    "description": "Delete Status Update",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "startups",
      "item": [
        {
          "id": "8c8a2b08-1d1d-46b9-92b0-731ac6fa659f",
          "name": "statusUpdate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.angel.co",
              "path": [
                "1",
                "status_updates/:status_update_id"
              ],
              "query": [
                {
                  "key": "message",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "startup_id",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "status_update_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete Status Update"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7e336397-965b-4976-a840-08c25b6bb65c"
            }
          ]
        }
      ]
    }
  ]
}