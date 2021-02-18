# REACT NOTES

## STRICT RULE OF REACT
- all react components must act like pure functions with respect to their props

### PURE FUNCTION
```js
funtion (a,b) {
  return a + b;
}

```

### IMPURE FUNCTION
```js
function (account, ammount) {
  account.total -= ammount
}
```
