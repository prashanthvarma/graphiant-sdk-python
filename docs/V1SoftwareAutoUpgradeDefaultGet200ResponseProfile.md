# V1SoftwareAutoUpgradeDefaultGet200ResponseProfile


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**action** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**occurrence** | [**V1SoftwareAutoUpgradeDefaultGet200ResponseProfileOccurrence**](V1SoftwareAutoUpgradeDefaultGet200ResponseProfileOccurrence.md) |  | [optional] 
**release** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_software_auto_upgrade_default_get200_response_profile import V1SoftwareAutoUpgradeDefaultGet200ResponseProfile

# TODO update the JSON string below
json = "{}"
# create an instance of V1SoftwareAutoUpgradeDefaultGet200ResponseProfile from a JSON string
v1_software_auto_upgrade_default_get200_response_profile_instance = V1SoftwareAutoUpgradeDefaultGet200ResponseProfile.from_json(json)
# print the JSON string representation of the object
print(V1SoftwareAutoUpgradeDefaultGet200ResponseProfile.to_json())

# convert the object into a dict
v1_software_auto_upgrade_default_get200_response_profile_dict = v1_software_auto_upgrade_default_get200_response_profile_instance.to_dict()
# create an instance of V1SoftwareAutoUpgradeDefaultGet200ResponseProfile from a dict
v1_software_auto_upgrade_default_get200_response_profile_from_dict = V1SoftwareAutoUpgradeDefaultGet200ResponseProfile.from_dict(v1_software_auto_upgrade_default_get200_response_profile_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


