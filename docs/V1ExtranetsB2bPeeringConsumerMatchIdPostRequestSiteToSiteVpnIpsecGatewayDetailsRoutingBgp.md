# V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address_families** | [**Dict[str, V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpAddressFamiliesValue]**](V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpAddressFamiliesValue.md) |  | [optional] 
**hold_timer** | **int** |  | [optional] 
**keepalive_timer** | **int** |  | [optional] 
**md5_password** | [**V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpMd5Password**](V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpMd5Password.md) |  | [optional] 
**peer_asn** | **int** |  | [optional] 
**send_community** | **bool** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_consumer_match_id_post_request_site_to_site_vpn_ipsec_gateway_details_routing_bgp import V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp from a JSON string
v1_extranets_b2b_peering_consumer_match_id_post_request_site_to_site_vpn_ipsec_gateway_details_routing_bgp_instance = V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_consumer_match_id_post_request_site_to_site_vpn_ipsec_gateway_details_routing_bgp_dict = v1_extranets_b2b_peering_consumer_match_id_post_request_site_to_site_vpn_ipsec_gateway_details_routing_bgp_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp from a dict
v1_extranets_b2b_peering_consumer_match_id_post_request_site_to_site_vpn_ipsec_gateway_details_routing_bgp_from_dict = V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgp.from_dict(v1_extranets_b2b_peering_consumer_match_id_post_request_site_to_site_vpn_ipsec_gateway_details_routing_bgp_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


