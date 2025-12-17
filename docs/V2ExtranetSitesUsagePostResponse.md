# V2ExtranetSitesUsagePostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bw_allocation** | **int** | the bandwidth allocation for the entity in kbps | [optional] 
**dl_stats** | [**List[IpfixStats]**](IpfixStats.md) |  | [optional] 
**ul_stats** | [**List[IpfixStats]**](IpfixStats.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v2_extranet_sites_usage_post_response import V2ExtranetSitesUsagePostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V2ExtranetSitesUsagePostResponse from a JSON string
v2_extranet_sites_usage_post_response_instance = V2ExtranetSitesUsagePostResponse.from_json(json)
# print the JSON string representation of the object
print(V2ExtranetSitesUsagePostResponse.to_json())

# convert the object into a dict
v2_extranet_sites_usage_post_response_dict = v2_extranet_sites_usage_post_response_instance.to_dict()
# create an instance of V2ExtranetSitesUsagePostResponse from a dict
v2_extranet_sites_usage_post_response_from_dict = V2ExtranetSitesUsagePostResponse.from_dict(v2_extranet_sites_usage_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


