
# Javascript blogs
Includes basic non-intuitive and advanced concepts

## Basics
### Types in javascript
- Javascript has types for only values not for variables
  - Explicit coercion (type casting in other languages)
    ```
    var age = 40; //type is Number
    age = String(40) //explicit type
    ```
  - Implicit coercion
    ```
    var age = 40; //type is Number
    age = 40 + "" //implicit type
    ```
- Falsy values in javascript
  `0, -0, NaN, "", false, undefined, null`
