# V1GlobalSiteListsPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** |  | [optional] 
**entries** | [**List[V1GlobalSiteListsPostRequestEntriesInner]**](V1GlobalSiteListsPostRequestEntriesInner.md) |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_site_lists_post_request import V1GlobalSiteListsPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalSiteListsPostRequest from a JSON string
v1_global_site_lists_post_request_instance = V1GlobalSiteListsPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1GlobalSiteListsPostRequest.to_json())

# convert the object into a dict
v1_global_site_lists_post_request_dict = v1_global_site_lists_post_request_instance.to_dict()
# create an instance of V1GlobalSiteListsPostRequest from a dict
v1_global_site_lists_post_request_from_dict = V1GlobalSiteListsPostRequest.from_dict(v1_global_site_lists_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


