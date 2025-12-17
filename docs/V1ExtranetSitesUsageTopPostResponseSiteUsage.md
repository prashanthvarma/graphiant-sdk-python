# V1ExtranetSitesUsageTopPostResponseSiteUsage


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**site_id** | **int** | the id of the site | [optional] 
**site_name** | **str** | the name of the site | [optional] 
**usage** | **float** | usage/consumption of the service on the site in kilo bytes | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranet_sites_usage_top_post_response_site_usage import V1ExtranetSitesUsageTopPostResponseSiteUsage

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetSitesUsageTopPostResponseSiteUsage from a JSON string
v1_extranet_sites_usage_top_post_response_site_usage_instance = V1ExtranetSitesUsageTopPostResponseSiteUsage.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetSitesUsageTopPostResponseSiteUsage.to_json())

# convert the object into a dict
v1_extranet_sites_usage_top_post_response_site_usage_dict = v1_extranet_sites_usage_top_post_response_site_usage_instance.to_dict()
# create an instance of V1ExtranetSitesUsageTopPostResponseSiteUsage from a dict
v1_extranet_sites_usage_top_post_response_site_usage_from_dict = V1ExtranetSitesUsageTopPostResponseSiteUsage.from_dict(v1_extranet_sites_usage_top_post_response_site_usage_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


