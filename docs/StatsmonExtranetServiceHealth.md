# StatsmonExtranetServiceHealth


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customer_name** | **str** | the name of the customer | [optional] 
**customer_prefix_health** | [**StatsmonExtranetPrefixHealth**](StatsmonExtranetPrefixHealth.md) |  | [optional] 
**overall_health** | **str** | the overall connectivity status of the service (Healthy, Impaired, Down) | [optional] 
**producer_prefix_health** | [**StatsmonExtranetPrefixHealth**](StatsmonExtranetPrefixHealth.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.statsmon_extranet_service_health import StatsmonExtranetServiceHealth

# TODO update the JSON string below
json = "{}"
# create an instance of StatsmonExtranetServiceHealth from a JSON string
statsmon_extranet_service_health_instance = StatsmonExtranetServiceHealth.from_json(json)
# print the JSON string representation of the object
print(StatsmonExtranetServiceHealth.to_json())

# convert the object into a dict
statsmon_extranet_service_health_dict = statsmon_extranet_service_health_instance.to_dict()
# create an instance of StatsmonExtranetServiceHealth from a dict
statsmon_extranet_service_health_from_dict = StatsmonExtranetServiceHealth.from_dict(statsmon_extranet_service_health_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


