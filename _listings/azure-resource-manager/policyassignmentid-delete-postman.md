{
  "info": {
    "name": "Azure Resource Manager API Deletes a policy assignment by ID.",
    "_postman_id": "293fa98d-c8f7-4133-8f5e-ff1ca22a2e0f",
    "description": "When providing a scope for the assigment, use '/subscriptions/{subscription-id}/' for subscriptions, '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}' for resource groups, and '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}' for resources.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "policy assignments",
      "item": [
        {
          "id": "075697b2-365b-4255-b24a-8c0588d4720b",
          "name": "PolicyAssignments_DeleteById",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                ":policyAssignmentId"
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
                  "id": "policyAssignmentId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "When providing a scope for the assigment, use '/subscriptions/{subscription-id}/' for subscriptions, '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}' for resource groups, and '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}' for resources"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a9f49834-a8ce-4927-9b63-dfa1807309c4"
            }
          ]
        }
      ]
    }
  ]
}