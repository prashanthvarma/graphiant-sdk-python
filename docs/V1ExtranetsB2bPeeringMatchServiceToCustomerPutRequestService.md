# V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**lan_segment** | **int** |  | [optional] 
**nat** | [**List[V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceNatInner]**](V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceNatInner.md) |  | [optional] 
**num_customers** | **int** |  | [optional] 
**service_prefixes** | [**List[V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceServicePrefixesInner]**](V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceServicePrefixesInner.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_match_service_to_customer_put_request_service import V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService from a JSON string
v1_extranets_b2b_peering_match_service_to_customer_put_request_service_instance = V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_match_service_to_customer_put_request_service_dict = v1_extranets_b2b_peering_match_service_to_customer_put_request_service_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService from a dict
v1_extranets_b2b_peering_match_service_to_customer_put_request_service_from_dict = V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestService.from_dict(v1_extranets_b2b_peering_match_service_to_customer_put_request_service_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


