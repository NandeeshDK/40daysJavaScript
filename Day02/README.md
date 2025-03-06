# Variables in JavaScript  

Variables in JavaScript are used to store and manage data. They can hold different types of values such as numbers, strings, objects, or functions. JavaScript provides three ways to declare variables:  

- **var** – can be re-declared or updated usually not recommended.
 var x = 10;
 var x = 11; 
- **let** – can be updated but not re-declared within the same function.
  let x=10;
  let x=11; is not correct 
- **const** – cannot be re-declared or updated after assignment.  
  const x=10;
  const x=20; is not correct
## Example  

```javascript
var x = 10;  // Function-scoped  
let y = 20;  // Block-scoped  
const z = 30; // Cannot be reassigned  
