# good code

1. console.log({object, object, object});
2. console.log('%c My code', 'color: red;font-weight: bold');
3. console.log([foo,bar,baz]); // Array foo  
4. show time run code
  console.time('startCode')
  function main(){}
  main();
  console.timeEnd('startCode')
5. 
let foo = {
  "name": "hahah",
  "age": 18,
  "date": "12/1/111"
}

function feed({name,age,date}){
  return 'Feed ${name} ${age} ${date}';
}

function feed(info){
  const {name, age, date} = info;
  return 'Feed ${name} ${age} ${date}';
}

6. 
let horse = {
  name: 'hihihaha',
  size: 'big',
  skills: ['badboy','cazy'],
  age: 18
}
const {name, size, skills} = horse;
bio = '${name} is a ${size}';

function horseAge(str, age){
  const ageStr = age > 5 ? 'old' : 'young';
  return '${str[0]}${ageStr} at ${age}';
}

8. create object
const lv10 = {...pikachu, ...stats}
const lv11 = {...pikachu, hp: 45}

let pokemon = [1,2,3]
pokemon = [...pokemon, 'data1', 'data2'];
pokemon = ['data0', ...pokemon, 'data1', 'data2'];

const orders = [500, 30, 99, 15, 255]
const total = orders.reduce((acc, cur) => acc + cur)
const withTax = orders.map(v => v * 1.1)
const highValue = orders.filter (v => v > 100)


9. 
const random = () => {
  return Promise.resolve(Math.random())
}

const sumRandomAsyncNums = async() => {
  const first = await random();
  const second = await random();
  const third = await random();
  
  console.log('result ${first + second + third}');
}

# clean code js

1. 

