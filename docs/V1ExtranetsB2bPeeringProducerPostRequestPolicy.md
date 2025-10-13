# V1ExtranetsB2bPeeringProducerPostRequestPolicy


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** |  | [optional] 
**global_object_ops** | [**Dict[str, V1ExtranetsB2bPeeringConsumerMatchIdPostRequestGlobalObjectOpsValue]**](V1ExtranetsB2bPeeringConsumerMatchIdPostRequestGlobalObjectOpsValue.md) |  | [optional] 
**prefix_tags** | [**List[V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceServicePrefixesInner]**](V1ExtranetsB2bPeeringMatchServiceToCustomerPostRequestServiceServicePrefixesInner.md) |  | [optional] 
**service_lan_segment** | **int** |  | [optional] 
**site** | [**List[V1ExtranetsB2bConsumerPostRequestSiteInformationInner]**](V1ExtranetsB2bConsumerPostRequestSiteInformationInner.md) |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_producer_post_request_policy import V1ExtranetsB2bPeeringProducerPostRequestPolicy

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringProducerPostRequestPolicy from a JSON string
v1_extranets_b2b_peering_producer_post_request_policy_instance = V1ExtranetsB2bPeeringProducerPostRequestPolicy.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringProducerPostRequestPolicy.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_producer_post_request_policy_dict = v1_extranets_b2b_peering_producer_post_request_policy_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringProducerPostRequestPolicy from a dict
v1_extranets_b2b_peering_producer_post_request_policy_from_dict = V1ExtranetsB2bPeeringProducerPostRequestPolicy.from_dict(v1_extranets_b2b_peering_producer_post_request_policy_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


