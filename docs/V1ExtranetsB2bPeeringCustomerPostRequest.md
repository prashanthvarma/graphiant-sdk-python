# V1ExtranetsB2bPeeringCustomerPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**invite** | [**V1ExtranetsB2bPeeringCustomerPostRequestInvite**](V1ExtranetsB2bPeeringCustomerPostRequestInvite.md) |  | [optional] 
**name** | **str** |  | [optional] 
**type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_customer_post_request import V1ExtranetsB2bPeeringCustomerPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringCustomerPostRequest from a JSON string
v1_extranets_b2b_peering_customer_post_request_instance = V1ExtranetsB2bPeeringCustomerPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringCustomerPostRequest.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_customer_post_request_dict = v1_extranets_b2b_peering_customer_post_request_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringCustomerPostRequest from a dict
v1_extranets_b2b_peering_customer_post_request_from_dict = V1ExtranetsB2bPeeringCustomerPostRequest.from_dict(v1_extranets_b2b_peering_customer_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


