---
title: "List plannerUsers"
description: "Get a list of the plannerUser objects and their properties."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# List plannerUsers
Namespace: microsoft.graph

Get a list of the [plannerUser](../resources/planneruser.md) objects and their properties.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from least to most privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
GET ** Collection URI for microsoft.graph.plannerUser not found
```

## Optional query parameters
This method supports some of the OData query parameters to help customize the response. For general information, see [OData query parameters](/graph/query-parameters).

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and a collection of [plannerUser](../resources/planneruser.md) objects in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "list_planneruser"
}
-->
``` http
GET https://graph.microsoft.com/beta** Collection URI for microsoft.graph.plannerUser not found
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(microsoft.graph.plannerUser)"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": [
    {
      "@odata.type": "#microsoft.graph.plannerUser",
      "id": "88872b0b-2b0b-8887-0b2b-87880b2b8788",
      "favoritePlanReferences": {
        "@odata.type": "microsoft.graph.plannerFavoritePlanReferenceCollection"
      },
      "recentPlanReferences": {
        "@odata.type": "microsoft.graph.plannerRecentPlanReferenceCollection"
      }
    }
  ]
}
```
