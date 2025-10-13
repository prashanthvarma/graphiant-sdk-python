# V1ExtranetsB2bPeeringProducerIdMatchingCustomersSummaryGet200ResponseInfoInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customer_id** | **str** |  | [optional] 
**customer_name** | **str** |  | [optional] 
**emails** | **List[str]** |  | [optional] 
**matched_services** | **int** |  | [optional] 
**peer_type** | **str** |  | [optional] 
**status** | **str** |  | [optional] 
**updated_at** | [**V1AlarmHistoryGet200ResponseHistoryInnerTime**](V1AlarmHistoryGet200ResponseHistoryInnerTime.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_producer_id_matching_customers_summary_get200_response_info_inner import V1ExtranetsB2bPeeringProducerIdMatchingCustomersSummaryGet200ResponseInfoInner

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringProducerIdMatchingCustomersSummaryGet200ResponseInfoInner from a JSON string
v1_extranets_b2b_peering_producer_id_matching_customers_summary_get200_response_info_inner_instance = V1ExtranetsB2bPeeringProducerIdMatchingCustomersSummaryGet200ResponseInfoInner.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringProducerIdMatchingCustomersSummaryGet200ResponseInfoInner.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_producer_id_matching_customers_summary_get200_response_info_inner_dict = v1_extranets_b2b_peering_producer_id_matching_customers_summary_get200_response_info_inner_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringProducerIdMatchingCustomersSummaryGet200ResponseInfoInner from a dict
v1_extranets_b2b_peering_producer_id_matching_customers_summary_get200_response_info_inner_from_dict = V1ExtranetsB2bPeeringProducerIdMatchingCustomersSummaryGet200ResponseInfoInner.from_dict(v1_extranets_b2b_peering_producer_id_matching_customers_summary_get200_response_info_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


