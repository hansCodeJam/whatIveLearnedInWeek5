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
function isItMedium(str) {
    let length = str.length;
    if(length ===  10) {
        return 'That\'s a regular sized string!'
    } else if (length === 20) {
        return "That's a regular sized string!"
    }
}

console.log(itItMedium(15))
//That's a regular sized string
```