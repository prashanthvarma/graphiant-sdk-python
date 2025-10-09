# V1B2bExtranetMonitoringFilterPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**is_b2_b** | **bool** |  | [optional] 
**is_provider** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_b2b_extranet_monitoring_filter_post_request import V1B2bExtranetMonitoringFilterPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1B2bExtranetMonitoringFilterPostRequest from a JSON string
v1_b2b_extranet_monitoring_filter_post_request_instance = V1B2bExtranetMonitoringFilterPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1B2bExtranetMonitoringFilterPostRequest.to_json())

# convert the object into a dict
v1_b2b_extranet_monitoring_filter_post_request_dict = v1_b2b_extranet_monitoring_filter_post_request_instance.to_dict()
# create an instance of V1B2bExtranetMonitoringFilterPostRequest from a dict
v1_b2b_extranet_monitoring_filter_post_request_from_dict = V1B2bExtranetMonitoringFilterPostRequest.from_dict(v1_b2b_extranet_monitoring_filter_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


