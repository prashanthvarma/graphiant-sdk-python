# V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**destination_address** | **str** |  | [optional] 
**ike_initiator** | **bool** |  | [optional] 
**mtu** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**remote_ike_peer_identity** | **str** |  | [optional] 
**routing** | [**V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRouting**](V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRouting.md) |  | [optional] 
**tcp_mss** | **int** |  | [optional] 
**tunnel1** | [**V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsTunnel1**](V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsTunnel1.md) |  | [optional] 
**tunnel2** | [**V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsTunnel1**](V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetailsTunnel1.md) |  | [optional] 
**vpn_profile** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_consumer_match_id_post_request_site_to_site_vpn_ipsec_gateway_details import V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails from a JSON string
v1_extranets_b2b_peering_consumer_match_id_post_request_site_to_site_vpn_ipsec_gateway_details_instance = V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_consumer_match_id_post_request_site_to_site_vpn_ipsec_gateway_details_dict = v1_extranets_b2b_peering_consumer_match_id_post_request_site_to_site_vpn_ipsec_gateway_details_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails from a dict
v1_extranets_b2b_peering_consumer_match_id_post_request_site_to_site_vpn_ipsec_gateway_details_from_dict = V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails.from_dict(v1_extranets_b2b_peering_consumer_match_id_post_request_site_to_site_vpn_ipsec_gateway_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


