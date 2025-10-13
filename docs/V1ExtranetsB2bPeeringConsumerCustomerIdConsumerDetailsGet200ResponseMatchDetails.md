# V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseMatchDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**consumer_prefixes** | **List[str]** |  | [optional] 
**customer** | [**V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseMatchDetailsCustomer**](V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseMatchDetailsCustomer.md) |  | [optional] 
**service** | [**V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseMatchDetailsService**](V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseMatchDetailsService.md) |  | [optional] 
**service_prefixes** | [**List[V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseMatchDetailsServicePrefixesInner]**](V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseMatchDetailsServicePrefixesInner.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get200_response_match_details import V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseMatchDetails

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseMatchDetails from a JSON string
v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get200_response_match_details_instance = V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseMatchDetails.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseMatchDetails.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get200_response_match_details_dict = v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get200_response_match_details_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseMatchDetails from a dict
v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get200_response_match_details_from_dict = V1ExtranetsB2bPeeringConsumerCustomerIdConsumerDetailsGet200ResponseMatchDetails.from_dict(v1_extranets_b2b_peering_consumer_customer_id_consumer_details_get200_response_match_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


