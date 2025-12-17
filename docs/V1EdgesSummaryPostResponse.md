# V1EdgesSummaryPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**edges_summary** | [**List[SearchEdgeSummary]**](SearchEdgeSummary.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_edges_summary_post_response import V1EdgesSummaryPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1EdgesSummaryPostResponse from a JSON string
v1_edges_summary_post_response_instance = V1EdgesSummaryPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1EdgesSummaryPostResponse.to_json())

# convert the object into a dict
v1_edges_summary_post_response_dict = v1_edges_summary_post_response_instance.to_dict()
# create an instance of V1EdgesSummaryPostResponse from a dict
v1_edges_summary_post_response_from_dict = V1EdgesSummaryPostResponse.from_dict(v1_edges_summary_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


