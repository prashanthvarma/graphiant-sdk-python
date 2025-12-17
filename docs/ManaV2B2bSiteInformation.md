# ManaV2B2bSiteInformation


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bw_allocation_site_lists** | **int** | Total Bandwidth allocation for the service on these site lists | [optional] 
**bw_allocation_sites** | **int** | Total Bandwidth allocation for the service on these sites | [optional] 
**policer_site_lists** | [**ManaV2Policer**](ManaV2Policer.md) |  | [optional] 
**policer_sites** | [**ManaV2Policer**](ManaV2Policer.md) |  | [optional] 
**site_lists** | **List[int]** |  | [optional] 
**sites** | **List[int]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_b2b_site_information import ManaV2B2bSiteInformation

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2B2bSiteInformation from a JSON string
mana_v2_b2b_site_information_instance = ManaV2B2bSiteInformation.from_json(json)
# print the JSON string representation of the object
print(ManaV2B2bSiteInformation.to_json())

# convert the object into a dict
mana_v2_b2b_site_information_dict = mana_v2_b2b_site_information_instance.to_dict()
# create an instance of ManaV2B2bSiteInformation from a dict
mana_v2_b2b_site_information_from_dict = ManaV2B2bSiteInformation.from_dict(mana_v2_b2b_site_information_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


