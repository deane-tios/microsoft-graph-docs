﻿# windowsPhone81TrustedRootCertificate resource type

Windows Phone 8.1+ Trusted Root Certificate configuration profile

Inherits from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)

### Methods
|Method|Return Type|Description|
|---|---|---|
|[List windowsPhone81TrustedRootCertificates](../api/intune_deviceconfig_windowsphone81trustedrootcertificate_list.md)|[windowsPhone81TrustedRootCertificate](../resources/intune_deviceconfig_windowsphone81trustedrootcertificate.md) collection|List properties and relationships of the [windowsPhone81TrustedRootCertificate](../resources/intune_deviceconfig_windowsphone81trustedrootcertificate.md) objects.|
|[Get windowsPhone81TrustedRootCertificate](../api/intune_deviceconfig_windowsphone81trustedrootcertificate_get.md)|[windowsPhone81TrustedRootCertificate](../resources/intune_deviceconfig_windowsphone81trustedrootcertificate.md)|Read properties and relationships of the [windowsPhone81TrustedRootCertificate](../resources/intune_deviceconfig_windowsphone81trustedrootcertificate.md) object.|
|[Create windowsPhone81TrustedRootCertificate](../api/intune_deviceconfig_windowsphone81trustedrootcertificate_create.md)|[windowsPhone81TrustedRootCertificate](../resources/intune_deviceconfig_windowsphone81trustedrootcertificate.md)|Create a new [windowsPhone81TrustedRootCertificate](../resources/intune_deviceconfig_windowsphone81trustedrootcertificate.md) object.|
|[Delete windowsPhone81TrustedRootCertificate](../api/intune_deviceconfig_windowsphone81trustedrootcertificate_delete.md)|None|Deletes a [windowsPhone81TrustedRootCertificate](../resources/intune_deviceconfig_windowsphone81trustedrootcertificate.md).|
|[Update windowsPhone81TrustedRootCertificate](../api/intune_deviceconfig_windowsphone81trustedrootcertificate_update.md)|[windowsPhone81TrustedRootCertificate](../resources/intune_deviceconfig_windowsphone81trustedrootcertificate.md)|Update the properties of a [windowsPhone81TrustedRootCertificate](../resources/intune_deviceconfig_windowsphone81trustedrootcertificate.md) object.|
|[List deviceConfigurationGroupAssignments](../api/intune_deviceconfig_windowsphone81trustedrootcertificate_list_deviceconfigurationgroupassignment.md)|[deviceConfigurationGroupAssignment](../resources/intune_deviceconfig_deviceconfigurationgroupassignment.md) collection|Get the deviceConfigurationGroupAssignments from the groupAssignments navigation property.|
|[List deviceConfigurationDeviceStatuses](../api/intune_deviceconfig_windowsphone81trustedrootcertificate_list_deviceconfigurationdevicestatus.md)|[deviceConfigurationDeviceStatus](../resources/intune_deviceconfig_deviceconfigurationdevicestatus.md) collection|Get the deviceConfigurationDeviceStatuses from the deviceStatuses navigation property.|
|[List deviceConfigurationUserStatuses](../api/intune_deviceconfig_windowsphone81trustedrootcertificate_list_deviceconfigurationuserstatus.md)|[deviceConfigurationUserStatus](../resources/intune_deviceconfig_deviceconfigurationuserstatus.md) collection|Get the deviceConfigurationUserStatuses from the userStatuses navigation property.|

### Properties
|Property|Type|Description|
|---|---|---|
|id|String|Key of the entity. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|lastModifiedDateTime|DateTimeOffset|DateTime the object was last modified. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|createdDateTime|DateTimeOffset|DateTime the object was created. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|description|String|Admin provided description of the Device Configuration. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|displayName|String|Admin provided name of the device configuration. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|version|Int32|Version of the device configuration. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|trustedRootCertificate|Binary|Trusted Root Certificate|
|certFileName|String|File name to display in UI.|

### Relationships
|Relationship|Type|Description|
|---|---|---|
|groupAssignments|[deviceConfigurationGroupAssignment](../resources/intune_deviceconfig_deviceconfigurationgroupassignment.md) collection|The list of group assignments for the device configuration profile. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|deviceStatuses|[deviceConfigurationDeviceStatus](../resources/intune_deviceconfig_deviceconfigurationdevicestatus.md) collection|Device configuration installation stauts by device. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|
|userStatuses|[deviceConfigurationUserStatus](../resources/intune_deviceconfig_deviceconfigurationuserstatus.md) collection|Device configuration installation stauts by user. Inherited from [deviceConfiguration](../resources/intune_deviceconfig_deviceconfiguration.md)|

### JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.windowsPhone81TrustedRootCertificate"
}
-->
```json
{
  "@odata.type": "#microsoft.graph.windowsPhone81TrustedRootCertificate",
  "id": "String (identifier)",
  "lastModifiedDateTime": "String (timestamp)",
  "createdDateTime": "String (timestamp)",
  "description": "String",
  "displayName": "String",
  "version": 1024,
  "trustedRootCertificate": "binary",
  "certFileName": "String"
}
```



