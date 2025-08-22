# V1OnboardingCloudinitGet200ResponseCloudinitTokensInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cloudinit_config** | [**V1OnboardingCloudinitGet200ResponseCloudinitTokensInnerCloudinitConfig**](V1OnboardingCloudinitGet200ResponseCloudinitTokensInnerCloudinitConfig.md) |  | [optional] 
**device_id** | **int** |  | [optional] 
**device_serial** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**role** | **str** |  | [optional] 
**token** | [**V1OnboardingCloudinitGet200ResponseCloudinitTokensInnerToken**](V1OnboardingCloudinitGet200ResponseCloudinitTokensInnerToken.md) |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_onboarding_cloudinit_get200_response_cloudinit_tokens_inner import V1OnboardingCloudinitGet200ResponseCloudinitTokensInner

# TODO update the JSON string below
json = "{}"
# create an instance of V1OnboardingCloudinitGet200ResponseCloudinitTokensInner from a JSON string
v1_onboarding_cloudinit_get200_response_cloudinit_tokens_inner_instance = V1OnboardingCloudinitGet200ResponseCloudinitTokensInner.from_json(json)
# print the JSON string representation of the object
print(V1OnboardingCloudinitGet200ResponseCloudinitTokensInner.to_json())

# convert the object into a dict
v1_onboarding_cloudinit_get200_response_cloudinit_tokens_inner_dict = v1_onboarding_cloudinit_get200_response_cloudinit_tokens_inner_instance.to_dict()
# create an instance of V1OnboardingCloudinitGet200ResponseCloudinitTokensInner from a dict
v1_onboarding_cloudinit_get200_response_cloudinit_tokens_inner_from_dict = V1OnboardingCloudinitGet200ResponseCloudinitTokensInner.from_dict(v1_onboarding_cloudinit_get200_response_cloudinit_tokens_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


