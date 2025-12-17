# V2ExtranetSitesConsumptionOverviewPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lan_segments** | [**List[IpfixConnectionMap]**](IpfixConnectionMap.md) |  | [optional] 
**regions** | [**List[IpfixConnectionMap]**](IpfixConnectionMap.md) |  | [optional] 
**sites** | [**List[IpfixConnectionMap]**](IpfixConnectionMap.md) |  | [optional] 
**total_usage** | **float** | total service usage in kilo bytes | [optional] 

## Example

```python
from graphiant_sdk.models.v2_extranet_sites_consumption_overview_post_response import V2ExtranetSitesConsumptionOverviewPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2ExtranetSitesConsumptionOverviewPostResponse from a JSON string
v2_extranet_sites_consumption_overview_post_response_instance = V2ExtranetSitesConsumptionOverviewPostResponse.from_json(json)
# print the JSON string representation of the object
print(V2ExtranetSitesConsumptionOverviewPostResponse.to_json())

# convert the object into a dict
v2_extranet_sites_consumption_overview_post_response_dict = v2_extranet_sites_consumption_overview_post_response_instance.to_dict()
# create an instance of V2ExtranetSitesConsumptionOverviewPostResponse from a dict
v2_extranet_sites_consumption_overview_post_response_from_dict = V2ExtranetSitesConsumptionOverviewPostResponse.from_dict(v2_extranet_sites_consumption_overview_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


