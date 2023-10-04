# Array_methods

1. push(): This method adds one or more elements to the end of an array.

 ```
const fruits = ['apple', 'banana'];
fruits.push('cherry', 'date');
console.log(fruits); // Output: ['apple', 'banana', 'cherry', 'date']
```

2. pop(): This method removes the last element from an array and returns it.

```
const fruits = ['apple', 'banana', 'cherry'];
const lastFruit = fruits.pop();
console.log(lastFruit); // Output: 'cherry'
console.log(fruits); // Output: ['apple', 'banana']
```

3. shift(): This method removes the first element from an array and returns it.

```
const fruits = ['apple', 'banana', 'cherry'];
const firstFruit = fruits.shift();
console.log(firstFruit); // Output: 'apple'
console.log(fruits); // Output: ['banana', 'cherry']
```

4. unshift(): This method adds one or more elements to the beginning of an array.

```
const fruits = ['banana', 'cherry'];
fruits.unshift('apple', 'date');
console.log(fruits); // Output: ['apple', 'date', 'banana', 'cherry']
```

5. concat(): This method combines two or more arrays to create a new array.

```
const fruits = ['apple', 'banana'];
const moreFruits = ['cherry', 'date'];
const allFruits = fruits.concat(moreFruits);
console.log(allFruits); // Output: ['apple', 'banana', 'cherry', 'date']
```

6. slice(): This method extracts a portion of an array into a new array without modifying the original.

```
const fruits = ['apple', 'banana', 'cherry', 'date'];
const selectedFruits = fruits.slice(1, 3); // Elements at index 1 and 2 (exclusive of 3)
console.log(selectedFruits); // Output: ['banana', 'cherry']
```

7. forEach(): This method iterates through each element in the array and applies a function to each element.

```
const numbers = [1, 2, 3, 4, 5];
numbers.forEach((number) => {
  console.log(number * 2); // Output: 2, 4, 6, 8, 10
});
```

8. map(): This method creates a new array by applying a function to each element in the original array.

```
const numbers = [1, 2, 3, 4, 5];
const doubledNumbers = numbers.map((number) => number * 2);
console.log(doubledNumbers); // Output: [2, 4, 6, 8, 10]
```

9. splice(): This method allows you to modify an array by adding, removing, or replacing elements at a specific index.

```
const fruits = ['apple', 'banana', 'cherry', 'date'];

// Remove 'cherry' and 'date' from index 2, then add 'grape' and 'kiwi' in their place
const removedFruits = fruits.splice(2, 2, 'grape', 'kiwi');

console.log(removedFruits); // Output: ['cherry', 'date']
console.log(fruits); // Output: ['apple', 'banana', 'grape', 'kiwi']
```

10. indexOf(): This method returns the first index at which a specified element is found in an array. If the element is not found, it returns -1.

```
const fruits = ['apple', 'banana', 'cherry'];
const index = fruits.indexOf('banana');
console.log(index); // Output: 1
```

11. lastIndexOf(): Similar to indexOf(), but it returns the last index at which a specified element is found in an array.

```
const fruits = ['apple', 'banana', 'cherry', 'banana'];
const lastIndex = fruits.lastIndexOf('banana');
console.log(lastIndex); // Output: 3
```

12. filter(): This method creates a new array with all elements that pass a test implemented by a provided function.

```
const numbers = [1, 2, 3, 4, 5];
const evenNumbers = numbers.filter((number) => number % 2 === 0);
console.log(evenNumbers); // Output: [2, 4]
```

13. find(): This method returns the first element in an array that satisfies a provided testing function.


```
const users = [
  { name: 'Alice', age: 25 },
  { name: 'Bob', age: 30 },
  { name: 'Charlie', age: 35 }
];

const user = users.find((user) => user.age === 30);
console.log(user); // Output: { name: 'Bob', age: 30 }
```

14. reduce(): This method reduces an array to a single value by applying a function to each element and accumulating the result.

```
const numbers = [1, 2, 3, 4, 5];
const sum = numbers.reduce((accumulator, currentValue) => accumulator + currentValue, 0);
console.log(sum); // Output: 15
```

15. sort(): This method sorts the elements of an array in place and returns the sorted array.

```
const fruits = ['banana', 'apple', 'cherry'];
fruits.sort();
console.log(fruits); // Output: ['apple', 'banana', 'cherry']
```

16. 
