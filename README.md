# js-practice
#### Symbols
**{}** => Braces__
**[]** => Brackets or Square brackets__
**()** => Parantheses



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
#### Checking weather the given number is even or odd
```javascript
function return1(){
  var a = 4;
if(a%2==0){
    return("Even")
} else {
    return("Not an Even")
}  
}
```
