# swagger_client.IotApi

All URIs are relative to *https://{tenant}.ceocloud.app/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**iot_statechange_device_state_post**](IotApi.md#iot_statechange_device_state_post) | **POST** /iot/statechange/{device}/{state} | 

# **iot_statechange_device_state_post**
> iot_statechange_device_state_post(device, state)



### Example
```python
from __future__ import print_function
import time
import swagger_client
from swagger_client.rest import ApiException
from pprint import pprint


# create an instance of the API class
api_instance = swagger_client.IotApi(swagger_client.ApiClient(configuration))
device = 'device_example' # str | Device that spawn event
state = 56 # int | Event spawned

try:
    api_instance.iot_statechange_device_state_post(device, state)
except ApiException as e:
    print("Exception when calling IotApi->iot_statechange_device_state_post: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **device** | **str**| Device that spawn event | 
 **state** | **int**| Event spawned | 

### Return type

void (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

