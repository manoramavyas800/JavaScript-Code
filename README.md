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
