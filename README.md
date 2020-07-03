# Poke Graphql API

### Run Project

```
  yarn or npm install
  yarn start or npm start

```
### Querys

##### url
http://localhost:5001/graphiql

Query to return a pokemon
```graphql
{
  pokemon(id:4) {
    id
    name
  }
}
```

Query to return a pokemon list
```graphql
{
  pokemons {
    id
    name
  }
}
```
### Tests 
Run Tests
```
npm test or yarn test

```