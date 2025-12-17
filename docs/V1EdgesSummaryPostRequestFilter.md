# V1EdgesSummaryPostRequestFilter


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_ids** | **List[int]** |  | [optional] 
**roles** | **List[str]** |  | [optional] 
**statuses** | **List[str]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_edges_summary_post_request_filter import V1EdgesSummaryPostRequestFilter

# TODO update the JSON string below
json = "{}"
# create an instance of V1EdgesSummaryPostRequestFilter from a JSON string
v1_edges_summary_post_request_filter_instance = V1EdgesSummaryPostRequestFilter.from_json(json)
# print the JSON string representation of the object
print(V1EdgesSummaryPostRequestFilter.to_json())

# convert the object into a dict
v1_edges_summary_post_request_filter_dict = v1_edges_summary_post_request_filter_instance.to_dict()
# create an instance of V1EdgesSummaryPostRequestFilter from a dict
v1_edges_summary_post_request_filter_from_dict = V1EdgesSummaryPostRequestFilter.from_dict(v1_edges_summary_post_request_filter_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


