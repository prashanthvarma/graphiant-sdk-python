# V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**consumer_id** | **int** |  | [optional] 
**consumer_name** | **str** |  | [optional] 
**emails** | **List[str]** |  | [optional] 
**global_object_device_summaries** | [**Dict[str, V1ExtranetsB2bPostRequestPolicyGlobalObjectDeviceSummariesValue]**](V1ExtranetsB2bPostRequestPolicyGlobalObjectDeviceSummariesValue.md) |  | [optional] 
**global_object_summaries** | [**Dict[str, V1ExtranetsB2bPostRequestPolicyGlobalObjectDeviceSummariesValue]**](V1ExtranetsB2bPostRequestPolicyGlobalObjectDeviceSummariesValue.md) |  | [optional] 
**ipsec_tunnel_config** | [**List[V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseIpsecTunnelConfigInner]**](V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseIpsecTunnelConfigInner.md) |  | [optional] 
**match_details** | [**V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseMatchDetails**](V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseMatchDetails.md) |  | [optional] 
**peer_type** | **str** |  | [optional] 
**policy** | [**List[V1ExtranetsB2bPeeringConsumerMatchIdPostRequestPolicyInner]**](V1ExtranetsB2bPeeringConsumerMatchIdPostRequestPolicyInner.md) |  | [optional] 
**site_information** | [**List[V1ExtranetsB2bConsumerPostRequestSiteInformationInner]**](V1ExtranetsB2bConsumerPostRequestSiteInformationInner.md) |  | [optional] 
**site_to_site_vpn** | [**V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpn**](V1ExtranetsB2bPeeringConsumerMatchIdPostRequestSiteToSiteVpn.md) |  | [optional] 
**status** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get200_response import V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response from a JSON string
v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get200_response_instance = V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get200_response_dict = v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get200_response_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response from a dict
v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get200_response_from_dict = V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200Response.from_dict(v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


