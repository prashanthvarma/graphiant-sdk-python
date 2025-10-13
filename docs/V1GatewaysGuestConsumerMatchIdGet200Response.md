# V1GatewaysGuestConsumerMatchIdGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**destination_prefixes** | **List[str]** |  | [optional] 
**ipsec_tunnel_config** | [**List[V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseIpsecTunnelConfigInner]**](V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseIpsecTunnelConfigInner.md) |  | [optional] 
**site_to_site_vpn** | [**V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpn**](V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpn.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_gateways_guest_consumer_match_id_get200_response import V1GatewaysGuestConsumerMatchIdGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of V1GatewaysGuestConsumerMatchIdGet200Response from a JSON string
v1_gateways_guest_consumer_match_id_get200_response_instance = V1GatewaysGuestConsumerMatchIdGet200Response.from_json(json)
# print the JSON string representation of the object
print(V1GatewaysGuestConsumerMatchIdGet200Response.to_json())

# convert the object into a dict
v1_gateways_guest_consumer_match_id_get200_response_dict = v1_gateways_guest_consumer_match_id_get200_response_instance.to_dict()
# create an instance of V1GatewaysGuestConsumerMatchIdGet200Response from a dict
v1_gateways_guest_consumer_match_id_get200_response_from_dict = V1GatewaysGuestConsumerMatchIdGet200Response.from_dict(v1_gateways_guest_consumer_match_id_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


