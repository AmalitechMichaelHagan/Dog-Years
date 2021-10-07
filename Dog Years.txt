//Variable that holds user's age
let myAge = 24;

//Holds the value for early dog years. This value is susceptible to change
let earlyYears = 2;

//Converts early dog years to human years.
earlyYears*=10.5;

//Stores years after earlyYears
let laterYears = myAge-2;

//converts lateryears to dog years
laterYears*=4;

console.log(laterYears +" "+ earlyYears);

//Calculates and stores value for final Age in dog years
let myAgeInDogYears = earlyYears + laterYears;

//stores user name in lowercases
let myName = 'MIKE'.toLowerCase();

console.log(`My name is ${myName}. I am ${myAge} years old in human years which is ${myAgeInDogYears} years old in dog years`);