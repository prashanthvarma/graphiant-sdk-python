# V1ExtranetsB2bPeeringConsumerMatchIdPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customer_id** | **int** |  | [optional] 
**global_object_ops** | [**Dict[str, ManaV2GlobalObjectServiceOps]**](ManaV2GlobalObjectServiceOps.md) |  | [optional] 
**id** | **int** | ID of the service which is being consumed by the customer (required) | 
**nat** | [**List[ManaV2B2bNat]**](ManaV2B2bNat.md) |  | 
**policy** | [**List[ManaV2B2bExtranetPeeringServiceConsumerLanSegmentPolicy]**](ManaV2B2bExtranetPeeringServiceConsumerLanSegmentPolicy.md) |  | 
**site_information** | [**List[ManaV2B2bSiteInformation]**](ManaV2B2bSiteInformation.md) |  | 
**site_to_site_vpn** | [**ManaV2GuestConsumerSiteToSiteVpnConfig**](ManaV2GuestConsumerSiteToSiteVpnConfig.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_consumer_match_id_post_request import V1ExtranetsB2bPeeringConsumerMatchIdPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringConsumerMatchIdPostRequest from a JSON string
v1_extranets_b2b_peering_consumer_match_id_post_request_instance = V1ExtranetsB2bPeeringConsumerMatchIdPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringConsumerMatchIdPostRequest.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_consumer_match_id_post_request_dict = v1_extranets_b2b_peering_consumer_match_id_post_request_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringConsumerMatchIdPostRequest from a dict
v1_extranets_b2b_peering_consumer_match_id_post_request_from_dict = V1ExtranetsB2bPeeringConsumerMatchIdPostRequest.from_dict(v1_extranets_b2b_peering_consumer_match_id_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


