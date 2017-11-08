# Hey Arnold

```javascript
function salute (persona) {
  if (persona == { nombre: 'Silvester' }) {
    return 'hola Silvester'
  } else {
    return 'hola Arnold'
  }
}
salute({ nombre: 'Silvester' })
```
The code prints "hola Arnold" because JavaScript compare objects by reference not by value. 
The if conditional statement is comparing 2 different objects so the return of the function will always be 'hola Arnold'.



