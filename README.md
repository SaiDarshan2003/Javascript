# Javascript
## 1.Get user input using prompt(“Enter your age:”). If user is 18 or older , give feedback: 'You are old enough to drive' but if not 18 give another feedback stating to wait for the number of years he needs to turn 18. 

### Sample output
Enter your age: 30

you are old enough to drive.

Enter your age:15

You are left with 3 years to drive
```
Solution:
var age=prompt("Enter your age:");
if (age>=18)
{
    console.log("You are old enough to drive")
}
else
{
    age=18-age;
    console.log("You are left with",age,"years to drive")
}
```

![image](https://user-images.githubusercontent.com/94692595/232670930-b2aa31ab-fc12-4ab9-9eaa-cb90af5d4c6b.png)


## 2.Compare the values of myAge and yourAge using if … else. Based on the comparison and log the result to console stating who is older (me or you). Use prompt(“Enter your age:”) to get the age as input.

### Sample output
Enter your age: 30

You are 5 years older than me

```
Solution:
var my=prompt("Enter my age:");
var you=prompt("Enter your age:");
var diff1
if (my>you)
{
    diff1=my-you
    console.log("Iam are",diff1," years older than you")
}20
else
{
    diff1=you-my
    console.log("You are",diff1," years older than me")
}

```
![image](https://user-images.githubusercontent.com/94692595/232671169-052cace0-61ee-4588-aa50-297ddd064b37.png)


## 3.Even numbers are divisible by 2 and the remainder is zero. How do you check, if a number is even or not using JavaScript?

### Sample output
Enter a number: 2

2 is an even number

Enter a number: 9

```
Solution:
var choice=prompt("Enter a number:")
if(choice%2==0)
{
    console.log(choice,"is an even number.")
}
else
{
    console.log(choice,"is an odd number.")
}
```
![image](https://user-images.githubusercontent.com/94692595/232671294-cd067120-d5e5-4786-b163-b10185bcda48.png)
