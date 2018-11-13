//generates a number between 0-9
function randomWholeNum() {

  return Math.floor(Math.random() * 10);
}

console.log(randomWholeNum())


//generates random number in range
function randomRange(myMin, myMax) {

  return Math.floor(Math.random() * (myMax - myMin + 1)) + myMin;

}

// Change these values to test your function
var myRandom = randomRange(5, 15);
console.log(myRandom);

//convert stringified number into whole number

function convertToInteger(str){
return parseInt(str);
}
convertToInteger("56") // 56
convertToInteger("blake") //NaN

//Use the parseInt Function with a Radix
function convertToInteger(str) {
return parseInt(str, 2)
}

convertToInteger("1011");
