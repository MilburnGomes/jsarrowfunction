Arrow function expressions

console.log('Welcome to Arrow Functions!');

// no parameters

// no parameter, regular function
function hello1() {
    return 'Hello!';
}
console.log('no parameters, regular function ' + hello1());

// no parameter, arrow function
const hello2 = () => {
    return 'Hello!';
}
console.log('no parameters, arrow function ' + hello2());

// no parameter, arrow function single line 
const hello3 = () => 'Hello!';
console.log('no parameters, arrow function single line  ' + hello3());

// one parameter

// one parameter, regular function
function hello4(x){
    return 'one parameter, regular function ' + 'Hello, ' + x;
}
console.log(hello4('milburn'));

// one parameter, arrow function
const hello5 = x => {
   return  'one parameter, arrow function ' + 'Hello, ' + x;
}
console.log(hello5('milburn'));

// one parameter, arrow function single line 
const hello6 = x => 'Hello, ' + x;
console.log('one parameter, arrow function single line ' + hello6('milburn'));

//two parameters

// two parameters, regular function
function hello7(x,y){
    return 'Hello, ' + x + ' ' + y; 
}
console.log('two parameters, regular function ' + hello7('milburn', 'gomes'));

// two parameters, arrow function
const hello8 = (x,y) =>{
	return 'two parameters, arrow function ' + 'Hello, ' + x + ' ' + y;
}
console.log(hello8('milburn', 'gomes'));

// two parameters, arrow function single line 
const hello9 = (x,y) =>  "Hello, " + x + " " + y;
console.log('two parameters, arrow function single line ' + hello9('milburn', 'gomes'));