
# OrganizationResponseDto


## Properties

Name | Type
------------ | -------------
`id` | string
`name` | string
`taskGroups` | [Array&lt;TaskGroupResponseDto&gt;](TaskGroupResponseDto.md)
`createdAt` | Date
`updatedAt` | Date
`status` | number
`version` | string

## Example

```typescript
import type { OrganizationResponseDto } from ''

// TODO: Update the object below with actual values
const example = {
  "id": null,
  "name": null,
  "taskGroups": null,
  "createdAt": null,
  "updatedAt": null,
  "status": null,
  "version": null,
} satisfies OrganizationResponseDto

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as OrganizationResponseDto
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


