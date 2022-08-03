# GraphQL 

### Run
> http://localhost:5000/graphql


### Query

```
{
    books {
        id,
        name
    },
    authors {
        id, 
        name
    },
    author(id: 1) {
        id,
        name
    }
}
// ...
```


### Mutation
```
{
    mutation {
        addBook(name: "The Godfather", authorId: 1) {
            id,
            name
        }
    }
}
```