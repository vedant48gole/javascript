//...............Primitive(datatypes)..........//

//Tips-1: NN BB SS U
//N(Null),N(NUMBER),S(SYMBOL),S(STRING),B(BOOLEAN),B(BRIGHT),U(UNDEFINED):

//................Example..............//
let a = null; //null
let b = 345; //number
let c = true; //Boolean
let d = BigInt(234) + BigInt(56); //Bigint
let e = "VEDANT"; //String
let f = Symbol("this is my car:"); //Symbol
console.log(a, b, c, d, e, f);
// see we make use of (typeof) to know the type of the variable
console.log(typeof e);

//............Non-Primitive(objects)...............//

//Note- These objects are used for mapping,Dictionary purpose(means making any list of classroom or market buying list)

//................Example..............//
const vedant = {
  vedant: true,
  ved: false,
  veda: 67,
  vedan: undefined,
};
console.log(vedant[("vedan", "ved")]);
// see we make use of (typeof) to know the type of the variable
