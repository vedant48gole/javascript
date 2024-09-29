//............PRACTICE SET QUESTION NO.1...........//
//Create a variable of type string and try to add a number to it?
//Solutins-
let a = "45";
let b = "65";
let c = "vedant";
console.log(a + b + c);

//............PRATICE SET QUESTION NO.2...........//
//Use typeof operator to find the datatype of the string in last question?
//soluton-
console.log(typeof (a + b + c));

//............PRATICE SET QUESTION NO.3...........//
//Create a const object in javascript can you change it to hold a number later?
//solution-
const item = {
  name: "vedant",
  room: 245,
  id: 12,
  car: true,
};
console.log(item);
// see here we make use of const to make a object and we can change the value of the object but we cannot change the object to hold a number or string later.



//............PRATICE SET QUESTION NO.4...........//
//Try to add a new key to the const object in problem 3 were you able to do it?
//Solution-
item["friend"] = "shubham";
item["name"] = "vedant";
console.log("item");



//............PRATICE SET QUESTION NO.5...........//
//Soluton=
const dict = {
  appricate: "recognize the full worth of.",
  ataraxia: "state of enjithy.",
  Discplined: "the distance between the hard work and consistency",
};
console.log(dict.Discplined);
