# V1ExtranetsB2bPostRequestPolicyGlobalObjectDeviceSummariesValueRoutingPoliciesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**attach_point** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**ip_version** | **int** |  | [optional] 
**name** | **str** |  | [optional] 
**num_attached_devices** | **int** |  | [optional] 
**num_attached_sites** | **int** |  | [optional] 
**num_failures** | **int** |  | [optional] 
**num_in_sync_devices** | **int** |  | [optional] 
**num_override_devices** | **int** |  | [optional] 
**num_policies** | **int** |  | [optional] 
**num_prefixes** | **int** |  | [optional] 
**num_rules** | **int** |  | [optional] 
**num_statements** | **int** |  | [optional] 
**traffic_policy_type** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_extranets_b2b_post_request_policy_global_object_device_summaries_value_routing_policies_inner import V1ExtranetsB2bPostRequestPolicyGlobalObjectDeviceSummariesValueRoutingPoliciesInner

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetsB2bPostRequestPolicyGlobalObjectDeviceSummariesValueRoutingPoliciesInner from a JSON string
v1_extranets_b2b_post_request_policy_global_object_device_summaries_value_routing_policies_inner_instance = V1ExtranetsB2bPostRequestPolicyGlobalObjectDeviceSummariesValueRoutingPoliciesInner.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetsB2bPostRequestPolicyGlobalObjectDeviceSummariesValueRoutingPoliciesInner.to_json())

# convert the object into a dict
v1_extranets_b2b_post_request_policy_global_object_device_summaries_value_routing_policies_inner_dict = v1_extranets_b2b_post_request_policy_global_object_device_summaries_value_routing_policies_inner_instance.to_dict()
# create an instance of V1ExtranetsB2bPostRequestPolicyGlobalObjectDeviceSummariesValueRoutingPoliciesInner from a dict
v1_extranets_b2b_post_request_policy_global_object_device_summaries_value_routing_policies_inner_from_dict = V1ExtranetsB2bPostRequestPolicyGlobalObjectDeviceSummariesValueRoutingPoliciesInner.from_dict(v1_extranets_b2b_post_request_policy_global_object_device_summaries_value_routing_policies_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


