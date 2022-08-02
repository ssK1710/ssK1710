Q1. Create a Function to Wish a User Happy Birthday, Ask User Date and Month and if it match with today data and month wish him/her
Hint: prompt function for user input

Q2. Enter the Age and Compute Total Weeks in a Human Life

Q3. Create a Template for Love Letter 

Q4. A Sandwich Calculator
1. Write a function called sandwich calculator. This should accept one value: bread
2. The function should return the total number of possible sandwiches based on the amount of breads available. I need 2 breads to make one sandwich, so if there are 10 breads, it should return 5. Test your function with console.log.
3. Extend your function so it accepts two values, bread and cheese.
4. It takes two sbreads and one cheese to make a sandwich. The function should return the total number of possible sandwiches, so if there are breads, but only 1 cheese, it should return 1.

Q5. Add the Following Case in add function
a) add(10,[1,"2",3],[one, "Amit",  two,"100"],"20")
________________________________________________
Ans1.
function wish(d,m){
    var dates = new Date();
    var day = dates.getDate();
    var month = dates.getMonth()+1;
    if(d == day && m == month){
        console.log("!Happy Birthday!");
    }
    else{
        console.log("!NO Birthday!");
    }
}
var d= prompt("Enter today date: ");
var m= prompt("Enter today month: ");
wish(d,m);

Ans2.
function week(age){
    console.log("Total weeks = ",age*52);
}
var age = prompt("Enter your age: ");
week(age);

Ans4.
(a) function sandwichCalculator(bread){
    var breads = Math.floor(bread/2);
    console.log("Total Sandwich = ",breads);
}
var bread = prompt("Enter number of bread: ");
sandwichCalculator(bread);

(b) function sandwichCalculator(bread, cheese){
    var breads=Math.floor(bread/2);
    if(breads>cheese){
        console.log("Total Sandwich : ",cheese);
    }
    else{
        console.log("Total Sandwich : ",breads);
    }
}
var bread = prompt("Enter number of bread: ");
var cheese = prompt("Enter number of cheese: ");
sandwichCalculator(bread, cheese);

Ans5.
function add(){
    var sum=0;
    for(i=0;i<arguments.length;i++){
        if(typeof arguments[i]=="function"){
            arguments[i]=arguments[i]();
        }
        sum = sum + (isNaN(parseInt(arguments[i]))?0:parseInt(arguments[i]));
    }
    return sum;
}
