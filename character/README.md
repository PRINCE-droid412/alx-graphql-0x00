# Character Information Queries

This project contains GraphQL queries to retrieve specific character details from a GraphQL API using their IDs.

## Files
- `character-id-1.graphql` – Query for character with ID 1
- `character-id-2.graphql` – Query for character with ID 2
- `character-id-3.graphql` – Query for character with ID 3
- `character-id-4.graphql` – Query for character with ID 4

## Fields Retrieved
Each query retrieves:
- `id`
- `name`
- `status`
- `species`
- `type`
- `gender`

## Example Query
```graphql
query {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}

