# V1AuthLoginTempPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**email** | **str** |  | [optional] 
**temp_password** | **str** |  | [optional] 
**match_id** | **float** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_auth_login_temp_post_request import V1AuthLoginTempPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1AuthLoginTempPostRequest from a JSON string
v1_auth_login_temp_post_request_instance = V1AuthLoginTempPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1AuthLoginTempPostRequest.to_json())

# convert the object into a dict
v1_auth_login_temp_post_request_dict = v1_auth_login_temp_post_request_instance.to_dict()
# create an instance of V1AuthLoginTempPostRequest from a dict
v1_auth_login_temp_post_request_from_dict = V1AuthLoginTempPostRequest.from_dict(v1_auth_login_temp_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


