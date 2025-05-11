# JavaScript-Code
//print gcd in js
let n1=prompt("Enter your number");
let n2=prompt("Enter your number");
let gcd=1;
for(let i=2; i<=n1; i++){
    while(n1%i==0&&n2%i==0){
        n1=n1/i;
        n2=n2/i;
        gcd=i;
    }
}
console.log(gcd);

//find Maximum Number in Array

let arr=[3,5,6,7,8];
let max=arr[0];
for(let i=1; i<arr.length; i++){
    if(arr[i]>max){
        max=arr[i];
    }
}
console.log(max);

//ptint these Patterns
/*1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5 */
let n=5;
for(let i=1; i<=n; i++){
    let row="";
    for(let j=1; j<=i; j++){
        row+=j+" ";
    }
        console.log(row);
    }
    //Chack if num is Palindrome or Not

let num = Number(prompt("Enter Your Number"));
 let reverse=0;
 let temp=num;
 while(temp!=0){
    let rem=temp%10;
    reverse=reverse*10+rem;
    temp=Math.floor(temp/10);
 }
 if(num===reverse){
    console.log("Palindrome");
 }else{
    console.log("Not Palindrome");
 }
