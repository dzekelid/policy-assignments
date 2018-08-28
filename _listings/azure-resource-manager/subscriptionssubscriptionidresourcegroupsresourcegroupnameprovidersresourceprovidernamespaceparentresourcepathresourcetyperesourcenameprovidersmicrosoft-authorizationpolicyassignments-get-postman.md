{
  "info": {
    "name": "Azure Resource Manager API Policy Assignments List For Resource",
    "_postman_id": "a1577f8a-bb57-4729-89de-a79e92817fb7",
    "description": "Gets policy assignments for a resource.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "policy assignments",
      "item": [
        {
          "id": "60b06895-4d88-4c9e-b636-a8587bf6cffe",
          "name": "PolicyAssignments_ListForResource",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourcegroups/:resourceGroupName/providers/:resourceProviderNamespace/:parentResourcePath/:resourceType/:resourceName/providers/Microsoft.Authorization/policyassignments"
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
                  "id": "parentResourcePath",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "resourceGroupName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "resourceName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "resourceProviderNamespace",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "resourceType",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "Gets policy assignments for a resource"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "73f978a1-1195-4860-9518-036ccd7f009d"
            }
          ]
        }
      ]
    }
  ]
}