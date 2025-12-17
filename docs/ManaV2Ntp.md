# ManaV2Ntp


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**domains** | **List[str]** |  | [optional] 
**error_message** | **str** |  | [optional] 
**global_id** | **int** |  | [optional] 
**id** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_ntp import ManaV2Ntp

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2Ntp from a JSON string
mana_v2_ntp_instance = ManaV2Ntp.from_json(json)
# print the JSON string representation of the object
print(ManaV2Ntp.to_json())

# convert the object into a dict
mana_v2_ntp_dict = mana_v2_ntp_instance.to_dict()
# create an instance of ManaV2Ntp from a dict
mana_v2_ntp_from_dict = ManaV2Ntp.from_dict(mana_v2_ntp_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


