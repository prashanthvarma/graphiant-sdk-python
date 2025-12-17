# V1ExtranetB2bMonitoringPeeringServiceBandwidthUsagePostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bw_allocation** | **int** | the bandwidth allocation for the entity in kbps | [optional] 
**dl_stats** | [**List[IpfixStats]**](IpfixStats.md) |  | [optional] 
**ul_stats** | [**List[IpfixStats]**](IpfixStats.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranet_b2b_monitoring_peering_service_bandwidth_usage_post_response import V1ExtranetB2bMonitoringPeeringServiceBandwidthUsagePostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetB2bMonitoringPeeringServiceBandwidthUsagePostResponse from a JSON string
v1_extranet_b2b_monitoring_peering_service_bandwidth_usage_post_response_instance = V1ExtranetB2bMonitoringPeeringServiceBandwidthUsagePostResponse.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetB2bMonitoringPeeringServiceBandwidthUsagePostResponse.to_json())

# convert the object into a dict
v1_extranet_b2b_monitoring_peering_service_bandwidth_usage_post_response_dict = v1_extranet_b2b_monitoring_peering_service_bandwidth_usage_post_response_instance.to_dict()
# create an instance of V1ExtranetB2bMonitoringPeeringServiceBandwidthUsagePostResponse from a dict
v1_extranet_b2b_monitoring_peering_service_bandwidth_usage_post_response_from_dict = V1ExtranetB2bMonitoringPeeringServiceBandwidthUsagePostResponse.from_dict(v1_extranet_b2b_monitoring_peering_service_bandwidth_usage_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


