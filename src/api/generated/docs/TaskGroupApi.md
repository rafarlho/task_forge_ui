# TaskGroupApi

All URIs are relative to *https://localhost:7003*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**apiTaskGroupGet**](TaskGroupApi.md#apitaskgroupget) | **GET** /api/TaskGroup |  |
| [**apiTaskGroupIdGet**](TaskGroupApi.md#apitaskgroupidget) | **GET** /api/TaskGroup/{id} |  |
| [**apiTaskGroupPost**](TaskGroupApi.md#apitaskgrouppost) | **POST** /api/TaskGroup |  |
| [**apiTaskGroupPut**](TaskGroupApi.md#apitaskgroupput) | **PUT** /api/TaskGroup |  |



## apiTaskGroupGet

> Array&lt;TaskGroupResponseDto&gt; apiTaskGroupGet()



### Example

```ts
import {
  Configuration,
  TaskGroupApi,
} from '';
import type { ApiTaskGroupGetRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new TaskGroupApi();

  try {
    const data = await api.apiTaskGroupGet();
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

[**Array&lt;TaskGroupResponseDto&gt;**](TaskGroupResponseDto.md)

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


## apiTaskGroupIdGet

> TaskGroupResponseDto apiTaskGroupIdGet(id)



### Example

```ts
import {
  Configuration,
  TaskGroupApi,
} from '';
import type { ApiTaskGroupIdGetRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new TaskGroupApi();

  const body = {
    // string
    id: 38400000-8cf0-11bd-b23e-10b96e4ef00d,
  } satisfies ApiTaskGroupIdGetRequest;

  try {
    const data = await api.apiTaskGroupIdGet(body);
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

[**TaskGroupResponseDto**](TaskGroupResponseDto.md)

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


## apiTaskGroupPost

> TaskGroupResponseDto apiTaskGroupPost(createTaskGroupDto)



### Example

```ts
import {
  Configuration,
  TaskGroupApi,
} from '';
import type { ApiTaskGroupPostRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new TaskGroupApi();

  const body = {
    // CreateTaskGroupDto
    createTaskGroupDto: ...,
  } satisfies ApiTaskGroupPostRequest;

  try {
    const data = await api.apiTaskGroupPost(body);
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
| **createTaskGroupDto** | [CreateTaskGroupDto](CreateTaskGroupDto.md) |  | |

### Return type

[**TaskGroupResponseDto**](TaskGroupResponseDto.md)

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


## apiTaskGroupPut

> TaskGroupResponseDto apiTaskGroupPut(updateTaskGroupDto)



### Example

```ts
import {
  Configuration,
  TaskGroupApi,
} from '';
import type { ApiTaskGroupPutRequest } from '';

async function example() {
  console.log("🚀 Testing  SDK...");
  const api = new TaskGroupApi();

  const body = {
    // UpdateTaskGroupDto
    updateTaskGroupDto: ...,
  } satisfies ApiTaskGroupPutRequest;

  try {
    const data = await api.apiTaskGroupPut(body);
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
| **updateTaskGroupDto** | [UpdateTaskGroupDto](UpdateTaskGroupDto.md) |  | |

### Return type

[**TaskGroupResponseDto**](TaskGroupResponseDto.md)

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

