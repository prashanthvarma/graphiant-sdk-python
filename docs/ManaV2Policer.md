# ManaV2Policer


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**burst_size** | **int** | Burst size for the policer (required) | 
**bw** | **int** | Bandwidth for the policer (required) | 

## Example

```python
from graphiant_sdk.models.mana_v2_policer import ManaV2Policer

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2Policer from a JSON string
mana_v2_policer_instance = ManaV2Policer.from_json(json)
# print the JSON string representation of the object
print(ManaV2Policer.to_json())

# convert the object into a dict
mana_v2_policer_dict = mana_v2_policer_instance.to_dict()
# create an instance of ManaV2Policer from a dict
mana_v2_policer_from_dict = ManaV2Policer.from_dict(mana_v2_policer_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


