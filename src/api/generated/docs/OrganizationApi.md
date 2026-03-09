# OrganizationApi

All URIs are relative to *https://localhost:7003*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**apiOrganizationGet**](OrganizationApi.md#apiorganizationget) | **GET** /api/Organization |  |
| [**apiOrganizationIdGet**](OrganizationApi.md#apiorganizationidget) | **GET** /api/Organization/{id} |  |
| [**apiOrganizationPost**](OrganizationApi.md#apiorganizationpost) | **POST** /api/Organization |  |
| [**apiOrganizationPut**](OrganizationApi.md#apiorganizationput) | **PUT** /api/Organization |  |
| [**apiOrganizationWithTaskGroupsIdGet**](OrganizationApi.md#apiorganizationwithtaskgroupsidget) | **GET** /api/Organization/withTaskGroups/{id} |  |



## apiOrganizationGet

> Array&lt;OrganizationResponseDto&gt; apiOrganizationGet()



### Example

```ts
import {
  Configuration,
  OrganizationApi,
} from '';
import type { ApiOrganizationGetRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new OrganizationApi();

  try {
    const data = await api.apiOrganizationGet();
    console.log(data);
  } catch (error) {
    console.error(error);
  }
}

// Run the test
example().catch(console.error);
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**Array&lt;OrganizationResponseDto&gt;**](OrganizationResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `text/plain`, `application/json`, `text/json`


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | OK |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


## apiOrganizationIdGet

> OrganizationResponseDto apiOrganizationIdGet(id)



### Example

```ts
import {
  Configuration,
  OrganizationApi,
} from '';
import type { ApiOrganizationIdGetRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new OrganizationApi();

  const body = {
    // string
    id: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
  } satisfies ApiOrganizationIdGetRequest;

  try {
    const data = await api.apiOrganizationIdGet(body);
    console.log(data);
  } catch (error) {
    console.error(error);
  }
}

// Run the test
example().catch(console.error);
```

### Parameters


| Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | `string` |  | [Defaults to `undefined`] |

### Return type

[**OrganizationResponseDto**](OrganizationResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `text/plain`, `application/json`, `text/json`


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | OK |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


## apiOrganizationPost

> OrganizationResponseDto apiOrganizationPost(createOrganizationDto)



### Example

```ts
import {
  Configuration,
  OrganizationApi,
} from '';
import type { ApiOrganizationPostRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new OrganizationApi();

  const body = {
    // CreateOrganizationDto
    createOrganizationDto: ...,
  } satisfies ApiOrganizationPostRequest;

  try {
    const data = await api.apiOrganizationPost(body);
    console.log(data);
  } catch (error) {
    console.error(error);
  }
}

// Run the test
example().catch(console.error);
```

### Parameters


| Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **createOrganizationDto** | [CreateOrganizationDto](CreateOrganizationDto.md) |  | |

### Return type

[**OrganizationResponseDto**](OrganizationResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`, `text/json`, `application/*+json`
- **Accept**: `text/plain`, `application/json`, `text/json`


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | OK |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


## apiOrganizationPut

> OrganizationResponseDto apiOrganizationPut(updateOrganizationDto)



### Example

```ts
import {
  Configuration,
  OrganizationApi,
} from '';
import type { ApiOrganizationPutRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new OrganizationApi();

  const body = {
    // UpdateOrganizationDto
    updateOrganizationDto: ...,
  } satisfies ApiOrganizationPutRequest;

  try {
    const data = await api.apiOrganizationPut(body);
    console.log(data);
  } catch (error) {
    console.error(error);
  }
}

// Run the test
example().catch(console.error);
```

### Parameters


| Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **updateOrganizationDto** | [UpdateOrganizationDto](UpdateOrganizationDto.md) |  | |

### Return type

[**OrganizationResponseDto**](OrganizationResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`, `text/json`, `application/*+json`
- **Accept**: `text/plain`, `application/json`, `text/json`


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | OK |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


## apiOrganizationWithTaskGroupsIdGet

> Array&lt;OrganizationResponseDto&gt; apiOrganizationWithTaskGroupsIdGet(id)



### Example

```ts
import {
  Configuration,
  OrganizationApi,
} from '';
import type { ApiOrganizationWithTaskGroupsIdGetRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new OrganizationApi();

  const body = {
    // string
    id: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
  } satisfies ApiOrganizationWithTaskGroupsIdGetRequest;

  try {
    const data = await api.apiOrganizationWithTaskGroupsIdGet(body);
    console.log(data);
  } catch (error) {
    console.error(error);
  }
}

// Run the test
example().catch(console.error);
```

### Parameters


| Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **id** | `string` |  | [Defaults to `undefined`] |

### Return type

[**Array&lt;OrganizationResponseDto&gt;**](OrganizationResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `text/plain`, `application/json`, `text/json`


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | OK |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)

