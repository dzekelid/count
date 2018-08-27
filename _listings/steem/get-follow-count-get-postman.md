{
  "info": {
    "name": "Steem get_follow_count",
    "_postman_id": "223d4c30-8d99-4196-8c89-f5edc4330043",
    "description": "get_follow_count",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Get",
      "item": [
        {
          "id": "ac1c03e2-7f15-4f26-82a2-ab9236517973",
          "name": "get-witness-count",
          "request": {
            "url": "http://api.steemjs.com/get_witness_count",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get_witness_count"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "676f3428-0395-4e07-9bc2-f507f6eca189"
            }
          ]
        },
        {
          "id": "78e06642-b82a-4547-bf92-afe329603c73",
          "name": "get-follow-count",
          "request": {
            "url": "http://api.steemjs.com/get_follow_count?account=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get_follow_count"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7d1f1021-3a10-4127-bd2c-612e0a4ff281"
            }
          ]
        }
      ]
    }
  ]
}