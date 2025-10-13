# V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseIpsecTunnelConfigInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bgp_graphiant_asn** | **int** |  | [optional] 
**bgp_local_asn** | **int** |  | [optional] 
**bgp_neighbor_hold_time** | **int** |  | [optional] 
**bgp_neighbor_ipv4** | **str** |  | [optional] 
**bgp_neighbor_ipv6** | **str** |  | [optional] 
**dpd_interval** | **int** |  | [optional] 
**dpd_retries** | **int** |  | [optional] 
**graphiant_destination_ip** | **str** |  | [optional] 
**graphiant_ike_id** | **str** |  | [optional] 
**graphiant_outer_tunnel_ip** | **str** |  | [optional] 
**graphiant_tunnel_ip** | **str** |  | [optional] 
**graphiant_tunnel_ipv6** | **str** |  | [optional] 
**ike_authentication_algorithm** | **str** |  | [optional] 
**ike_authentication_method** | **str** |  | [optional] 
**ike_dh_algorithm** | **str** |  | [optional] 
**ike_encryption_algorithm** | **str** |  | [optional] 
**ike_lifetime** | **str** |  | [optional] 
**ike_preshared_key** | **str** |  | [optional] 
**ike_version** | **int** |  | [optional] 
**ipsec_authentication_algorithm** | **str** |  | [optional] 
**ipsec_encryption_algorithm** | **str** |  | [optional] 
**ipsec_extended_sequence_number** | **bool** |  | [optional] 
**ipsec_lifetime** | **str** |  | [optional] 
**ipsec_mode** | **str** |  | [optional] 
**ipsec_pfs_algorithm** | **str** |  | [optional] 
**ipsec_protocol** | **str** |  | [optional] 
**local_ike_id** | **str** |  | [optional] 
**local_outer_tunnel_ip** | **str** |  | [optional] 
**local_tunnel_ip** | **str** |  | [optional] 
**local_tunnel_ipv6** | **str** |  | [optional] 
**tcp_mss** | **int** |  | [optional] 
**tunnel_mtu** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get200_response_ipsec_tunnel_config_inner import V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseIpsecTunnelConfigInner

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseIpsecTunnelConfigInner from a JSON string
v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get200_response_ipsec_tunnel_config_inner_instance = V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseIpsecTunnelConfigInner.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseIpsecTunnelConfigInner.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get200_response_ipsec_tunnel_config_inner_dict = v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get200_response_ipsec_tunnel_config_inner_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseIpsecTunnelConfigInner from a dict
v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get200_response_ipsec_tunnel_config_inner_from_dict = V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseIpsecTunnelConfigInner.from_dict(v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get200_response_ipsec_tunnel_config_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


