# GraphQL Character Queries

## Overview
This project demonstrates how to query data from the **Rick and Morty GraphQL API** using the `character(id: ID!)` field.  
Each query retrieves details of a specific character by their ID.

## API Endpoint
`https://rickandmortyapi.com/graphql`

## Fields Retrieved
- **id**
- **name**
- **status**
- **species**
- **type**
- **gender**

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
