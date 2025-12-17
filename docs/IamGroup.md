# IamGroup


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** |  | [optional] 
**enterprise_ids** | **List[int]** |  | [optional] 
**enterprise_permissions** | [**Dict[str, IamEnterprisePermissions]**](IamEnterprisePermissions.md) |  | [optional] 
**group_type** | **str** |  | [optional] 
**id** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**permissions** | [**CommonPermissions**](CommonPermissions.md) |  | [optional] 
**time_window_end** | **int** |  | [optional] 
**time_window_start** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.iam_group import IamGroup

# TODO update the JSON string below
json = "{}"
# create an instance of IamGroup from a JSON string
iam_group_instance = IamGroup.from_json(json)
# print the JSON string representation of the object
print(IamGroup.to_json())

# convert the object into a dict
iam_group_dict = iam_group_instance.to_dict()
# create an instance of IamGroup from a dict
iam_group_from_dict = IamGroup.from_dict(iam_group_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


