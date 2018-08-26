{
  "info": {
    "name": "SubscriptionClient",
    "_postman_id": "f28deef7-61fc-44c8-b106-70942f5333d8",
    "description": "All resource groups and resources exist within subscriptions. These operation enable you get information about your subscriptions and tenants. A tenant is a dedicated instance of Azure Active Directory (Azure AD) for your organization.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "policy assignments",
      "item": [
        {
          "id": "aab9d645-5926-4bb4-964e-9a517f1bae4b",
          "name": "PolicyAssignments_Delete",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a policy assignment"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6ff4c856-592e-4d76-be56-e6a3bd0729d5"
            }
          ]
        }
      ]
    }
  ]
}