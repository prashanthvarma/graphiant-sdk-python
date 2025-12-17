# ManaV2NewSite


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**global_prefix_set_ops** | **Dict[str, str]** |  | [optional] 
**ipfix_exporter_ops** | **Dict[str, str]** |  | [optional] 
**ipfix_exporter_ops_v2** | [**Dict[str, ManaV2GlobalObjectOperationConfig]**](ManaV2GlobalObjectOperationConfig.md) |  | [optional] 
**location** | [**ManaV2Location**](ManaV2Location.md) |  | [optional] 
**name** | **str** |  | [optional] 
**notes** | **str** |  | [optional] 
**ntp_ops** | **Dict[str, str]** |  | [optional] 
**prefix_set_ops** | **Dict[str, str]** |  | [optional] 
**route_tag** | [**ManaV2RouteTag**](ManaV2RouteTag.md) |  | [optional] 
**routing_policy_ops** | **Dict[str, str]** |  | [optional] 
**snmp_ops** | **Dict[str, str]** |  | [optional] 
**syslog_server_ops** | **Dict[str, str]** |  | [optional] 
**syslog_server_ops_v2** | [**Dict[str, ManaV2GlobalObjectOperationConfig]**](ManaV2GlobalObjectOperationConfig.md) |  | [optional] 
**traffic_policy_ops** | **Dict[str, str]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_new_site import ManaV2NewSite

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2NewSite from a JSON string
mana_v2_new_site_instance = ManaV2NewSite.from_json(json)
# print the JSON string representation of the object
print(ManaV2NewSite.to_json())

# convert the object into a dict
mana_v2_new_site_dict = mana_v2_new_site_instance.to_dict()
# create an instance of ManaV2NewSite from a dict
mana_v2_new_site_from_dict = ManaV2NewSite.from_dict(mana_v2_new_site_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


