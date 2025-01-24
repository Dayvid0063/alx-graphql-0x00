# GraphQL Character Queries

## Task 0: Get Specific Character by ID
Four queries to fetch individual character details using their IDs (1-4).
Each query retrieves:
- id
- name
- status
- species
- type
- gender

## Task 1: Get List of Characters
Four queries to fetch paginated lists of characters (pages 1-4).
Each query retrieves:
- id
- name
- status
- image

## File Structure
- `character-id-{n}.graphql`: Individual character queries
- `character-id-{n}-output.json`: Query results
- `characters-page-{n}.graphql`: Character list queries
- `characters-page-{n}-output.json`: Query results

## Project Structure
alx-graphql-0x00/
└── character/
    ├── README.md
    ├── character-id-1.graphql
    ├── character-id-1-output.json
    ├── character-id-2.graphql
    ├── character-id-2-output.json
    ├── character-id-3.graphql
    ├── character-id-3-output.json
    ├── character-id-4.graphql
    ├── character-id-4-output.json
    ├── characters-page-1.graphql
    ├── characters-page-1-output.json
    ├── characters-page-2.graphql
    ├── characters-page-2-output.json
    ├── characters-page-3.graphql
    ├── characters-page-3-output.json
    ├── characters-page-4.graphql
    └── characters-page-4-output.json

## Usage
Execute queries against the GraphQL endpoint using a GraphQL client.
