# V1ExtranetSitesUsageTopPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | the id associated with an entity - consumer_id for consumer, and service_id for the producer/service (required) | 
**is_b2_b** | **bool** | whether the entity is a b2b entity (true for b2b entity, false for local extranet entity) (required) | 
**is_provider** | **bool** | whether the entity is a provider or consumer (required) | 
**service_id** | **int** |  | [optional] 
**time_window** | [**StatsmonTimeWindow**](StatsmonTimeWindow.md) |  | 

## Example

```python
from graphiant_sdk.models.v1_extranet_sites_usage_top_post_request import V1ExtranetSitesUsageTopPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetSitesUsageTopPostRequest from a JSON string
v1_extranet_sites_usage_top_post_request_instance = V1ExtranetSitesUsageTopPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetSitesUsageTopPostRequest.to_json())

# convert the object into a dict
v1_extranet_sites_usage_top_post_request_dict = v1_extranet_sites_usage_top_post_request_instance.to_dict()
# create an instance of V1ExtranetSitesUsageTopPostRequest from a dict
v1_extranet_sites_usage_top_post_request_from_dict = V1ExtranetSitesUsageTopPostRequest.from_dict(v1_extranet_sites_usage_top_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


