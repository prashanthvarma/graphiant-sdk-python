# V1GroupsIdMembersDeletePostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**member_ids** | **List[str]** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_groups_id_members_delete_post_request import V1GroupsIdMembersDeletePostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of V1GroupsIdMembersDeletePostRequest from a JSON string
v1_groups_id_members_delete_post_request_instance = V1GroupsIdMembersDeletePostRequest.from_json(json)
# print the JSON string representation of the object
print(V1GroupsIdMembersDeletePostRequest.to_json())

# convert the object into a dict
v1_groups_id_members_delete_post_request_dict = v1_groups_id_members_delete_post_request_instance.to_dict()
# create an instance of V1GroupsIdMembersDeletePostRequest from a dict
v1_groups_id_members_delete_post_request_from_dict = V1GroupsIdMembersDeletePostRequest.from_dict(v1_groups_id_members_delete_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


