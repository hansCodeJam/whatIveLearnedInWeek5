# What I've learned in week 5

### Javascript
- Booleans
  - Deals with True and False
  - && And
  - || OR

```Javascript
function alwaysTrue() {
    return true;
}

alwaysTrue(false, true, 34, 'string');
//true

function isTeacher(str){
    return str === 'teacher';
}

isTeacher('teacher');
//true
```

- Ternary
  - shorter version of if-else statement
```Javascript
let drinkingAge = 21;
let age = 26;

function bev(){
    let beverage = (age >= drinkingAge) ? "Beer" : "Juice";
    console.log(beverage);
    //Beer
}
```

- We practiced more on if-else statement with string.length
```Javascript
function howLongIsMyString(str) {
  if(str.length > 20) {
    return "That's a long string!"
  } else if (str.length === 20) {
    return "That's a regular sized string!"
  } else if (str.length === 10) {
    return "That's a regular sized string!"
  } else if (str.length < 10) {
    return "That's a small string!"
  }
}

console.log(howLongIsMyString(9))
//That's a small string
```