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
