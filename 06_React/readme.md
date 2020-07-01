# React (Folder)

## Advanced JavaScript For React Part 1  

### 2.7. แบบฝึกหัด ( slide 27 )  
+ 1.ในบรรทัดที่มีเลข 1 2 และ 3 จะได้ค่าออกมาเป็นอะไร
> 📙 `answer.`  
```javascript
let animal = {
  jumps: null
};
let rabbit = {
  __proto__: animal,
  jumps: true
};

alert( rabbit.jumps ); // ? (1) ค่าออกมาเป็น true

delete rabbit.jumps;

alert( rabbit.jumps ); // ? (2) ค่าออกมาเป็น null

delete animal.jumps;

alert( rabbit.jumps ); // ? (3) ค่าออกมาเป็น undefined

```  

### 2.7. แบบฝึกหัด ( slide 28 )  
+ 2.ใช้ __proto__ ในการกำหนด prototype object ดังนี้  
+ pockets → bed → table → head. 
> 📙 `answer.`  
```javascript
let pockets = {
  money: 2000
};
let bed = {
    __proto__ : pockets,
  sheet: 1,
  pillow: 2
};
let table = {
    __proto__ : bed,
  pen: 3
};
let head = {
    __proto__ : table,
  glasses: 1
};
```  

### 2.7. แบบฝึกหัด ( slide 29 )  
+ 3.การเขียนโค๊ดแบบนี้ object ไหนจะเป็นคนได้ property full ไป
> 📙 `answer.`  
```javascript
let animal = {
  eat() {
    this.full = true;
  }
};
let rabbit = {
  __proto__: animal
};
rabbit.eat();

// ตอบ. rabbit ได้ {full: true}
```  

### 2.7. แบบฝึกหัด ( slide 30 )  
+ 4.การเขียนโค๊ดแบบนี้ กระเพราะจะถูกแชร์กันจะแก้ไขยังไงดี
> 📙 `answer.`  
```javascript
let hamster = {
  stomach: [],

  eat(food) {
    this.stomach.push(food);
  }
};

let speedy = {
    stomach: [],    // <<= (เพิ่มบรรทัดนี้) แก้ไขโดยการกำหนดให้มี stomach เป็นของตัวเอง
  __proto__: hamster    
};

let lazy = {
    stomach: [],    // <<= (เพิ่มบรรทัดนี้) แก้ไขโดยการกำหนดให้มี stomach เป็นของตัวเอง
  __proto__: hamster
};

// This one found the food
speedy.eat("apple");
alert( speedy.stomach ); // apple

// This one also has it, why? fix please.
alert( lazy.stomach ); // apple <<=(เมื่อทั้งสอง object มี stomach ของตัวเอง,speedyก็ไม่ต้องแชร์appleกับlazy=[])
```  

### 3.4. แบบฝึกหัด ( slide 45 )  
+ 1.จากโค๊ดต่อไปนี้มีการสร้าง new Rabbit() ขึ้นมา
> 📙 `answer.`  
```javascript
function Rabbit() {}
Rabbit.prototype = {
  eats: true
};
let rabbit = new Rabbit();
alert( rabbit.eats ); // true

let rabbit2 = new Rabbit();     // <== (สร้าง new Rabbit() มาใหม่ )
console.log(rabbit2.eats);
```  

### 3.4. แบบฝึกหัด ( slide 46 )  
+ ถ้ามีการ alert ในบรรทัดดังกล่าวจะได้อะไรออกมา
> 📙 `answer.`  
```javascript
function Rabbit() {}
Rabbit.prototype = {
  eats: true
};

let rabbit = new Rabbit();

Rabbit.prototype = {};

alert( rabbit.eats ); // ? <== ( ได้ค่า true )
```  

### 3.4. แบบฝึกหัด ( slide 47 )  
+ ถ้ามีการเปลี่ยนบรรทัดสีเหลืองจะเป็นอย่างไร
> 📙 `answer.`  
```javascript
function Rabbit() {}
Rabbit.prototype = {
  eats: true
};

let rabbit = new Rabbit();

Rabbit.prototype.eats = false;  // (การเปลี่ยนบรรทัดนี้)

alert( rabbit.eats ); // ? <== ( ส่งผลให้ค่า rabbit.eats เปลี่ยนไปด้วย, ค่าที่ออกมาตอนนี้คือ false )
```  

### 3.4. แบบฝึกหัด ( slide 48 )  
+ ถ้ามีการเปลี่ยนบรรทัดสีเหลืองจะเป็นอย่างไร
> 📙 `answer.`  
```javascript
function Rabbit() {}
Rabbit.prototype = {
  eats: true
};

let rabbit = new Rabbit();

delete rabbit.eats;     // (การเปลี่ยนบรรทัดนี้ ไม่ส่งผลอะไร เพราะ rabbit ไม่มี eats ขอตัวเอง)

alert( rabbit.eats ); // ? <== ( ค่าที่ออกมายังคงเป็น True , เพราะ rabbiy ใช้ prototype ที่รับมาจาก Rabbit )
```  

