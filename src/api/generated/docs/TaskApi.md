# TaskApi

All URIs are relative to *https://localhost:7003*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**apiTaskGet**](TaskApi.md#apitaskget) | **GET** /api/Task |  |
| [**apiTaskIdGet**](TaskApi.md#apitaskidget) | **GET** /api/Task/{id} |  |
| [**apiTaskPost**](TaskApi.md#apitaskpost) | **POST** /api/Task |  |
| [**apiTaskPut**](TaskApi.md#apitaskput) | **PUT** /api/Task |  |



## apiTaskGet

> Array&lt;TaskResponseDto&gt; apiTaskGet()



### Example

```ts
import {
  Configuration,
  TaskApi,
} from '';
import type { ApiTaskGetRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new TaskApi();

  try {
    const data = await api.apiTaskGet();
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

[**Array&lt;TaskResponseDto&gt;**](TaskResponseDto.md)

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


## apiTaskIdGet

> TaskResponseDto apiTaskIdGet(id)



### Example

```ts
import {
  Configuration,
  TaskApi,
} from '';
import type { ApiTaskIdGetRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new TaskApi();

  const body = {
    // string
    id: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
  } satisfies ApiTaskIdGetRequest;

  try {
    const data = await api.apiTaskIdGet(body);
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

[**TaskResponseDto**](TaskResponseDto.md)

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


## apiTaskPost

> TaskResponseDto apiTaskPost(createTaskDto)



### Example

```ts
import {
  Configuration,
  TaskApi,
} from '';
import type { ApiTaskPostRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new TaskApi();

  const body = {
    // CreateTaskDto
    createTaskDto: ...,
  } satisfies ApiTaskPostRequest;

  try {
    const data = await api.apiTaskPost(body);
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
| **createTaskDto** | [CreateTaskDto](CreateTaskDto.md) |  | |

### Return type

[**TaskResponseDto**](TaskResponseDto.md)

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


## apiTaskPut

> TaskResponseDto apiTaskPut(updateTaskDto)



### Example

```ts
import {
  Configuration,
  TaskApi,
} from '';
import type { ApiTaskPutRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new TaskApi();

  const body = {
    // UpdateTaskDto
    updateTaskDto: ...,
  } satisfies ApiTaskPutRequest;

  try {
    const data = await api.apiTaskPut(body);
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
| **updateTaskDto** | [UpdateTaskDto](UpdateTaskDto.md) |  | |

### Return type

[**TaskResponseDto**](TaskResponseDto.md)

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

