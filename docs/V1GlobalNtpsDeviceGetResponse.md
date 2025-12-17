# V1GlobalNtpsDeviceGetResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ntps** | [**List[ManaV2Ntp]**](ManaV2Ntp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_ntps_device_get_response import V1GlobalNtpsDeviceGetResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalNtpsDeviceGetResponse from a JSON string
v1_global_ntps_device_get_response_instance = V1GlobalNtpsDeviceGetResponse.from_json(json)
# print the JSON string representation of the object
print(V1GlobalNtpsDeviceGetResponse.to_json())

# convert the object into a dict
v1_global_ntps_device_get_response_dict = v1_global_ntps_device_get_response_instance.to_dict()
# create an instance of V1GlobalNtpsDeviceGetResponse from a dict
v1_global_ntps_device_get_response_from_dict = V1GlobalNtpsDeviceGetResponse.from_dict(v1_global_ntps_device_get_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


