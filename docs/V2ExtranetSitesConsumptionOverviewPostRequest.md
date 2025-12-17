# V2ExtranetSitesConsumptionOverviewPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customer_name** | **str** | a filter to get usage for a specific customer | [optional] 
**flipped_view** | **bool** | whether to view the data from the consumer&#39;s perspective (true) or the provider&#39;s perspective (false) (required) | 
**id** | **int** | the id associated with an entity - consumer_id for consumer, and service_id for the producer/service (required) | 
**is_b2_b** | **bool** | whether the entity is a b2b entity (true for b2b entity, false for local extranet entity) (required) | 
**is_provider** | **bool** | whether the entity is a provider or consumer (required) | 
**site_id** | **int** | a filter to get usage for a specific site | [optional] 
**time_window** | [**StatsmonTimeWindow**](StatsmonTimeWindow.md) |  | 
**vrf_id** | **int** | a filter to get usage for a specific vrf | [optional] 

## Example

```python
from graphiant_sdk.models.v2_extranet_sites_consumption_overview_post_request import V2ExtranetSitesConsumptionOverviewPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V2ExtranetSitesConsumptionOverviewPostRequest from a JSON string
v2_extranet_sites_consumption_overview_post_request_instance = V2ExtranetSitesConsumptionOverviewPostRequest.from_json(json)
# print the JSON string representation of the object
print(V2ExtranetSitesConsumptionOverviewPostRequest.to_json())

# convert the object into a dict
v2_extranet_sites_consumption_overview_post_request_dict = v2_extranet_sites_consumption_overview_post_request_instance.to_dict()
# create an instance of V2ExtranetSitesConsumptionOverviewPostRequest from a dict
v2_extranet_sites_consumption_overview_post_request_from_dict = V2ExtranetSitesConsumptionOverviewPostRequest.from_dict(v2_extranet_sites_consumption_overview_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


