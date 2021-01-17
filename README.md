# graphqldemo

This demo is from blog:  https://developer.okta.com/blog/2020/01/31/java-graphql

# Start the server

./mvnw spring-boot:run

or from STS :  Run As ->  Spring Boot App


http://localhost:8080/gui

# Queries and mutations

get all foods
```
{
  foods {
    id
    name
    isGood
  }
}
```

You can also find a specific food by ID using a query like the following:
```

{ food(id: 1) { name } }

```

Create a new food by running the saveFood() mutation:
```
mutation {
  saveFood(food: { name: "Pasta" }) {
    id
    isGood
  }
}
```

