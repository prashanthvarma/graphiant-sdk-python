# V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPost200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**first_level** | [**List[V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPost200ResponseFirstLevelInner]**](V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPost200ResponseFirstLevelInner.md) |  | [optional] 
**second_level** | [**List[V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPost200ResponseFirstLevelInner]**](V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPost200ResponseFirstLevelInner.md) |  | [optional] 
**third_level** | [**List[V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPost200ResponseFirstLevelInner]**](V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPost200ResponseFirstLevelInner.md) |  | [optional] 
**total_usage** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranet_b2b_monitoring_peering_service_consumption_overview_post200_response import V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPost200Response

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPost200Response from a JSON string
v1_extranet_b2b_monitoring_peering_service_consumption_overview_post200_response_instance = V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPost200Response.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPost200Response.to_json())

# convert the object into a dict
v1_extranet_b2b_monitoring_peering_service_consumption_overview_post200_response_dict = v1_extranet_b2b_monitoring_peering_service_consumption_overview_post200_response_instance.to_dict()
# create an instance of V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPost200Response from a dict
v1_extranet_b2b_monitoring_peering_service_consumption_overview_post200_response_from_dict = V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPost200Response.from_dict(v1_extranet_b2b_monitoring_peering_service_consumption_overview_post200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


