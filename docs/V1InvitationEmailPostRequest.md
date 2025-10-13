# V1InvitationEmailPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**admin_email** | **str** |  | [optional] 
**customer_id** | **int** |  | [optional] 
**customer_name** | **str** |  | [optional] 
**is_graphiant** | **bool** |  | [optional] 
**service_id** | **int** |  | [optional] 
**service_name** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_invitation_email_post_request import V1InvitationEmailPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1InvitationEmailPostRequest from a JSON string
v1_invitation_email_post_request_instance = V1InvitationEmailPostRequest.from_json(json)
# print the JSON string representation of the object
print(V1InvitationEmailPostRequest.to_json())

# convert the object into a dict
v1_invitation_email_post_request_dict = v1_invitation_email_post_request_instance.to_dict()
# create an instance of V1InvitationEmailPostRequest from a dict
v1_invitation_email_post_request_from_dict = V1InvitationEmailPostRequest.from_dict(v1_invitation_email_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


