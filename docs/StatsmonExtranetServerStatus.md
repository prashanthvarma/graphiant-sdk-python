# StatsmonExtranetServerStatus


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address** | **str** | the IP address of the server | [optional] 
**status** | **str** | the health status of the server (Healthy, Impaired, Down) | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_extranet_server_status import StatsmonExtranetServerStatus

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonExtranetServerStatus from a JSON string
statsmon_extranet_server_status_instance = StatsmonExtranetServerStatus.from_json(json)
# print the JSON string representation of the object
print(StatsmonExtranetServerStatus.to_json())

# convert the object into a dict
statsmon_extranet_server_status_dict = statsmon_extranet_server_status_instance.to_dict()
# create an instance of StatsmonExtranetServerStatus from a dict
statsmon_extranet_server_status_from_dict = StatsmonExtranetServerStatus.from_dict(statsmon_extranet_server_status_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


