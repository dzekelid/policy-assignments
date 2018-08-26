---
name: Azure Resource Manager
x-slug: azure-resource-manager
description: Azure Resource Manager enables you to deploy and manage the infrastructure
  for your Azure solutions. You organize related resources in resource groups, and
  deploy your resources with JSON templates. For an introduction to deploying and
  managing resources with Resource Manager, see Azure Resource Manager overview.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Policy Assignments
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/policy-assignments/master/_listings/azure-resource-manager/apis.md
specificationVersion: "0.14"
apis:
- name: SubscriptionClient - Policy Assignments Delete
  x-api-slug: scopeprovidersmicrosoft-authorizationpolicyassignmentspolicyassignmentname-delete
  description: Deletes a policy assignment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com//
  tags: Microsoft, Resources, Links, API Service Provider, API Provider, Deployments,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policy-assignments/master/_listings/azure-resource-manager/scopeprovidersmicrosoft-authorizationpolicyassignmentspolicyassignmentname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policy-assignments/master/_listings/azure-resource-manager/scopeprovidersmicrosoft-authorizationpolicyassignmentspolicyassignmentname-delete-openapi.md
- name: SubscriptionClient - Policy Assignments Get
  x-api-slug: scopeprovidersmicrosoft-authorizationpolicyassignmentspolicyassignmentname-get
  description: Gets a policy assignment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com//
  tags: Microsoft, Resources, Links, API Service Provider, API Provider, Deployments,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policy-assignments/master/_listings/azure-resource-manager/scopeprovidersmicrosoft-authorizationpolicyassignmentspolicyassignmentname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policy-assignments/master/_listings/azure-resource-manager/scopeprovidersmicrosoft-authorizationpolicyassignmentspolicyassignmentname-get-openapi.md
- name: SubscriptionClient - Policy Assignments List For Resource
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersresourceprovidernamespaceparentresourcepathresourcetyperesourcenameprovidersmicrosoft-authorizationpolicyassignments-get
  description: Gets policy assignments for a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com//
  tags: Microsoft, Resources, Links, API Service Provider, API Provider, Deployments,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policy-assignments/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersresourceprovidernamespaceparentresourcepathresourcetyperesourcenameprovidersmicrosoft-authorizationpolicyassignments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policy-assignments/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersresourceprovidernamespaceparentresourcepathresourcetyperesourcenameprovidersmicrosoft-authorizationpolicyassignments-get-openapi.md
- name: SubscriptionClient - Policy Assignments List
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-authorizationpolicyassignments-get
  description: Gets all the policy assignments for a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com//
  tags: Microsoft, Resources, Links, API Service Provider, API Provider, Deployments,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policy-assignments/master/_listings/azure-resource-manager/subscriptionssubscriptionidprovidersmicrosoft-authorizationpolicyassignments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policy-assignments/master/_listings/azure-resource-manager/subscriptionssubscriptionidprovidersmicrosoft-authorizationpolicyassignments-get-openapi.md
- name: SubscriptionClient - Deletes a policy assignment by ID.
  x-api-slug: policyassignmentid-delete
  description: When providing a scope for the assigment, use '/subscriptions/{subscription-id}/'
    for subscriptions, '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}'
    for resource groups, and '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}'
    for resources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com//
  tags: Microsoft, Resources, Links, API Service Provider, API Provider, Deployments,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policy-assignments/master/_listings/azure-resource-manager/policyassignmentid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policy-assignments/master/_listings/azure-resource-manager/policyassignmentid-delete-openapi.md
- name: SubscriptionClient - Gets a policy assignment by ID.
  x-api-slug: policyassignmentid-get
  description: When providing a scope for the assigment, use '/subscriptions/{subscription-id}/'
    for subscriptions, '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}'
    for resource groups, and '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}'
    for resources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com//
  tags: Microsoft, Resources, Links, API Service Provider, API Provider, Deployments,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policy-assignments/master/_listings/azure-resource-manager/policyassignmentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policy-assignments/master/_listings/azure-resource-manager/policyassignmentid-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.resource.health.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.resource.manager.stack.network
- type: x-website
  url: https://docs.microsoft.com/en-us/rest/api/resources/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---