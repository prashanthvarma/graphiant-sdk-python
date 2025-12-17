# StatsmonExtranetPrefixHealth


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**health** | **str** | the health status of the prefix (Healthy, Impaired, Down) | [optional] 
**missing_prefixes** | **List[str]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_extranet_prefix_health import StatsmonExtranetPrefixHealth

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonExtranetPrefixHealth from a JSON string
statsmon_extranet_prefix_health_instance = StatsmonExtranetPrefixHealth.from_json(json)
# print the JSON string representation of the object
print(StatsmonExtranetPrefixHealth.to_json())

# convert the object into a dict
statsmon_extranet_prefix_health_dict = statsmon_extranet_prefix_health_instance.to_dict()
# create an instance of StatsmonExtranetPrefixHealth from a dict
statsmon_extranet_prefix_health_from_dict = StatsmonExtranetPrefixHealth.from_dict(statsmon_extranet_prefix_health_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


