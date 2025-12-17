# V2MonitoringExtranetStatusDetailsGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**edge_statuses** | [**List[StatsmonExtranetEdgeStatus]**](StatsmonExtranetEdgeStatus.md) |  | [optional] 
**location** | **str** | the location of the site | [optional] 
**region** | **str** | the region of the site | [optional] 
**site_status** | [**StatsmonExtranetSiteStatus**](StatsmonExtranetSiteStatus.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_monitoring_extranet_status_details_get_response import V2MonitoringExtranetStatusDetailsGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2MonitoringExtranetStatusDetailsGetResponse from a JSON string
v2_monitoring_extranet_status_details_get_response_instance = V2MonitoringExtranetStatusDetailsGetResponse.from_json(json)
# print the JSON string representation of the object
print(V2MonitoringExtranetStatusDetailsGetResponse.to_json())

# convert the object into a dict
v2_monitoring_extranet_status_details_get_response_dict = v2_monitoring_extranet_status_details_get_response_instance.to_dict()
# create an instance of V2MonitoringExtranetStatusDetailsGetResponse from a dict
v2_monitoring_extranet_status_details_get_response_from_dict = V2MonitoringExtranetStatusDetailsGetResponse.from_dict(v2_monitoring_extranet_status_details_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


