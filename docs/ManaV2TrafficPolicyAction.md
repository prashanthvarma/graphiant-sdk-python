# ManaV2TrafficPolicyAction


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**backup** | **str** | Backup circuit for the traffic policy action | [optional] 
**var_class** | **str** | Class for the traffic policy action | [optional] 
**primary** | **str** | Primary circuit for the traffic policy action | [optional] 
**result** | **str** | Result for the traffic policy action | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_traffic_policy_action import ManaV2TrafficPolicyAction

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2TrafficPolicyAction from a JSON string
mana_v2_traffic_policy_action_instance = ManaV2TrafficPolicyAction.from_json(json)
# print the JSON string representation of the object
print(ManaV2TrafficPolicyAction.to_json())

# convert the object into a dict
mana_v2_traffic_policy_action_dict = mana_v2_traffic_policy_action_instance.to_dict()
# create an instance of ManaV2TrafficPolicyAction from a dict
mana_v2_traffic_policy_action_from_dict = ManaV2TrafficPolicyAction.from_dict(mana_v2_traffic_policy_action_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


