# -5
<!DOCTYPE html> 
<html lang="en"> 
<head> 
<meta charset="UTF-8"> 
<meta name="viewport" content="width=device-width, initial-scale=1.0"> 
<meta http-equiv="X-UA-Compatible" content="ie=edge"> 
<title>Document</title>
 
//1 
console.log("15"+false) 
console.log("15"+true) 
console.log("15"-false) 
console.log("15"-true) 
//2 
var A =[0,4,3] 
console.log(A[0]+A[2]+A[1]); 
console.log(A[0]*A[2]*A[1]); 
var B = A.length 
var C = ++B 
console.log(C); 
console.log(A[A.length-1]%C); 
//3 
var a = 11 
var b = 12 
var c = 10 
var p = (a+b+c)/2 
var S = Math.sqrt(p*(p-a)*(p-b)*(p-c)) 
console.log(S); 
//4 
var x=4, y 
y=4*x++// y= 4*4 x=4+1 
console.log(y, x); 
var x=4, y 
y=4*++x //x=4+1 y=4*x 
console.log(y, x); 
var x=4, y 
y=4*x— 
console.log(y, x); 
var x=4, y 
y=4*--x 
console.log(y, x); 
//5 
var n = 10 
n = n + 5 // n = 15 
console.log(n); 
var x = 10 
x += 5 
console.log(x); 
