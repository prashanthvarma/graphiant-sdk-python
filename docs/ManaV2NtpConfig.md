# ManaV2NtpConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**domains** | **List[str]** |  | [optional] 
**global_id** | **int** |  | [optional] 
**is_global_sync** | **bool** |  | [optional] 
**name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_ntp_config import ManaV2NtpConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2NtpConfig from a JSON string
mana_v2_ntp_config_instance = ManaV2NtpConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2NtpConfig.to_json())

# convert the object into a dict
mana_v2_ntp_config_dict = mana_v2_ntp_config_instance.to_dict()
# create an instance of ManaV2NtpConfig from a dict
mana_v2_ntp_config_from_dict = ManaV2NtpConfig.from_dict(mana_v2_ntp_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


