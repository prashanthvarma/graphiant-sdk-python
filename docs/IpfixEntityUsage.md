# IpfixEntityUsage


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | id of the entity | [optional] 
**name** | **str** | name of the entity | [optional] 
**usage** | **float** | usage in kbps | [optional] 

## Example

```python
from graphiant_sdk.models.ipfix_entity_usage import IpfixEntityUsage

# TODO update the JSON string below
json = "{}"
# create an instance of IpfixEntityUsage from a JSON string
ipfix_entity_usage_instance = IpfixEntityUsage.from_json(json)
# print the JSON string representation of the object
print(IpfixEntityUsage.to_json())

# convert the object into a dict
ipfix_entity_usage_dict = ipfix_entity_usage_instance.to_dict()
# create an instance of IpfixEntityUsage from a dict
ipfix_entity_usage_from_dict = IpfixEntityUsage.from_dict(ipfix_entity_usage_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


