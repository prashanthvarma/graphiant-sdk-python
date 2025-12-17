# V1ExtranetB2bMonitoringPeeringServiceServiceHealthPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | the id of the service (required) | 
**is_provider** | **bool** | whether the entity is a provider/producer or consumer (required) | 

## Example

```python
from graphiant_sdk.models.v1_extranet_b2b_monitoring_peering_service_service_health_post_request import V1ExtranetB2bMonitoringPeeringServiceServiceHealthPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1ExtranetB2bMonitoringPeeringServiceServiceHealthPostRequest from a JSON string
v1_extranet_b2b_monitoring_peering_service_service_health_post_request_instance = V1ExtranetB2bMonitoringPeeringServiceServiceHealthPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1ExtranetB2bMonitoringPeeringServiceServiceHealthPostRequest.to_json())

# convert the object into a dict
v1_extranet_b2b_monitoring_peering_service_service_health_post_request_dict = v1_extranet_b2b_monitoring_peering_service_service_health_post_request_instance.to_dict()
# create an instance of V1ExtranetB2bMonitoringPeeringServiceServiceHealthPostRequest from a dict
v1_extranet_b2b_monitoring_peering_service_service_health_post_request_from_dict = V1ExtranetB2bMonitoringPeeringServiceServiceHealthPostRequest.from_dict(v1_extranet_b2b_monitoring_peering_service_service_health_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


