{
  "info": {
    "name": "Azure Resource Manager API Policy Assignments List",
    "_postman_id": "971aff3b-da93-4ae9-9fe0-9aa8553e442c",
    "description": "Gets all the policy assignments for a subscription.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "policy assignments",
      "item": [
        {
          "id": "06a002bd-e7d8-4617-bf27-79e0d556d6c2",
          "name": "PolicyAssignments_List",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/providers/Microsoft.Authorization/policyassignments"
              ],
              "query": [
                {
                  "key": "$filter",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets all the policy assignments for a subscription"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b23c91db-fcc7-4726-aecc-9ab497c48ef4"
            }
          ]
        }
      ]
    }
  ]
}