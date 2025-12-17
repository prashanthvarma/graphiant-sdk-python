# V1ExtranetSitesUsagePostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bw_allocation** | **int** | the bandwidth allocation for the entity in kbps | [optional] 
**dl_stats** | [**List[IpfixStats]**](IpfixStats.md) |  | [optional] 
**ul_stats** | [**List[IpfixStats]**](IpfixStats.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranet_sites_usage_post_response import V1ExtranetSitesUsagePostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetSitesUsagePostResponse from a JSON string
v1_extranet_sites_usage_post_response_instance = V1ExtranetSitesUsagePostResponse.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetSitesUsagePostResponse.to_json())

# convert the object into a dict
v1_extranet_sites_usage_post_response_dict = v1_extranet_sites_usage_post_response_instance.to_dict()
# create an instance of V1ExtranetSitesUsagePostResponse from a dict
v1_extranet_sites_usage_post_response_from_dict = V1ExtranetSitesUsagePostResponse.from_dict(v1_extranet_sites_usage_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


