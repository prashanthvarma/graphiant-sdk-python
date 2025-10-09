# V1ExtranetsB2bPeeringConsumerIdPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customer_id** | **int** |  | [optional] 
**nat** | [**List[V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceNatInner]**](V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceNatInner.md) |  | [optional] 
**policy** | [**List[V1ExtranetsB2bPeeringConsumerIdPostRequestPolicyInner]**](V1ExtranetsB2bPeeringConsumerIdPostRequestPolicyInner.md) |  | [optional] 
**site_information** | [**List[V1ExtranetsB2bConsumerPostRequestSiteInformationInner]**](V1ExtranetsB2bConsumerPostRequestSiteInformationInner.md) |  | [optional] 
**site_to_site_vpn** | [**V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpn**](V1ExtranetsB2bPeeringConsumerIdPostRequestSiteToSiteVpn.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_consumer_id_post_request import V1ExtranetsB2bPeeringConsumerIdPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringConsumerIdPostRequest from a JSON string
v1_extranets_b2b_peering_consumer_id_post_request_instance = V1ExtranetsB2bPeeringConsumerIdPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringConsumerIdPostRequest.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_consumer_id_post_request_dict = v1_extranets_b2b_peering_consumer_id_post_request_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringConsumerIdPostRequest from a dict
v1_extranets_b2b_peering_consumer_id_post_request_from_dict = V1ExtranetsB2bPeeringConsumerIdPostRequest.from_dict(v1_extranets_b2b_peering_consumer_id_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


