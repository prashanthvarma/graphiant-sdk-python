# ManaV2B2bExtranetPeeringServiceCustomerInvite


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**admin_email** | **List[str]** |  | 
**maximum_number_of_sites** | **int** | Maximum number of sites for the peering service customer (required) | 

## Example

```python
from graphiant_sdk.models.mana_v2_b2b_extranet_peering_service_customer_invite import ManaV2B2bExtranetPeeringServiceCustomerInvite

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2B2bExtranetPeeringServiceCustomerInvite from a JSON string
mana_v2_b2b_extranet_peering_service_customer_invite_instance = ManaV2B2bExtranetPeeringServiceCustomerInvite.from_json(json)
# print the JSON string representation of the object
print(ManaV2B2bExtranetPeeringServiceCustomerInvite.to_json())

# convert the object into a dict
mana_v2_b2b_extranet_peering_service_customer_invite_dict = mana_v2_b2b_extranet_peering_service_customer_invite_instance.to_dict()
# create an instance of ManaV2B2bExtranetPeeringServiceCustomerInvite from a dict
mana_v2_b2b_extranet_peering_service_customer_invite_from_dict = ManaV2B2bExtranetPeeringServiceCustomerInvite.from_dict(mana_v2_b2b_extranet_peering_service_customer_invite_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


