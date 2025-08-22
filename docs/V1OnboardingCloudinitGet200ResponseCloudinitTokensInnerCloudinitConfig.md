# V1OnboardingCloudinitGet200ResponseCloudinitTokensInnerCloudinitConfig


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**device_type** | **str** |  | [optional] 
**dns_servers** | **str** |  | [optional] 
**hostname** | **str** |  | [optional] 
**interfaces** | [**List[V1OnboardingCloudinitGet200ResponseCloudinitTokensInnerCloudinitConfigInterfacesInner]**](V1OnboardingCloudinitGet200ResponseCloudinitTokensInnerCloudinitConfigInterfacesInner.md) |  | [optional] 
**local_web_password** | **str** |  | [optional] 

## Example

```python
from graphiant_sdk.models.v1_onboarding_cloudinit_get200_response_cloudinit_tokens_inner_cloudinit_config import V1OnboardingCloudinitGet200ResponseCloudinitTokensInnerCloudinitConfig

# TODO update the JSON string below
json = "{}"
# create an instance of V1OnboardingCloudinitGet200ResponseCloudinitTokensInnerCloudinitConfig from a JSON string
v1_onboarding_cloudinit_get200_response_cloudinit_tokens_inner_cloudinit_config_instance = V1OnboardingCloudinitGet200ResponseCloudinitTokensInnerCloudinitConfig.from_json(json)
# print the JSON string representation of the object
print(V1OnboardingCloudinitGet200ResponseCloudinitTokensInnerCloudinitConfig.to_json())

# convert the object into a dict
v1_onboarding_cloudinit_get200_response_cloudinit_tokens_inner_cloudinit_config_dict = v1_onboarding_cloudinit_get200_response_cloudinit_tokens_inner_cloudinit_config_instance.to_dict()
# create an instance of V1OnboardingCloudinitGet200ResponseCloudinitTokensInnerCloudinitConfig from a dict
v1_onboarding_cloudinit_get200_response_cloudinit_tokens_inner_cloudinit_config_from_dict = V1OnboardingCloudinitGet200ResponseCloudinitTokensInnerCloudinitConfig.from_dict(v1_onboarding_cloudinit_get200_response_cloudinit_tokens_inner_cloudinit_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


