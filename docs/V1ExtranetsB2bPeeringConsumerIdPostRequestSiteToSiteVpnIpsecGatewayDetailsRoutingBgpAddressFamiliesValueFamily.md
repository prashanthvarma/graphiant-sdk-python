# V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpAddressFamiliesValueFamily


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address_family** | **str** |  | [optional] 
**inbound_policy** | [**V1GlobalConfigPatchRequestRoutingPoliciesValuePolicyStatementsValueStatementActionsValueActionCallPolicy**](V1GlobalConfigPatchRequestRoutingPoliciesValuePolicyStatementsValueStatementActionsValueActionCallPolicy.md) |  | [optional] 
**outbound_policy** | [**V1GlobalConfigPatchRequestRoutingPoliciesValuePolicyStatementsValueStatementActionsValueActionCallPolicy**](V1GlobalConfigPatchRequestRoutingPoliciesValuePolicyStatementsValueStatementActionsValueActionCallPolicy.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_consumer_id_post_request_site_to_site_vpn_ipsec_gateway_details_routing_bgp_address_families_value_family import V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpAddressFamiliesValueFamily

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpAddressFamiliesValueFamily from a JSON string
v1_extranets_b2b_peering_consumer_id_post_request_site_to_site_vpn_ipsec_gateway_details_routing_bgp_address_families_value_family_instance = V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpAddressFamiliesValueFamily.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpAddressFamiliesValueFamily.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_consumer_id_post_request_site_to_site_vpn_ipsec_gateway_details_routing_bgp_address_families_value_family_dict = v1_extranets_b2b_peering_consumer_id_post_request_site_to_site_vpn_ipsec_gateway_details_routing_bgp_address_families_value_family_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpAddressFamiliesValueFamily from a dict
v1_extranets_b2b_peering_consumer_id_post_request_site_to_site_vpn_ipsec_gateway_details_routing_bgp_address_families_value_family_from_dict = V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpnIpsecGatewayDetailsRoutingBgpAddressFamiliesValueFamily.from_dict(v1_extranets_b2b_peering_consumer_id_post_request_site_to_site_vpn_ipsec_gateway_details_routing_bgp_address_families_value_family_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


