for (let dan = 2; dan <= 9; dan++) {
    console.log(`[${dan}단]`);
    
    for (let i = 1; i <= 9; i++) {
        console.log(`${dan} x ${i} = ${dan * i}`);
        
    }
    
    console.log("");
}


let num = 0
while (num <10){
    num++;
    if (num % 2 == 0){
        continue
    }
console.log(num);
}

//1부터 10까지 출력할때 7을 만나면 더 이상 출력하지 않는 코드

num = 1
while (num <=10){
    
    if (num <7){
     console.log(num);
    }
    num++
    
}



let i = 0

//
while(i <= 4) {
    console.log(i);
    i++
}




i = 0;
do {
    console.log (i);
    i++;

} while(i <= 4)


let sum = 0;

for (let i = 1; i <= 909090900; i++) {
    sum += i;
}
console.log(sum);


const arr = ["햄스터", "짱룡", "원숭이", "용"]
arr.push("고야이");

for (let i = 0; i < arr.length; i++){
    console.log(arr[i]);
    
}



function solution(start_num,end_num) {
    let answer = [];
    
    for (let i = start_num; i <= end_num; i++) {
        answer.push(i);
    }
    
    return answer;
}
