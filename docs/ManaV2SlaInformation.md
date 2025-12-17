# ManaV2SlaInformation


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**backup_circuit** | **str** | Backup circuit for the SLA information | [optional] 
**var_class** | **str** | Class for the SLA information | [optional] 
**primary_circuit** | **str** | Primary circuit for the SLA information | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_sla_information import ManaV2SlaInformation

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2SlaInformation from a JSON string
mana_v2_sla_information_instance = ManaV2SlaInformation.from_json(json)
# print the JSON string representation of the object
print(ManaV2SlaInformation.to_json())

# convert the object into a dict
mana_v2_sla_information_dict = mana_v2_sla_information_instance.to_dict()
# create an instance of ManaV2SlaInformation from a dict
mana_v2_sla_information_from_dict = ManaV2SlaInformation.from_dict(mana_v2_sla_information_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


