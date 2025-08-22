# V1GlobalSiteListsGet200ResponseEntriesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**created_at** | [**V1AlarmHistoryGet200ResponseHistoryInnerTime**](V1AlarmHistoryGet200ResponseHistoryInnerTime.md) |  | [optional] 
**description** | **str** |  | [optional] 
**edge_references** | **int** |  | [optional] 
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**policy_references** | **int** |  | [optional] 
**site_list_references** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_site_lists_get200_response_entries_inner import V1GlobalSiteListsGet200ResponseEntriesInner

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalSiteListsGet200ResponseEntriesInner from a JSON string
v1_global_site_lists_get200_response_entries_inner_instance = V1GlobalSiteListsGet200ResponseEntriesInner.from_json(json)
# print the JSON string representation of the object
print(V1GlobalSiteListsGet200ResponseEntriesInner.to_json())

# convert the object into a dict
v1_global_site_lists_get200_response_entries_inner_dict = v1_global_site_lists_get200_response_entries_inner_instance.to_dict()
# create an instance of V1GlobalSiteListsGet200ResponseEntriesInner from a dict
v1_global_site_lists_get200_response_entries_inner_from_dict = V1GlobalSiteListsGet200ResponseEntriesInner.from_dict(v1_global_site_lists_get200_response_entries_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


