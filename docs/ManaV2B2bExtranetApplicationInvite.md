# ManaV2B2bExtranetApplicationInvite


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**admin_email** | **str** | Admin email of the customer (required) | 
**consumer_burst_size** | **int** | Maximum Burst size per site for the customer (required) | 
**consumer_bw_site** | **int** | Maximum Bandwidth allocation per site for the customer (required) | 
**enterprise_id** | **int** | Enterprise ID of the customer (required) | 
**maximum_site_count** | **int** | Maximum number of sites for the customer (required) | 
**service_prefixes** | **List[str]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_b2b_extranet_application_invite import ManaV2B2bExtranetApplicationInvite

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2B2bExtranetApplicationInvite from a JSON string
mana_v2_b2b_extranet_application_invite_instance = ManaV2B2bExtranetApplicationInvite.from_json(json)
# print the JSON string representation of the object
print(ManaV2B2bExtranetApplicationInvite.to_json())

# convert the object into a dict
mana_v2_b2b_extranet_application_invite_dict = mana_v2_b2b_extranet_application_invite_instance.to_dict()
# create an instance of ManaV2B2bExtranetApplicationInvite from a dict
mana_v2_b2b_extranet_application_invite_from_dict = ManaV2B2bExtranetApplicationInvite.from_dict(mana_v2_b2b_extranet_application_invite_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


