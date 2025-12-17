# V1GlobalConfigPatchRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**global_prefix_sets** | [**Dict[str, ManaV2NullablePrefixSetConfig]**](ManaV2NullablePrefixSetConfig.md) |  | [optional] 
**ipfix_exporters** | [**Dict[str, ManaV2NullableIpfixExporterConfig]**](ManaV2NullableIpfixExporterConfig.md) |  | [optional] 
**ntps** | [**Dict[str, ManaV2NullableNtpConfig]**](ManaV2NullableNtpConfig.md) |  | [optional] 
**prefix_sets** | [**Dict[str, ManaV2NullableEnterprisePrefixSetConfig]**](ManaV2NullableEnterprisePrefixSetConfig.md) |  | [optional] 
**routing_policies** | [**Dict[str, ManaV2NullableRoutingPolicyConfig]**](ManaV2NullableRoutingPolicyConfig.md) |  | [optional] 
**snmps** | [**Dict[str, ManaV2NullableSnmpConfig]**](ManaV2NullableSnmpConfig.md) |  | [optional] 
**syslog_servers** | [**Dict[str, ManaV2NullableSyslogCollectorConfig]**](ManaV2NullableSyslogCollectorConfig.md) |  | [optional] 
**traffic_policies** | [**ManaV2ForwardingPolicyConfig**](ManaV2ForwardingPolicyConfig.md) |  | [optional] 
**vpn_profiles** | [**Dict[str, ManaV2NullableIPsecVpnProfilesConfig]**](ManaV2NullableIPsecVpnProfilesConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_config_patch_request import V1GlobalConfigPatchRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalConfigPatchRequest from a JSON string
v1_global_config_patch_request_instance = V1GlobalConfigPatchRequest.from_json(json)
# print the JSON string representation of the object
print(V1GlobalConfigPatchRequest.to_json())

# convert the object into a dict
v1_global_config_patch_request_dict = v1_global_config_patch_request_instance.to_dict()
# create an instance of V1GlobalConfigPatchRequest from a dict
v1_global_config_patch_request_from_dict = V1GlobalConfigPatchRequest.from_dict(v1_global_config_patch_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


