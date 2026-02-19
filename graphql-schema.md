# GraphQL Schema

## Type Definitions

```graphql
type User {
  id: ID!
  name: String!
  email: String!
}
```

## Query Definitions

```graphql
type Query {
  users: [User]
  user(id: ID!): User
}
```

## Example Query

```graphql
query {
  users {
    id
    name
  }
}
```
