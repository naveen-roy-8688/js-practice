# js-practice
#### Symbols
**{}** => Braces<br>
**[]** => Brackets or Square brackets<br>
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

### Reverse String 
```javascript
var reverseString="Vasant"
console.log(reverseString.split(''))
console.log(reverseString.split('').reverse())
console.log(reverseString.split('').reverse().join(''))
```

####forEach function in js
```javascript
var cars=["Maruti Suzuki","Tata, Hyundai","Mahindra","Kia"]
cars.forEach(function (index,values){
    console.log(values +"=>"+ index)
})
```
# All programs
```javascript
https://github.com/naveen-roy-8688/js-practice


function finsn(n){
    const sum = 0
    for (let i = 0; i <= n; i++ )
        sum = sum + i;
    return sum;
}finsn(5);

function findsum(n){

    const sum = 0;
    for (let i = 1; i <= n; i++)
        sum = sum + i;
    return sum;
} const n = 5;
console.log(findsum(5));
function findsum(n){

    let sum = 0;
    for (let i = 1; i <= n; i++)
        sum = sum + i;
    return sum;
} const n = 5;
console.log(findsum(5));

function fun23(name){
    return name
}
function fun24(name1){
    var ot=fun23("mass")
    console.log(ot+name1)
}fun24("vasanf")

function vasantrao(runnint){
    return runnint
}vasantrao("1")

var b = alert(":enter alert name");
console.log(b)

var a=prompt("enter yourname");
console.log(a)

function greet(){
    return("Statement-1")
    return("Statement-2")
    return("Statement-3")
}

function findSum(n) {
    let sum = 0;
    for (let i = 1; i <= n; i++)
        sum = sum + i;
    return sum;
}

// Driver code
const n = 5;
console.log(findSum(n));

var num1 = 2512;
// base 10 string representation
str_num1 = num1.toString(); // '2512'
console.log(str_num1);
typeof num1


var num3 = -5.645;var num1 = 2512;
// base 10 string representation
str_num1 = num1.toString(); // '2512'
console.log(str_num1);

// base 16 string representation
str_num1 = num1.toString(16); // '9d0'
console.log(str_num1);

var num2 = -10;
// base 2 string representation
// positive binary repr with negative sign rather than 2's complement
str_num2 = num2.toString(2); // '-1010'
str_num3 = num3.toString(); // '-5.645'
console.log(str_num3);

const number=prompt("enter number a number: ")
if (n %2==0){
    console.log("given number is even number");

}else{
    console.log("given number is odd number")
}
var n=9;
if (n %2==0){
    console.log("given number is even number");

}else{
    console.log("given number is odd number")
}

function return1(){
  var a = 4;
if(a%2==0){
    return("Even")
} else {
    return("Not an Even")
}  
}
a=window.prompt("Enter value")



sampleArray.forEach(function(){})
undefined
sampleArray.forEach(function(i,index){
    console.log(i+" => "+index)
})
VM3950:2 1 => 0
VM3950:2 2 => 1
VM3950:2 3 => 2
VM3950:2 Navin => 3
VM3950:2 false => 4
VM3950:2 ()=>{ return "Hi"} => 5
undefined
sampleArray.forEach(function(i,index,arrayElement){
    console.log(i+" => "+index+" => "+arrayElement)
})
VM4019:2 1 => 0 => 1,2,3,Navin,false,()=>{ return "Hi"}
VM4019:2 2 => 1 => 1,2,3,Navin,false,()=>{ return "Hi"}
VM4019:2 3 => 2 => 1,2,3,Navin,false,()=>{ return "Hi"}
VM4019:2 Navin => 3 => 1,2,3,Navin,false,()=>{ return "Hi"}
VM4019:2 false => 4 => 1,2,3,Navin,false,()=>{ return "Hi"}
VM4019:2 ()=>{ return "Hi"} => 5 => 1,2,3,Navin,false,()=>{ return "Hi"}



function return1(){
  var a = 4;
if(a%2==0){
    return("Even")
} else {
    return("Not an Even")
}  
}
var obj=return1()
console.log(obj)

function return1(){
  var a = prompt("Enter value")
if(a%2==0){
    return("Even")
} else {
    return("Not an Even")
}  
}
var obj=return1()
console.log(obj)

reverse string=>
______________
var a="vasanth"

a.split('').reverse().join('')
console.log(a)

array program=>
_____________
var cars=["nano","audi","benz","maruthi","toyoto"]
cars[0]

-----------
var s=[12,45,67,89,43,12,34,76,45,98,10,89,64,25,31,61]
for (i=0;i<s.length;i++){
    if(s[i]%2==0){
        console.log(s[i])
----------------------
arrow functons=>
var sum=(a,b)=>{
    console.log(a+b)
}
undefined
sum(2,3)


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

function test(a,b,c,d){
    return amigos[a*b+c-d]
}


// Filter prime numbers from an array
var sampleArray=[45, 85, 96, 75, 63, 21, 55, 62, 32, 23, 61, 77]
for(var i of sampleArray){
    if(checkPrime(i)){
        console.log(i)
    }
}

var str="Vasanth"
undefined
var str="Vasanth-S"
undefined
str.split('-')
(2) ['Vasanth', 'S']
var str="Vasanth"
undefined
console.log(str.split('').reverse().join(''))
VM5314:1 htnasaV
undefined
console.log([...str].reverse().join(''))
VM5343:1 htnasaV
[...str]
(7) ['V', 'a', 's', 'a', 'n', 't', 'h']
0
: 
"V"
1
: 
"a"
2
: 
"s"
3
: 
"a"
4
: 
"n"
5
: 
"t"
6
: 
"h"
length
: 
7
[[Prototype]]
: 
Array(0)

Palindrome:-
____________

function checkPalindrome(param){
    if(param ===[...param].reverse().join('')){
        console.log("Palindrome")
    } else {
        console.log("Not a palindrome")
    }
}

// Calling a function
checkPalindrome(prompt("Enter a string to check weather it is palindrome or not ?"))

var a="mad"
var b=a.split().reverse().join()
if(a===b){
    return true;
}else{
    return false;
}

function findFactorial(inputNum){
    var fact=1;
    for(var i=1; i<=inputNum; i++){
        fact*=i
    }

    console.log(fact)
}


var findFactorial=(inputNum)=>{
    var fact=1;
    for(var i=1; i<=inputNum; i++){
        fact*=i
    }

    console.log(fact)
}

undefined
findFactorial(7)






Splice Method:

var sampleArray=[1,2,3,4,5,8,6]
-> Addition of an element in an array
-> Deletion of an element from an array

splice(start_index, num_of_elemets_tobe_deleted, num_of_elements_tobe_add)

sampleArray.splice(5)

```

