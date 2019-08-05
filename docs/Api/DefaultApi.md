# Swagger\Client\DefaultApi

All URIs are relative to *https://k9aqkpifhj.execute-api.ap-southeast-1.amazonaws.com/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**wordsGet**](DefaultApi.md#wordsGet) | **GET** /words | Get All Words available from Crystal Words Bank
[**wordsOptions**](DefaultApi.md#wordsOptions) | **OPTIONS** /words | 
[**wordsPost**](DefaultApi.md#wordsPost) | **POST** /words | POST Request will update any data in the Bank


# **wordsGet**
> \Swagger\Client\Model\ModelEmpty wordsGet()

Get All Words available from Crystal Words Bank

**Get Request without params will return all the words availble for now.**

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->wordsGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->wordsGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**\Swagger\Client\Model\ModelEmpty**](../Model/ModelEmpty.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **wordsOptions**
> \Swagger\Client\Model\ModelEmpty wordsOptions()



### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->wordsOptions();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->wordsOptions: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**\Swagger\Client\Model\ModelEmpty**](../Model/ModelEmpty.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **wordsPost**
> \Swagger\Client\Model\ModelEmpty wordsPost()

POST Request will update any data in the Bank

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->wordsPost();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->wordsPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**\Swagger\Client\Model\ModelEmpty**](../Model/ModelEmpty.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

