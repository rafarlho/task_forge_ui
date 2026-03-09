
# TaskResponseDto


## Properties

Name | Type
------------ | -------------
`id` | string
`taskGroupId` | string
`name` | string
`description` | string
`stationName` | string
`assignee` | string
`createdAt` | Date
`updatedAt` | Date
`status` | number
`version` | string

## Example

```typescript
import type { TaskResponseDto } from ''

// TODO: Update the object below with actual values
const example = {
  "id": null,
  "taskGroupId": null,
  "name": null,
  "description": null,
  "stationName": null,
  "assignee": null,
  "createdAt": null,
  "updatedAt": null,
  "status": null,
  "version": null,
} satisfies TaskResponseDto

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as TaskResponseDto
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


