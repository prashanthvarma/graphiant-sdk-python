# ManaV2ExtranetConsumerNatRule


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**outside_nat_prefix** | **str** | Optional nat prefix associated with a service prefix with an empty string indicating no NATing | [optional] 
**service_prefix** | **str** | Service prefix for the NAT rule (required) | 

## Example

```python
from graphiant_sdk.models.mana_v2_extranet_consumer_nat_rule import ManaV2ExtranetConsumerNatRule

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2ExtranetConsumerNatRule from a JSON string
mana_v2_extranet_consumer_nat_rule_instance = ManaV2ExtranetConsumerNatRule.from_json(json)
# print the JSON string representation of the object
print(ManaV2ExtranetConsumerNatRule.to_json())

# convert the object into a dict
mana_v2_extranet_consumer_nat_rule_dict = mana_v2_extranet_consumer_nat_rule_instance.to_dict()
# create an instance of ManaV2ExtranetConsumerNatRule from a dict
mana_v2_extranet_consumer_nat_rule_from_dict = ManaV2ExtranetConsumerNatRule.from_dict(mana_v2_extranet_consumer_nat_rule_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


