
# CreateTaskDto


## Properties

Name | Type
------------ | -------------
`name` | string
`descrition` | string
`assignee` | string
`taskGroupId` | string

## Example

```typescript
import type { CreateTaskDto } from ''

// TODO: Update the object below with actual values
const example = {
  "name": null,
  "descrition": null,
  "assignee": null,
  "taskGroupId": null,
} satisfies CreateTaskDto

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as CreateTaskDto
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


