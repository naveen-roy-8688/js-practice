# js-practice
Practical programs

### List of practiced programs

#### Check weather the given number is Palindrome or Not
```javascript
    function checkPalindrome(param){
        if(param ===[...param].reverse().join('')){
            console.log("Palindrome")
        } else {
            console.log("Not a palindrome")
        }
    }

  // Calling a function
  checkPalindrome(prompt("Enter a string to check weather it is palindrome or not ?"))
```

#### Check weather the given number is Prime or not
```javascript
// Check weather the given number is prime or not
    function checkPrime(num){
        var count=0;
        for(var i=1; i<=num; i++){
            if(num%i === 0 ){
                count=count+1
            }
        }
    
        if(count === 2){
            return true;
        } else {
            return false;
        }
    }
```

#### Check Factorial
```javascript
    function findFactorial(inputNum){
    var fact=1;
    for(var i=1; i<=inputNum; i++){
        fact*=i
    }

    console.log(fact)
}

// Calling the above funvtion
findFactorial(Number(prompt("Enter a number to check fact of it")))

findFactorial(5)
```
