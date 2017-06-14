# DefaultApi

All URIs are relative to *https://dev-virtserver.swaggerhub.com/qa1Org_A/SHUB-3853/1.0.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**searchInventory**](DefaultApi.md#searchInventory) | **GET** /inventory | searches inventory test


<a name="searchInventory"></a>
# **searchInventory**
> searchInventory()

searches inventory test

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.DefaultApi;


DefaultApi apiInstance = new DefaultApi();
try {
    apiInstance.searchInventory();
} catch (ApiException e) {
    System.err.println("Exception when calling DefaultApi#searchInventory");
    e.printStackTrace();
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

