# swagger_client.DefaultApi

All URIs are relative to *https://eu.api.blizzard.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**hearthstone_cardbacks_get**](DefaultApi.md#hearthstone_cardbacks_get) | **GET** /hearthstone/cardbacks | 
[**hearthstone_cards_get**](DefaultApi.md#hearthstone_cards_get) | **GET** /hearthstone/cards | 

# **hearthstone_cardbacks_get**
> hearthstone_cardbacks_get(locale=locale)



Auto generated using Swagger Inspector

### Example
```python
from __future__ import print_function
import time
import swagger_client
from swagger_client.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = swagger_client.DefaultApi()
locale = 'locale_example' # str |  (optional)

try:
    api_instance.hearthstone_cardbacks_get(locale=locale)
except ApiException as e:
    print("Exception when calling DefaultApi->hearthstone_cardbacks_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **locale** | **str**|  | [optional] 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json; charset=utf-8

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **hearthstone_cards_get**
> hearthstone_cards_get(locale=locale, mana_cost=mana_cost)



Auto generated using Swagger Inspector

### Example
```python
from __future__ import print_function
import time
import swagger_client
from swagger_client.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = swagger_client.DefaultApi()
locale = 'locale_example' # str |  (optional)
mana_cost = 'mana_cost_example' # str |  (optional)

try:
    api_instance.hearthstone_cards_get(locale=locale, mana_cost=mana_cost)
except ApiException as e:
    print("Exception when calling DefaultApi->hearthstone_cards_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **locale** | **str**|  | [optional] 
 **mana_cost** | **str**|  | [optional] 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json; charset=utf-8

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

