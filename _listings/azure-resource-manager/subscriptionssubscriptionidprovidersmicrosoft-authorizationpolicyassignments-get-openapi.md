---
swagger: "2.0"
x-collection-name: Azure Resource Manager
x-complete: 0
info:
  title: Azure Resource Manager API Policy Assignments List
  description: Gets all the policy assignments for a subscription.
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
    put:
      summary: Creates a policy assignment.
      description: Policy assignments are inherited by child resources. For example,
        when you apply a policy to a resource group that policy is assigned to all
        resources in the group.
      operationId: PolicyAssignments_Create
      x-api-path-slug: scopeprovidersmicrosoft-authorizationpolicyassignmentspolicyassignmentname-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters for the policy assignment
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: policyAssignmentName
        description: The name of the policy assignment
      - in: path
        name: scope
        description: The scope of the policy assignment
      responses:
        200:
          description: OK
      tags:
      - Policy Assignments
    get:
      summary: Policy Assignments Get
      description: Gets a policy assignment.
      operationId: PolicyAssignments_Get
      x-api-path-slug: scopeprovidersmicrosoft-authorizationpolicyassignmentspolicyassignmentname-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: policyAssignmentName
        description: The name of the policy assignment to get
      - in: path
        name: scope
        description: The scope of the policy assignment
      responses:
        200:
          description: OK
      tags:
      - Policy Assignments
  ? /subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{parentResourcePath}/{resourceType}/{resourceName}/providers/Microsoft.Authorization/policyassignments
  : get:
      summary: Policy Assignments List For Resource
      description: Gets policy assignments for a resource.
      operationId: PolicyAssignments_ListForResource
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersresourceprovidernamespaceparentresourcepathresourcetyperesourcenameprovidersmicrosoft-authorizationpolicyassignments-get
      parameters:
      - in: query
        name: $filter
        description: The filter to apply on the operation
      - in: query
        name: No Name
      - in: path
        name: parentResourcePath
        description: The parent resource path
      - in: path
        name: resourceGroupName
        description: The name of the resource group containing the resource
      - in: path
        name: resourceName
        description: The name of the resource with policy assignments
      - in: path
        name: resourceProviderNamespace
        description: The namespace of the resource provider
      - in: path
        name: resourceType
        description: The resource type
      responses:
        200:
          description: OK
      tags:
      - Policy Assignments
  /subscriptions/{subscriptionId}/providers/Microsoft.Authorization/policyassignments:
    get:
      summary: Policy Assignments List
      description: Gets all the policy assignments for a subscription.
      operationId: PolicyAssignments_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-authorizationpolicyassignments-get
      parameters:
      - in: query
        name: $filter
        description: The filter to apply on the operation
      - in: query
        name: No Name
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