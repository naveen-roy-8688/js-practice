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
