# V1B2bExtranetMonitoringFilterPost200ResponseFilters


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customers** | [**List[V1B2bExtranetMonitoringFilterPost200ResponseFiltersCustomersInner]**](V1B2bExtranetMonitoringFilterPost200ResponseFiltersCustomersInner.md) |  | [optional] 
**sites** | [**List[V1B2bExtranetMonitoringFilterPost200ResponseFiltersCustomersInner]**](V1B2bExtranetMonitoringFilterPost200ResponseFiltersCustomersInner.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_b2b_extranet_monitoring_filter_post200_response_filters import V1B2bExtranetMonitoringFilterPost200ResponseFilters

# TODO update the JSON string below
json = "{}"
# create an instance of V1B2bExtranetMonitoringFilterPost200ResponseFilters from a JSON string
v1_b2b_extranet_monitoring_filter_post200_response_filters_instance = V1B2bExtranetMonitoringFilterPost200ResponseFilters.from_json(json)
# print the JSON string representation of the object
print(V1B2bExtranetMonitoringFilterPost200ResponseFilters.to_json())

# convert the object into a dict
v1_b2b_extranet_monitoring_filter_post200_response_filters_dict = v1_b2b_extranet_monitoring_filter_post200_response_filters_instance.to_dict()
# create an instance of V1B2bExtranetMonitoringFilterPost200ResponseFilters from a dict
v1_b2b_extranet_monitoring_filter_post200_response_filters_from_dict = V1B2bExtranetMonitoringFilterPost200ResponseFilters.from_dict(v1_b2b_extranet_monitoring_filter_post200_response_filters_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


