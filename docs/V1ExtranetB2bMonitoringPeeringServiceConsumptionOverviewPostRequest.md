# V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customer_name** | **str** |  | [optional] 
**flipped_view** | **bool** |  | [optional] 
**id** | **int** |  | [optional] 
**is_b2_b** | **bool** |  | [optional] 
**is_provider** | **bool** |  | [optional] 
**site_id** | **int** |  | [optional] 
**time_window** | [**V2NotificationlistPostRequestTimeWindow**](V2NotificationlistPostRequestTimeWindow.md) |  | [optional] 
**vrf_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranet_b2b_monitoring_peering_service_consumption_overview_post_request import V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest from a JSON string
v1_extranet_b2b_monitoring_peering_service_consumption_overview_post_request_instance = V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest.to_json())

# convert the object into a dict
v1_extranet_b2b_monitoring_peering_service_consumption_overview_post_request_dict = v1_extranet_b2b_monitoring_peering_service_consumption_overview_post_request_instance.to_dict()
# create an instance of V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest from a dict
v1_extranet_b2b_monitoring_peering_service_consumption_overview_post_request_from_dict = V1ExtranetB2bMonitoringPeeringServiceConsumptionOverviewPostRequest.from_dict(v1_extranet_b2b_monitoring_peering_service_consumption_overview_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


