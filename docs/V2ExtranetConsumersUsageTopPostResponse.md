# V2ExtranetConsumersUsageTopPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**top_consumers** | [**List[IpfixEntityUsage]**](IpfixEntityUsage.md) |  | [optional] 
**total_customers** | **int** | total number of customers | [optional] 
**total_usage** | **float** | total service usage in kilo bytes | [optional] 

## Example

```python
from graphiant_sdk.models.v2_extranet_consumers_usage_top_post_response import V2ExtranetConsumersUsageTopPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2ExtranetConsumersUsageTopPostResponse from a JSON string
v2_extranet_consumers_usage_top_post_response_instance = V2ExtranetConsumersUsageTopPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2ExtranetConsumersUsageTopPostResponse.to_json())

# convert the object into a dict
v2_extranet_consumers_usage_top_post_response_dict = v2_extranet_consumers_usage_top_post_response_instance.to_dict()
# create an instance of V2ExtranetConsumersUsageTopPostResponse from a dict
v2_extranet_consumers_usage_top_post_response_from_dict = V2ExtranetConsumersUsageTopPostResponse.from_dict(v2_extranet_consumers_usage_top_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


