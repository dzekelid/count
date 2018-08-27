{
  "info": {
    "name": "Steem get_witness_count",
    "_postman_id": "74a3ed50-1ad9-43ca-82ee-a904e7e7374d",
    "description": "get_witness_count",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Get",
      "item": [
        {
          "id": "d10ba16a-2d35-4ad2-943f-719ef53656e5",
          "name": "get-witnesses",
          "request": {
            "url": "http://api.steemjs.com/get_witnesses?witnessIds=%7B%7D",
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
            "description": "get_witnesses"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4cd92bf8-1171-4b42-be3c-1e52e5333e26"
            }
          ]
        },
        {
          "id": "54c27905-042d-41f7-b6fc-97c5ba8c6158",
          "name": "get-witnesses-by-vote",
          "request": {
            "url": "http://api.steemjs.com/get_witnesses_by_vote?from=%7B%7D&limit=%7B%7D",
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
            "description": "get_witnesses_by_vote"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4eff9fd5-d5c4-4f6b-98e6-69b9b896c8ba"
            }
          ]
        },
        {
          "id": "2c8a3e8b-a52f-4982-9c14-5a3bdb8d68d7",
          "name": "get-active-witnesses",
          "request": {
            "url": "http://api.steemjs.com/get_active_witnesses",
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
            "description": "get_active_witnesses"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2cfe8e49-8a3d-40ee-a48c-6e4c3d991987"
            }
          ]
        },
        {
          "id": "f04be7a9-e73d-4ed2-b78c-e24e931deb87",
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
              "id": "32c2a7fc-14f5-4c38-93ef-1368545e0c04"
            }
          ]
        },
        {
          "id": "406bef4a-743c-46ef-9b9c-670affab33bf",
          "name": "get-witness-schedule",
          "request": {
            "url": "http://api.steemjs.com/get_witness_schedule",
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
            "description": "get_witness_schedule"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3f314a68-1171-4dcf-8706-26fddc450fc4"
            }
          ]
        },
        {
          "id": "9af9294d-e804-490a-b073-986332abed03",
          "name": "get-witness-by-account",
          "request": {
            "url": "http://api.steemjs.com/get_witness_by_account?accountName=%7B%7D",
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
            "description": "get_witness_by_account"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "77eb96a8-1488-4c11-966e-d2e62b280fd5"
            }
          ]
        }
      ]
    },
    {
      "name": "Lookup",
      "item": [
        {
          "id": "3c98f08c-2272-44a8-bc93-ac0dbc987134",
          "name": "lookup-witness-accounts-regex-search",
          "request": {
            "url": "http://api.steemjs.com/lookup_witness_accounts?limit=%7B%7D&lowerBoundName=%7B%7D",
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
            "description": "lookup_witness_accounts regex search"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "003d48a7-8fe7-46ab-9e45-58b9c9d48ac0"
            }
          ]
        }
      ]
    },
    {
      "name": "Witness",
      "item": [
        {
          "id": "e3c9082c-e04c-469f-81ee-e1b8bde71486",
          "name": "witness-update",
          "request": {
            "url": "http://api.steemjs.com/witness_update?block_signing_key=%7B%7D&fee=%7B%7D&owner=%7B%7D&props=%7B%7D&url=%7B%7D",
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
            "description": "witness_update"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "85602453-88ff-4954-ad47-27f6d1983692"
            }
          ]
        }
      ]
    }
  ]
}