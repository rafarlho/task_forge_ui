
# TaskGroupResponseDto


## Properties

Name | Type
------------ | -------------
`id` | string
`name` | string
`description` | string
`organizationId` | string
`tasks` | [Array&lt;TaskResponseDto&gt;](TaskResponseDto.md)
`createdAt` | Date
`updatedAt` | Date
`version` | string

## Example

```typescript
import type { TaskGroupResponseDto } from ''

// TODO: Update the object below with actual values
const example = {
  "id": null,
  "name": null,
  "description": null,
  "organizationId": null,
  "tasks": null,
  "createdAt": null,
  "updatedAt": null,
  "version": null,
} satisfies TaskGroupResponseDto

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as TaskGroupResponseDto
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


