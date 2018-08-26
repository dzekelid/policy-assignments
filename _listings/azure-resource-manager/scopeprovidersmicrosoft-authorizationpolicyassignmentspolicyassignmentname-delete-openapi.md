---
swagger: "2.0"
x-collection-name: Azure Resource Manager
x-complete: 0
info:
  title: Azure Resource Manager API Policy Assignments Delete
  description: Deletes a policy assignment.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{scope}/providers/Microsoft.Authorization/policyassignments/{policyAssignmentName}:
    delete:
      summary: Policy Assignments Delete
      description: Deletes a policy assignment.
      operationId: PolicyAssignments_Delete
      x-api-path-slug: scopeprovidersmicrosoft-authorizationpolicyassignmentspolicyassignmentname-delete
      parameters:
      - in: query
        name: No Name
      - in: path
        name: policyAssignmentName
        description: The name of the policy assignment to delete
      - in: path
        name: scope
        description: The scope of the policy assignment
      responses:
        200:
          description: OK
      tags:
      - Policy Assignments
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---