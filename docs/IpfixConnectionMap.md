# IpfixConnectionMap


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**connections** | **Dict[str, int]** |  | [optional] 
**connections_v2** | **Dict[str, float]** |  | [optional] 
**name** | **str** | the name of the connection | [optional] 

## Example

```python
from graphiant_sdk.models.ipfix_connection_map import IpfixConnectionMap

# TODO update the JSON string below
json = "{}"
# create an instance of IpfixConnectionMap from a JSON string
ipfix_connection_map_instance = IpfixConnectionMap.from_json(json)
# print the JSON string representation of the object
print(IpfixConnectionMap.to_json())

# convert the object into a dict
ipfix_connection_map_dict = ipfix_connection_map_instance.to_dict()
# create an instance of IpfixConnectionMap from a dict
ipfix_connection_map_from_dict = IpfixConnectionMap.from_dict(ipfix_connection_map_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


