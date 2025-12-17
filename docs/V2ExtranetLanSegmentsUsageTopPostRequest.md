# V2ExtranetLanSegmentsUsageTopPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | the id associated with an entity - consumer_id for consumer, and service_id for the producer/service (required) | 
**is_b2_b** | **bool** | whether the entity is a b2b entity (true for b2b entity, false for local extranet entity) (required) | 
**is_provider** | **bool** | whether the entity is a provider or consumer (required) | 
**time_window** | [**StatsmonTimeWindow**](StatsmonTimeWindow.md) |  | 

## Example

```python
from graphiant_sdk.models.v2_extranet_lan_segments_usage_top_post_request import V2ExtranetLanSegmentsUsageTopPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V2ExtranetLanSegmentsUsageTopPostRequest from a JSON string
v2_extranet_lan_segments_usage_top_post_request_instance = V2ExtranetLanSegmentsUsageTopPostRequest.from_json(json)
# print the JSON string representation of the object
print(V2ExtranetLanSegmentsUsageTopPostRequest.to_json())

# convert the object into a dict
v2_extranet_lan_segments_usage_top_post_request_dict = v2_extranet_lan_segments_usage_top_post_request_instance.to_dict()
# create an instance of V2ExtranetLanSegmentsUsageTopPostRequest from a dict
v2_extranet_lan_segments_usage_top_post_request_from_dict = V2ExtranetLanSegmentsUsageTopPostRequest.from_dict(v2_extranet_lan_segments_usage_top_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


