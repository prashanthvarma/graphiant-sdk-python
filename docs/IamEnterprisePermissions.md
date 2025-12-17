# IamEnterprisePermissions


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**group_type** | **str** |  (required) | [optional] 
**permissions** | [**CommonPermissions**](CommonPermissions.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.iam_enterprise_permissions import IamEnterprisePermissions

# TODO update the JSON string below
json = "{}"
# create an instance of IamEnterprisePermissions from a JSON string
iam_enterprise_permissions_instance = IamEnterprisePermissions.from_json(json)
# print the JSON string representation of the object
print(IamEnterprisePermissions.to_json())

# convert the object into a dict
iam_enterprise_permissions_dict = iam_enterprise_permissions_instance.to_dict()
# create an instance of IamEnterprisePermissions from a dict
iam_enterprise_permissions_from_dict = IamEnterprisePermissions.from_dict(iam_enterprise_permissions_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


