# StatsmonTimeWindow


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bucket_size_sec** | **int** | the size of the time window in seconds (required) | 
**old_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**recent_ts** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_time_window import StatsmonTimeWindow

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonTimeWindow from a JSON string
statsmon_time_window_instance = StatsmonTimeWindow.from_json(json)
# print the JSON string representation of the object
print(StatsmonTimeWindow.to_json())

# convert the object into a dict
statsmon_time_window_dict = statsmon_time_window_instance.to_dict()
# create an instance of StatsmonTimeWindow from a dict
statsmon_time_window_from_dict = StatsmonTimeWindow.from_dict(statsmon_time_window_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


