# Problem 1: Number Swapping

## Question: Swap two numbers using two variables (with let and Array Destructuring) 
###  Solution
```javascript

let a = 5;
let b = 10;

[a, b] = [b, a];

console.log(a);
console.log(b);

```


# Problem 2 
## Question: Take input from the user and check that prime or not prime



### Solution:

```javascript
function isPrime(num) {
  if (num <= 1) return false;
  for (let i = 2; i < Math.sqrt(num); i++) {
    if (num % i === 0) return false;
  }
  return true;
}
```

# Problem 3 :
## Question: Take input from the user and check the palindrome or not

### Solution:

```javascript
function isPalindrome(str) {
  const reversed = str.split('').reverse().join('');
  return str === reversed;
}
```

# Problem 4:
## Question: Take an array as an input and find out the largest number from the array 

### Solution:

```javascript
function findLargest(arr) {
  return Math.max(...arr);
}

```


# Problem 5:
## Question: Take a array as an input and remove duplicates from an array

### Solution: 

```javascript
function removeDuplicates(arr) {
  return [...new Set(arr)];
}

```


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
