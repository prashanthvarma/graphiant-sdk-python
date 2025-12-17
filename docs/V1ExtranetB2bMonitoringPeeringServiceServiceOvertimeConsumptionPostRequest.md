# V1ExtranetB2bMonitoringPeeringServiceServiceOvertimeConsumptionPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | the id associated with an entity - consumer_id for consumer, and service_id for the producer/service (required) | 
**is_b2_b** | **bool** | whether the entity is a b2b entity (true for b2b entity, false for local extranet entity) (required) | 
**is_provider** | **bool** | whether the entity is a provider or consumer (required) | 
**site_id** | **int** | a filter to get usage for a specific site | [optional] 
**subscription_name** | **str** | Optional subscription name for filter | [optional] 
**time_window** | [**StatsmonTimeWindow**](StatsmonTimeWindow.md) |  | 
**vrf_id** | **int** | a filter to get usage for a specific vrf | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranet_b2b_monitoring_peering_service_service_overtime_consumption_post_request import V1ExtranetB2bMonitoringPeeringServiceServiceOvertimeConsumptionPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetB2bMonitoringPeeringServiceServiceOvertimeConsumptionPostRequest from a JSON string
v1_extranet_b2b_monitoring_peering_service_service_overtime_consumption_post_request_instance = V1ExtranetB2bMonitoringPeeringServiceServiceOvertimeConsumptionPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetB2bMonitoringPeeringServiceServiceOvertimeConsumptionPostRequest.to_json())

# convert the object into a dict
v1_extranet_b2b_monitoring_peering_service_service_overtime_consumption_post_request_dict = v1_extranet_b2b_monitoring_peering_service_service_overtime_consumption_post_request_instance.to_dict()
# create an instance of V1ExtranetB2bMonitoringPeeringServiceServiceOvertimeConsumptionPostRequest from a dict
v1_extranet_b2b_monitoring_peering_service_service_overtime_consumption_post_request_from_dict = V1ExtranetB2bMonitoringPeeringServiceServiceOvertimeConsumptionPostRequest.from_dict(v1_extranet_b2b_monitoring_peering_service_service_overtime_consumption_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


