# V1ExtranetB2bMonitoringPeeringServiceConsumersUsageTopPost200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**top_consumers** | [**List[V1ExtranetB2bMonitoringPeeringServiceConsumersUsageTopPost200ResponseTopConsumersInner]**](V1ExtranetB2bMonitoringPeeringServiceConsumersUsageTopPost200ResponseTopConsumersInner.md) |  | [optional] 
**total_customers** | **int** |  | [optional] 
**total_usage** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranet_b2b_monitoring_peering_service_consumers_usage_top_post200_response import V1ExtranetB2bMonitoringPeeringServiceConsumersUsageTopPost200Response

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetB2bMonitoringPeeringServiceConsumersUsageTopPost200Response from a JSON string
v1_extranet_b2b_monitoring_peering_service_consumers_usage_top_post200_response_instance = V1ExtranetB2bMonitoringPeeringServiceConsumersUsageTopPost200Response.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetB2bMonitoringPeeringServiceConsumersUsageTopPost200Response.to_json())

# convert the object into a dict
v1_extranet_b2b_monitoring_peering_service_consumers_usage_top_post200_response_dict = v1_extranet_b2b_monitoring_peering_service_consumers_usage_top_post200_response_instance.to_dict()
# create an instance of V1ExtranetB2bMonitoringPeeringServiceConsumersUsageTopPost200Response from a dict
v1_extranet_b2b_monitoring_peering_service_consumers_usage_top_post200_response_from_dict = V1ExtranetB2bMonitoringPeeringServiceConsumersUsageTopPost200Response.from_dict(v1_extranet_b2b_monitoring_peering_service_consumers_usage_top_post200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


