{
  "info": {
    "name": "Azure Resource Manager API Policy Assignments Get",
    "_postman_id": "52279230-3506-4a5f-ba3c-f29b7918daeb",
    "description": "Gets a policy assignment.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "policy assignments",
      "item": [
        {
          "id": "44530a30-a27e-4f0d-bf5c-3230ff75fdb1",
          "name": "PolicyAssignments_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                ":scope/providers/Microsoft.Authorization/policyassignments/:policyAssignmentName"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "policyAssignmentName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "scope",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a policy assignment"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "203bfa75-4fad-4bcb-b061-cae9a6cbea3e"
            }
          ]
        }
      ]
    }
  ]
}