# Character Query — Rick and Morty GraphQL API

## Objective
Write a GraphQL query to retrieve a specific character’s information using their ID.

## Endpoint
https://rickandmortyapi.com/graphql

## Query Fields
- id
- name
- status
- species
- type
- gender

## Files Included
- `character-id-1.graphql` & `character-id-1-output.json`
- `character-id-2.graphql` & `character-id-2-output.json`
- `character-id-3.graphql` & `character-id-3-output.json`
- `character-id-4.graphql` & `character-id-4-output.json`

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
```

## Expected Output
```json
{
  "data": {
    "character": {
      "id": "1",
      "name": "Rick Sanchez",
      "status": "Alive",
      "species": "Human",
      "type": "",
      "gender": "Male"
    }
  }
}
```
