# V1ExtranetsB2bPeeringProducerPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**policy** | [**ManaV2B2bExtranetPeeringServiceProducerPolicy**](ManaV2B2bExtranetPeeringServiceProducerPolicy.md) |  | 
**service_name** | **str** |  | [optional] 
**type** | **str** | Type of the service whether it is application or peering (required) | 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_producer_post_request import V1ExtranetsB2bPeeringProducerPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringProducerPostRequest from a JSON string
v1_extranets_b2b_peering_producer_post_request_instance = V1ExtranetsB2bPeeringProducerPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringProducerPostRequest.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_producer_post_request_dict = v1_extranets_b2b_peering_producer_post_request_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringProducerPostRequest from a dict
v1_extranets_b2b_peering_producer_post_request_from_dict = V1ExtranetsB2bPeeringProducerPostRequest.from_dict(v1_extranets_b2b_peering_producer_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


