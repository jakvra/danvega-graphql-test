# Spring for GraphQL CRUD + Testing

This repository contains code for the following YouTube videos: 

- [GraphQL CRUD Java](https://youtu.be/AgSO3rcSuHE)
- [GraphQL API Testing](https://youtu.be/0b0x3C_BTT8)


```graphql
query all {
  findAll {
    id
    name
    size
  }
}

query byId {
  findOne(id:2) {
    id
    name
    size
  }
}

mutation create {
  create(name:"jacobs new coffee", size:VENTI) {
    id
    name
    size
  }
}

mutation update {
  update(id: 4, name:"jacobs updated coffee", size:TALL) {
    id
    name
    size
  }
}

mutation delete {
  delete(id: 4) {
    id
    name
    size
  }
}
```