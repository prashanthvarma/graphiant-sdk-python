# V1AuthMfaPatchRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**allowed_mfa_types** | **List[str]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_auth_mfa_patch_request import V1AuthMfaPatchRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1AuthMfaPatchRequest from a JSON string
v1_auth_mfa_patch_request_instance = V1AuthMfaPatchRequest.from_json(json)
# print the JSON string representation of the object
print(V1AuthMfaPatchRequest.to_json())

# convert the object into a dict
v1_auth_mfa_patch_request_dict = v1_auth_mfa_patch_request_instance.to_dict()
# create an instance of V1AuthMfaPatchRequest from a dict
v1_auth_mfa_patch_request_from_dict = V1AuthMfaPatchRequest.from_dict(v1_auth_mfa_patch_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


