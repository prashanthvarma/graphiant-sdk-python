# V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpn


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**emails** | **List[str]** |  | [optional] 
**ipsec_gateway_details** | [**V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails**](V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpnIpsecGatewayDetails.md) |  | [optional] 
**region_id** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_consumer_match_id_post_request_site_to_site_vpn import V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpn

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpn from a JSON string
v1_extranets_b2b_peering_consumer_match_id_post_request_site_to_site_vpn_instance = V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpn.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpn.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_consumer_match_id_post_request_site_to_site_vpn_dict = v1_extranets_b2b_peering_consumer_match_id_post_request_site_to_site_vpn_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpn from a dict
v1_extranets_b2b_peering_consumer_match_id_post_request_site_to_site_vpn_from_dict = V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpn.from_dict(v1_extranets_b2b_peering_consumer_match_id_post_request_site_to_site_vpn_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


