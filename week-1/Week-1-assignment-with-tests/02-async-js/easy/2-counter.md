## Counter without setInterval

Without using setInterval, try to code a counter in Javascript. There is a hint at the bottom of the file if you get stuck.




var counter =1;

function printAndincreaseCount() {
    console.clear();
    console.log(counter);
    counter += 1;
}

for( var i=0; i<10; i++){
    setInterval(printAndincreaseCount, (i+1)* 1000);
}




































































(Hint: setTimeout)