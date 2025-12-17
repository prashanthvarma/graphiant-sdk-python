# StatsmonExtranetEdgeStatus


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**created_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**disconnected_reason** | **str** | the reason for the edge being disconnected | [optional] 
**hostname** | **str** | the hostname of the edge | [optional] 
**id** | **int** | the id of the edge/device | [optional] 
**site_name** | **str** | the name of the site | [optional] 
**status** | **str** | the health status of the edge (Healthy, Impaired, Down) | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_extranet_edge_status import StatsmonExtranetEdgeStatus

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonExtranetEdgeStatus from a JSON string
statsmon_extranet_edge_status_instance = StatsmonExtranetEdgeStatus.from_json(json)
# print the JSON string representation of the object
print(StatsmonExtranetEdgeStatus.to_json())

# convert the object into a dict
statsmon_extranet_edge_status_dict = statsmon_extranet_edge_status_instance.to_dict()
# create an instance of StatsmonExtranetEdgeStatus from a dict
statsmon_extranet_edge_status_from_dict = StatsmonExtranetEdgeStatus.from_dict(statsmon_extranet_edge_status_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


