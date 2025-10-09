# V1ExtranetsB2bPeeringMatchServicesSummaryGet200ResponseServicesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** |  | [optional] 
**lan_segment** | **int** |  | [optional] 
**matched_customers** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**status** | **str** |  | [optional] 
**type** | **str** |  | [optional] 
**updated_at** | [**V1AlarmHistoryGet200ResponseHistoryInnerTime**](V1AlarmHistoryGet200ResponseHistoryInnerTime.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_peering_match_services_summary_get200_response_services_inner import V1ExtranetsB2bPeeringMatchServicesSummaryGet200ResponseServicesInner

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPeeringMatchServicesSummaryGet200ResponseServicesInner from a JSON string
v1_extranets_b2b_peering_match_services_summary_get200_response_services_inner_instance = V1ExtranetsB2bPeeringMatchServicesSummaryGet200ResponseServicesInner.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPeeringMatchServicesSummaryGet200ResponseServicesInner.to_json())

# convert the object into a dict
v1_extranets_b2b_peering_match_services_summary_get200_response_services_inner_dict = v1_extranets_b2b_peering_match_services_summary_get200_response_services_inner_instance.to_dict()
# create an instance of V1ExtranetsB2bPeeringMatchServicesSummaryGet200ResponseServicesInner from a dict
v1_extranets_b2b_peering_match_services_summary_get200_response_services_inner_from_dict = V1ExtranetsB2bPeeringMatchServicesSummaryGet200ResponseServicesInner.from_dict(v1_extranets_b2b_peering_match_services_summary_get200_response_services_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


