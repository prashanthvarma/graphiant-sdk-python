# V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**first_level** | [**List[IpfixConnectionMap]**](IpfixConnectionMap.md) |  | [optional] 
**second_level** | [**List[IpfixConnectionMap]**](IpfixConnectionMap.md) |  | [optional] 
**third_level** | [**List[IpfixConnectionMap]**](IpfixConnectionMap.md) |  | [optional] 
**total_usage** | **float** | total service usage in kilo bytes | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranet_b2b_monitoring_peering_service_consumption_overview_post_response import V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostResponse from a JSON string
v1_extranet_b2b_monitoring_peering_service_consumption_overview_post_response_instance = V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostResponse.to_json())

# convert the object into a dict
v1_extranet_b2b_monitoring_peering_service_consumption_overview_post_response_dict = v1_extranet_b2b_monitoring_peering_service_consumption_overview_post_response_instance.to_dict()
# create an instance of V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostResponse from a dict
v1_extranet_b2b_monitoring_peering_service_consumption_overview_post_response_from_dict = V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostResponse.from_dict(v1_extranet_b2b_monitoring_peering_service_consumption_overview_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


