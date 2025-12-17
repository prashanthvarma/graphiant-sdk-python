# ManaV2EdgeDeviceConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bgp_enabled** | **bool** |  | [optional] 
**bgp_instance** | [**ManaV2BgpInstanceConfig**](ManaV2BgpInstanceConfig.md) |  | [optional] 
**circuits** | [**Dict[str, ManaV2CircuitConfig]**](ManaV2CircuitConfig.md) |  | [optional] 
**dhcp_server_enabled** | **bool** |  | [optional] 
**dns** | [**ManaV2NullableDnsConfig**](ManaV2NullableDnsConfig.md) |  | [optional] 
**interfaces** | [**Dict[str, ManaV2NullableInterfaceConfig]**](ManaV2NullableInterfaceConfig.md) |  | [optional] 
**ipfix_enabled** | **bool** |  | [optional] 
**ipfix_exporters** | [**Dict[str, ManaV2NullableIpfixExporterConfig]**](ManaV2NullableIpfixExporterConfig.md) |  | [optional] 
**lag_interfaces** | [**Dict[str, ManaV2NullableLagInterfaceConfig]**](ManaV2NullableLagInterfaceConfig.md) |  | [optional] 
**lldp_enabled** | **bool** |  | [optional] 
**local_route_tag** | [**ManaV2NullableRouteTagSet**](ManaV2NullableRouteTagSet.md) |  | [optional] 
**local_web_server_password** | **str** |  | [optional] 
**location** | [**ManaV2Location**](ManaV2Location.md) |  | [optional] 
**maintenance_mode** | **bool** |  | [optional] 
**name** | **str** |  | [optional] 
**nat_policy** | [**ManaV2NatPolicyConfig**](ManaV2NatPolicyConfig.md) |  | [optional] 
**ntp_global_object** | [**Dict[str, ManaV2NullableNtpConfig]**](ManaV2NullableNtpConfig.md) |  | [optional] 
**ospfv2_enabled** | **bool** |  | [optional] 
**ospfv3_enabled** | **bool** |  | [optional] 
**prefix_sets** | [**Dict[str, ManaV2NullablePrefixSetConfig]**](ManaV2NullablePrefixSetConfig.md) |  | [optional] 
**region** | **str** |  | [optional] 
**region_name** | **str** |  | [optional] 
**route_policies** | [**Dict[str, ManaV2NullableRoutingPolicyConfig]**](ManaV2NullableRoutingPolicyConfig.md) |  | [optional] 
**segments** | [**Dict[str, ManaV2VrfConfig]**](ManaV2VrfConfig.md) |  | [optional] 
**site** | [**ManaV2NewSite**](ManaV2NewSite.md) |  | [optional] 
**site_to_site_vpn** | [**Dict[str, ManaV2NullableIPsecTunnelConfig]**](ManaV2NullableIPsecTunnelConfig.md) |  | [optional] 
**snmp** | [**ManaV2NullableSnmpConfig**](ManaV2NullableSnmpConfig.md) |  | [optional] 
**snmp_global_object** | [**Dict[str, ManaV2NullableSnmpConfig]**](ManaV2NullableSnmpConfig.md) |  | [optional] 
**static_routes_enabled** | **bool** |  | [optional] 
**traffic_policy** | [**ManaV2ForwardingPolicyConfig**](ManaV2ForwardingPolicyConfig.md) |  | [optional] 
**vrrp_enabled** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_edge_device_config import ManaV2EdgeDeviceConfig

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2EdgeDeviceConfig from a JSON string
mana_v2_edge_device_config_instance = ManaV2EdgeDeviceConfig.from_json(json)
# print the JSON string representation of the object
print(ManaV2EdgeDeviceConfig.to_json())

# convert the object into a dict
mana_v2_edge_device_config_dict = mana_v2_edge_device_config_instance.to_dict()
# create an instance of ManaV2EdgeDeviceConfig from a dict
mana_v2_edge_device_config_from_dict = ManaV2EdgeDeviceConfig.from_dict(mana_v2_edge_device_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


