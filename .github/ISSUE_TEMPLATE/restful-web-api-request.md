---
name: RESTful Web API request
about: Create a document to create API
title: "[API]"
labels: feature
assignees: ''

---

## Is your feature request related to a problem?
I want to get a user by email.

Because...

## Expected Request
Endpoint: `/users?email=[email]`
Method: GET
Credential: true

## Expected Response
Status Code: 200
Result:
```typescript
// User DTO or at least I need the following  data
type User = {
id: UUID
name: string,
email: string
}
```

## Additional context

**Related PRs:**

**Related Issues:**
