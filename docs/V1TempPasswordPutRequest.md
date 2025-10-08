# V1TempPasswordPutRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customer_name** | **str** |  | [optional] 
**emails** | **List[str]** |  | [optional] 
**service_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_temp_password_put_request import V1TempPasswordPutRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1TempPasswordPutRequest from a JSON string
v1_temp_password_put_request_instance = V1TempPasswordPutRequest.from_json(json)
# print the JSON string representation of the object
print(V1TempPasswordPutRequest.to_json())

# convert the object into a dict
v1_temp_password_put_request_dict = v1_temp_password_put_request_instance.to_dict()
# create an instance of V1TempPasswordPutRequest from a dict
v1_temp_password_put_request_from_dict = V1TempPasswordPutRequest.from_dict(v1_temp_password_put_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


