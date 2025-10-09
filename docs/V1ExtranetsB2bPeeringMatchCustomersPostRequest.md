# V1ExtranetsB2bPeeringMatchCustomersPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**info** | [**List[V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner]**](V1ExtranetsB2bPeeringMatchCustomersPostRequestInfoInner.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_match_customers_post_request import V1ExtranetsB2bPeeringMatchCustomersPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringMatchCustomersPostRequest from a JSON string
v1_extranets_b2b_peering_match_customers_post_request_instance = V1ExtranetsB2bPeeringMatchCustomersPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringMatchCustomersPostRequest.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_match_customers_post_request_dict = v1_extranets_b2b_peering_match_customers_post_request_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringMatchCustomersPostRequest from a dict
v1_extranets_b2b_peering_match_customers_post_request_from_dict = V1ExtranetsB2bPeeringMatchCustomersPostRequest.from_dict(v1_extranets_b2b_peering_match_customers_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


