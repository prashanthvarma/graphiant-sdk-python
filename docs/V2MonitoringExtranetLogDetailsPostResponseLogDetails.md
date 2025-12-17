# V2MonitoringExtranetLogDetailsPostResponseLogDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**hostname** | **str** | the hostname of the log | [optional] 
**reason** | **str** | the reason for the log | [optional] 
**server_address** | **str** | the address of the server | [optional] 
**site_name** | **str** | the name of the site | [optional] 
**ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_monitoring_extranet_log_details_post_response_log_details import V2MonitoringExtranetLogDetailsPostResponseLogDetails

# TODO update the JSON string below
json = "{}"
# create an instance of V2MonitoringExtranetLogDetailsPostResponseLogDetails from a JSON string
v2_monitoring_extranet_log_details_post_response_log_details_instance = V2MonitoringExtranetLogDetailsPostResponseLogDetails.from_json(json)
# print the JSON string representation of the object
print(V2MonitoringExtranetLogDetailsPostResponseLogDetails.to_json())

# convert the object into a dict
v2_monitoring_extranet_log_details_post_response_log_details_dict = v2_monitoring_extranet_log_details_post_response_log_details_instance.to_dict()
# create an instance of V2MonitoringExtranetLogDetailsPostResponseLogDetails from a dict
v2_monitoring_extranet_log_details_post_response_log_details_from_dict = V2MonitoringExtranetLogDetailsPostResponseLogDetails.from_dict(v2_monitoring_extranet_log_details_post_response_log_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


