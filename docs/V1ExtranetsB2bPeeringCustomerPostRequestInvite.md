# V1ExtranetsB2bPeeringCustomerPostRequestInvite


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**admin_email** | **List[str]** |  | [optional] 
**maximum_number_of_sites** | **int** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_customer_post_request_invite import V1ExtranetsB2bPeeringCustomerPostRequestInvite

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringCustomerPostRequestInvite from a JSON string
v1_extranets_b2b_peering_customer_post_request_invite_instance = V1ExtranetsB2bPeeringCustomerPostRequestInvite.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringCustomerPostRequestInvite.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_customer_post_request_invite_dict = v1_extranets_b2b_peering_customer_post_request_invite_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringCustomerPostRequestInvite from a dict
v1_extranets_b2b_peering_customer_post_request_invite_from_dict = V1ExtranetsB2bPeeringCustomerPostRequestInvite.from_dict(v1_extranets_b2b_peering_customer_post_request_invite_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


