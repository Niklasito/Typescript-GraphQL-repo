TO CREATE A FRUIT DO THE FOLLOWING:

```
mutation
{
createFruit(input: {
name: "Banana"
category: "berries"
}) {
category
name
id
}
}
```

TO GET ALL USERS DO THE FOLLOWING:

```
{
getFruits{
id
name
category
}
}
```
