# V1ExtranetsB2bPeeringConsumerCustomerIdMatchDetailsGet200ResponseDetailsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**consumer_prefixes** | **List[str]** |  | [optional] 
**customer** | [**V1ExtranetsB2bPeeringConsumerCustomerIdMatchDetailsGet200ResponseDetailsInnerCustomer**](V1ExtranetsB2bPeeringConsumerCustomerIdMatchDetailsGet200ResponseDetailsInnerCustomer.md) |  | [optional] 
**service** | [**V1ExtranetsB2bPeeringConsumerCustomerIdMatchDetailsGet200ResponseDetailsInnerService**](V1ExtranetsB2bPeeringConsumerCustomerIdMatchDetailsGet200ResponseDetailsInnerService.md) |  | [optional] 
**service_prefixes** | [**List[V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceServicePrefixesInner]**](V1ExtranetsB2bPeeringMatchServiceToCustomerPutRequestServiceServicePrefixesInner.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_consumer_customer_id_match_details_get200_response_details_inner import V1ExtranetsB2bPeeringConsumerCustomerIdMatchDetailsGet200ResponseDetailsInner

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringConsumerCustomerIdMatchDetailsGet200ResponseDetailsInner from a JSON string
v1_extranets_b2b_peering_consumer_customer_id_match_details_get200_response_details_inner_instance = V1ExtranetsB2bPeeringConsumerCustomerIdMatchDetailsGet200ResponseDetailsInner.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringConsumerCustomerIdMatchDetailsGet200ResponseDetailsInner.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_consumer_customer_id_match_details_get200_response_details_inner_dict = v1_extranets_b2b_peering_consumer_customer_id_match_details_get200_response_details_inner_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringConsumerCustomerIdMatchDetailsGet200ResponseDetailsInner from a dict
v1_extranets_b2b_peering_consumer_customer_id_match_details_get200_response_details_inner_from_dict = V1ExtranetsB2bPeeringConsumerCustomerIdMatchDetailsGet200ResponseDetailsInner.from_dict(v1_extranets_b2b_peering_consumer_customer_id_match_details_get200_response_details_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


