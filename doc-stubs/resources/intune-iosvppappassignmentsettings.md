---
title: "iosVppAppAssignmentSettings resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# iosVppAppAssignmentSettings resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [mobileAppAssignmentSettings](../resources/mobileappassignmentsettings.md).

## Properties
|Property|Type|Description|
|:---|:---|:---|
|isRemovable|Boolean|**TODO: Add Description**|
|uninstallOnDeviceRemoval|Boolean|**TODO: Add Description**|
|useDeviceLicensing|Boolean|**TODO: Add Description**|
|vpnConfigurationId|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.iosVppAppAssignmentSettings"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.iosVppAppAssignmentSettings",
  "useDeviceLicensing": "Boolean",
  "vpnConfigurationId": "String",
  "uninstallOnDeviceRemoval": "Boolean",
  "isRemovable": "Boolean"
}
```
