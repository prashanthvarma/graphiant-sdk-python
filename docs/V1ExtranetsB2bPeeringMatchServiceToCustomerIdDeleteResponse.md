# V1ExtranetsB2bPeeringMatchServiceToCustomerIdDeleteResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**activity_id** | **str** | activity id for the delete operation (required) | [optional] 
**consumer_activity_id** | **str** | activity id for the consumer delete operation (required) | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_match_service_to_customer_id_delete_response import V1ExtranetsB2bPeeringMatchServiceToCustomerIdDeleteResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringMatchServiceToCustomerIdDeleteResponse from a JSON string
v1_extranets_b2b_peering_match_service_to_customer_id_delete_response_instance = V1ExtranetsB2bPeeringMatchServiceToCustomerIdDeleteResponse.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringMatchServiceToCustomerIdDeleteResponse.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_match_service_to_customer_id_delete_response_dict = v1_extranets_b2b_peering_match_service_to_customer_id_delete_response_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringMatchServiceToCustomerIdDeleteResponse from a dict
v1_extranets_b2b_peering_match_service_to_customer_id_delete_response_from_dict = V1ExtranetsB2bPeeringMatchServiceToCustomerIdDeleteResponse.from_dict(v1_extranets_b2b_peering_match_service_to_customer_id_delete_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


