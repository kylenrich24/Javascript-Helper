# 🗒️ Javascript 🗒️

✔️ lightweight - doesn't eat much memory and has simple syntax/features<br>
✔️ cross-platform - can be used dynamically and not just on web development<br>
✔️ object-oriented - based on object type of programming<br>

<br>

## ❗ Variables

### 🔔 Data Types
- number (always floating)<br>
- string<br>
- boolean<br>
- undefined(no value in declaration)<br>
- null<br>  

🔆 These are <strong>Primitive</strong>. They are the only data types that are not objects in Javascript.<br>
✔️ Dynamic Typing - we don't have to define the datatype of a variable when declaring it<br>
✔️ Mutation - the important concept of variables is that we can change/mutate its value<br>
✔️ Coercion - JS converts the variable data type as needed<br>

```javascript
const number = 1  // we can't mutate a const, js will throw an error

// const and let are block scoped (i.e {}, if, for, while
// const and let are not hoisted
{
 const secret = "no access"
 let anotherSecret = "password"
}

// we can't access secret and anotherSecret here
```
