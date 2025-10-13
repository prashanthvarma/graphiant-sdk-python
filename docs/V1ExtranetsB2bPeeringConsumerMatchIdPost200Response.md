# V1ExtranetsB2bPeeringConsumerMatchIdPost200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**lan_segment** | **int** |  | [optional] 
**nat** | [**List[V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceNatInner]**](V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceNatInner.md) |  | [optional] 
**site_information** | [**List[V1ExtranetsB2bConsumerPostRequestSiteInformationInner]**](V1ExtranetsB2bConsumerPostRequestSiteInformationInner.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_consumer_match_id_post200_response import V1ExtranetsB2bPeeringConsumerMatchIdPost200Response

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringConsumerMatchIdPost200Response from a JSON string
v1_extranets_b2b_peering_consumer_match_id_post200_response_instance = V1ExtranetsB2bPeeringConsumerMatchIdPost200Response.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringConsumerMatchIdPost200Response.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_consumer_match_id_post200_response_dict = v1_extranets_b2b_peering_consumer_match_id_post200_response_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringConsumerMatchIdPost200Response from a dict
v1_extranets_b2b_peering_consumer_match_id_post200_response_from_dict = V1ExtranetsB2bPeeringConsumerMatchIdPost200Response.from_dict(v1_extranets_b2b_peering_consumer_match_id_post200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


