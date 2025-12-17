# ManaV2B2bNat


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**outside_nat_prefix** | **str** | Outside NAT prefix for the customer prefix | [optional] 
**prefix** | **str** | Prefix imported into the service (required) | 

## Example

```python
from graphiant_sdk.models.mana_v2_b2b_nat import ManaV2B2bNat

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2B2bNat from a JSON string
mana_v2_b2b_nat_instance = ManaV2B2bNat.from_json(json)
# print the JSON string representation of the object
print(ManaV2B2bNat.to_json())

# convert the object into a dict
mana_v2_b2b_nat_dict = mana_v2_b2b_nat_instance.to_dict()
# create an instance of ManaV2B2bNat from a dict
mana_v2_b2b_nat_from_dict = ManaV2B2bNat.from_dict(mana_v2_b2b_nat_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


