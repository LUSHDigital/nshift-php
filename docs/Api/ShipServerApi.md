# Swagger\Client\ShipServerApi

All URIs are relative to *https://api.shipmentserver.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**shipServerActorIDAvailableServicesGet**](ShipServerApi.md#shipserveractoridavailableservicesget) | **GET** /ShipServer/{actorID}/availableServices | Get Products for actor
[**shipServerActorIDBatchReportsBatchReportIDGet**](ShipServerApi.md#shipserveractoridbatchreportsbatchreportidget) | **GET** /ShipServer/{actorID}/batchReports/{batchReportID} | Get batch report
[**shipServerActorIDBatchShipmentsBatchIDGet**](ShipServerApi.md#shipserveractoridbatchshipmentsbatchidget) | **GET** /ShipServer/{actorID}/batchShipments/{batchID} | Get batch shipments
[**shipServerActorIDBatchesBatchIDGet**](ShipServerApi.md#shipserveractoridbatchesbatchidget) | **GET** /ShipServer/{actorID}/batches/{batchID} | Get Batch Details
[**shipServerActorIDBatchesPost**](ShipServerApi.md#shipserveractoridbatchespost) | **POST** /ShipServer/{actorID}/batches | Get Batch List
[**shipServerActorIDCheckoutPost**](ShipServerApi.md#shipserveractoridcheckoutpost) | **POST** /ShipServer/{actorID}/checkout | Get delivery optionswithout shipping rules defined
[**shipServerActorIDDropPointIDsDropPointIDPost**](ShipServerApi.md#shipserveractoriddroppointidsdroppointidpost) | **POST** /ShipServer/{actorID}/dropPointIDs/{dropPointID} | Get drop point by ID
[**shipServerActorIDDropPointsPost**](ShipServerApi.md#shipserveractoriddroppointspost) | **POST** /ShipServer/{actorID}/dropPoints | Get drop points
[**shipServerActorIDImportUploadPost**](ShipServerApi.md#shipserveractoridimportuploadpost) | **POST** /ShipServer/{actorID}/importUpload | Import Upload
[**shipServerActorIDJobsJobIDGet**](ShipServerApi.md#shipserveractoridjobsjobidget) | **GET** /ShipServer/{actorID}/jobs/{jobID} | Get job
[**shipServerActorIDOrderAdvicePost**](ShipServerApi.md#shipserveractoridorderadvicepost) | **POST** /ShipServer/{actorID}/orderAdvice | Creation of an order
[**shipServerActorIDOrdersPost**](ShipServerApi.md#shipserveractoridorderspost) | **POST** /ShipServer/{actorID}/orders | Store order
[**shipServerActorIDPackagesManifestPut**](ShipServerApi.md#shipserveractoridpackagesmanifestput) | **PUT** /ShipServer/{actorID}/packages/manifest | Transmit/manifest packages
[**shipServerActorIDPickupLockerAllocationsPost**](ShipServerApi.md#shipserveractoridpickuplockerallocationspost) | **POST** /ShipServer/{actorID}/pickupLockerAllocations | Pickup Locker Allocations
[**shipServerActorIDPickupLockersPost**](ShipServerApi.md#shipserveractoridpickuplockerspost) | **POST** /ShipServer/{actorID}/pickupLockers | Get pickup lockers
[**shipServerActorIDProductsGet**](ShipServerApi.md#shipserveractoridproductsget) | **GET** /ShipServer/{actorID}/products | Get Products
[**shipServerActorIDSaveShipmentPost**](ShipServerApi.md#shipserveractoridsaveshipmentpost) | **POST** /ShipServer/{actorID}/saveShipment | Save shipment
[**shipServerActorIDSenderAddressGet**](ShipServerApi.md#shipserveractoridsenderaddressget) | **GET** /ShipServer/{actorID}/senderAddress | Get Sender Address
[**shipServerActorIDShipAdvisesPost**](ShipServerApi.md#shipserveractoridshipadvisespost) | **POST** /ShipServer/{actorID}/shipAdvises | Get delivery options
[**shipServerActorIDShipmentPricesPost**](ShipServerApi.md#shipserveractoridshipmentpricespost) | **POST** /ShipServer/{actorID}/shipmentPrices | Get Shipment Price
[**shipServerActorIDShipmentValidationsPost**](ShipServerApi.md#shipserveractoridshipmentvalidationspost) | **POST** /ShipServer/{actorID}/shipmentValidations | Validate shipment
[**shipServerActorIDShipmentsDefaultsPost**](ShipServerApi.md#shipserveractoridshipmentsdefaultspost) | **POST** /ShipServer/{actorID}/shipments/defaults | Apply defaults on shipment
[**shipServerActorIDShipmentsLabelReprintPost**](ShipServerApi.md#shipserveractoridshipmentslabelreprintpost) | **POST** /ShipServer/{actorID}/shipments/labelReprint | Reprint Labels
[**shipServerActorIDShipmentsManifestPut**](ShipServerApi.md#shipserveractoridshipmentsmanifestput) | **PUT** /ShipServer/{actorID}/shipments/manifest | Transmit/manifest Shipments
[**shipServerActorIDShipmentsPost**](ShipServerApi.md#shipserveractoridshipmentspost) | **POST** /ShipServer/{actorID}/shipments | Submit/Print Shipment
[**shipServerActorIDShipmentsShipmentTagDelete**](ShipServerApi.md#shipserveractoridshipmentsshipmenttagdelete) | **DELETE** /ShipServer/{actorID}/shipments/{shipmentTag} | Delete shipment
[**shipServerActorIDShipmentsShipmentTagDetailsPatch**](ShipServerApi.md#shipserveractoridshipmentsshipmenttagdetailspatch) | **PATCH** /ShipServer/{actorID}/shipments/{shipmentTag}/details | Update Details
[**shipServerActorIDShipmentsShipmentTagDocumentListsGet**](ShipServerApi.md#shipserveractoridshipmentsshipmenttagdocumentlistsget) | **GET** /ShipServer/{actorID}/shipments/{shipmentTag}/documentLists | Get document list for a shipment
[**shipServerActorIDShipmentsShipmentTagDocumentsGet**](ShipServerApi.md#shipserveractoridshipmentsshipmenttagdocumentsget) | **GET** /ShipServer/{actorID}/shipments/{shipmentTag}/documents | Get documents for a shipment
[**shipServerActorIDShipmentsShipmentTagGet**](ShipServerApi.md#shipserveractoridshipmentsshipmenttagget) | **GET** /ShipServer/{actorID}/shipments/{shipmentTag} | Get existing shipment
[**shipServerActorIDShipmentsShipmentTagLinesLineTagDelete**](ShipServerApi.md#shipserveractoridshipmentsshipmenttaglineslinetagdelete) | **DELETE** /ShipServer/{actorID}/shipments/{shipmentTag}/lines/{lineTag} | Delete line
[**shipServerActorIDShipmentsShipmentTagLinesLineTagPatch**](ShipServerApi.md#shipserveractoridshipmentsshipmenttaglineslinetagpatch) | **PATCH** /ShipServer/{actorID}/shipments/{shipmentTag}/lines/{lineTag} | Update Line
[**shipServerActorIDShipmentsShipmentTagLinesPost**](ShipServerApi.md#shipserveractoridshipmentsshipmenttaglinespost) | **POST** /ShipServer/{actorID}/shipments/{shipmentTag}/lines | New shipment line
[**shipServerActorIDShipmentsShipmentTagPackagesPackageTagDelete**](ShipServerApi.md#shipserveractoridshipmentsshipmenttagpackagespackagetagdelete) | **DELETE** /ShipServer/{actorID}/shipments/{shipmentTag}/packages/{packageTag} | Delete package
[**shipServerActorIDShipmentsShipmentTagTrackingURLGet**](ShipServerApi.md#shipserveractoridshipmentsshipmenttagtrackingurlget) | **GET** /ShipServer/{actorID}/shipments/{shipmentTag}/trackingURL | Get Tracking URL
[**shipServerActorIDShippingRulesPost**](ShipServerApi.md#shipserveractoridshippingrulespost) | **POST** /ShipServer/{actorID}/shippingRules | Save shipping rules
[**shipServerActorIDStacksGet**](ShipServerApi.md#shipserveractoridstacksget) | **GET** /ShipServer/{actorID}/stacks | Get stacks
[**shipServerActorIDStacksPost**](ShipServerApi.md#shipserveractoridstackspost) | **POST** /ShipServer/{actorID}/stacks | Create stack
[**shipServerActorIDStacksShipmentsPatch**](ShipServerApi.md#shipserveractoridstacksshipmentspatch) | **PATCH** /ShipServer/{actorID}/stacks/shipments | Move shipments
[**shipServerActorIDStacksShipmentsPost**](ShipServerApi.md#shipserveractoridstacksshipmentspost) | **POST** /ShipServer/{actorID}/stacks/shipments | Get stackshipments
[**shipServerActorIDStacksStackIDDelete**](ShipServerApi.md#shipserveractoridstacksstackiddelete) | **DELETE** /ShipServer/{actorID}/stacks/{stackID} | Delete stack
[**shipServerActorIDStacksStackIDManifestPut**](ShipServerApi.md#shipserveractoridstacksstackidmanifestput) | **PUT** /ShipServer/{actorID}/stacks/{stackID}/manifest | Transmit stack
[**shipServerActorIDSubmitOrderPost**](ShipServerApi.md#shipserveractoridsubmitorderpost) | **POST** /ShipServer/{actorID}/submitOrder | Submit order
[**shipServerActorIDTimeSlotAllocationsPost**](ShipServerApi.md#shipserveractoridtimeslotallocationspost) | **POST** /ShipServer/{actorID}/timeSlotAllocations | Time slot allocations
[**shipServerActorIDTimeSlotsPost**](ShipServerApi.md#shipserveractoridtimeslotspost) | **POST** /ShipServer/{actorID}/timeSlots | Get time slots
[**shipServerActorIDValidRoutesPost**](ShipServerApi.md#shipserveractoridvalidroutespost) | **POST** /ShipServer/{actorID}/validRoutes | Check sender/receiver addresses.
[**shipServerActorIDVoidTimeSlotPost**](ShipServerApi.md#shipserveractoridvoidtimeslotpost) | **POST** /ShipServer/{actorID}/voidTimeSlot | Void Time slot
[**shipServerActorIDWaybillsPost**](ShipServerApi.md#shipserveractoridwaybillspost) | **POST** /ShipServer/{actorID}/waybills | Get waybills

# **shipServerActorIDAvailableServicesGet**
> shipServerActorIDAvailableServicesGet($actor_id, $include_carriers, $include_sub_carriers, $include_products, $include_icons, $include_services, $include_goods_types, $include_validations, $carrier_concep_id)

Get Products for actor

Returns available products with attributes              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#get_availableServices\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$include_carriers = true; // bool | Include Carriers in response
$include_sub_carriers = false; // bool | Include SubCarriers in response
$include_products = true; // bool | Include Products in response
$include_icons = false; // bool | Include Carrier Icons in response,
$include_services = true; // bool | Include Services in response,
$include_goods_types = true; // bool | Include Goods Types in response,
$include_validations = false; // bool | Include validation rules for products in response
$carrier_concep_id = 0; // int | Return data only for carrier with this concept ID

try {
    $apiInstance->shipServerActorIDAvailableServicesGet($actor_id, $include_carriers, $include_sub_carriers, $include_products, $include_icons, $include_services, $include_goods_types, $include_validations, $carrier_concep_id);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDAvailableServicesGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **include_carriers** | **bool**| Include Carriers in response | [optional] [default to true]
 **include_sub_carriers** | **bool**| Include SubCarriers in response | [optional] [default to false]
 **include_products** | **bool**| Include Products in response | [optional] [default to true]
 **include_icons** | **bool**| Include Carrier Icons in response, | [optional] [default to false]
 **include_services** | **bool**| Include Services in response, | [optional] [default to true]
 **include_goods_types** | **bool**| Include Goods Types in response, | [optional] [default to true]
 **include_validations** | **bool**| Include validation rules for products in response | [optional] [default to false]
 **carrier_concep_id** | **int**| Return data only for carrier with this concept ID | [optional] [default to 0]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDBatchReportsBatchReportIDGet**
> shipServerActorIDBatchReportsBatchReportIDGet($actor_id, $batch_report_id)

Get batch report

Returns a batch report.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#get_batchreports\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$batch_report_id = 56; // int | Job ID

try {
    $apiInstance->shipServerActorIDBatchReportsBatchReportIDGet($actor_id, $batch_report_id);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDBatchReportsBatchReportIDGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **batch_report_id** | **int**| Job ID |

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDBatchShipmentsBatchIDGet**
> shipServerActorIDBatchShipmentsBatchIDGet($actor_id, $batch_id)

Get batch shipments

Returns the list of shipments in a batch.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#get_batchshipments\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$batch_id = 56; // int | Batch ID

try {
    $apiInstance->shipServerActorIDBatchShipmentsBatchIDGet($actor_id, $batch_id);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDBatchShipmentsBatchIDGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **batch_id** | **int**| Batch ID |

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDBatchesBatchIDGet**
> shipServerActorIDBatchesBatchIDGet($actor_id, $batch_id)

Get Batch Details

Get the details about the documents in the batch.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#get_batches\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$batch_id = 56; // int | Batch ID

try {
    $apiInstance->shipServerActorIDBatchesBatchIDGet($actor_id, $batch_id);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDBatchesBatchIDGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **batch_id** | **int**| Batch ID |

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDBatchesPost**
> shipServerActorIDBatchesPost($actor_id, $body)

Get Batch List

Get the list of batches.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_batches\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: {"data":{"StartIndex":"0", "Count":5, "SortField":"TransmitDt", "SortDirection":1}}

try {
    $apiInstance->shipServerActorIDBatchesPost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDBatchesPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: {&quot;data&quot;:{&quot;StartIndex&quot;:&quot;0&quot;, &quot;Count&quot;:5, &quot;SortField&quot;:&quot;TransmitDt&quot;, &quot;SortDirection&quot;:1}} | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDCheckoutPost**
> shipServerActorIDCheckoutPost($actor_id, $body)

Get delivery optionswithout shipping rules defined

Returns a list of valid shipping alternatives without a shipping rules file              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post checkout\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST:    {"data":{"Kind":"1","Addresses":[{"Kind":1,"Name1":"Mr Test Order","Street1":"Street 10","PostCode":"1405","City":"Langhus","Email":"a@noexitingqwerty.nnn","CountryCode":"NO"}],"Lines":[{"PkgWeight":"111","Height":"10","Length":"100","Width":"100","PkgVol":"10000","Pkgs":[{"ItemNo":1}]}]},"options":{"Price":"1"}}

try {
    $apiInstance->shipServerActorIDCheckoutPost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDCheckoutPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST:    {&quot;data&quot;:{&quot;Kind&quot;:&quot;1&quot;,&quot;Addresses&quot;:[{&quot;Kind&quot;:1,&quot;Name1&quot;:&quot;Mr Test Order&quot;,&quot;Street1&quot;:&quot;Street 10&quot;,&quot;PostCode&quot;:&quot;1405&quot;,&quot;City&quot;:&quot;Langhus&quot;,&quot;Email&quot;:&quot;a@noexitingqwerty.nnn&quot;,&quot;CountryCode&quot;:&quot;NO&quot;}],&quot;Lines&quot;:[{&quot;PkgWeight&quot;:&quot;111&quot;,&quot;Height&quot;:&quot;10&quot;,&quot;Length&quot;:&quot;100&quot;,&quot;Width&quot;:&quot;100&quot;,&quot;PkgVol&quot;:&quot;10000&quot;,&quot;Pkgs&quot;:[{&quot;ItemNo&quot;:1}]}]},&quot;options&quot;:{&quot;Price&quot;:&quot;1&quot;}} | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDDropPointIDsDropPointIDPost**
> shipServerActorIDDropPointIDsDropPointIDPost($actor_id, $drop_point_id, $body)

Get drop point by ID

<a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_dropPointIDs\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$drop_point_id = "drop_point_id_example"; // string | Drop Point ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: { "Kind": 1, "ProdConceptID": 1041, "Services": [ 142002 ], "Addresses": [ { "Kind": 1, "Name1": "sample", "Street1": "Street 10", "PostCode": "1400", "City": "city", "CountryCode": "NO" } ] }

try {
    $apiInstance->shipServerActorIDDropPointIDsDropPointIDPost($actor_id, $drop_point_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDDropPointIDsDropPointIDPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **drop_point_id** | **string**| Drop Point ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: { &quot;Kind&quot;: 1, &quot;ProdConceptID&quot;: 1041, &quot;Services&quot;: [ 142002 ], &quot;Addresses&quot;: [ { &quot;Kind&quot;: 1, &quot;Name1&quot;: &quot;sample&quot;, &quot;Street1&quot;: &quot;Street 10&quot;, &quot;PostCode&quot;: &quot;1400&quot;, &quot;City&quot;: &quot;city&quot;, &quot;CountryCode&quot;: &quot;NO&quot; } ] } | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDDropPointsPost**
> shipServerActorIDDropPointsPost($actor_id, $body)

Get drop points

Returns drop points (PUDOs) for the given product.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_dropPoints\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: { "data": { "Kind": 1, "ProdConceptID": 5748, "Addresses": [ { "Kind": 1, "Name1": "Name", "Street1": "Street 10", "PostCode": "1132nb", "City": "Volendam", "Phone": "00000000", "Mobile": "00000000", "Email": "a@noexitingqwerty.nnn", "CountryCode": "NL" }, { "Kind": 2, "Name1": "Name", "Street1": "Street 10", "PostCode": "24539", "City": "Neumünster", "Phone": "00000000", "Mobile": "00000000", "CountryCode": "DE" } ], "Lines": [ { "LineWeight": 2775, "PkgWeight": 2775, "Pkgs": [ { "ItemNo": 1 } ] } ], "Services": [ 676008 ] }, "options": { "EarliestPickup": "2021-06-16T06:00", "LatestPickup": "2021-06-16T21:00", "TimeLog": 1 } }

try {
    $apiInstance->shipServerActorIDDropPointsPost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDDropPointsPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: { &quot;data&quot;: { &quot;Kind&quot;: 1, &quot;ProdConceptID&quot;: 5748, &quot;Addresses&quot;: [ { &quot;Kind&quot;: 1, &quot;Name1&quot;: &quot;Name&quot;, &quot;Street1&quot;: &quot;Street 10&quot;, &quot;PostCode&quot;: &quot;1132nb&quot;, &quot;City&quot;: &quot;Volendam&quot;, &quot;Phone&quot;: &quot;00000000&quot;, &quot;Mobile&quot;: &quot;00000000&quot;, &quot;Email&quot;: &quot;a@noexitingqwerty.nnn&quot;, &quot;CountryCode&quot;: &quot;NL&quot; }, { &quot;Kind&quot;: 2, &quot;Name1&quot;: &quot;Name&quot;, &quot;Street1&quot;: &quot;Street 10&quot;, &quot;PostCode&quot;: &quot;24539&quot;, &quot;City&quot;: &quot;Neumünster&quot;, &quot;Phone&quot;: &quot;00000000&quot;, &quot;Mobile&quot;: &quot;00000000&quot;, &quot;CountryCode&quot;: &quot;DE&quot; } ], &quot;Lines&quot;: [ { &quot;LineWeight&quot;: 2775, &quot;PkgWeight&quot;: 2775, &quot;Pkgs&quot;: [ { &quot;ItemNo&quot;: 1 } ] } ], &quot;Services&quot;: [ 676008 ] }, &quot;options&quot;: { &quot;EarliestPickup&quot;: &quot;2021-06-16T06:00&quot;, &quot;LatestPickup&quot;: &quot;2021-06-16T21:00&quot;, &quot;TimeLog&quot;: 1 } } | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDImportUploadPost**
> shipServerActorIDImportUploadPost($actor_id, $body)

Import Upload

Uploads a file for import              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_importUpload\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: { "data": { "filename": "Import1.txt", "filecontent": "MTEzNjE7NzA0NzQ7TmFtZTs7OzAwMDAwMDAwO0hhbG1zdGFkO1NFO0s2ODM2NjA7OztQMTk7RElCUzs0NTQ7U0VLOzs7", "importkeys": "W10=", "version": "0.0" } }

try {
    $apiInstance->shipServerActorIDImportUploadPost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDImportUploadPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: { &quot;data&quot;: { &quot;filename&quot;: &quot;Import1.txt&quot;, &quot;filecontent&quot;: &quot;MTEzNjE7NzA0NzQ7TmFtZTs7OzAwMDAwMDAwO0hhbG1zdGFkO1NFO0s2ODM2NjA7OztQMTk7RElCUzs0NTQ7U0VLOzs7&quot;, &quot;importkeys&quot;: &quot;W10&#x3D;&quot;, &quot;version&quot;: &quot;0.0&quot; } } | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDJobsJobIDGet**
> shipServerActorIDJobsJobIDGet($actor_id, $job_id)

Get job

Get the status of a job.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#get_jobs\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$job_id = 56; // int | Job ID

try {
    $apiInstance->shipServerActorIDJobsJobIDGet($actor_id, $job_id);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDJobsJobIDGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **job_id** | **int**| Job ID |

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDOrderAdvicePost**
> shipServerActorIDOrderAdvicePost($actor_id, $body)

Creation of an order

Creates an existing order without submitting it              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_orderAdvice\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: { "data": { "Kind": 1, "OrderNo": "772157949528", "Lines": [ { "Length": 150, "Height": 100, "PkgWeight": 130, "Width": 100, "PkgVol": 1500000, "Pkgs": [ { "ItemNo": 1, "PkgNo": "" } ] } ], "Addresses": [ { "Kind": 1, "Name1": "Name", "Street1": "Street 10", "PostCode": "0360", "City": "OSLO", "POPostCode": "0580", "POCity": "OSLO", "Phone": "00000000", "Mobile": "12341234", "Email": "a@noexitingqwerty.nnn", "CountryCode": "NO" } ], "References": [ { "Kind": 7, "Value": "ECOM12364313" } ] }, "options": { "ServiceLevel": "STANDARD", "RequiredDeliveryDate": "2021-10-25", "UseShippingRules": "1", "ValidatePostCode": null, "Visibility": "extended" } }

try {
    $apiInstance->shipServerActorIDOrderAdvicePost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDOrderAdvicePost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: { &quot;data&quot;: { &quot;Kind&quot;: 1, &quot;OrderNo&quot;: &quot;772157949528&quot;, &quot;Lines&quot;: [ { &quot;Length&quot;: 150, &quot;Height&quot;: 100, &quot;PkgWeight&quot;: 130, &quot;Width&quot;: 100, &quot;PkgVol&quot;: 1500000, &quot;Pkgs&quot;: [ { &quot;ItemNo&quot;: 1, &quot;PkgNo&quot;: &quot;&quot; } ] } ], &quot;Addresses&quot;: [ { &quot;Kind&quot;: 1, &quot;Name1&quot;: &quot;Name&quot;, &quot;Street1&quot;: &quot;Street 10&quot;, &quot;PostCode&quot;: &quot;0360&quot;, &quot;City&quot;: &quot;OSLO&quot;, &quot;POPostCode&quot;: &quot;0580&quot;, &quot;POCity&quot;: &quot;OSLO&quot;, &quot;Phone&quot;: &quot;00000000&quot;, &quot;Mobile&quot;: &quot;12341234&quot;, &quot;Email&quot;: &quot;a@noexitingqwerty.nnn&quot;, &quot;CountryCode&quot;: &quot;NO&quot; } ], &quot;References&quot;: [ { &quot;Kind&quot;: 7, &quot;Value&quot;: &quot;ECOM12364313&quot; } ] }, &quot;options&quot;: { &quot;ServiceLevel&quot;: &quot;STANDARD&quot;, &quot;RequiredDeliveryDate&quot;: &quot;2021-10-25&quot;, &quot;UseShippingRules&quot;: &quot;1&quot;, &quot;ValidatePostCode&quot;: null, &quot;Visibility&quot;: &quot;extended&quot; } } | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDOrdersPost**
> shipServerActorIDOrdersPost($actor_id, $body)

Store order

Store an order (shipment) in Order Databases for later use with On-premises or DeliveryHub. Data: shipment JSON - does not need to be complete shipment.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_orders\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: {"data":{"Kind":1,"OrderNo":19576,"Addresses":[{"Kind":1,"Name1":"Leveranser AB","Street1":"Test Street 1","PostCode":"24542","City":"Staffanstorp","Phone":"00000000","Mobile":"00000000","Email":"a@noexitingqwerty.nnn","Attention":"TEST","CountryCode":"SE"},{"Kind":2,"Name1":"Consignor AB","Street1":"Street 10","PostCode":"22350","City":"Lund","Phone":"046-123456","Mobile":"046-123456","Email":"a@noexitingqwerty.nnn","Attention": "Kundtjänst","CountryCode":"SE"},{"Kind":10,"CustNo":""}],"Amounts":[{"Kind":10,"CurrencyCode":3,"Value":""}],"Lines":[{"PkgWeight":2000,"Height":"150","Length":"150","Width":"150","References":[{"Kind":23,"Value":""}],"PkgVol":0,"Pkgs":[{"ItemNo":1}]}]},"options":{"OrderID":"12345"}}

try {
    $apiInstance->shipServerActorIDOrdersPost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDOrdersPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: {&quot;data&quot;:{&quot;Kind&quot;:1,&quot;OrderNo&quot;:19576,&quot;Addresses&quot;:[{&quot;Kind&quot;:1,&quot;Name1&quot;:&quot;Leveranser AB&quot;,&quot;Street1&quot;:&quot;Test Street 1&quot;,&quot;PostCode&quot;:&quot;24542&quot;,&quot;City&quot;:&quot;Staffanstorp&quot;,&quot;Phone&quot;:&quot;00000000&quot;,&quot;Mobile&quot;:&quot;00000000&quot;,&quot;Email&quot;:&quot;a@noexitingqwerty.nnn&quot;,&quot;Attention&quot;:&quot;TEST&quot;,&quot;CountryCode&quot;:&quot;SE&quot;},{&quot;Kind&quot;:2,&quot;Name1&quot;:&quot;Consignor AB&quot;,&quot;Street1&quot;:&quot;Street 10&quot;,&quot;PostCode&quot;:&quot;22350&quot;,&quot;City&quot;:&quot;Lund&quot;,&quot;Phone&quot;:&quot;046-123456&quot;,&quot;Mobile&quot;:&quot;046-123456&quot;,&quot;Email&quot;:&quot;a@noexitingqwerty.nnn&quot;,&quot;Attention&quot;: &quot;Kundtjänst&quot;,&quot;CountryCode&quot;:&quot;SE&quot;},{&quot;Kind&quot;:10,&quot;CustNo&quot;:&quot;&quot;}],&quot;Amounts&quot;:[{&quot;Kind&quot;:10,&quot;CurrencyCode&quot;:3,&quot;Value&quot;:&quot;&quot;}],&quot;Lines&quot;:[{&quot;PkgWeight&quot;:2000,&quot;Height&quot;:&quot;150&quot;,&quot;Length&quot;:&quot;150&quot;,&quot;Width&quot;:&quot;150&quot;,&quot;References&quot;:[{&quot;Kind&quot;:23,&quot;Value&quot;:&quot;&quot;}],&quot;PkgVol&quot;:0,&quot;Pkgs&quot;:[{&quot;ItemNo&quot;:1}]}]},&quot;options&quot;:{&quot;OrderID&quot;:&quot;12345&quot;}} | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDPackagesManifestPut**
> shipServerActorIDPackagesManifestPut($actor_id, $body)

Transmit/manifest packages

This method will transmit the specified packages(s). PackageCSIDs contains a comma delimited list of one or multiple PkgCSID, which identify the packages that should be transmitted. The selection of packages will be transmitted to carrier when the method is executed.  <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#put_manifest_\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request PUT:  {"data":{"PackageCSIDs":[4566,4585]},"options":{}}

try {
    $apiInstance->shipServerActorIDPackagesManifestPut($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDPackagesManifestPut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request PUT:  {&quot;data&quot;:{&quot;PackageCSIDs&quot;:[4566,4585]},&quot;options&quot;:{}} | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDPickupLockerAllocationsPost**
> shipServerActorIDPickupLockerAllocationsPost($actor_id, $body)

Pickup Locker Allocations

Allocates a pickup locker. To use this, you need to call GetPickupLockers, or GetShipAdvise first with options parameter “PickupLocker”:1.               This method will return an AllocatedPickupLockerToken.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_pickupLockerAllocations\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: {"data": {"ProdConceptID": 7358, "AgentNo": "1344", "Addresses": [{"Kind": 1, "Name1": "Test Receiver", "Street1": "Street 10", "PostCode": "11848", "City": "Göteborg", "CustNo": "5", "Mobile": "+4411223344", "CountryCode": "SE", "Email": "a@noexitingqwerty.nnn", "Country": "Sweden", "ERPRef": "5"}, {"Kind": 2, "Name1": "Sender Test", "Street1": "Lisebergsvägen 2", "PostCode": "43891", "Mobile": "99887766", "City": "Landvetter", "CustNo": "3425964", "CountryCode": "SE", "Country": "Sweden", "Email": "a@noexitingqwerty.nnn"}], "References": [{"Kind": 108, "Value": "2021-10-15T00:00:00"}, {"Kind": 109, "Value": "2021-10-15T00:22:00"}, {"Kind": 110, "Value": "2021-10-15T00:01:00"}, {"Kind": 111, "Value": "2021-10-15T00:22:00"}, {"Kind": 140, "Value": "a@b.c"}], "Lines": [{"LineWeight": 4000, "PkgWeight": 4000, "Width": 10, "Height": 400, "Length": 10, "Pkgs": [{"ItemNo": 3}], "References": [{"Kind": 23, "Value": "cool stuff"}]}]},"options":{"PickupLockerToken":"ZXlKemIzSjBYMk52WkdVaU9pSkpUalVpTENKaGRtRnBiR0ZpYVd4cGRIbGZkRzlyWlc0aU9pSmlNekU1T1RkbFlTMDRPVFZoTFRSbFpqY3RPR1ZtWkMwek5XVTRNak5oWkdVNFlXSWlmUT09O0lONTtULU1hcmlhdG9yZ2V0IChTd2VkZW5ib3Jnc2cpIFByZXNzYnlyw6VuIChpbW9yZ29uIH4xNjowMCk7O1dvbGxtYXIgWXhrdWxsc2dhdGFuIDg7V29sbG1hciBZeGt1bGxzZ2F0YW4gODsxMTg1MDtTdG9ja2hvbG07O1NFOzs7", "TimeLog": 1,"Token":"_-1_0_7892_7961_4593_5599_0_0__0__12/30/1899_12/30/1899_TimeSlots__"}}

try {
    $apiInstance->shipServerActorIDPickupLockerAllocationsPost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDPickupLockerAllocationsPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: {&quot;data&quot;: {&quot;ProdConceptID&quot;: 7358, &quot;AgentNo&quot;: &quot;1344&quot;, &quot;Addresses&quot;: [{&quot;Kind&quot;: 1, &quot;Name1&quot;: &quot;Test Receiver&quot;, &quot;Street1&quot;: &quot;Street 10&quot;, &quot;PostCode&quot;: &quot;11848&quot;, &quot;City&quot;: &quot;Göteborg&quot;, &quot;CustNo&quot;: &quot;5&quot;, &quot;Mobile&quot;: &quot;+4411223344&quot;, &quot;CountryCode&quot;: &quot;SE&quot;, &quot;Email&quot;: &quot;a@noexitingqwerty.nnn&quot;, &quot;Country&quot;: &quot;Sweden&quot;, &quot;ERPRef&quot;: &quot;5&quot;}, {&quot;Kind&quot;: 2, &quot;Name1&quot;: &quot;Sender Test&quot;, &quot;Street1&quot;: &quot;Lisebergsvägen 2&quot;, &quot;PostCode&quot;: &quot;43891&quot;, &quot;Mobile&quot;: &quot;99887766&quot;, &quot;City&quot;: &quot;Landvetter&quot;, &quot;CustNo&quot;: &quot;3425964&quot;, &quot;CountryCode&quot;: &quot;SE&quot;, &quot;Country&quot;: &quot;Sweden&quot;, &quot;Email&quot;: &quot;a@noexitingqwerty.nnn&quot;}], &quot;References&quot;: [{&quot;Kind&quot;: 108, &quot;Value&quot;: &quot;2021-10-15T00:00:00&quot;}, {&quot;Kind&quot;: 109, &quot;Value&quot;: &quot;2021-10-15T00:22:00&quot;}, {&quot;Kind&quot;: 110, &quot;Value&quot;: &quot;2021-10-15T00:01:00&quot;}, {&quot;Kind&quot;: 111, &quot;Value&quot;: &quot;2021-10-15T00:22:00&quot;}, {&quot;Kind&quot;: 140, &quot;Value&quot;: &quot;a@b.c&quot;}], &quot;Lines&quot;: [{&quot;LineWeight&quot;: 4000, &quot;PkgWeight&quot;: 4000, &quot;Width&quot;: 10, &quot;Height&quot;: 400, &quot;Length&quot;: 10, &quot;Pkgs&quot;: [{&quot;ItemNo&quot;: 3}], &quot;References&quot;: [{&quot;Kind&quot;: 23, &quot;Value&quot;: &quot;cool stuff&quot;}]}]},&quot;options&quot;:{&quot;PickupLockerToken&quot;:&quot;ZXlKemIzSjBYMk52WkdVaU9pSkpUalVpTENKaGRtRnBiR0ZpYVd4cGRIbGZkRzlyWlc0aU9pSmlNekU1T1RkbFlTMDRPVFZoTFRSbFpqY3RPR1ZtWkMwek5XVTRNak5oWkdVNFlXSWlmUT09O0lONTtULU1hcmlhdG9yZ2V0IChTd2VkZW5ib3Jnc2cpIFByZXNzYnlyw6VuIChpbW9yZ29uIH4xNjowMCk7O1dvbGxtYXIgWXhrdWxsc2dhdGFuIDg7V29sbG1hciBZeGt1bGxzZ2F0YW4gODsxMTg1MDtTdG9ja2hvbG07O1NFOzs7&quot;, &quot;TimeLog&quot;: 1,&quot;Token&quot;:&quot;_-1_0_7892_7961_4593_5599_0_0__0__12/30/1899_12/30/1899_TimeSlots__&quot;}} | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDPickupLockersPost**
> shipServerActorIDPickupLockersPost($actor_id, $body)

Get pickup lockers

Returns a list of available pickup lockers.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_pickupLockers\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: { "data": { "ProdConceptID": 7358, "AgentNo": "1344", "Addresses": [ { "Kind": 1, "Name1": "Test Receiver", "Street1": "Street 10", "PostCode": "11848", "City": "Göteborg", "Mobile": "00000000", "Email": "a@noexitingqwerty.nnn" }, { "Kind": 2, "Name1": "Sender Test", "Street1": "Street 10", "PostCode": "43891", "Mobile": "00000000", "City": "Landvetter", "CustNo": "3425964", "Email": "a@noexitingqwerty.nnn" } ], "References": [ { "Kind": 108, "Value": "2021-10-15T00:00:00" }, { "Kind": 109, "Value": "2021-10-15T00:22:00" }, { "Kind": 110, "Value": "2021-10-15T00:01:00" }, { "Kind": 111, "Value": "2021-10-15T00:22:00" }, { "Kind": 140, "Value": "a@b.c" } ], "Lines": [ { "LineWeight": 4000, "PkgWeight": 4000, "Width": 10, "Height": 400, "Length": 10, "Pkgs": [ { "ItemNo": 3 } ], "References": [ { "Kind": 23, "Value": "cool stuff" } ] } ] }, "options": { "TimeLog": 1, "Token": "_-1_0_7892_7961_4593_5599_0_0__0__12/30/1899_12/30/1899_TimeSlots__" } }

try {
    $apiInstance->shipServerActorIDPickupLockersPost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDPickupLockersPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: { &quot;data&quot;: { &quot;ProdConceptID&quot;: 7358, &quot;AgentNo&quot;: &quot;1344&quot;, &quot;Addresses&quot;: [ { &quot;Kind&quot;: 1, &quot;Name1&quot;: &quot;Test Receiver&quot;, &quot;Street1&quot;: &quot;Street 10&quot;, &quot;PostCode&quot;: &quot;11848&quot;, &quot;City&quot;: &quot;Göteborg&quot;, &quot;Mobile&quot;: &quot;00000000&quot;, &quot;Email&quot;: &quot;a@noexitingqwerty.nnn&quot; }, { &quot;Kind&quot;: 2, &quot;Name1&quot;: &quot;Sender Test&quot;, &quot;Street1&quot;: &quot;Street 10&quot;, &quot;PostCode&quot;: &quot;43891&quot;, &quot;Mobile&quot;: &quot;00000000&quot;, &quot;City&quot;: &quot;Landvetter&quot;, &quot;CustNo&quot;: &quot;3425964&quot;, &quot;Email&quot;: &quot;a@noexitingqwerty.nnn&quot; } ], &quot;References&quot;: [ { &quot;Kind&quot;: 108, &quot;Value&quot;: &quot;2021-10-15T00:00:00&quot; }, { &quot;Kind&quot;: 109, &quot;Value&quot;: &quot;2021-10-15T00:22:00&quot; }, { &quot;Kind&quot;: 110, &quot;Value&quot;: &quot;2021-10-15T00:01:00&quot; }, { &quot;Kind&quot;: 111, &quot;Value&quot;: &quot;2021-10-15T00:22:00&quot; }, { &quot;Kind&quot;: 140, &quot;Value&quot;: &quot;a@b.c&quot; } ], &quot;Lines&quot;: [ { &quot;LineWeight&quot;: 4000, &quot;PkgWeight&quot;: 4000, &quot;Width&quot;: 10, &quot;Height&quot;: 400, &quot;Length&quot;: 10, &quot;Pkgs&quot;: [ { &quot;ItemNo&quot;: 3 } ], &quot;References&quot;: [ { &quot;Kind&quot;: 23, &quot;Value&quot;: &quot;cool stuff&quot; } ] } ] }, &quot;options&quot;: { &quot;TimeLog&quot;: 1, &quot;Token&quot;: &quot;_-1_0_7892_7961_4593_5599_0_0__0__12/30/1899_12/30/1899_TimeSlots__&quot; } } | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDProductsGet**
> shipServerActorIDProductsGet($actor_id)

Get Products

Gets all carriers and sub carriers, products and services for the given actor along with the correspondingConceptIDs and ServiceIDs.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#get_products\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID

try {
    $apiInstance->shipServerActorIDProductsGet($actor_id);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDProductsGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDSaveShipmentPost**
> shipServerActorIDSaveShipmentPost($actor_id, $body)

Save shipment

Save/post shipment, returns created shipment along with labels if requested.               <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_saveshipment\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST:    { "data": { "Kind": 1, "ProdConceptID": 2816, "Addresses": [ { "Kind": 1, "Name1": "Name Receiver", "Street1": "Street 10", "PostCode": "11848", "City": "Göteborg", "CustNo": "5", "Mobile": "00000000", "CountryCode": "SE", "Email": "a@noexitingqwerty.nnn", "Country": "Sweden" } ], "Lines": [ { "LineWeight": 500, "Pkgs": [ { "ItemNo": 1 } ] } ] }, "options": { } }

try {
    $apiInstance->shipServerActorIDSaveShipmentPost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDSaveShipmentPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST:    { &quot;data&quot;: { &quot;Kind&quot;: 1, &quot;ProdConceptID&quot;: 2816, &quot;Addresses&quot;: [ { &quot;Kind&quot;: 1, &quot;Name1&quot;: &quot;Name Receiver&quot;, &quot;Street1&quot;: &quot;Street 10&quot;, &quot;PostCode&quot;: &quot;11848&quot;, &quot;City&quot;: &quot;Göteborg&quot;, &quot;CustNo&quot;: &quot;5&quot;, &quot;Mobile&quot;: &quot;00000000&quot;, &quot;CountryCode&quot;: &quot;SE&quot;, &quot;Email&quot;: &quot;a@noexitingqwerty.nnn&quot;, &quot;Country&quot;: &quot;Sweden&quot; } ], &quot;Lines&quot;: [ { &quot;LineWeight&quot;: 500, &quot;Pkgs&quot;: [ { &quot;ItemNo&quot;: 1 } ] } ] }, &quot;options&quot;: { } } | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDSenderAddressGet**
> shipServerActorIDSenderAddressGet($actor_id)

Get Sender Address

Get Sender Address by actor id              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#get_senderAddress\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID

try {
    $apiInstance->shipServerActorIDSenderAddressGet($actor_id);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDSenderAddressGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDShipAdvisesPost**
> shipServerActorIDShipAdvisesPost($actor_id, $body)

Get delivery options

Returns a list of valid shipping alternatives.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_shipAdvises\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST:    {"data":{"Kind":"1","Addresses":[{"Kind":1,"Name1":"Mr Test Order","Street1":"Street 10","PostCode":"1405","City":"Langhus","Email":"a@noexitingqwerty.nnn","CountryCode":"NO"}],"Lines":[{"PkgWeight":"111","Height":"10","Length":"100","Width":"100","PkgVol":"10000","Pkgs":[{"ItemNo":1}]}]},"options":{"ServiceLevel":"test","Price":"1"}}

try {
    $apiInstance->shipServerActorIDShipAdvisesPost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDShipAdvisesPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST:    {&quot;data&quot;:{&quot;Kind&quot;:&quot;1&quot;,&quot;Addresses&quot;:[{&quot;Kind&quot;:1,&quot;Name1&quot;:&quot;Mr Test Order&quot;,&quot;Street1&quot;:&quot;Street 10&quot;,&quot;PostCode&quot;:&quot;1405&quot;,&quot;City&quot;:&quot;Langhus&quot;,&quot;Email&quot;:&quot;a@noexitingqwerty.nnn&quot;,&quot;CountryCode&quot;:&quot;NO&quot;}],&quot;Lines&quot;:[{&quot;PkgWeight&quot;:&quot;111&quot;,&quot;Height&quot;:&quot;10&quot;,&quot;Length&quot;:&quot;100&quot;,&quot;Width&quot;:&quot;100&quot;,&quot;PkgVol&quot;:&quot;10000&quot;,&quot;Pkgs&quot;:[{&quot;ItemNo&quot;:1}]}]},&quot;options&quot;:{&quot;ServiceLevel&quot;:&quot;test&quot;,&quot;Price&quot;:&quot;1&quot;}} | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDShipmentPricesPost**
> shipServerActorIDShipmentPricesPost($actor_id, $body)

Get Shipment Price

Calculates price based on the shipment if price calculation is activated on product              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_shipmentPrices\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: { "data": { "Kind": 1, "DimensionalWeight": 900, "Weight": 900, "ActorCSID": 73, "CarriagePayer": 1, "ProdConceptID": 2, "StackCSID": "155", "Addresses": [ { "Kind": 1, "Name1": "Bane", "Street1": "Street 10", "PostCode": "5863", "City": "BERGEN", "CountryCode": "NO" }, { "Kind": 2, "Name1": "Name", "Street1": "Street 10", "PostCode": "0680", "City": "Oslo", "CountryCode": "NO" } ], "Lines": [ { "LineWeight": 900, "PkgWeight": 900, "Number": 1 } ] } }

try {
    $apiInstance->shipServerActorIDShipmentPricesPost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDShipmentPricesPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: { &quot;data&quot;: { &quot;Kind&quot;: 1, &quot;DimensionalWeight&quot;: 900, &quot;Weight&quot;: 900, &quot;ActorCSID&quot;: 73, &quot;CarriagePayer&quot;: 1, &quot;ProdConceptID&quot;: 2, &quot;StackCSID&quot;: &quot;155&quot;, &quot;Addresses&quot;: [ { &quot;Kind&quot;: 1, &quot;Name1&quot;: &quot;Bane&quot;, &quot;Street1&quot;: &quot;Street 10&quot;, &quot;PostCode&quot;: &quot;5863&quot;, &quot;City&quot;: &quot;BERGEN&quot;, &quot;CountryCode&quot;: &quot;NO&quot; }, { &quot;Kind&quot;: 2, &quot;Name1&quot;: &quot;Name&quot;, &quot;Street1&quot;: &quot;Street 10&quot;, &quot;PostCode&quot;: &quot;0680&quot;, &quot;City&quot;: &quot;Oslo&quot;, &quot;CountryCode&quot;: &quot;NO&quot; } ], &quot;Lines&quot;: [ { &quot;LineWeight&quot;: 900, &quot;PkgWeight&quot;: 900, &quot;Number&quot;: 1 } ] } } | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDShipmentValidationsPost**
> shipServerActorIDShipmentValidationsPost($actor_id, $body)

Validate shipment

Validate a shipment to find missing/wrong data              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_shipmentvalidations\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: { "data": { "Kind": 1, "Addresses": [ { "Kind": 1, "Name1": "RecName1", "Name2": "RecName2", "Street1": "Street 10", "PostCode": "0680", "City": "OSLO", "Phone": "00000000", "Email": "a@noexitingqwerty.nnn", "CountryCode": "NO" }, { "Kind": 2, "Name1": "SenName1", "Name2": "SenName2", "Street1": "Street 10", "PostCode": "0681", "City": "OSLO", "Mobile": "00000000", "Email": "a@noexitingqwerty.nnn", "CountryCode": "NO" } ], "Lines": [ { "LineWeight": 5000, "PkgWeight": 5000, "GoodsTypeID": 1, "Pkgs": [ {}, {} ], "References": [ { "Kind": 23, "Value": "Contents" } ] } ], "References": [ { "Kind": 32, "Value": "AdditionalReference 1" } ], "Amounts": [ { "Kind": 1, "CurrencyCode": "1", "CurrencyClientId": 1, "Value": 10, "ShipmentId": 0, "Id": 0 } ], "Messages": [ { "Kind": 2, "Text": "CarrierMessage 1", "ShipmentId": 0, "Id": 0 } ], "ProdConceptID": 185 }, "options": { "Labels": "none" } }

try {
    $apiInstance->shipServerActorIDShipmentValidationsPost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDShipmentValidationsPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: { &quot;data&quot;: { &quot;Kind&quot;: 1, &quot;Addresses&quot;: [ { &quot;Kind&quot;: 1, &quot;Name1&quot;: &quot;RecName1&quot;, &quot;Name2&quot;: &quot;RecName2&quot;, &quot;Street1&quot;: &quot;Street 10&quot;, &quot;PostCode&quot;: &quot;0680&quot;, &quot;City&quot;: &quot;OSLO&quot;, &quot;Phone&quot;: &quot;00000000&quot;, &quot;Email&quot;: &quot;a@noexitingqwerty.nnn&quot;, &quot;CountryCode&quot;: &quot;NO&quot; }, { &quot;Kind&quot;: 2, &quot;Name1&quot;: &quot;SenName1&quot;, &quot;Name2&quot;: &quot;SenName2&quot;, &quot;Street1&quot;: &quot;Street 10&quot;, &quot;PostCode&quot;: &quot;0681&quot;, &quot;City&quot;: &quot;OSLO&quot;, &quot;Mobile&quot;: &quot;00000000&quot;, &quot;Email&quot;: &quot;a@noexitingqwerty.nnn&quot;, &quot;CountryCode&quot;: &quot;NO&quot; } ], &quot;Lines&quot;: [ { &quot;LineWeight&quot;: 5000, &quot;PkgWeight&quot;: 5000, &quot;GoodsTypeID&quot;: 1, &quot;Pkgs&quot;: [ {}, {} ], &quot;References&quot;: [ { &quot;Kind&quot;: 23, &quot;Value&quot;: &quot;Contents&quot; } ] } ], &quot;References&quot;: [ { &quot;Kind&quot;: 32, &quot;Value&quot;: &quot;AdditionalReference 1&quot; } ], &quot;Amounts&quot;: [ { &quot;Kind&quot;: 1, &quot;CurrencyCode&quot;: &quot;1&quot;, &quot;CurrencyClientId&quot;: 1, &quot;Value&quot;: 10, &quot;ShipmentId&quot;: 0, &quot;Id&quot;: 0 } ], &quot;Messages&quot;: [ { &quot;Kind&quot;: 2, &quot;Text&quot;: &quot;CarrierMessage 1&quot;, &quot;ShipmentId&quot;: 0, &quot;Id&quot;: 0 } ], &quot;ProdConceptID&quot;: 185 }, &quot;options&quot;: { &quot;Labels&quot;: &quot;none&quot; } } | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDShipmentsDefaultsPost**
> shipServerActorIDShipmentsDefaultsPost($actor_id, $body)

Apply defaults on shipment

Applies the configuration defaults on the given shipment, returning the serialized shipment.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_shipments_Defaults\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: {"data":{"Kind":"1","ProdCSID":4338,"Addresses":[{"Kind":1,"Name1":"Mr Test Order","Street1":"Street 10","PostCode":"1405","City":"Langhus","Email":"a@noexitingqwerty.nnn","CountryCode":"NO"}],"Lines":[{"PkgWeight":"111","Height":"10","Length":"100","Width":"100","PkgVol":"10000","Pkgs":[{"ItemNo":1}]}]},"options":{"ProductChanged":1430}}

try {
    $apiInstance->shipServerActorIDShipmentsDefaultsPost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDShipmentsDefaultsPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: {&quot;data&quot;:{&quot;Kind&quot;:&quot;1&quot;,&quot;ProdCSID&quot;:4338,&quot;Addresses&quot;:[{&quot;Kind&quot;:1,&quot;Name1&quot;:&quot;Mr Test Order&quot;,&quot;Street1&quot;:&quot;Street 10&quot;,&quot;PostCode&quot;:&quot;1405&quot;,&quot;City&quot;:&quot;Langhus&quot;,&quot;Email&quot;:&quot;a@noexitingqwerty.nnn&quot;,&quot;CountryCode&quot;:&quot;NO&quot;}],&quot;Lines&quot;:[{&quot;PkgWeight&quot;:&quot;111&quot;,&quot;Height&quot;:&quot;10&quot;,&quot;Length&quot;:&quot;100&quot;,&quot;Width&quot;:&quot;100&quot;,&quot;PkgVol&quot;:&quot;10000&quot;,&quot;Pkgs&quot;:[{&quot;ItemNo&quot;:1}]}]},&quot;options&quot;:{&quot;ProductChanged&quot;:1430}} | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDShipmentsLabelReprintPost**
> shipServerActorIDShipmentsLabelReprintPost($actor_id, $body)

Reprint Labels

Returns the labels from a shipment in the format requested              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_labelReprint\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: {"data":{"ShpCSID":2} ,"options":{"Labels":"PNG"}}

try {
    $apiInstance->shipServerActorIDShipmentsLabelReprintPost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDShipmentsLabelReprintPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: {&quot;data&quot;:{&quot;ShpCSID&quot;:2} ,&quot;options&quot;:{&quot;Labels&quot;:&quot;PNG&quot;}} | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDShipmentsManifestPut**
> shipServerActorIDShipmentsManifestPut($actor_id, $body)

Transmit/manifest Shipments

This method will transmit the specified shipment(s). ShipmentCSIDs contains a comma delimited list of one or multiple ShpCSIDs, which identify the shipments that should be transmitted. The selection of shipments will be transmitted to carrier when the method is executed.  <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#put_manifest\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request PUT:  {"data":{"ShipmentTags":["021602A9-F214-49B5-89BE-A40DC6E4CF55", "5D534521-8152-4483-8ED7-B74FD1BBF8DD"]},"options":{}}

try {
    $apiInstance->shipServerActorIDShipmentsManifestPut($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDShipmentsManifestPut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request PUT:  {&quot;data&quot;:{&quot;ShipmentTags&quot;:[&quot;021602A9-F214-49B5-89BE-A40DC6E4CF55&quot;, &quot;5D534521-8152-4483-8ED7-B74FD1BBF8DD&quot;]},&quot;options&quot;:{}} | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDShipmentsPost**
> shipServerActorIDShipmentsPost($actor_id, $body)

Submit/Print Shipment

Submits shipment, returns created shipment along with labels if requested.  <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_shipments\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST:    { "data": { "Kind": 1, "ProdConceptID": 2816, "Addresses": [ { "Kind": 1, "Name1": "Name Receiver", "Street1": "Street 10", "PostCode": "11848", "City": "Göteborg", "Mobile": "00000000", "CountryCode": "SE", "Email": "a@noexitingqwerty.nnn", }, { "Kind": 2, "Name1": "Name Receiver", "Street1": "Street 10", "PostCode": "11848", "City": "Göteborg", "Mobile": "00000000", "CountryCode": "SE", "Email": "a@noexitingqwerty.nnn", } ], "Lines": [ { "LineWeight": 500, "Pkgs": [ { "ItemNo": 1 } ] } ] }, "options": { "TimeLog": 0, "UseShippingRules": 0, "Visibility": "extended", "Labels": "ZPLGK" } }

try {
    $apiInstance->shipServerActorIDShipmentsPost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDShipmentsPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST:    { &quot;data&quot;: { &quot;Kind&quot;: 1, &quot;ProdConceptID&quot;: 2816, &quot;Addresses&quot;: [ { &quot;Kind&quot;: 1, &quot;Name1&quot;: &quot;Name Receiver&quot;, &quot;Street1&quot;: &quot;Street 10&quot;, &quot;PostCode&quot;: &quot;11848&quot;, &quot;City&quot;: &quot;Göteborg&quot;, &quot;Mobile&quot;: &quot;00000000&quot;, &quot;CountryCode&quot;: &quot;SE&quot;, &quot;Email&quot;: &quot;a@noexitingqwerty.nnn&quot;, }, { &quot;Kind&quot;: 2, &quot;Name1&quot;: &quot;Name Receiver&quot;, &quot;Street1&quot;: &quot;Street 10&quot;, &quot;PostCode&quot;: &quot;11848&quot;, &quot;City&quot;: &quot;Göteborg&quot;, &quot;Mobile&quot;: &quot;00000000&quot;, &quot;CountryCode&quot;: &quot;SE&quot;, &quot;Email&quot;: &quot;a@noexitingqwerty.nnn&quot;, } ], &quot;Lines&quot;: [ { &quot;LineWeight&quot;: 500, &quot;Pkgs&quot;: [ { &quot;ItemNo&quot;: 1 } ] } ] }, &quot;options&quot;: { &quot;TimeLog&quot;: 0, &quot;UseShippingRules&quot;: 0, &quot;Visibility&quot;: &quot;extended&quot;, &quot;Labels&quot;: &quot;ZPLGK&quot; } } | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDShipmentsShipmentTagDelete**
> shipServerActorIDShipmentsShipmentTagDelete($actor_id, $shipment_tag, $body)

Delete shipment

Deletes shipment by ShpCSID. Only shipments that are not transmitted can be deleted.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#delete_shipments\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$shipment_tag = "shipment_tag_example"; // string | Shipment Tag
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Optional - can be empty

try {
    $apiInstance->shipServerActorIDShipmentsShipmentTagDelete($actor_id, $shipment_tag, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDShipmentsShipmentTagDelete: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **shipment_tag** | **string**| Shipment Tag |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Optional - can be empty | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDShipmentsShipmentTagDetailsPatch**
> shipServerActorIDShipmentsShipmentTagDetailsPatch($actor_id, $shipment_tag, $body)

Update Details

Update shipment details.               <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#patch_details\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$shipment_tag = "shipment_tag_example"; // string | Shipment Tag
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: {"data":{"DetailGroups":[{"GroupID":1,"GroupDisplayName":"Customs Article","Rows":[{"RowNo":1,"LineNo":1,"Details":[{"KindID":1,"Value":"Updated A for l1","DisplayName":"Article No"},{"KindID":7,"Value":"Updated desc l1","DisplayName":"Description of Goods"}]},{"RowNo":2,"LineNo":2,"Details":[{"KindID":1,"Value":"A for l2","DisplayName":"Article No"},{"KindID":7,"Value":"desc l2","DisplayName":"Description of Goods"}]}]},{"GroupID":2,"GroupDisplayName":"Customs Information","Details":[{"KindID":11,"Value":"Updated VAT Sender","DisplayName":"Vat No (Sender)"}]}]},"options":{"Labels":"none"}}

try {
    $apiInstance->shipServerActorIDShipmentsShipmentTagDetailsPatch($actor_id, $shipment_tag, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDShipmentsShipmentTagDetailsPatch: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **shipment_tag** | **string**| Shipment Tag |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: {&quot;data&quot;:{&quot;DetailGroups&quot;:[{&quot;GroupID&quot;:1,&quot;GroupDisplayName&quot;:&quot;Customs Article&quot;,&quot;Rows&quot;:[{&quot;RowNo&quot;:1,&quot;LineNo&quot;:1,&quot;Details&quot;:[{&quot;KindID&quot;:1,&quot;Value&quot;:&quot;Updated A for l1&quot;,&quot;DisplayName&quot;:&quot;Article No&quot;},{&quot;KindID&quot;:7,&quot;Value&quot;:&quot;Updated desc l1&quot;,&quot;DisplayName&quot;:&quot;Description of Goods&quot;}]},{&quot;RowNo&quot;:2,&quot;LineNo&quot;:2,&quot;Details&quot;:[{&quot;KindID&quot;:1,&quot;Value&quot;:&quot;A for l2&quot;,&quot;DisplayName&quot;:&quot;Article No&quot;},{&quot;KindID&quot;:7,&quot;Value&quot;:&quot;desc l2&quot;,&quot;DisplayName&quot;:&quot;Description of Goods&quot;}]}]},{&quot;GroupID&quot;:2,&quot;GroupDisplayName&quot;:&quot;Customs Information&quot;,&quot;Details&quot;:[{&quot;KindID&quot;:11,&quot;Value&quot;:&quot;Updated VAT Sender&quot;,&quot;DisplayName&quot;:&quot;Vat No (Sender)&quot;}]}]},&quot;options&quot;:{&quot;Labels&quot;:&quot;none&quot;}} | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDShipmentsShipmentTagDocumentListsGet**
> shipServerActorIDShipmentsShipmentTagDocumentListsGet($actor_id, $shipment_tag)

Get document list for a shipment

The method returns a list of all the documents that was created on the shipment at submit, e.g.freight letters and Waybill.It is carrier specific which documents that are available.       Use the method GetDocument to retrieve the documents.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#get_documentLists\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$shipment_tag = "shipment_tag_example"; // string | Shipment Tag

try {
    $apiInstance->shipServerActorIDShipmentsShipmentTagDocumentListsGet($actor_id, $shipment_tag);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDShipmentsShipmentTagDocumentListsGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **shipment_tag** | **string**| Shipment Tag |

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDShipmentsShipmentTagDocumentsGet**
> shipServerActorIDShipmentsShipmentTagDocumentsGet($actor_id, $shipment_tag)

Get documents for a shipment

Returns all documents for the shipment that is enabled on the carrier / product.  The label will not be returned in the result.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#get_documents\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$shipment_tag = "shipment_tag_example"; // string | Shipment Tag

try {
    $apiInstance->shipServerActorIDShipmentsShipmentTagDocumentsGet($actor_id, $shipment_tag);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDShipmentsShipmentTagDocumentsGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **shipment_tag** | **string**| Shipment Tag |

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDShipmentsShipmentTagGet**
> shipServerActorIDShipmentsShipmentTagGet($actor_id, $shipment_tag)

Get existing shipment

Get shipment object by ShpCSID.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#get_shipments\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$shipment_tag = "shipment_tag_example"; // string | Shipment Tag

try {
    $apiInstance->shipServerActorIDShipmentsShipmentTagGet($actor_id, $shipment_tag);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDShipmentsShipmentTagGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **shipment_tag** | **string**| Shipment Tag |

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDShipmentsShipmentTagLinesLineTagDelete**
> shipServerActorIDShipmentsShipmentTagLinesLineTagDelete($actor_id, $shipment_tag, $line_tag, $body)

Delete line

Delete an existing line. Cannot delete the only line from shipment or cannot delete a line on a shipment that has been transmitted.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#delete_lines\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$shipment_tag = "shipment_tag_example"; // string | Shipment Tag
$line_tag = "line_tag_example"; // string | Line Tag
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Can be empty

try {
    $apiInstance->shipServerActorIDShipmentsShipmentTagLinesLineTagDelete($actor_id, $shipment_tag, $line_tag, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDShipmentsShipmentTagLinesLineTagDelete: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **shipment_tag** | **string**| Shipment Tag |
 **line_tag** | **string**| Line Tag |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Can be empty | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDShipmentsShipmentTagLinesLineTagPatch**
> shipServerActorIDShipmentsShipmentTagLinesLineTagPatch($actor_id, $shipment_tag, $line_tag, $body)

Update Line

Update shipment line.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#patch_lines\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$shipment_tag = "shipment_tag_example"; // string | Shipment Tag
$line_tag = "line_tag_example"; // string | Line Tag
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: {"data":{"LineWeight":5000,"PkgWeight":5000,"LineVol":1000000,"PickupDt":"2022-11-12T00:00:00","PkgVol":1000000,"Loadmeter":20,"GoodsTypeID":1,"GoodsTypeName":"Paket","RecycleTypeID":1,"RecycleTypeName":"EUR","RecycleTypeCode":"EUR","GoodsTypeKey1":"PC","GoodsTypeKey2":"PKT","Pkgs":[{"PkgCSID":122027,"ItemNo":1}]},"options":{"Labels":"none"}}

try {
    $apiInstance->shipServerActorIDShipmentsShipmentTagLinesLineTagPatch($actor_id, $shipment_tag, $line_tag, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDShipmentsShipmentTagLinesLineTagPatch: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **shipment_tag** | **string**| Shipment Tag |
 **line_tag** | **string**| Line Tag |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: {&quot;data&quot;:{&quot;LineWeight&quot;:5000,&quot;PkgWeight&quot;:5000,&quot;LineVol&quot;:1000000,&quot;PickupDt&quot;:&quot;2022-11-12T00:00:00&quot;,&quot;PkgVol&quot;:1000000,&quot;Loadmeter&quot;:20,&quot;GoodsTypeID&quot;:1,&quot;GoodsTypeName&quot;:&quot;Paket&quot;,&quot;RecycleTypeID&quot;:1,&quot;RecycleTypeName&quot;:&quot;EUR&quot;,&quot;RecycleTypeCode&quot;:&quot;EUR&quot;,&quot;GoodsTypeKey1&quot;:&quot;PC&quot;,&quot;GoodsTypeKey2&quot;:&quot;PKT&quot;,&quot;Pkgs&quot;:[{&quot;PkgCSID&quot;:122027,&quot;ItemNo&quot;:1}]},&quot;options&quot;:{&quot;Labels&quot;:&quot;none&quot;}} | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDShipmentsShipmentTagLinesPost**
> shipServerActorIDShipmentsShipmentTagLinesPost($actor_id, $shipment_tag, $body)

New shipment line

Add new line to shipment              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_lines\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$shipment_tag = "shipment_tag_example"; // string | Shipment Tag
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: {"data":{"LineWeight":1000,"PkgWeight":1000,"Height":30,"Length":30,"Width":30,"LineVol":27000,"PkgVol":27000,"Pkgs":[{"ItemNo":1,"References":[{"Kind":346,"Value":"False"}]}],"References":[{"Kind":23,"Value":"oranges"},{"Kind":24,"Value":"org"},{"Kind":345,"Value":"False"}]},"options":{}}

try {
    $apiInstance->shipServerActorIDShipmentsShipmentTagLinesPost($actor_id, $shipment_tag, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDShipmentsShipmentTagLinesPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **shipment_tag** | **string**| Shipment Tag |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: {&quot;data&quot;:{&quot;LineWeight&quot;:1000,&quot;PkgWeight&quot;:1000,&quot;Height&quot;:30,&quot;Length&quot;:30,&quot;Width&quot;:30,&quot;LineVol&quot;:27000,&quot;PkgVol&quot;:27000,&quot;Pkgs&quot;:[{&quot;ItemNo&quot;:1,&quot;References&quot;:[{&quot;Kind&quot;:346,&quot;Value&quot;:&quot;False&quot;}]}],&quot;References&quot;:[{&quot;Kind&quot;:23,&quot;Value&quot;:&quot;oranges&quot;},{&quot;Kind&quot;:24,&quot;Value&quot;:&quot;org&quot;},{&quot;Kind&quot;:345,&quot;Value&quot;:&quot;False&quot;}]},&quot;options&quot;:{}} | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDShipmentsShipmentTagPackagesPackageTagDelete**
> shipServerActorIDShipmentsShipmentTagPackagesPackageTagDelete($actor_id, $shipment_tag, $package_tag, $body)

Delete package

Deletes package by PkgCSID. Only packages that are not transmitted can be deleted.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#delete_packages\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$shipment_tag = "shipment_tag_example"; // string | Shipment Tag
$package_tag = "package_tag_example"; // string | Package Tag
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Can be empty

try {
    $apiInstance->shipServerActorIDShipmentsShipmentTagPackagesPackageTagDelete($actor_id, $shipment_tag, $package_tag, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDShipmentsShipmentTagPackagesPackageTagDelete: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **shipment_tag** | **string**| Shipment Tag |
 **package_tag** | **string**| Package Tag |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Can be empty | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDShipmentsShipmentTagTrackingURLGet**
> shipServerActorIDShipmentsShipmentTagTrackingURLGet($actor_id, $shipment_tag)

Get Tracking URL

Returns the tracking URL (s) for the requested shipment on both shipment and package level.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#get_trackingURL\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$shipment_tag = "shipment_tag_example"; // string | Shipment Tag

try {
    $apiInstance->shipServerActorIDShipmentsShipmentTagTrackingURLGet($actor_id, $shipment_tag);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDShipmentsShipmentTagTrackingURLGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **shipment_tag** | **string**| Shipment Tag |

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDShippingRulesPost**
> shipServerActorIDShippingRulesPost($actor_id, $body)

Save shipping rules

saves the encoded shipping rules file given in the context of actor.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_shippingRules\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: { "data": { "ShippingRules": "PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjxDU1I+DQoJPFNlcnZpY2VMZXZlbHM+DQoJCTxTZXJ2aWNlTGV2ZWwgbmFtZT0iU3RhbmRhcmQiPg0KCQkJPFByb2R1Y3RzPg0KCQkJCTxQcm9kdWN0IG5hbWU9IkJ1ZCIgY29uY2VwdGlkPSI3MDYiIGNvbW1lbnQ9IkdCIiByYW5rPSIxMDAiPg0KCQkJCQk8VmFsaWRhdGlvblJ1bGVzPg0KCQkJCQkJPFZhbGlkYXRpb25SdWxlIG5hbWU9ImZsb2F0bGltaXRzIiBtaW49IjEwMCIgbWF4PSIxMDAwIiBmaWVsZD0iZmxkX0xMZW5ndGgiLz4NCgkJCQkJPC9WYWxpZGF0aW9uUnVsZXM+DQoJCQkJPC9Qcm9kdWN0Pg0KCQkJCTxQcm9kdWN0IG5hbWU9IlBhbGwiIGNvbmNlcHRpZD0iNzA4IiBjb21tZW50PSJHQiIgcm Fuaz0iNTAiPg0KCQkJCQk8UG9zdGNvZGVWYWxpZGF0aW9ucz4NCgkJCQkJCTxQb3N0Y29kZVZhbGlkYXRpb24gY291bnRyeT0iTk8iIGV4Y2x1ZGU9IjAiIHR5cGU9Ik5PIj4NCgkJCQkJCQk8UmFuZ2UgbWluPSIwNTU1IiBtYXg9IiIvPg0KCQkJCQkJPC9Qb3N0Y29kZVZhbGlkYXRpb24+DQoJCQkJCTwvUG9zdGNvZGVWYWxpZGF0aW9ucz4NCgkJCQkJPFZhbGlkYXRpb25SdWxlcz4NCgkJCQkJCTxWYWxpZGF0aW9uUnVsZSBuYW1lPSJjb3VudHJ5IiBhbGxvd2NvdW50cmllcz0iTk8iIGZpZWxkPSJmbGRfQWRyQ291bnRyeSIvPg0KCQkJCQk8L1ZhbGlkYXRpb25SdWxlcz4NCgkJCQk8L1Byb2R1Y3Q+DQoJCQk8L1Byb2R1Y3RzPg0KCQkJPEFsbG9jYXRpb25SdWxlcz4NCgkJCQk8QWxsb2NhdGlvblJ1bGUgdHlwZT0iaGlnaGVzdHJhbmsiLz4NCgkJCTwvQWxsb2NhdGlvblJ1bGVzPg0KCQk8L1NlcnZpY2VMZXZlbD4NCgk8L1NlcnZpY2VMZXZlbHM+DQo8L0NTUj4NCg" } }

try {
    $apiInstance->shipServerActorIDShippingRulesPost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDShippingRulesPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: { &quot;data&quot;: { &quot;ShippingRules&quot;: &quot;PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjxDU1I+DQoJPFNlcnZpY2VMZXZlbHM+DQoJCTxTZXJ2aWNlTGV2ZWwgbmFtZT0iU3RhbmRhcmQiPg0KCQkJPFByb2R1Y3RzPg0KCQkJCTxQcm9kdWN0IG5hbWU9IkJ1ZCIgY29uY2VwdGlkPSI3MDYiIGNvbW1lbnQ9IkdCIiByYW5rPSIxMDAiPg0KCQkJCQk8VmFsaWRhdGlvblJ1bGVzPg0KCQkJCQkJPFZhbGlkYXRpb25SdWxlIG5hbWU9ImZsb2F0bGltaXRzIiBtaW49IjEwMCIgbWF4PSIxMDAwIiBmaWVsZD0iZmxkX0xMZW5ndGgiLz4NCgkJCQkJPC9WYWxpZGF0aW9uUnVsZXM+DQoJCQkJPC9Qcm9kdWN0Pg0KCQkJCTxQcm9kdWN0IG5hbWU9IlBhbGwiIGNvbmNlcHRpZD0iNzA4IiBjb21tZW50PSJHQiIgcm Fuaz0iNTAiPg0KCQkJCQk8UG9zdGNvZGVWYWxpZGF0aW9ucz4NCgkJCQkJCTxQb3N0Y29kZVZhbGlkYXRpb24gY291bnRyeT0iTk8iIGV4Y2x1ZGU9IjAiIHR5cGU9Ik5PIj4NCgkJCQkJCQk8UmFuZ2UgbWluPSIwNTU1IiBtYXg9IiIvPg0KCQkJCQkJPC9Qb3N0Y29kZVZhbGlkYXRpb24+DQoJCQkJCTwvUG9zdGNvZGVWYWxpZGF0aW9ucz4NCgkJCQkJPFZhbGlkYXRpb25SdWxlcz4NCgkJCQkJCTxWYWxpZGF0aW9uUnVsZSBuYW1lPSJjb3VudHJ5IiBhbGxvd2NvdW50cmllcz0iTk8iIGZpZWxkPSJmbGRfQWRyQ291bnRyeSIvPg0KCQkJCQk8L1ZhbGlkYXRpb25SdWxlcz4NCgkJCQk8L1Byb2R1Y3Q+DQoJCQk8L1Byb2R1Y3RzPg0KCQkJPEFsbG9jYXRpb25SdWxlcz4NCgkJCQk8QWxsb2NhdGlvblJ1bGUgdHlwZT0iaGlnaGVzdHJhbmsiLz4NCgkJCTwvQWxsb2NhdGlvblJ1bGVzPg0KCQk8L1NlcnZpY2VMZXZlbD4NCgk8L1NlcnZpY2VMZXZlbHM+DQo8L0NTUj4NCg&quot; } } | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDStacksGet**
> shipServerActorIDStacksGet($actor_id)

Get stacks

returns data on all stacks along with the carrier data which the stack belongs to.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#get_stacks\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID

try {
    $apiInstance->shipServerActorIDStacksGet($actor_id);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDStacksGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDStacksPost**
> shipServerActorIDStacksPost($actor_id, $body)

Create stack

Create new stack.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_stacks\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: {"data": {"StackName": "TestStack", "SubcarrierConceptID": 22},"options": {}}

try {
    $apiInstance->shipServerActorIDStacksPost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDStacksPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: {&quot;data&quot;: {&quot;StackName&quot;: &quot;TestStack&quot;, &quot;SubcarrierConceptID&quot;: 22},&quot;options&quot;: {}} | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDStacksShipmentsPatch**
> shipServerActorIDStacksShipmentsPatch($actor_id, $body)

Move shipments

Moves shipments to another stack.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#patch_stacks_shipments\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request PATCH: {"data":{"StackCSID":156,"ShipmentTags":["6D48DB14-5DA2-40EB-9383-FFDDE6347F4F"]},"options":{}}

try {
    $apiInstance->shipServerActorIDStacksShipmentsPatch($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDStacksShipmentsPatch: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request PATCH: {&quot;data&quot;:{&quot;StackCSID&quot;:156,&quot;ShipmentTags&quot;:[&quot;6D48DB14-5DA2-40EB-9383-FFDDE6347F4F&quot;]},&quot;options&quot;:{}} | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDStacksShipmentsPost**
> shipServerActorIDStacksShipmentsPost($actor_id, $body)

Get stackshipments

returns shipments from chosen stack/subcarrer/conceptid.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_stacks_shipments\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: {"data" : {"StackCSID": 133}} or {"data" : {"SubcarrierCSID": 12}} or {"data" : {"CarrierCSID": 22}} see doc in link

try {
    $apiInstance->shipServerActorIDStacksShipmentsPost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDStacksShipmentsPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: {&quot;data&quot; : {&quot;StackCSID&quot;: 133}} or {&quot;data&quot; : {&quot;SubcarrierCSID&quot;: 12}} or {&quot;data&quot; : {&quot;CarrierCSID&quot;: 22}} see doc in link | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDStacksStackIDDelete**
> shipServerActorIDStacksStackIDDelete($actor_id, $stack_id, $body)

Delete stack

Deletes stack by StackCSID. It is only possible to delete a stack that is empty (not containing any shipments).              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#del_stacks\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$stack_id = 56; // int | Stack ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Can be empty

try {
    $apiInstance->shipServerActorIDStacksStackIDDelete($actor_id, $stack_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDStacksStackIDDelete: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **stack_id** | **int**| Stack ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Can be empty | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDStacksStackIDManifestPut**
> shipServerActorIDStacksStackIDManifestPut($actor_id, $stack_id, $body)

Transmit stack

Transmit shipments from a stack              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#put_stacks_manifest\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$stack_id = 56; // int | Stack ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: { "data": { "StackCSID": "36437" }}

try {
    $apiInstance->shipServerActorIDStacksStackIDManifestPut($actor_id, $stack_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDStacksStackIDManifestPut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **stack_id** | **int**| Stack ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: { &quot;data&quot;: { &quot;StackCSID&quot;: &quot;36437&quot; }} | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDSubmitOrderPost**
> shipServerActorIDSubmitOrderPost($actor_id, $body)

Submit order

Submits an existing order; optionally it also creates a return label; prints the labels on a certain workstation.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_submitOrder\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: {"data":{"Kind":1,"ShpCSID":524,"OrderNo":"772157949528","Lines":[{"Length":150,"Height":100,"PkgWeight":130,"Width":100,"PkgVol":1500000,"Pkgs":[{"ItemNo":1,"PkgNo":""}]}],"DetailGroups":[{"GroupID":1,"Rows":[{"GoodsLineNo":1,"Details":[{"KindID":1,"Value":"2102421501404NYE460"},{"KindID":2,"Value":"4.24"},{"KindID":4,"Value":"CN"},{"KindID":5,"Value":"1"},{"KindID":6,"Value":".13"},{"KindID":7,"Value":"VL TONAL EMBROIDERY ENTRY TEE"},{"KindID":9,"Value":"1"},{"KindID":10,"Value":"34.99"},{"KindID":17,"Value":"EUR"},{"KindID":18,"Value":"6109100010"},{"KindID":186,"Value":"T.SHIRT"},{"KindID":192,"Value":"N"}]}]}],"Addresses":[{"Kind":1,"Name1":"AutoReceiver","Street1":"Street 10","PostCode":"0360","City":"OSLO","POPostCode":"0580","POCity":"OSLO","Phone":"67 06 49 91","Mobile":"12341234","Email":"a@noexitingqwerty.nnn","ContactCSID":5299935,"Fax":"67 06 49 92","CountryCode":"NO","Country":"NORWAY","CountryCodeISO3":"NOR","CountryISOID":578}],"References":[{"Kind":7,"Value":"ECOM12364313"}]},"options":{"ReturnShipmentServiceLevel":"Return","Labels":"PNG","UseCopy":0,"Visibility":"extended","ReturnShipmentFirst":0}}

try {
    $apiInstance->shipServerActorIDSubmitOrderPost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDSubmitOrderPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: {&quot;data&quot;:{&quot;Kind&quot;:1,&quot;ShpCSID&quot;:524,&quot;OrderNo&quot;:&quot;772157949528&quot;,&quot;Lines&quot;:[{&quot;Length&quot;:150,&quot;Height&quot;:100,&quot;PkgWeight&quot;:130,&quot;Width&quot;:100,&quot;PkgVol&quot;:1500000,&quot;Pkgs&quot;:[{&quot;ItemNo&quot;:1,&quot;PkgNo&quot;:&quot;&quot;}]}],&quot;DetailGroups&quot;:[{&quot;GroupID&quot;:1,&quot;Rows&quot;:[{&quot;GoodsLineNo&quot;:1,&quot;Details&quot;:[{&quot;KindID&quot;:1,&quot;Value&quot;:&quot;2102421501404NYE460&quot;},{&quot;KindID&quot;:2,&quot;Value&quot;:&quot;4.24&quot;},{&quot;KindID&quot;:4,&quot;Value&quot;:&quot;CN&quot;},{&quot;KindID&quot;:5,&quot;Value&quot;:&quot;1&quot;},{&quot;KindID&quot;:6,&quot;Value&quot;:&quot;.13&quot;},{&quot;KindID&quot;:7,&quot;Value&quot;:&quot;VL TONAL EMBROIDERY ENTRY TEE&quot;},{&quot;KindID&quot;:9,&quot;Value&quot;:&quot;1&quot;},{&quot;KindID&quot;:10,&quot;Value&quot;:&quot;34.99&quot;},{&quot;KindID&quot;:17,&quot;Value&quot;:&quot;EUR&quot;},{&quot;KindID&quot;:18,&quot;Value&quot;:&quot;6109100010&quot;},{&quot;KindID&quot;:186,&quot;Value&quot;:&quot;T.SHIRT&quot;},{&quot;KindID&quot;:192,&quot;Value&quot;:&quot;N&quot;}]}]}],&quot;Addresses&quot;:[{&quot;Kind&quot;:1,&quot;Name1&quot;:&quot;AutoReceiver&quot;,&quot;Street1&quot;:&quot;Street 10&quot;,&quot;PostCode&quot;:&quot;0360&quot;,&quot;City&quot;:&quot;OSLO&quot;,&quot;POPostCode&quot;:&quot;0580&quot;,&quot;POCity&quot;:&quot;OSLO&quot;,&quot;Phone&quot;:&quot;67 06 49 91&quot;,&quot;Mobile&quot;:&quot;12341234&quot;,&quot;Email&quot;:&quot;a@noexitingqwerty.nnn&quot;,&quot;ContactCSID&quot;:5299935,&quot;Fax&quot;:&quot;67 06 49 92&quot;,&quot;CountryCode&quot;:&quot;NO&quot;,&quot;Country&quot;:&quot;NORWAY&quot;,&quot;CountryCodeISO3&quot;:&quot;NOR&quot;,&quot;CountryISOID&quot;:578}],&quot;References&quot;:[{&quot;Kind&quot;:7,&quot;Value&quot;:&quot;ECOM12364313&quot;}]},&quot;options&quot;:{&quot;ReturnShipmentServiceLevel&quot;:&quot;Return&quot;,&quot;Labels&quot;:&quot;PNG&quot;,&quot;UseCopy&quot;:0,&quot;Visibility&quot;:&quot;extended&quot;,&quot;ReturnShipmentFirst&quot;:0}} | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDTimeSlotAllocationsPost**
> shipServerActorIDTimeSlotAllocationsPost($actor_id, $body)

Time slot allocations

Allocate a specific time slot.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_timeSlotAllocations\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: {"data":{"Addresses":[{"Kind":1,"Name1":"Test Receiver","Street1":"Street 10","PostCode":"11848","City":"Göteborg","CustNo":"5","Phone":"004007123456","Mobile":"00000000","CountryCode":"SE","Email":"a@noexitingqwerty.nnn","Country":"Sweden","ERPRef":"5"},{"Kind":10,"Name1":"Sender Test","Street1":"Street 10","PostCode":"43891","Mobile":"00000000","Phone":"004007123456","City":"Landvetter","CustNo":"3425964","CountryCode":"SE","Country":"Sweden","Email":"a@noexitingqwerty.nnn"}],"Lines":[{"LineWeight":4000,"PkgWeight":4000,"Width":10,"Height":400,"Length":10,"Pkgs":[{"ItemNo":3}],"References":[{"Kind":23,"Value":"cool stuff"}]}]},"options":{"Token":"_-1_0_7892_7961_4593_5599_0_0__0__12/30/1899_12/30/1899_TimeSlots__","TimeSlotToken":"..."}}

try {
    $apiInstance->shipServerActorIDTimeSlotAllocationsPost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDTimeSlotAllocationsPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: {&quot;data&quot;:{&quot;Addresses&quot;:[{&quot;Kind&quot;:1,&quot;Name1&quot;:&quot;Test Receiver&quot;,&quot;Street1&quot;:&quot;Street 10&quot;,&quot;PostCode&quot;:&quot;11848&quot;,&quot;City&quot;:&quot;Göteborg&quot;,&quot;CustNo&quot;:&quot;5&quot;,&quot;Phone&quot;:&quot;004007123456&quot;,&quot;Mobile&quot;:&quot;00000000&quot;,&quot;CountryCode&quot;:&quot;SE&quot;,&quot;Email&quot;:&quot;a@noexitingqwerty.nnn&quot;,&quot;Country&quot;:&quot;Sweden&quot;,&quot;ERPRef&quot;:&quot;5&quot;},{&quot;Kind&quot;:10,&quot;Name1&quot;:&quot;Sender Test&quot;,&quot;Street1&quot;:&quot;Street 10&quot;,&quot;PostCode&quot;:&quot;43891&quot;,&quot;Mobile&quot;:&quot;00000000&quot;,&quot;Phone&quot;:&quot;004007123456&quot;,&quot;City&quot;:&quot;Landvetter&quot;,&quot;CustNo&quot;:&quot;3425964&quot;,&quot;CountryCode&quot;:&quot;SE&quot;,&quot;Country&quot;:&quot;Sweden&quot;,&quot;Email&quot;:&quot;a@noexitingqwerty.nnn&quot;}],&quot;Lines&quot;:[{&quot;LineWeight&quot;:4000,&quot;PkgWeight&quot;:4000,&quot;Width&quot;:10,&quot;Height&quot;:400,&quot;Length&quot;:10,&quot;Pkgs&quot;:[{&quot;ItemNo&quot;:3}],&quot;References&quot;:[{&quot;Kind&quot;:23,&quot;Value&quot;:&quot;cool stuff&quot;}]}]},&quot;options&quot;:{&quot;Token&quot;:&quot;_-1_0_7892_7961_4593_5599_0_0__0__12/30/1899_12/30/1899_TimeSlots__&quot;,&quot;TimeSlotToken&quot;:&quot;...&quot;}} | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDTimeSlotsPost**
> shipServerActorIDTimeSlotsPost($actor_id, $body)

Get time slots

Return available time slots for a product.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_timeSlots\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: {"data":{"ProdConceptID":5799,"Addresses":[{"Kind":1,"Name1":"Test ","Attention":"Test","Street1":"Street 10","PostCode":"0580","City":"OSLO","CountryCode":"NO","Email":"a@noexitingqwerty.nnn","Phone":"00000000"},{"Kind":2,"Attention":"Att Sender","Name1":"Sender for all","Street1":"Street 10","PostCode":"0192","City":"OSLO","Phone":"004007123456","Email":"a@noexitingqwerty.nnn","CountryCode":"NO"}],"Lines":[{"LineWeight":4000,"PkgWeight":4000,"Width":10,"Height":400,"Length":10,"Pkgs":[{"ItemNo":3}],"References":[{"Kind":23,"Value":"cool stuff"}]}]},"options":{"EarliestPickup":"2021-06-16T06:00","LatestPickup":"2021-06-16T21:00","TimeLog":1}}

try {
    $apiInstance->shipServerActorIDTimeSlotsPost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDTimeSlotsPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: {&quot;data&quot;:{&quot;ProdConceptID&quot;:5799,&quot;Addresses&quot;:[{&quot;Kind&quot;:1,&quot;Name1&quot;:&quot;Test &quot;,&quot;Attention&quot;:&quot;Test&quot;,&quot;Street1&quot;:&quot;Street 10&quot;,&quot;PostCode&quot;:&quot;0580&quot;,&quot;City&quot;:&quot;OSLO&quot;,&quot;CountryCode&quot;:&quot;NO&quot;,&quot;Email&quot;:&quot;a@noexitingqwerty.nnn&quot;,&quot;Phone&quot;:&quot;00000000&quot;},{&quot;Kind&quot;:2,&quot;Attention&quot;:&quot;Att Sender&quot;,&quot;Name1&quot;:&quot;Sender for all&quot;,&quot;Street1&quot;:&quot;Street 10&quot;,&quot;PostCode&quot;:&quot;0192&quot;,&quot;City&quot;:&quot;OSLO&quot;,&quot;Phone&quot;:&quot;004007123456&quot;,&quot;Email&quot;:&quot;a@noexitingqwerty.nnn&quot;,&quot;CountryCode&quot;:&quot;NO&quot;}],&quot;Lines&quot;:[{&quot;LineWeight&quot;:4000,&quot;PkgWeight&quot;:4000,&quot;Width&quot;:10,&quot;Height&quot;:400,&quot;Length&quot;:10,&quot;Pkgs&quot;:[{&quot;ItemNo&quot;:3}],&quot;References&quot;:[{&quot;Kind&quot;:23,&quot;Value&quot;:&quot;cool stuff&quot;}]}]},&quot;options&quot;:{&quot;EarliestPickup&quot;:&quot;2021-06-16T06:00&quot;,&quot;LatestPickup&quot;:&quot;2021-06-16T21:00&quot;,&quot;TimeLog&quot;:1}} | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDValidRoutesPost**
> shipServerActorIDValidRoutesPost($actor_id, $body)

Check sender/receiver addresses.

Check if sender and receiver addresses are valid for product              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_valideRoutes\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST:    { "data": { "Kind": 1, "ProdConceptID": 2816, "Addresses": [ { "Kind": 1, "Name1": "Name Receiver", "Street1": "Street 10", "PostCode": "11848", "City": "Göteborg", "Mobile": "00000000", "CountryCode": "SE", "Email": "a@noexitingqwerty.nnn" }, { "Kind": 2, "Name1": "Name sender", "Street1": "Street 10", "PostCode": "11848", "City": "Göteborg", "Mobile": "00000000", "CountryCode": "SE", "Email": "a@noexitingqwerty.nnn" } ] } }

try {
    $apiInstance->shipServerActorIDValidRoutesPost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDValidRoutesPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST:    { &quot;data&quot;: { &quot;Kind&quot;: 1, &quot;ProdConceptID&quot;: 2816, &quot;Addresses&quot;: [ { &quot;Kind&quot;: 1, &quot;Name1&quot;: &quot;Name Receiver&quot;, &quot;Street1&quot;: &quot;Street 10&quot;, &quot;PostCode&quot;: &quot;11848&quot;, &quot;City&quot;: &quot;Göteborg&quot;, &quot;Mobile&quot;: &quot;00000000&quot;, &quot;CountryCode&quot;: &quot;SE&quot;, &quot;Email&quot;: &quot;a@noexitingqwerty.nnn&quot; }, { &quot;Kind&quot;: 2, &quot;Name1&quot;: &quot;Name sender&quot;, &quot;Street1&quot;: &quot;Street 10&quot;, &quot;PostCode&quot;: &quot;11848&quot;, &quot;City&quot;: &quot;Göteborg&quot;, &quot;Mobile&quot;: &quot;00000000&quot;, &quot;CountryCode&quot;: &quot;SE&quot;, &quot;Email&quot;: &quot;a@noexitingqwerty.nnn&quot; } ] } } | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDVoidTimeSlotPost**
> shipServerActorIDVoidTimeSlotPost($actor_id, $body)

Void Time slot

Allocate time slot token.              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#post_voidTimeSlot\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: {"data":{"ProdCSID":113,"Addresses":[{"Kind":1,"Name1":"Test Receiver","Street1":"Street 10","PostCode":"11848","City":"Göteborg","CustNo":"5","Phone":"004007123456","Mobile":"00000000","CountryCode":"SE","Email":"a@noexitingqwerty.nnn","Country":"Sweden","ERPRef":"5"},{"Kind":10,"Name1":"Sender Test","Street1":"Street 10","PostCode":"43891","Mobile":"00000000","Phone":"004007123456","City":"Landvetter","CustNo":"3425964","CountryCode":"SE","Country":"Sweden","Email":"a@noexitingqwerty.nnn"}],"Lines":[{"LineWeight":4000,"PkgWeight":4000,"Width":10,"Height":400,"Length":10,"Pkgs":[{"ItemNo":3}],"References":[{"Kind":23,"Value":"cool stuff"}]}]},"options":{"Token":"-1_0_7892_7961_4593_5599_0_0__0__12/30/1899_12/30/1899_TimeSlots_","AllocatedTimeSlotToken":"..."}}

try {
    $apiInstance->shipServerActorIDVoidTimeSlotPost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDVoidTimeSlotPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: {&quot;data&quot;:{&quot;ProdCSID&quot;:113,&quot;Addresses&quot;:[{&quot;Kind&quot;:1,&quot;Name1&quot;:&quot;Test Receiver&quot;,&quot;Street1&quot;:&quot;Street 10&quot;,&quot;PostCode&quot;:&quot;11848&quot;,&quot;City&quot;:&quot;Göteborg&quot;,&quot;CustNo&quot;:&quot;5&quot;,&quot;Phone&quot;:&quot;004007123456&quot;,&quot;Mobile&quot;:&quot;00000000&quot;,&quot;CountryCode&quot;:&quot;SE&quot;,&quot;Email&quot;:&quot;a@noexitingqwerty.nnn&quot;,&quot;Country&quot;:&quot;Sweden&quot;,&quot;ERPRef&quot;:&quot;5&quot;},{&quot;Kind&quot;:10,&quot;Name1&quot;:&quot;Sender Test&quot;,&quot;Street1&quot;:&quot;Street 10&quot;,&quot;PostCode&quot;:&quot;43891&quot;,&quot;Mobile&quot;:&quot;00000000&quot;,&quot;Phone&quot;:&quot;004007123456&quot;,&quot;City&quot;:&quot;Landvetter&quot;,&quot;CustNo&quot;:&quot;3425964&quot;,&quot;CountryCode&quot;:&quot;SE&quot;,&quot;Country&quot;:&quot;Sweden&quot;,&quot;Email&quot;:&quot;a@noexitingqwerty.nnn&quot;}],&quot;Lines&quot;:[{&quot;LineWeight&quot;:4000,&quot;PkgWeight&quot;:4000,&quot;Width&quot;:10,&quot;Height&quot;:400,&quot;Length&quot;:10,&quot;Pkgs&quot;:[{&quot;ItemNo&quot;:3}],&quot;References&quot;:[{&quot;Kind&quot;:23,&quot;Value&quot;:&quot;cool stuff&quot;}]}]},&quot;options&quot;:{&quot;Token&quot;:&quot;-1_0_7892_7961_4593_5599_0_0__0__12/30/1899_12/30/1899_TimeSlots_&quot;,&quot;AllocatedTimeSlotToken&quot;:&quot;...&quot;}} | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **shipServerActorIDWaybillsPost**
> shipServerActorIDWaybillsPost($actor_id, $body)

Get waybills

Returns waybills              <a target=\"_blank\" href=\"https://helpcenter.nshift.com/hc/en-us/articles/4401176907676-Methods-Version-2-0#get_waybill\">See documentation</a>

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');
// Configure API key authorization: IdentityApiKey
$config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = Swagger\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');// Configure HTTP basic authorization: basic
$config = Swagger\Client\Configuration::getDefaultConfiguration()
              ->setUsername('YOUR_USERNAME')
              ->setPassword('YOUR_PASSWORD');


$apiInstance = new Swagger\Client\Api\ShipServerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$actor_id = 56; // int | Actor ID
$body = new \Swagger\Client\Model\RequestBody(); // \Swagger\Client\Model\RequestBody | Sample request POST: {"data": {"BookingNo": "255664","CustomsRefNo": "Norway","ContentsPallet": "","HalfPallet": "1","QuarterPallet": "","Oversize": "","Other": "","SendersPlace": "Hillerød","Date": "17.10.2016","Sender": "Test ApS, Frydenborgvej 32, 3400 Hillerød, Denmark","CustNo": "10432061","DestinationCountryTerminal": "Norway, POSTNORD","AgentNorge": "","AgentReceiver": "Test, 0484 Oslo, Norway","DestinationCountry": "Norway","BusinessBulksplit.ColliNo": "","BusinessBulksplit.TotalNetWeight": "","BusinessBulksplit.AddedServices.0.Type": "","BusinessBulksplit.AddedServices.0.ColliNo": "","BusinessBulksplit.AddedServices.1.Type": "","BusinessBulksplit.AddedServices.1.ColliNo": "","BusinessBulksplit.AddedServices.2.Type": "","BusinessBulksplit.AddedServices.2.ColliNo": "","BusinessBulksplit.AddedServices.3.Type": "","BusinessBulksplit.AddedServices.3.ColliNo": "","MyPackBulksplit.ColliNo": "29","MyPackBulksplit.TotalNetWeight": "13","MyPackBulksplit.AddedServices.0.Type": "","MyPackBulksplit.AddedServices.0.ColliNo": "","MyPackBulksplit.AddedService.s1.Type": "","MyPackBulksplit.AddedServices.1.ColliNo": "","MyPackBulksplit.AddedServices.2.Type": "","MyPackBulksplit.AddedServices.2.ColliNo": "","MyPackBulksplit.AddedServices.3.Type": "","MyPackBulksplit.AddedServices.3.ColliNo": "","Pallet.ColliNo": "","Pallet.TotalNetWeight": "","Pallet.AddedServices.0.Type": "","Pallet.AddedServices.0.ColliNo": "","Pallet.AddedServices.1.Type": "","Pallet.AddedServices.1.ColliNo": "","Pallet.AddedServices.2.Type": "","Pallet.AddedServices.2.ColliNo": "","Pallet.AddedServices.3.Type": "","Pallet.AddedServices.3.ColliNo": "","PackageIDPallet": "","BatchCSID": 4948000,"CountryCode": "NO"}}

try {
    $apiInstance->shipServerActorIDWaybillsPost($actor_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling ShipServerApi->shipServerActorIDWaybillsPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **actor_id** | **int**| Actor ID |
 **body** | [**\Swagger\Client\Model\RequestBody**](../Model/RequestBody.md)| Sample request POST: {&quot;data&quot;: {&quot;BookingNo&quot;: &quot;255664&quot;,&quot;CustomsRefNo&quot;: &quot;Norway&quot;,&quot;ContentsPallet&quot;: &quot;&quot;,&quot;HalfPallet&quot;: &quot;1&quot;,&quot;QuarterPallet&quot;: &quot;&quot;,&quot;Oversize&quot;: &quot;&quot;,&quot;Other&quot;: &quot;&quot;,&quot;SendersPlace&quot;: &quot;Hillerød&quot;,&quot;Date&quot;: &quot;17.10.2016&quot;,&quot;Sender&quot;: &quot;Test ApS, Frydenborgvej 32, 3400 Hillerød, Denmark&quot;,&quot;CustNo&quot;: &quot;10432061&quot;,&quot;DestinationCountryTerminal&quot;: &quot;Norway, POSTNORD&quot;,&quot;AgentNorge&quot;: &quot;&quot;,&quot;AgentReceiver&quot;: &quot;Test, 0484 Oslo, Norway&quot;,&quot;DestinationCountry&quot;: &quot;Norway&quot;,&quot;BusinessBulksplit.ColliNo&quot;: &quot;&quot;,&quot;BusinessBulksplit.TotalNetWeight&quot;: &quot;&quot;,&quot;BusinessBulksplit.AddedServices.0.Type&quot;: &quot;&quot;,&quot;BusinessBulksplit.AddedServices.0.ColliNo&quot;: &quot;&quot;,&quot;BusinessBulksplit.AddedServices.1.Type&quot;: &quot;&quot;,&quot;BusinessBulksplit.AddedServices.1.ColliNo&quot;: &quot;&quot;,&quot;BusinessBulksplit.AddedServices.2.Type&quot;: &quot;&quot;,&quot;BusinessBulksplit.AddedServices.2.ColliNo&quot;: &quot;&quot;,&quot;BusinessBulksplit.AddedServices.3.Type&quot;: &quot;&quot;,&quot;BusinessBulksplit.AddedServices.3.ColliNo&quot;: &quot;&quot;,&quot;MyPackBulksplit.ColliNo&quot;: &quot;29&quot;,&quot;MyPackBulksplit.TotalNetWeight&quot;: &quot;13&quot;,&quot;MyPackBulksplit.AddedServices.0.Type&quot;: &quot;&quot;,&quot;MyPackBulksplit.AddedServices.0.ColliNo&quot;: &quot;&quot;,&quot;MyPackBulksplit.AddedService.s1.Type&quot;: &quot;&quot;,&quot;MyPackBulksplit.AddedServices.1.ColliNo&quot;: &quot;&quot;,&quot;MyPackBulksplit.AddedServices.2.Type&quot;: &quot;&quot;,&quot;MyPackBulksplit.AddedServices.2.ColliNo&quot;: &quot;&quot;,&quot;MyPackBulksplit.AddedServices.3.Type&quot;: &quot;&quot;,&quot;MyPackBulksplit.AddedServices.3.ColliNo&quot;: &quot;&quot;,&quot;Pallet.ColliNo&quot;: &quot;&quot;,&quot;Pallet.TotalNetWeight&quot;: &quot;&quot;,&quot;Pallet.AddedServices.0.Type&quot;: &quot;&quot;,&quot;Pallet.AddedServices.0.ColliNo&quot;: &quot;&quot;,&quot;Pallet.AddedServices.1.Type&quot;: &quot;&quot;,&quot;Pallet.AddedServices.1.ColliNo&quot;: &quot;&quot;,&quot;Pallet.AddedServices.2.Type&quot;: &quot;&quot;,&quot;Pallet.AddedServices.2.ColliNo&quot;: &quot;&quot;,&quot;Pallet.AddedServices.3.Type&quot;: &quot;&quot;,&quot;Pallet.AddedServices.3.ColliNo&quot;: &quot;&quot;,&quot;PackageIDPallet&quot;: &quot;&quot;,&quot;BatchCSID&quot;: 4948000,&quot;CountryCode&quot;: &quot;NO&quot;}} | [optional]

### Return type

void (empty response body)

### Authorization

[IdentityApiKey](../../README.md#IdentityApiKey), [basic](../../README.md#basic)

### HTTP request headers

 - **Content-Type**: application/json, text/json, application/_*+json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

