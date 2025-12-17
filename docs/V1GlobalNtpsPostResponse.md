# V1GlobalNtpsPostResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ntps** | [**List[ManaV2Ntp]**](ManaV2Ntp.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_global_ntps_post_response import V1GlobalNtpsPostResponse

# TODO update the JSON string below
json = "{}"
# create an instance of V1GlobalNtpsPostResponse from a JSON string
v1_global_ntps_post_response_instance = V1GlobalNtpsPostResponse.from_json(json)
# print the JSON string representation of the object
print(V1GlobalNtpsPostResponse.to_json())

# convert the object into a dict
v1_global_ntps_post_response_dict = v1_global_ntps_post_response_instance.to_dict()
# create an instance of V1GlobalNtpsPostResponse from a dict
v1_global_ntps_post_response_from_dict = V1GlobalNtpsPostResponse.from_dict(v1_global_ntps_post_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


