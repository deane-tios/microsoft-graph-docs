﻿# List defaultManagedAppConfigurations
List properties and relationships of the [defaultManagedAppConfiguration](../resources/intune_mam_defaultmanagedappconfiguration.md) objects.
### Prerequisites
One of the following **scopes** is required to execute this API:

*DeviceManagementApps.ReadWrite.All; DeviceManagementApps.Read.All*
### HTTP Request
<!-- {
  "blockType": "ignored"
}
-->
```http
GET /managedAppPolicies/
GET /managedAppRegistrations/{id}/appliedPolicies/
GET /managedAppRegistrations/{id}/intendedPolicies/
```

### Request headers
|Header|Value|
|---|---|
|Authorization|Bearer &lt;token&gt; Required.|
|Accept|application/json|

### Request body
Do not supply a request body for this method.

### Response
If successful, this method returns a `200 OK` response code and a collection of [defaultManagedAppConfiguration](../resources/intune_mam_defaultmanagedappconfiguration.md) objects in the response body.

### Example
##### Request
Here is an example of the request.
```http
GET https://graph.microsoft.com/beta/managedAppPolicies/
```

##### Response
Here is an example of the response. Note: The response object shown here may be truncated for brevity. All of the properties will be returned from an actual call.
```http
HTTP/1.1 200 OK
Content-Type: application/json
Content-Length: 563

{
  "value": [
    {
      "@odata.type": "#microsoft.graph.defaultManagedAppConfiguration",
      "displayName": "Display Name value",
      "description": "Description value",
      "lastModifiedTime": "2017-01-01T00:03:18.5958204-08:00",
      "deployedAppCount": 16,
      "id": "6f83d45c-d45c-6f83-5cd4-836f5cd4836f",
      "version": "Version value",
      "customSettings": [
        {
          "@odata.type": "microsoft.graph.keyValuePair",
          "name": "Name value",
          "value": "Value value"
        }
      ]
    }
  ]
}
```