### 3.4. แบบฝึกหัด ( slide 49 )  
+ ถ้ามีการเปลี่ยนบรรทัดสีเหลืองจะเป็นอย่างไร
> 📙 `answer.`  
```javascript
function Rabbit() {}
Rabbit.prototype = {
  eats: true
};

let rabbit = new Rabbit();

delete Rabbit.prototype.eats;  // (การเปลี่ยนบรรทัดนี้)

alert( rabbit.eats ); // ? <== ( ส่งผลให้ค่า rabbit.eats เปลี่ยนไปด้วย, ค่าที่ออกมาตอนนี้คือ undefined )
```  

### 3.4. แบบฝึกหัด ( slide 50 )  
+ 2.ถ้าเราต้องการสร้างใช้ constructor ของ obj เราสามารถเขียนแบบนี้ได้ไหม
+ `let obj2 = new obj.constructor();`
> 📙 `answer.`  
```javascript
// (ไม่ได้ครับ เพราะยังไม่มีการสร้าง obj )
```  

### 4.6. แบบฝึกหัด ( slide 63 )  
+ 1.ให้เพิ่ม Method defer เข้าไปใน prototypes ของทุกฟังก์ชัน  
+ โดย Method นี้จะทำหน้าที่ alert ข้อความออกมาหลังจากผ่านไป ms  
> 📙 `answer.`  
```javascript
Function.prototype.defer = function(ms){
    let f = this;
    return function(...args){
        setTimeout(() => f.apply(this,args) ,ms);
    }
}

function f() {
  alert("Hello!");
}

let printHello = f.defer(1000); // แสดง "Hello!" หลังจากผ่านไป 1 วินาที
printHello();
```  

### 4.6. แบบฝึกหัด (Optional) ( slide 64 )  
+ 2.ให้เพิ่ม Method defer เข้าไปใน prototypes ของทุกฟังก์ชัน  
+ โดย Method นี้จะทำหน้าที่ return Function ให้ alert(a+b) เมื่อผ่านไป ms  
> 📙 `answer.`  
```javascript
Function.prototype.defer = function(ms){
    let f = this;
    return function(...args){
        setTimeout(() => f.apply(this,args) ,ms)
    }
}

function f(a, b) {
  alert( a + b );
}

f.defer(1000)(1, 2); // แสดง 3 หลังจากผ่านไป 1 วินาที
```  

### 5.2. แบบฝึกหัด ( slide 71-72 )  
+ 1.มี Object Dictionary ที่สร้างจาก Object.create(null) เพื่อเก็บ key/value pairs  
    + -ให้เพิ่ม Method dictionary.toString() และคืนค่าเป็น key ทั้งหมดออกมาที่คั้นด้วย comma  
> 📙 `answer.`  
```javascript
let dictionary = Object.create(null);

// your code to add dictionary.toString method
dictionary = Object.create(null, {
    toString : {
        value(){
            return Object.keys(this).join();
        }
    }
});

// add some data
dictionary.apple = "Apple";
dictionary.__proto__ = "test"; // __proto__ is a regular property key here

// only apple and __proto__ are in the loop
for(let key in dictionary) {
  alert(key); // "apple", then "__proto__"
}

// your toString in action
alert(dictionary); // "apple,__proto__"
console.log(dictionary);
```  

### 5.2. แบบฝึกหัด ( slide 73 )  
+ 2.สร้าง object rabbit ด้วย new keyword  
> 📙 `answer.`  
```javascript
function Rabbit(name) {
  this.name = name;
}
Rabbit.prototype.sayHi = function() {
  alert(this.name);
};

let rabbit = new Rabbit("Rabbit");
rabbit.sayHi();
```  

### 5.2. แบบฝึกหัด ( slide 74 )  
+ คำสั่งทั้งหมดนี้ทำงานเหมือนกันหรือไม่
> 📙 `answer.`  
```javascript
function Rabbit(name) {
  this.name = name;
}
Rabbit.prototype.sayHi = function() {
  alert(this.name);
};

let rabbit = new Rabbit("Rabbit");

rabbit.sayHi();                         // <== ตอบ. 'Rabbit' ทั้งหมดไม่เหมือนกัน
Rabbit.prototype.sayHi();               // <== ตอบ. undefined ทั้งหมดไม่เหมือนกัน
Object.getPrototypeOf(rabbit).sayHi();  // <== ตอบ. undefined ทั้งหมดไม่เหมือนกัน
rabbit.__proto__.sayHi();               // <== ตอบ. undefined ทั้งหมดไม่เหมือนกัน
```   
