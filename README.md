# graphqldemo

This demo is from blog:  https://developer.okta.com/blog/2020/01/31/java-graphql

# Start the server

./mvnw spring-boot:run

or from STS :  Run As ->  Spring Boot App


http://localhost:8080/gui

# Queries and mutations

```
{
  foods {
    id
    name
    isGood
  }
}
```