# V1ExtranetB2bMonitoringPeeringServiceBandwidthUsagePost200ResponseDlStatsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**avg_usage** | **float** |  | [optional] 
**peak_usage** | **float** |  | [optional] 
**ts** | [**V1AlarmHistoryGet200ResponseHistoryInnerTime**](V1AlarmHistoryGet200ResponseHistoryInnerTime.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranet_b2b_monitoring_peering_service_bandwidth_usage_post200_response_dl_stats_inner import V1ExtranetB2bMonitoringPeeringServiceBandwidthUsagePost200ResponseDlStatsInner

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetB2bMonitoringPeeringServiceBandwidthUsagePost200ResponseDlStatsInner from a JSON string
v1_extranet_b2b_monitoring_peering_service_bandwidth_usage_post200_response_dl_stats_inner_instance = V1ExtranetB2bMonitoringPeeringServiceBandwidthUsagePost200ResponseDlStatsInner.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetB2bMonitoringPeeringServiceBandwidthUsagePost200ResponseDlStatsInner.to_json())

# convert the object into a dict
v1_extranet_b2b_monitoring_peering_service_bandwidth_usage_post200_response_dl_stats_inner_dict = v1_extranet_b2b_monitoring_peering_service_bandwidth_usage_post200_response_dl_stats_inner_instance.to_dict()
# create an instance of V1ExtranetB2bMonitoringPeeringServiceBandwidthUsagePost200ResponseDlStatsInner from a dict
v1_extranet_b2b_monitoring_peering_service_bandwidth_usage_post200_response_dl_stats_inner_from_dict = V1ExtranetB2bMonitoringPeeringServiceBandwidthUsagePost200ResponseDlStatsInner.from_dict(v1_extranet_b2b_monitoring_peering_service_bandwidth_usage_post200_response_dl_stats_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


