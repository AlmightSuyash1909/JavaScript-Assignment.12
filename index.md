   #### 🥇What's the output of the following, write the output next to the code as comment.

  ## Logical AND operation

```js
true && true; // true

true && false; // false

false && true; // false

false && false; // false

"foo" && "bar"; // "bar"

"bar" && "foo"; // "foo"
 
"foo" && ""; // ""

"" && "foo"; // ""

" " && "John" && "" && false; // ""

false && "Hey" && undefined; // false

"undefined" && false && 42; // false
```
 
  ## Logical OR operation

```js
true || true; // true

true || false; // true

false || true; // true

false || false; // false

"foo" || "bar"; // "foo"

"bar" || "foo"; // "bar"

"foo" || ""; // "foo"

"" || "foo"; // "foo"

" " || "John" || "" || false; // " " 

false || "Hey" || undefined; // "hey"

"undefined" || false || 42; // "undefined"
```

  ## Write the output of the code next to each line:

```js
let a = 5,

  b = 10;
(a != b) && (a < b); //  true

(a > b) || (a == b); // false

(a < b) || (a == b); // true
 
!(a < b); // false

!(a > b); // true

!!a; // true

!!(a>b); // false
```