## Array of object
``` javascript
var array=[{name:"Hanu", age:33,salary:180000},{name:"Pavan",age:28,salary:2000000},{name:"Naveen",age:29,salary:3000000},{name:"Purugu",age:22,salary:100000},{name:"Petta",age:26,salary:600000},{name:"Kasim",age:23,salary:300000}]
for (i=0;i<array.length;i++){
    console.log(array[i])
}
for (i=0;i<array.length;i++){
    console.log(array[i].name)
}
```
## morethan 20k salary 
```javascript
for (i=0;i<array.length;i++){
    if (array[i].salary > 200000){
        console.log(array[i])}
```
# have morethan 20k salary names
```javascript
for (i=0;i<array.length;i++){
    if (array[i].salary > 200000){
        console.log(array[i].name)}
```
## DOM manipulation by creating dynamic element
``` javascript
index.html
.......................

<div id="myelement">Old Text</div>

index.js
..................
var divElement=document.getElementById("myelement");

var ul=document.createElement("ul")
var li=document.createElement("li")
li.textContent="Tiger Naveen"

ul.appendChild(li)
divElement.appendChild(ul)
```
## Dynamically creating DOM elements
```javascript
___________________________________________

var divElement=document.getElementById("myelement");

var listOfAnimals=["Lion", "Tiger", "Liger", "Tigon"];

var ul=document.createElement("ul")

listOfAnimals.map(animalItem=>{
    var li=document.createElement("li")
    li.textContent=animalItem;
    ul.appendChild(li)
})

divElement.appendChild(ul)
```

## Number converts into string

```javascript
var num=100
var str=String(num)
console.log(str)
console.log(typeof str)

```
## String converts into number
```javascript
var str="40"
var num=Number(str)
console.log(str)
console.log(typeof num)
```
## (OR)
```javascript
var str="45px"
var num=parseInt(str)
console.log(num)
```
## Number or String coverts into Boolean
```javscript
var val=Boolean(0)
var val1=Boolean("Hello")
console.log(val)
console.log(val1)
```
## Splice usage
```javascript
SYN:(Start,Delete count,add items)
var sampleArray1=["mango","orange","apple","pine apple","custed"]
sampleArray1.splice(0,1,"banana")

shift=>removing the first left value
unshift=>it's adding new value in first index
sampleArray1.shift()
sampleArray1.unshift("banana")
```
## slice usage
``javascript
var sampleArray1=["mango","orange","apple","pine apple","custed"]
sampleArray1.slice(0,3)
sampleArray.slice(-1)   ---->"custed"
```


