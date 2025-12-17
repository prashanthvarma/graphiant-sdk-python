# ManaV2Device


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bgp** | [**ManaV2BgpInstance**](ManaV2BgpInstance.md) |  | [optional] 
**bgp_enabled** | **bool** |  | [optional] 
**circuits** | [**List[ManaV2Circuit]**](ManaV2Circuit.md) |  | [optional] 
**config_updated_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**created_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**dhcp_server_enabled** | **bool** |  | [optional] 
**dns** | [**ManaV2Dns**](ManaV2Dns.md) |  | [optional] 
**gdi** | **int** |  | [optional] 
**hostname** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**interfaces** | [**List[ManaV2Interface]**](ManaV2Interface.md) |  | [optional] 
**internal_state** | **str** |  | [optional] 
**ipfix_enabled** | **bool** |  | [optional] 
**ipfix_exporters** | [**List[ManaV2IpfixExporter]**](ManaV2IpfixExporter.md) |  | [optional] 
**ipsec_tunnels** | [**List[ManaV2SiteToSiteIPsec]**](ManaV2SiteToSiteIPsec.md) |  | [optional] 
**last_booted_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**lldp_enabled** | **bool** |  | [optional] 
**local_route_tag** | [**ManaV2RouteTag**](ManaV2RouteTag.md) |  | [optional] 
**local_web_server_password** | **str** |  | [optional] 
**location** | [**ManaV2Location**](ManaV2Location.md) |  | [optional] 
**maintenance_mode** | **bool** |  | [optional] 
**nat_policy** | [**ManaV2NatPolicy**](ManaV2NatPolicy.md) |  | [optional] 
**notes** | **str** |  | [optional] 
**ntp** | [**ManaV2Ntp**](ManaV2Ntp.md) |  | [optional] 
**oper_staled** | **bool** |  | [optional] 
**oper_staled_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**oper_updated_at** | [**GoogleProtobufTimestamp**](GoogleProtobufTimestamp.md) |  | [optional] 
**ospfv2_enabled** | **bool** |  | [optional] 
**ospfv3_enabled** | **bool** |  | [optional] 
**platform** | **str** |  | [optional] 
**prefix_sets** | [**List[ManaV2PrefixSet]**](ManaV2PrefixSet.md) |  | [optional] 
**reboot_reason** | **str** |  | [optional] 
**region** | [**ManaV2Region**](ManaV2Region.md) |  | [optional] 
**region_override** | [**ManaV2Region**](ManaV2Region.md) |  | [optional] 
**role** | **str** |  | [optional] 
**routing_policies** | [**List[ManaV2RoutingPolicy]**](ManaV2RoutingPolicy.md) |  | [optional] 
**segments** | [**List[ManaV2Vrf]**](ManaV2Vrf.md) |  | [optional] 
**serial_number** | **str** |  | [optional] 
**site** | [**ManaV2Site**](ManaV2Site.md) |  | [optional] 
**snmp** | [**ManaV2Snmp**](ManaV2Snmp.md) |  | [optional] 
**software_version** | **str** |  | [optional] 
**static_routes_enabled** | **bool** |  | [optional] 
**status** | **str** |  | [optional] 
**traffic_policy** | [**ManaV2ForwardingPolicy**](ManaV2ForwardingPolicy.md) |  | [optional] 
**uptime** | [**GoogleProtobufDuration**](GoogleProtobufDuration.md) |  | [optional] 
**vrrp_enabled** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.mana_v2_device import ManaV2Device

# TODO update the JSON string below
json = "{}"
# create an instance of ManaV2Device from a JSON string
mana_v2_device_instance = ManaV2Device.from_json(json)
# print the JSON string representation of the object
print(ManaV2Device.to_json())

# convert the object into a dict
mana_v2_device_dict = mana_v2_device_instance.to_dict()
# create an instance of ManaV2Device from a dict
mana_v2_device_from_dict = ManaV2Device.from_dict(mana_v2_device_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


