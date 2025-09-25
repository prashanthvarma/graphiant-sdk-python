# V1ExtranetB2bMonitoringPeeringServiceServiceHealthPost200ResponseServiceHealthInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customer_name** | **str** |  | [optional] 
**customer_prefix_health** | [**V1ExtranetB2bMonitoringPeeringServiceServiceHealthPost200ResponseServiceHealthInnerCustomerPrefixHealth**](V1ExtranetB2bMonitoringPeeringServiceServiceHealthPost200ResponseServiceHealthInnerCustomerPrefixHealth.md) |  | [optional] 
**overall_health** | **str** |  | [optional] 
**producer_prefix_health** | [**V1ExtranetB2bMonitoringPeeringServiceServiceHealthPost200ResponseServiceHealthInnerCustomerPrefixHealth**](V1ExtranetB2bMonitoringPeeringServiceServiceHealthPost200ResponseServiceHealthInnerCustomerPrefixHealth.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranet_b2b_monitoring_peering_service_service_health_post200_response_service_health_inner import V1ExtranetB2bMonitoringPeeringServiceServiceHealthPost200ResponseServiceHealthInner

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetB2bMonitoringPeeringServiceServiceHealthPost200ResponseServiceHealthInner from a JSON string
v1_extranet_b2b_monitoring_peering_service_service_health_post200_response_service_health_inner_instance = V1ExtranetB2bMonitoringPeeringServiceServiceHealthPost200ResponseServiceHealthInner.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetB2bMonitoringPeeringServiceServiceHealthPost200ResponseServiceHealthInner.to_json())

# convert the object into a dict
v1_extranet_b2b_monitoring_peering_service_service_health_post200_response_service_health_inner_dict = v1_extranet_b2b_monitoring_peering_service_service_health_post200_response_service_health_inner_instance.to_dict()
# create an instance of V1ExtranetB2bMonitoringPeeringServiceServiceHealthPost200ResponseServiceHealthInner from a dict
v1_extranet_b2b_monitoring_peering_service_service_health_post200_response_service_health_inner_from_dict = V1ExtranetB2bMonitoringPeeringServiceServiceHealthPost200ResponseServiceHealthInner.from_dict(v1_extranet_b2b_monitoring_peering_service_service_health_post200_response_service_health_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


