# This is table test file

## table validation
The results are similar to the following values:

| Property Name | Value |
|-|----|
| Name | `AzureGermanCloud` |
| EnableAdfsAuthentication | `False` |
| ActiveDirectoryServiceEndpointResourceI | `http://management.core.cloudapi.de/` |
| GalleryURL | `https://gallery.cloudapi.de/` |
| ManagementPortalUrl | `https://portal.microsoftazure.de/` |
| ServiceManagementUrl | `https://manage.core.cloudapi.de/` |
| PublishSettingsFileUrl| `https://manage.microsoftazure.de/publishsettings/index` |
| ResourceManagerUrl | `http://management.microsoftazure.de/` |
| SqlDatabaseDnsSuffix | `.database.cloudapi.de` |
| **StorageEndpointSuffix** | `core.cloudapi.de` |
| ... | ... |
To retrieve just the storage endpoint suffix property, retrieve the specific cloud and ask for just that one property.

```powershell
$environment = Get-AzEnvironment -Name AzureGermanCloud
Write-Host "Storage EndPoint Suffix = " $environment.StorageEndpointSuffix
```


## table validation 2
Delivery slots:

| |**Monday**|**Tuesday**|**Wednesday**|**Thursday**|
|-|-------|-------|-------|-------|
|**09:00 - 11:00**|B|C|D|E|
|09:00 - 11:00|B|C|D|E|
|**09:00 - 11:00**|B|C|D|E|
|**09:00 - 11:00**|B|C|D|E|