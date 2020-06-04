# JavaScript (Folder)

## Basic part1
### Lab 1 ตัวแปรและประเภทของข้อมูล > slide 43  
+ Lab 1
    + ให้ประกาศตัวแปรชื่อ human และ name
    + ใส่ชื่อตัวเองลงในตัวแปร name
    + นำค่าที่อยู่ในตัวแปร name ไปใส่ให้ human 
    + เมื่อ console.log(human) ออกมาต้องเป็นชื่อตัวเอง
> 📙 `answer.`  
```javascript
    let human = "";
    let name = "";
    name = "surasak";
    human = name;
    console.log(human);
```  

### Lab 2 ตัวแปรและประเภทของข้อมูล > slide 44  
+ Lab 2
    + ตั้งชื่อตัวแปรที่ใช้เก็บจำนวนเงินในกระเป๋าตังของคุณ
    + ตั้งชื่อตัวแปรที่ใช้เก็บชื่อของ พ่อและแม่ของคุณ
    + ตั้งชื่อตัวแปรที่ใช้เก็บที่อยู่ของบ้านคุณ
    + ตั้งชื่อตัวแปรที่ใช้เก็บอายุของจักรวาล
> 📙 `answer.`  
```javascript
    let myMoney = 0;
    let nameFarther = "farther Name";
    let nameMother = "mother Name";
    let myAddress = "Bangkok Thailand";
    let approximately = "13.6 billion years"
    let galaxyAge = 13.6;
```  

### Exercise 2 ตัวแปรและประเภทของข้อมูล > slide 64  
+ ตัวแปรและประเภทของข้อมูล (Exercise 2)
    + 2.1. กำหนดตัวแปรสำหรับเก็บชื่อ และกำหนดค่าเริ่มต้นเป็นชื่อของผู้เรียน
    + 2.2. กำหนดตัวแปรสำหรับเก็บอายุ และกำหนดค่าเริ่มต้นเป็นอายุของผู้เรียน
    + 2.3. กำหนดตัวแปรสำหรับเก็บที่อยู่ และกำหนดค่าเริ่มต้นเป็นที่อยู่ของผู้เรียน
    + 2.4. กำหนดตัวแปรสำหรับเก็บประวัติของนักเรียนโดยใช้ตัวแปรทั้ง 3 ตัวด้านบนประกอบการเขียนประวัตินี้ด้วย  
> 📙 `answer.`  
```javascript
    let name2 = 'surasak';
    let age2 = '100';
    let address2 = "Bangkok Thailand";
    const history2 = name2 + age2 + address2 ;
```  

### 4.6. แบบฝึกหัด การดำเนินการเบื้องต้น > slide 93-94  
+ 1.ให้ระบุค่าของ a, b, c และ d หลังจากจบ statements ทั้งสามบรรทัด
> 📙 `answer.`  
```javascript
let a = 1, b = 1 ;
let c = ++a;
let d = b++;

    \\ a = 1
    \\ b = 1
    \\ c = 2
    \\ d = 1
```  
+ 2.จงหาผลลัพธ์ของ Statement ต่อไปนี้
> 📙 `answer.`  
```javascript
    const test_1 = "" + 1 + 0           // 1.   = 10
    const test_2 =  "" - 1 + 0          // 2.   = -1
    const test_3 = true + false         // 3.   = 1
    const test_4 = 6 / "3"              // 4.   = 2
    const test_5 = "2" * "3"            // 5.   = 6
    const test_6 = 4 + 5 + "px"         // 6.   = "9px"
    const test_7 = "$" + 4 + 5          // 7.   = $45"
    const test_8 = "4" - 2              // 8.   = 2
    const test_9 = "4px" - 2            // 9.   = NaN
    const test_10 = 7 / 0               // 10.  = Infinity
    const test_11 =	"  -9  " + 5        // 11.  = "  -9  5"
    const test_12 =	"  -9  " - 5        // 12.  = -14
    const test_13 =	null + 1            // 13.  = 1
    const test_14 =	undefined + 1       // 14.  = NaN
    const test_15 =	" \t \n" - 2        // 15.  = -2
```  

### 5.7. การเปรียบเทียบ - แบบฝึกหัด > slide 117  
+ 1.จงหาค่าของการเปรียบเทียบต่อไปนี้  
> 📙 `answer.`  
```javascript
    const test_16 = 5 > 4                   // = true
    const test_17 = "apple" > "pineapple"   // = false
    const test_18 = "2" > "12"              // = true
    const test_19 = undefined == null       // = true
    const test_20 = undefined === null      // = false
    const test_21 = "bee" < "be"            // = false
    const test_22 = "bee" > "Bee"           // = true
    const test_23 = "Bee" < "be"            // = true
```  

### 6.5. แบบฝึกหัด > slide 132-135   
+ 1.Browser จะโชว์ข้อความ “Hello Codecamp #5” ไหม
> if ("0") {  
>   alert("Hello Codecamp #5");  
> }  
> 📙 `answer.`  
```
    'แสดง ข้อความ "Hello Codecamp #5"'
```  
+ 2.ใช้ if else ในการเขียนถามชื่อของคุณ
    + ถ้าตอบถูกให้แสดงคำว่า “เก่งมาก”
    + ถ้าตอบผิดให้แสดงคำว่า “คุณไม่รู้จักชื่อฉัน”
> 📙 `answer.`  
```javascript
    let slide133 = prompt('ชื่อของคุณคือ ?','ato')
    if (slide133 === 'ato') {
        alert('เก่งมาก');
    } else {
        alert('คุณไม่รู้จักชื่อฉัน');
    }
```  
+ 3.ใช้ prompt ในการรับคะแนนมาคำนวณเกรด
    + ถ้าคะแนน มากกว่าเท่ากับ 80 ได้ A
    + ถ้าคะแนน อยู่ระหว่าง 70 - 79 ได้ B
    + ถ้าคะแนน อยู่ระหว่าง 60 - 69 ได้ C
    + ถ้าคะแนน อยู่ระหว่าง 50 - 59 ได้ D
    + ถ้าคะแนน น้อยกว่า 50 ได้ F
> 📙 `answer.`  
```javascript
    let grade = prompt('รับคะแนนมาคำนวณเกรด',80);
    if (grade < 50) {
        alert('เกรด F');
    } else if (grade < 60) {
        alert('เกรด D');
    } else if (grade < 70) {
        alert('เกรด C');
    } else if (grade < 80) {
        alert('เกรด B');
    } else if (grade >= 80) {
        alert('เกรด A');
    } else {
        alert('Please input Number');
    }
```  
+ 4.เปลี่ยน if-else ข้างล่างในอยู่ในรูปของ Ternary Operators
> 📙 `answer.`  
```javascript
let age = prompt('How old are you?');
let price = 0;

if (age < 18 ) {
    price = 2000;
} else {
    price = 3500;
}

// # Ternary Operators
price = (age < 18 ) ? price = 2000 :  price = 3500;

alert(price);
```  

### Homework > slide 137   
+ 1.จงคำนวณค่าด้านล่างต่อไปนี้ และ คอมเม้นตอบหลังคำถาม  
> 📙 `answer.`  
```javascript
const test_01 = 5 + "34"                                            // "534"
const test_02 = 5 ** 4                                              // 625
const test_03 = 5 - "4"                                             // 1
const test_04 = 10 % 5                                              // 0
const test_05 = 5 % 10;                                             // 5
const test_06 = (2 ** 5) % 2                                        // 0
const test_07 = "Java" + "Script"                                   // "JavaScript"
const test_08 = " " + " "                                           // "  "
const test_09 = " " + 0                                             // " 0"
const test_010 = 20 + 4 + "15"                                      // "2415"
const test_011 = true + true                                        // 2
const test_012 = true + false                                       // 1
const test_013 = false + true                                       // 1
const test_014 = false - true                                       // -1
const test_015 = false - true + false - true + false;               // -2
const test_016 = (true + true) ** 4                                 // 16
const test_017 = 19 + true + "20"                                   // "2020"
const test_018 = 3 - 4                                              // -1
const test_019 = "Bob" - "bill"                                     // NaN
const test_020 = "Code" + "Camp" + true + false + null + undefined  // "CodeCamptruefalsenullundefined"
```  
+ 2.จงคำนวณค่าเปรียบเทียบต่อไปนี้ และ คอมเม้นตอบด้านหลังเหมือนข้างบน  
> 📙 `answer.`  
```javascript
const test2_01 = 5 >= 1                 // true
const test2_02 = 0 === 1                // false
const test2_03 = 4 <= 1                 // false
const test2_04 = 1 != 1                 // false
const test2_05 = 1 == "1"               // true
const test2_06 = 1 === "1"              // false
const test2_07 = "2" == "2"             // true
const test2_08 = "2" === "2"            // true
const test2_09 = "12" !== 12            // true
const test2_010 = "15" != 15            // false
const test2_011 = "A" > "B"             // false
const test2_012 = "B" < "C"             // true
const test2_013 = "a" > "A"             // true
const test2_014 = "b" < "A"             // false
const test2_015 = "bee" > "bbe"         // true
const test2_016 = "BeE" < "Bee"         // true
const test2_017 = "SonTer" > "Soncom"   // false
const test2_018 = "circle" > "circles"  // false
const test2_019 = "NaRuTo" < "nArUtO"   // true
const test2_020 = true === false        // false
const test2_021 = true != true          // false
```  
+ 3.สร้าง String ที่มีค่า "Hello, It's me. "Mario"."  
> 📙 `answer.`  
```javascript
    let text_string = `Hello, It's me. "Mario".`;
    console.log(text_string);
```  

## Basic part2
### ตัวดำเนินการแบบตรรกะ > slide 25-29  
+ 1.คำสั่งต่อไปนี้จะแสดงค่าเป็นอะไร
> 📙 `answer.`  
```javascript
    alert( null || 2 || undefined );        // 2
    alert( alert(1) || 2 || alert(3) );     // 1 และ 2
    alert( 1 && null && 2 );                // null
    alert( alert(1) && alert(2) );          // 1 และ undefined
    alert( null || 2 && 3 || 4 );           // 3
```  
+ 2.เขียนคำสั่ง if ที่เช็คอายุว่าอยู่ระหว่าง 18 - 60
> 📙 `answer.`  
```javascript
    const age18to60 = (age) => !!((age >= 18) && (age <= 60));
    console.log('age18to60(18)= ',age18to60(18));
    console.log('age18to60(100)= ',age18to60(100));
```  
+ 3.เขียนคำสั่ง if ที่เช็คอายุว่าไม่อยู่ระหว่าง 18 - 60
> 📙 `answer.`  
```javascript
    const notAge18to60 = (age) => !!((age < 18) || (age > 60));
    console.log('notAge18to60(18)= ',notAge18to60(15));
    console.log('notAge18to60(100)= ',notAge18to60(30));
```  
+ 4.คำสั่ง alert ไหนที่จะถูกรันบ้าง
> 📙 `answer.`  
```javascript
if (-1 || 0) alert( 'first' );          // รัน ได้ค่า first
if (-1 && 0) alert( 'second' );         // ไม่รัน
if (null || -1 && 0) alert( 'third' );  // ไม่รัน SyntaxError
``` 
+ 5.ให้เขียนระบบ login  
+ ให้ใช้ prompt ในการถามใครเป็นคน login
    + ถ้าผู้ใช้กรอกว่า “Admin” ให้ใช้ prompt ถาม password
        + วิธีเช็ค Password
        + ถ้า string นั้นเป็น “codecamp#5” ให้ alert “ยินดีต้อนรับ”
        + ถ้า string เป็นอย่างอื่นให้ alert เป็น “Wrong password”
        + ถ้าเป็น string ว่าง หรือ กด cancel ให้ alert ว่า “ยกเลิก”
    + ถ้าผู้ใช้กรอกอย่างอื่นที่ไม่ใช่ “Admin” ให้ alert ว่า “ผมไม่รู้จักคุณ”
    + ถ้าผู้ใช้กรอก input เป็น string ว่าง หรือกด Esc ให้ alert ว่า “ยกเลิก”
> 📙 `answer.`  
```javascript
    let checkUser = prompt('Who are you (ใครเป็นคน login) ?','Admin');    
    if (!!(checkUser)) {        
        if (checkUser === 'Admin') {
            let checkPassword = prompt('in put password (string นั้นเป็น “codecamp#6”) ?','codecamp#6');
            if (!!(checkPassword)) {
                if (checkPassword === 'codecamp#6') {
                    alert('☺ ยินดีต้อนรับ ☺');
                } else {
                    alert('Wrong password');
                }
            } else {
                alert('ยกเลิก');
            }
        } else {
            alert('ผมไม่รู้จักคุณ');
        }
    } else {
        alert('ยกเลิก');
    }
```  

### วงวน for และ while > slide 43-47  
+ 1.เลขที่ถูก alert เป็นลำดับสุดท้ายคือเลขอะไร
> 📙 `answer.`  
```javascript
let i = 3;
while (i) {
  alert( i-- );
}
    // alertลำดับสุดท้ายคือเลข 1
```  
+ 2.code ทั้งสองอันนี้จะแสดง alert ออกมาเหมือนกันทั้งหมดหรือไม่
> 📙 `answer.`  
```javascript
//# Left
let i = 0;
while (++i < 5) alert( i );
//# Right 
let i = 0;
while (i++ < 5) alert( i );

    // code ทั้งสองอันนี้จะแสดง alert ไม่เหมือนกัน (ฝั่งซ้ายแสดง [1,2,3,4], ฝั่งขวาแสดง [1,2,3,4,5])
```  
+ 3.code ทั้งสองอันนี้จะแสดง alert ออกมาเหมือนกันทั้งหมดหรือไม่
> 📙 `answer.`  
```javascript
//# Top 
for (let i = 0; i < 5; i++) alert( i );
//# bottom 
for (let i = 0; i < 5; ++i) alert( i );

    // code ทั้งสองอันนี้จะแสดง alert เหมือนกัน (ฝั่งบนและล่างแสดง [0,1,2,3,4]
```  
+ 4.ให้เขียน loop ทั้งแสดงเลข 2 ถึง 10 ออกมา
> 📙 `answer.`  
```javascript
    for (let i = 2; i <= 10; i++) {
        console.log(i)
    }
``` 
+ 5.เปลี่ยน code for loop ด้านล่างนี้ให้เป็น while loop โดยที่ผลลัพธ์ยังเหมือนเดิม
> 📙 `answer.`  
```javascript
// # for Loop 
for (let i = 0; i < 3; i++) {
  alert( `number ${i}!` );
}
// # while loop
let i = 0;
while (i < 3) {
    alert( `number ${i}!` );
    i++;
}
``` 
+ 6.ให้เขียนเกมส์ทายตัวเลขสำหรับเล่นสองคน โดย
    + ให้ผู้เล่นคนแรกพิมพ์เลขใส่ใน prompt ที่อยู่ระหว่าง 1 ถึง 100 โดยไม่ให้ผู้เล่นคนที่สองรู้ว่าตัวเลขเป็นอะไร
    + และให้ผู้เล่นคนที่สองทายเลขโดยการพิมพ์เลขใส่ใน prompt จนกว่าจะถูก ถ้าไม่ถูก จะต้องบอกด้วยว่าเลขที่ผู้เล่นคนที่สองพิมพ์เข้ามา มากกว่า หรือ น้อยกว่าคำตอบนั้น
> 📙 `answer.`  
```javascript
let player1 = prompt('ผู้เล่นคนแรกพิมพ์เลข 1 ถึง 100','');
let player2 = '';
while (player1 !== player2) {
    player2 = prompt('ผู้เล่นคนที่สองทายเลข','');
    if (player1 === player2) {
        alert('คุณทายถูกต้อง');
        break;
    }
    if (Number(player2) > Number(player1)) {
        alert('เลขของคุณ มากกว่า');
    } else {
        alert('เลขของคุณ น้อยกว่า');
    }
    console.log(player1," O_o ",player2)
    continue;   
}
``` 

### แบบฝึดหัด Swtich Cases > slide 56-57  
+ 1.แปลง Code ดังกล่าวเป็น if-else statement
> 📙 `answer.`  
```javascript
let browser = 'Chrome';
switch (browser) {
  case 'Edge':
    alert( "You've got the Edge!" );
    break;
  case 'Chrome':
  case 'Firefox':
  case 'Safari':
  case 'Opera':
    alert( 'Okay we support these browsers too' );
    break;
  default:
    alert( 'We hope that this page looks ok!' );
}

// แปลงเป็น if-else statement
if (browser === 'Edge') {
    alert( "You've got the Edge!" );
} else if (browser === 'Chrome' || browser === 'Firefox'|| browser === 'Safari'|| browser === 'Opera') {
    alert( 'Okay we support these browsers too' );
} else {
    alert( 'We hope that this page looks ok!' );
}
```  
+ 2.แปลง Code ดังกล่าวเป็น Switch cases
> 📙 `answer.`  
```javascript
let a = +prompt('a?', '');
if (a == 0) {
  alert( 0 );
}
if (a == 1) {
  alert( 1 );
}
if (a == 2 || a == 3) {
  alert( '2,3' );
}

// แปลง Code เป็น Switch cases
switch() {
    case 0:
        alert( 0 );
        break;
    case 1:
        alert( 1 );
        break;
    case 2:
    case 3:
        alert( '2,3' );
        break;
    default:
        break;
}
``` 

### แบบฝึกหัดพิเศษ ฟังก์ชัน > slide 78-100
1. จงเขียน method draw(int n) ให้ print ออกมาในกรณี n มีค่าต่างๆ ได้ผลลัพดังนี้  
![](/05_JavaScript/test_s/01.png?raw=true)
> 📙 `answer.`  
```javascript
const method_draw = (n) => String.prototype.padStart(n,'*');
console.log(method_draw(2));
console.log(method_draw(3));
console.log(method_draw(4));
```  
2. จงเขียน method draw(int n) ให้ print ออกมาในกรณี n มีค่าต่างๆ ได้ผลลัพดังนี้  
![](/05_JavaScript/test_s/02.png?raw=true)
> 📙 `answer.`  
```javascript
function method_drawB(n){
    let str = '';
    for (let i=0; i<n; i++) {
        for (let x=0; x<n; x++) {
            str = str + '*';
        }
        str = str + '\n';
    }
    return str;
}
console.log(method_drawB(2));
console.log(method_drawB(3));
console.log(method_drawB(4));
```  
3. จงเขียน method draw(int n) ให้ print ออกมาในกรณี n มีค่าต่างๆ ได้ผลลัพดังนี้  
![](/05_JavaScript/test_s/03.png?raw=true)
> 📙 `answer.`  
```javascript
function method_drawC(n){
    let str = '';
    for (let i=1; i<=n; i++) {
        for (let x=1; x<=n; x++) {
            str = str + x;
        }
        str = str + '\n';
    }
    return str;
}
console.log(method_drawC(2));
console.log(method_drawC(3));
console.log(method_drawC(4));
```  
4. จงเขียน method draw(int n) ให้ print ออกมาในกรณี n มีค่าต่างๆ ได้ผลลัพดังนี้  
![](/05_JavaScript/test_s/04.png?raw=true)
> 📙 `answer.`  
```javascript
function method_drawD(n){
    let str = '';
    for (let i=1; i<=n; i++) {
        for (let x=1; x<=n; x++) {
            str = str + i;
        }
        str = str + '\n';
    }
    return str;
}
console.log(method_drawD(2));
console.log(method_drawD(3));
console.log(method_drawD(4));
```  
5. จงเขียน method draw(int n) ให้ print ออกมาในกรณี n มีค่าต่างๆ ได้ผลลัพดังนี้  
![](/05_JavaScript/test_s/05.png?raw=true)
> 📙 `answer.`  
```javascript
function method_drawE(n){
    let str = '';
    for (let i=n; i>=1; i--) {
        for (let x=1; x<=n; x++) {
            str = str + i;
        }
        str = str + '\n';
    }
    return str;
}
console.log(method_drawE(2));
console.log(method_drawE(3));
console.log(method_drawE(4));
```  
6. จงเขียน method draw(int n) ให้ print ออกมาในกรณี n มีค่าต่างๆ ได้ผลลัพดังนี้  
![](/05_JavaScript/test_s/06.png?raw=true)
> 📙 `answer.`  
```javascript
function method_drawF(n){
    let str = '';
    let count = 1;  
    for (let i=0; i<n; i++) {
        for (let x=1; x<=n; x++) {
            str = str + count; 
            count++;            
        }                       
        str = str + '\n';        
    }
    return str;
}
console.log(method_drawF(2));
console.log(method_drawF(3));
console.log(method_drawF(4));
```  
7. จงเขียน method draw(int n) ให้ print ออกมาในกรณี n มีค่าต่างๆ ได้ผลลัพดังนี้  
![](/05_JavaScript/test_s/07.png?raw=true)
> 📙 `answer.`  
```javascript
function method_drawG(n){
    let str = '';
    let count = n*n;  
    for (let i=0; i<n; i++) {
        for (let x=1; x<=n; x++) {
            str = str + count; 
            count--;            
        }                       
        str = str + '\n';        
    }
    return str;
}
console.log(method_drawG(2));
console.log(method_drawG(3));
console.log(method_drawG(4));
```  
8. จงเขียน method draw(int n) ให้ print ออกมาในกรณี n มีค่าต่างๆ ได้ผลลัพดังนี้  
![](/05_JavaScript/test_s/08.png?raw=true)
> 📙 `answer.`  
```javascript
function method_drawH(n){
    let str = '';     
    for (let i=0; i<n; i++) {
        for (let x=0; x<n; x+=n) {
            str = str + (i*2);                        
        }                       
        str = str + '\n';        
    }
    return str;
}
console.log(method_drawH(2));
console.log(method_drawH(3));
console.log(method_drawH(4));
```  
9. จงเขียน method draw(int n) ให้ print ออกมาในกรณี n มีค่าต่างๆ ได้ผลลัพดังนี้  
![](/05_JavaScript/test_s/09.png?raw=true)
> 📙 `answer.`  
```javascript
function method_drawI(n){
    let str = '';     
    for (let i=1; i<=n; i++) {
        for (let x=0; x<n; x+=n) {
            str = str + (i*2);                        
        }                       
        str = str + '\n';        
    }
    return str;
}
console.log(method_drawI(2));
console.log(method_drawI(3));
console.log(method_drawI(4));
```  
10. จงเขียน method draw(int n) ให้ print ออกมาในกรณี n มีค่าต่างๆ ได้ผลลัพดังนี้  
![](/05_JavaScript/test_s/10.png?raw=true)
> 📙 `answer.`  
```javascript
function method_drawJ(n){
    let str = '';     
    for (let i=0; i<n; i++) {
        for (let x=1; x<=n; x++) {
            str = str + (x+(x*i));                        
        }                       
        str = str + '\n';        
    }
    return str;
}
console.log(method_drawJ(2));
console.log(method_drawJ(3));
console.log(method_drawJ(4));
```  
11. จงเขียน method draw(int n) ให้ print ออกมาในกรณี n มีค่าต่างๆ ได้ผลลัพดังนี้  
![](/05_JavaScript/test_s/11.png?raw=true)
> 📙 `answer.`  
```javascript
function method_drawK(n){
    let str = '';     
    for (let i=1; i<=n; i++) {
        for (let x=1; x<=n; x++) {
            let symbol = (x === i) ? '-' : '*' ;
            str = str + symbol;                        
        }                       
        str = str + '\n';        
    }
    return str;
}
console.log(method_drawK(2));
console.log(method_drawK(3));
console.log(method_drawK(4));
```  
12. จงเขียน method draw(int n) ให้ print ออกมาในกรณี n มีค่าต่างๆ ได้ผลลัพดังนี้  
![](/05_JavaScript/test_s/12.png?raw=true)
> 📙 `answer.`  
```javascript
function method_drawL(n){
    let str = '';     
    for (let i=n; i>=1; i--) {
        for (let x=1; x<=n; x++) {
            let symbol = (x === i) ? '-' : '*' ;
            str = str + symbol;                        
        }                       
        str = str + '\n';        
    }
    return str;
}
console.log(method_drawL(2));
console.log(method_drawL(3));
console.log(method_drawL(4));
```  
13. จงเขียน method draw(int n) ให้ print ออกมาในกรณี n มีค่าต่างๆ ได้ผลลัพดังนี้  
![](/05_JavaScript/test_s/13.png?raw=true)
> 📙 `answer.`  
```javascript
function method_drawM(n){
    let str = '';       
    for (let i=1; i<=n; i++) {
        for (let x=1; x<=n; x++) {
            let symbol = (x > i) ? '-' : '*' ;
            str = str + symbol;                        
        }                       
        str = str + '\n';        
    }
    return str;
}
console.log(`%c${method_drawM(2)}`,'font-weight: bold; font-size: 1.2rem');
console.log(`%c${method_drawM(3)}`,'font-weight: bold; font-size: 1.2rem');
console.log(`%c${method_drawM(4)}`,'font-weight: bold; font-size: 1.2rem');
```  
14. จงเขียน method draw(int n) ให้ print ออกมาในกรณี n มีค่าต่างๆ ได้ผลลัพดังนี้  
![](/05_JavaScript/test_s/14.png?raw=true)
> 📙 `answer.`  
```javascript
function method_drawN(n){
    let str = '';       
    for (let i=n; i>=1; i--) {
        for (let x=1; x<=n; x++) {
            let symbol = (x > i) ? '-' : '*' ;
            str = str + symbol;                        
        }                       
        str = str + '\n';        
    }
    return str;
}
console.log(`%c${method_drawN(2)}`,'font-weight: bold; font-size: 1.2rem');
console.log(`%c${method_drawN(3)}`,'font-weight: bold; font-size: 1.2rem');
console.log(`%c${method_drawN(4)}`,'font-weight: bold; font-size: 1.2rem');
```  
15. จงเขียน method draw(int n) ให้ print ออกมาในกรณี n มีค่าต่างๆ ได้ผลลัพดังนี้  
![](/05_JavaScript/test_s/15.png?raw=true)
> 📙 `answer.`  
```javascript
function method_drawO(n){
    let str = '';       
    for (let i=1; i<=n; i++) {
        for (let x=1; x<=n; x++) {
            let symbol = (x > i) ? '-' : '*' ;
            str = str + symbol;                        
        }                       
        str = str + '\n';        
    }
    for (let i=(n-1); i>=1; i--) {
        for (let x=1; x<=n; x++) {
            let symbol = (x > i) ? '-' : '*' ;
            str = str + symbol;                        
        }                       
        str = str + '\n';        
    }
    return str;
}
console.log(method_drawO(2));
console.log(method_drawO(3));
console.log(method_drawO(4));
```  
16. โจทย์ข้อ 16 หาย น่าจะพิมพ์ข้าม  
17. จงเขียน method draw(int n) ให้ print ออกมาในกรณี n มีค่าต่างๆ ได้ผลลัพดังนี้  
![](/05_JavaScript/test_s/17.png?raw=true)
> 📙 `answer.`  
```javascript
function method_drawQ(n){
    let str = '';       
    for (let i=n; i>=1; i--) {
        for (let x=1; x<=n; x++) {
            let symbol = (x < i) ? '-' : '*' ;
            str = str + symbol;                        
        }                       
        str = str + '\n';        
    }
    return str;
}
console.log(method_drawQ(2));
console.log(method_drawQ(3));
console.log(method_drawQ(4));
```  
18. จงเขียน method draw(int n) ให้ print ออกมาในกรณี n มีค่าต่างๆ ได้ผลลัพดังนี้  
![](/05_JavaScript/test_s/18.png?raw=true)
> 📙 `answer.`  
```javascript
function method_drawR(n){
    let str = '';       
    for (let i=1; i<=n; i++) {
        for (let x=1; x<=n; x++) {
            let symbol = (x < i) ? '-' : '*' ;
            str = str + symbol;                        
        }                       
        str = str + '\n';        
    }
    return str;
}
console.log(method_drawR(2));
console.log(method_drawR(3));
console.log(method_drawR(4));
```  
19. จงเขียน method draw(int n) ให้ print ออกมาในกรณี n มีค่าต่างๆ ได้ผลลัพดังนี้  
![](/05_JavaScript/test_s/19.png?raw=true)
> 📙 `answer.`  
```javascript
function method_drawS(n){
    let str = ''; 
    for (let i=n; i>=1; i--) {
        for (let x=1; x<=n; x++) {
            let symbol = (x < i) ? '-' : '*' ;
            str = str + symbol;                        
        }                       
        str = str + '\n';        
    }      
    for (let i=2; i<=n; i++) {
        for (let x=1; x<=n; x++) {
            let symbol = (x < i) ? '-' : '*' ;
            str = str + symbol;                        
        }                       
        str = str + '\n';        
    }
    return str;
}
console.log(method_drawS(2));
console.log(method_drawS(3));
console.log(method_drawS(4));
```  
20. จงเขียน method draw(int n) ให้ print ออกมาในกรณี n มีค่าต่างๆ ได้ผลลัพดังนี้  
![](/05_JavaScript/test_s/20.png?raw=true)
> 📙 `answer.`  
```javascript
function method_drawT(n){
    let str = '';
    let count = 1; 
    for (let i=n; i>=1; i--) {
        for (let x=1; x<=n; x++) {
            let symbol = (x < i) ? '-' : Number(count) ;
            str = str + symbol;
            if (typeof symbol === 'number') {
                count++;
            }
        }                       
        str = str + '\n';        
    }      
    for (let i=2; i<=n; i++) {
        for (let x=1; x<=n; x++) {
            let symbol = (x < i) ? '-' : Number(count) ;
            str = str + symbol;
            if (typeof symbol === 'number') {
                count++;
            }                                   
        }                       
        str = str + '\n';        
    }
    return str;
}
console.log(method_drawT(2));
console.log(method_drawT(3));
console.log(method_drawT(4));
```  
21. จงเขียน method draw(int n) ให้ print ออกมาในกรณี n มีค่าต่างๆ ได้ผลลัพดังนี้  
![](/05_JavaScript/test_s/21.png?raw=true)
> 📙 `answer.`  
```javascript
function method_drawU(n){
    let str = '';         
    for (let i=n; i>=1; i--) {
        for (let x=1; x<=n; x++) {
            let symbol = (x < i) ? '-' : '*' ;
            str = str + symbol;                        
        }
        for (let x=(n-1); x>=1; x--) {
            let symbol = (x < i) ? '-' : '*' ;
            str = str + symbol;                        
        }                       
        str = str + '\n';        
    }
    return str;
}
console.log(method_drawU(2));
console.log(method_drawU(3));
console.log(method_drawU(4));
```  
22. จงเขียน method draw(int n) ให้ print ออกมาในกรณี n มีค่าต่างๆ ได้ผลลัพดังนี้  
![](/05_JavaScript/test_s/22.png?raw=true)
> 📙 `answer.`  
```javascript
function method_drawV(n){
    let str = '';         
    for (let i=1; i<=n; i++) {
        for (let x=1; x<=n; x++) {
            let symbol = (x < i) ? '-' : '*' ;
            str = str + symbol;                        
        }
        for (let x=(n-1); x>=1; x--) {
            let symbol = (x < i) ? '-' : '*' ;
            str = str + symbol;                        
        }                       
        str = str + '\n';        
    }
    return str;
}
console.log(method_drawV(2));
console.log(method_drawV(3));
console.log(method_drawV(4));
```  
23. จงเขียน method draw(int n) ให้ print ออกมาในกรณี n มีค่าต่างๆ ได้ผลลัพดังนี้  
![](/05_JavaScript/test_s/23.png?raw=true)
> 📙 `answer.`  
```javascript
function method_drawW(n){
    let str = '';
    for (let i=n; i>=1; i--) {
        for (let x=1; x<=n; x++) {
            let symbol = (x < i) ? '-' : '*' ;
            str = str + symbol;                        
        }
        for (let x=(n-1); x>=1; x--) {
            let symbol = (x < i) ? '-' : '*' ;
            str = str + symbol;                        
        }                       
        str = str + '\n';        
    }       
    for (let i=2; i<=n; i++) {        
        for (let x=1; x<=n; x++) {
            let symbol = (x < i) ? '-' : '*' ;
            str = str + symbol;                        
        }
        for (let x=(n-1); x>=1; x--) {
            let symbol = (x < i) ? '-' : '*' ;
            str = str + symbol;                        
        }                       
        str = str + '\n';        
    }
    return str;
}
console.log(method_drawW(2));
console.log(method_drawW(3));
console.log(method_drawW(4));
```  
24. จงเขียน method draw(int n) ให้ print ออกมาในกรณี n มีค่าต่างๆ ได้ผลลัพดังนี้  
![](/05_JavaScript/test_s/24.png?raw=true)
> 📙 `answer.`  
```javascript
function method_drawX(n){
    let str = '';
    let count = 1;
    for (let i=n; i>=1; i--) {
        for (let x=1; x<=n; x++) {
            let symbol = (x < i) ? '-' : Number(count) ;
            str = str + symbol;
            if (typeof symbol === 'number') {
                count++;
            }                        
        }
        for (let x=(n-1); x>=1; x--) {
            let symbol = (x < i) ? '-' : Number(count) ;
            str = str + symbol; 
            if (typeof symbol === 'number') {
                count++;
            }                       
        }                       
        str = str + '\n';        
    }       
    for (let i=2; i<=n; i++) {        
        for (let x=1; x<=n; x++) {
            let symbol = (x < i) ? '-' : Number(count) ;
            str = str + symbol; 
            if (typeof symbol === 'number') {
                count++;
            }                       
        }
        for (let x=(n-1); x>=1; x--) {
            let symbol = (x < i) ? '-' : Number(count) ;
            str = str + symbol; 
            if (typeof symbol === 'number') {
                count++;
            }                       
        }                       
        str = str + '\n';        
    }
    return str;
}
console.log(method_drawX(2));
console.log(method_drawX(3));
console.log(method_drawX(4));
```  

### แบบฝึกหัด Arrow Function > slide 120  
+ แปลง function ข้างล่างให้อยู่ในรูป arrow function
> 📙 `answer.`  
```javascript
function ask(question, yes, no) {
  if (confirm(question)) yes()
  else no();
}
ask(
  "Do you agree?",
  function() { alert("You agreed."); },
  function() { alert("You canceled the execution."); }
);

// แปลง arrow function
let ask_arrow = (question, yes, no) => (confirm(question)) ? yes() : no() ;
ask_arrow("Do you agree?", () => (alert("You agreed.")), () => (alert("You canceled the execution.")) );

``` 


---
---


## Advance part 1  

### การเขียน Code ( slide 24 )  
+ 1.10. แบบฝึกหัด
    + แก้ไขการเขียนโค้ดต่อไปนี้ (จัดโค้ดใหม่)
> 📙 `answer.`     
```javascript
function pow(x, n) {
  let result = 1;
  for(let i = 0 ; i < n ; i++) {
      result *= x;
      }
  return result;
}

let x = prompt("x?", ''), n = prompt("n?", '');

if (n <= 0) {
  alert(`Power ${n} is not supported, please enter an integer number greater than zero`);
} else {
  alert(pow(x, n));
}
```  

### Object ( slide 53 )  
+ 1.ให้สร้าง Object แบบ Object Iteral โดยให้กำหนดตัวแปรชื่อ human  
+ โดยมี Properties ทั้ง 5 อย่าง ชื่อของผู้เรียน เป็น String  
    + a.อายุของผู้เรียนเป็น number  
    + b.บ้านของตัวเองเป็น String  
    + c.โสดหรือไม่โสดเป็น boolean  
    + d.คะแนนความฉลาดของตัวเองเป็น number (เต็ม 10)  
> 📙 `answer.`     
```javascript
let human = {age:15, home:'bangkok', single:'true', intelligence:0.1e2};
``` 

### Object ( slide 56 )  
+ 4.7. Computed Properties - แบบฝึกหัด  
	+ 1.ให้เขียนโปรแกรมที่รับค่า key และ value ของ Properties ของ Object หนึ่ง   
    + จนกว่าจะเจอคำว่า stop และนำค่าเหล่านั้นมาสร้าง Object หลังจากนั้น console.log() object นั้นออกมา   
> 📙 `answer.`     
```javascript
let key = prompt('Enter key: ');
let obj = {};
while (key !== 'stop') {
    let value = prompt('Enter value: ');
    obj[key] = value;    
    key = prompt('Enter key: ');    
}
console.log(obj);
```  

### Object ( slide 57 ) 
+ 4.7.Computed Properties - แบบฝึกหัด  
	+ 2.ให้เขียนโปรแกรมที่รับค่า key และ value ของ Properties ของ Object หนึ่ง  
    + โดยให้ key เป็นชื่อของผลไม้ และ value เป็นจำนวนของผลไม้ (number)  
    + โดยถ้า ผลไม้ชนิดไหนที่มีมากกว่า 1 ผล ให้เติม s ไปหลัง key นั้นด้วย   
> 📙 `answer.`     
```javascript
let i = 0;
let obj = {};
while (i < 3) { //กำหนดรับค่า สามรอบ
    let key = prompt('Enter fruit name: ');
    let value = prompt('Enter Number: ',2);
    if (value > 1) {
        key = `${key}s`;
    }
    obj[key] = value;
    i++;
}
console.log(obj);
```  

### Object ( slide 78 )  
+ 4.18. แบบฝึกหัด  
    + 1.ให้ทำตามคำสั่งต่อไปนี้  
        + a.สร้าง Object เปล่าขึ้นมา  
        + b.เพิ่ม properties name เข้าไปและให้ value เป็น “Sonter”  
        + c.เพิ่ม properties surname เข้าไปและให้ value เป็น “Pakorn”  
        + d.เปลี่ยน properties name เป็น “Boy”  
        + e.ลบ properties name ออกจาก Object  
> 📙 `answer.`     
```javascript
let obj = {};
obj = {name: 'Sonter'};
obj = {surname: 'Pakorn'};
obj[name] = 'boy';
delete obj[name];
console.log(obj);
```  

### Object ( slide 79 )  
+ 4.18. แบบฝึกหัด
    + 2.ให้เขียนฟังก์ชันชื่อ isEmpty(obj) โดยจะมี parameters เป็น obj และ ฟังก์ชันนี้จะเช็คว่า obj  
    + นี้มี properties ไหม ถ้ามีให้คืนค่า true ถ้าไม่มีให้คืนค่า false  
> 📙 `answer.`     
```javascript
function isEmpty(obj) {
    for (let key in obj) {
        return false;
    }
    return true
}
console.log(isEmpty());
```  

### Object ( slide 80 )  
+ 4.18. แบบฝึกหัด  
    + 3.การเขียนข้างล่างต่อไปนี้ Error ไหม  
> 📙 `answer.`     
```javascript
const user = {
    name: "John"
};

// does it work?
user.name = "Pete";

// it work (ไม่มีerror)
```  

### Object ( slide 81 )  
+ 4.18. แบบฝึกหัด
    + 4.จงเขียนฟังก์ชัน sum(obj) ที่รับ obj ที่เก็บ properties โดยมี key เป็นชื่อพนักงาน  
    + และมี value เป็นเงินเดือน ให้ฟังก์ชันคืนค่าเป็นผลรวมของเงินเดือนพนักงานทั้งหมด  
> 📙 `answer.`     
```javascript
let salaries = {
    John: 100,
    Ann: 160,
    Pete: 130
}

function sum(obj) {
    let value = 0;
    for (let key in obj) {
        value += obj[key];
    }
    return value;
}

console.log(sum(salaries));
```  

### Object ( slide 82 )  
+ 4.18. แบบฝึกหัด
    + 5.จงเขียนฟังก์ชัน multiplyNumeric(obj, times) โดยถ้า properties นั้นมี value เป็น number  
    + ให้คุณ value นั้นด้วย times ถ้าข้อมูลเเป็นอย่างอื่นไม่ต้องทำอะไร  
> 📙 `answer.`     
```javascript
let menu = {
    width: 200,
    height: 300,
    title: "My menu"
};

function multiplyNumeric(obj, times) {
    for (let key in obj) {
        if (typeof obj[key] !== 'number') continue;
        obj[key] = obj[key] * times;
    }
}
multiplyNumeric(menu,10);
console.log(menu);
```  

### Methods ของ Object ( slide 100 )  
+ 6.6. แบบฝึกหัด  
    + 1.การทำงานของ code ดังกล่าวจะได้อะไรออกมา  
> 📙 `answer.`     
```javascript
let user = {
  name: "John",
  go: function() { alert(this.name) }
}
(user.go)()

// แสดงค่า Error (user is not defined)
```  

### Methods ของ Object ( slide 101 )  
+ 6.6. แบบฝึกหัด  
    + 2.การทำงานของ code ดังกล่าวจะได้อะไรออกมา  
> 📙 `answer.`     
```javascript
function makeUser() {
    return {
        name: "John",
        ref: this
    };
};

let user = makeUser();

alert( user.ref.name ); // What's the result?

// ไม่แสดงค่าอะไร
``` 

### Methods ของ Object ( slide 102 )  
+ 6.6. แบบฝึกหัด  
    + 3.สร้าง object calculator จาก 3 methods นี้:  
        + read() ใช้ prompts สำหรับรับค่ามา 2 ค่าและเก็บเป็น object properties.  
        + sum() คืนค่าผลบวกของ 2 ค่านั้น.  
        + mul() คืนค่าผลคูณของ 2 ค่านั้น.  
> 📙 `answer.`     
```javascript
let calculator = {
    // ... your code ...
    read(){
        this.number1 = Number(prompt('Enter first Number: '));
        this.number2 = Number(prompt('Enter second Number: '));
    },
    sum(){
        return this.number1 + this.number2;
    },
    mul(){
        return this.number1 * this.number2;
    }
};

calculator.read();
alert( calculator.sum() );
alert( calculator.mul() );
```  

### Methods ของ Object ( slide 103-105 )  
+ 6.6. แบบฝึกหัด  
    + 4.ให้ Object ชื่อ ladder มี method ขึ้น และ ลง    
    + (ต่อ). Object ชื่อ ladder สามารถเรียก function แบบนี้ได้  
    + (ต่อ). ดัดแปลง Object ชื่อ ladder สามารถเรียก function แบบนี้ได้  
> 📙 `answer.`     
```javascript
let ladder = {
    step: 0,
    up() {
        this.step++;
        return this;
    },
    down() {
        this.step--;
        return this;
    },
    showStep: function() { // shows the current step
        alert( this.step );
    }
};

// ladder.up();
// ladder.up();
// ladder.down();
// ladder.showStep(); // 1

ladder.up().up().down().showStep(); // 1
```  

### Constructor กับ New ( slide 118 )  
+ 7.4. แบบฝึกหัด  
    + 1.สร้าง constructor function ที่ใช้สำหรับสร้าง Calculator โดยต้องมี 3 Methods นี้  
        + a.read(): รับค่าจาก propmt สองตัว  
        + b.sum(): ให้คืนค่าจากการบวกกันของตัวแปรสองตัว  
        + c.mul(): ให้คืนค่าจากการคูณกันของตัวแปรสองตัว  
> 📙 `answer.`     
```javascript
function Calculator(){
    this.read = function(){
        this.number1 = Number(prompt('Enter first Number: '));
        this.number2 = Number(prompt('Enter second Number: '));
    },
    this.sum = function(){
        return this.number1 + this.number2;
    },
    this.mul = function(){
        return this.number1 * this.number2;
    }
}

let test = new Calculator();
test.read();
console.log(test.sum());
console.log(test.mul());
```  

### Constructor กับ New ( slide 119 )   
+ 7.4. แบบฝึกหัด  
    + 2.สร้าง constructor function Accumulator(startingValue)  
        + a.โดยที่ Object ดังกล่าวควร เก็บผลรวมไว้ใน property ที่มี key ชื่อว่า value,  
        + ค่าเริ่มต้นของ key ชื่อ value นี้ คือ startingValue  
        + b.ฟังก์ชัน read() ควรอ่านค่าจาก propmt() และ เพิ่มค่าที่ใส่เข้ามาใน key ชื่อ value  
        + พูดง่าย ๆ ก็คือ value คือผลรวมของ prompt โดยเริ่มจาก startingValue  
> 📙 `answer.`     
```javascript
function Accumulator(startingValue) {
    this.value = startingValue;
    this.read = function(){
        let num = Number(prompt('Enter Number: '));
        this.value += num
    }
}

let sum = new Accumulator(10);
sum.read();
console.log(`allSum.value = ${sum.value}`);
``` 

---

## Advance part 2  

### ตัวเลข ( slide 28 )  
+ 1.9. แบบฝึกหัด  
    + 1.ให้เขียนฟังก์ชัน random(min, max) ที่จะ random เลข float ตั้งแต่ min จนถึง max มาให้เรา (ไม่รวม max)  
> 📙 `answer.`     
```javascript
function random(min,max) {
    return Math.random(min) * max + 1;
}

// alert( random(1, 5) ); // 1.2345623452
// alert( random(1, 5) ); // 3.7894332423
// alert( random(1, 5) ); // 4.3435234525

let numberRandom = random(1,5);
console.log(numberRandom);
```  

### ข้อความ (String) ( slide 58 )  
+ 2.11. แบบฝึกหัด  
    + 1.เขียนฟังก์ชัน ucFirst(string) โดยทำคืนค่าเป็น string เดิม แต่ตัวแรกของ string กลายเป็นพิมพ์ใหญ่  
> 📙 `answer.`     
```javascript
function ucFirst(string) {    
    return `${string[0].toUpperCase()}${string.slice(1)}`;
}

console.log(ucFirst('hello world string test ☺')); // Hello world string test ☺
```  

### ข้อความ (String) ( slide 59 )  
+ 2.11. แบบฝึกหัด  
    + 2.เขียนฟังก์ชันที่ checkSpam โดยถ้าข้อความดังกล่าวมีคำว่า “xxx” หรือ “viagra”   
    + ให้คืนค่าเป็น true ถ้าไม่มีให้คืนค่าเป็น false  
> 📙 `answer.`     
```javascript
function checkSpam(str) {
    return str.includes('xxx') || str.includes('viagra');
}

console.log(checkSpam('hello world xxx'));  // true
console.log(checkSpam('hello world viagra'));  // true
console.log(checkSpam('hello world text abcd string ☺'));  // false
```  

### ข้อความ (String) ( slide 60 )  
+ 2.11. แบบฝึกหัด   
    + 3.เขียนฟังก์ชันที่ truncate(str, maxlength) โดยฟังก์ชันดังกล่าวจะเช็คว่า string ที่ถูกส่งเข้ามา  
    + มีความยาวเกิน maxlength ไหม ถ้าเกินให้แทน ข้อความต่อจากนั้นด้วย “...”  
> 📙 `answer.`     
```javascript
// truncate("What I'd like to tell on this topic is:", 20) = "What I'd like to tel..."
// truncate("Hi everyone!", 20) = "Hi everyone!"

function truncate(str, maxlength) {
    if (str.length > 20) {        
        return `${str.slice(0,20)}...`;
    }
    return str;
}

console.log(truncate("What I'd like to tell on this topic is:", 20));
console.log(truncate("Hi everyone!", 20));
```  

### ข้อความ (String) ( slide 61 )  
+ 2.11. แบบฝึกหัด  
    + 4.เขียนฟังก์ชันที่ extractCurrencyValue(string, rate) โดยที่ฟังก์ชันดังกล่าวจะแปลง string ที่เป็นค่าเงิน   
    + dollar ให้เป็น number ที่มีค่าเป็นเงินบาทไทย โดยอ้างอิง rate จาก parameters ตัวที่สอง ที่ส่งมาให้  
> 📙 `answer.`     
```javascript
function extractCurrencyValue(string, rate) {
    let getStrNumber = string.replace(/[\$a-z]/gi,'');
    return (Number(getStrNumber) * rate);
}

alert( extractCurrencyValue('$120', 30.5) === 3660 ); // true
console.log( extractCurrencyValue('$120', 30.5) === 3660 ); // true
```   

### Array ( slide 88 )   
+ 3.11. แบบฝึกหัด  
    + 1.ผลลัพธ์ของความยาว array คืออะไร  
> 📙 `answer.`     
```javascript
let fruits = ["Apples", "Pear", "Orange"];

let shoppingCart = fruits;
shoppingCart.push("Banana");

alert( fruits.length ); // 4
```  

### Array ( slide 89-90 )   
+ 3.11. แบบฝึกหัด  
    + 2.ให้ทำตามขั้นตอนต่อไปนี้  
        + a.สร้าง array ชื่อ styles ที่มี items ชื่อ “Jazz” และ “Blues”  
        + b.เพิ่ม “Rock-n-Roll” ต่อท้าย  
        + c.นำค่า Classics ไปทับค่าตรงกลางของ Array  
        + d.นำ items ตัวแรกออกมาและลบ items ตัวนั้นออกจาก array  
        + e.เพิ่ม “Rap” และ “Reggae” ไปข้างหน้าของ Array  
> 📙 `answer.`     
```javascript
let styles = ['Jazz', 'Blues'];  // a.สร้าง array ชื่อ styles ที่มี items ชื่อ “Jazz” และ “Blues”  

styles.push('Rock-n-Roll');  // b.เพิ่ม “Rock-n-Roll” ต่อท้าย 

styles[(Math.floor(styles.length / 2))] = 'Classics';  // c.นำค่า Classics ไปทับค่าตรงกลางของ Array 

styles.shift();  // d.นำ items ตัวแรกออกมาและลบ items ตัวนั้นออกจาก array 

styles = ['Rap', 'Reggae', ...styles]  // e.เพิ่ม “Rap” และ “Reggae” ไปข้างหน้าของ Array

console.log(styles);  // ["Rap", "Reggae", "Classics", "Rock-n-Roll"]
```  

### Array ( slide 91 )   
+ 3.11. แบบฝึกหัด  
    + 3.เขียนฟังก์ชัน sumInput() ที่  
        + a.ใช้ propmt รับ value มาเก็บใน array  
        + b.หยุดถามเมื่อเจอค่าที่ไม่ใช่ ตัวเลข  
        + c.คำนวณผลรวมของตัวเลขทั้งหมดใน Array  
> 📙 `answer.`     
```javascript
function sumInput() {
    let numArray = [];    
    let infinite = true;
    let sum = 0;
    while (infinite) {        
        let value = prompt('Enter a Number (is stop when string!): ');

        if ( value === '' || (/[^\d]/gi).test(value) === true ) {
            infinite = false;
            break;
        }
        numArray.push(Number(value));
    } 
    sum = numArray.length > 0 ? numArray.reduce((a,b) => a + b) : 0;
      
    console.log(numArray);
    console.log(`ผลรวมของตัวเลขทั้งหมดใน Array = ${sum}`);
    alert(`ผลรวมของตัวเลขทั้งหมดใน Array = ${sum}`);
}
sumInput();
```  

### Array ( slide 92 )   
+ 3.11. แบบฝึกหัด  
    + 4.Maximal contiguous subarray (**Optional**)  
    + ให้เขียนฟังก์ชัน getMaxSubSum(arr) ที่ return ผลรวมของ subarray ที่มากที่สุดที่ติดกัน  
> 📙 `answer.`     
```javascript
function getMaxSubSum(arr) {    
    let sum = arr[0];    
    let sumMax = sum; // sometime => if array length === 1

    for (let i = 1; i < arr.length; i++) {  // start of length 2
        sum = Math.max(arr[i], sum + arr[i]);
        if(sumMax < sum) (sumMax = sum);  // performance ,if not ,not process
    }
    return sumMax;
}

// getMaxSubSum([-1, 2, 3, -9]) == 5 (the sum of highlighted items)
// getMaxSubSum([2, -1, 2, 3, -9]) == 6
// getMaxSubSum([-1, 2, 3, -9, 11]) == 11
// getMaxSubSum([-2, -1, 1, 2]) == 3
// getMaxSubSum([100, -9, 2, -3, 5]) == 100
// getMaxSubSum([1, 2, 3]) == 6 (take all)
console.log(getMaxSubSum([-1, 2, 3, -9]));
console.log(getMaxSubSum([2, -1, 2, 3, -9]));
console.log(getMaxSubSum([-1, 2, 3, -9, 11]));
console.log(getMaxSubSum([-2, -1, 1, 2]));
console.log(getMaxSubSum([100, -9, 2, -3, 5]));
console.log(getMaxSubSum([1, 2, 3]));
```  

### Methods ของ Array ( slide 124-135 )  
+ 4.10. แบบฝึกหัด  
    + ให้สร้าง array2 จาก array1 ตามที่โจทย์กำหนด โดยใช้ฟังก์ชัน Array.map()  
> 📙 `answer.`     
```javascript
// 1.1 
let array1 = [1, 2, 30, 400]
// array2 [2, 4, 60, 800]

let array2 = array1.map(a => a * 2);
console.log(array2);
```  
    
> 📙 `answer.`     
```javascript
// 1.2 
let array1 = [1, 2, 3, 4]
// array2 ["1", "2", "3", "4"]

let array2 = array1.map(a => String(a));
console.log(array2);
```  

> 📙 `answer.`     
```javascript
// 1.3 
let array1 = [1, "1", 2, {}] 
// array2 ["number", "string", "number", "object"]

let array2 = array1.map(a => String(typeof a));
console.log(array2);
```  

> 📙 `answer.`     
```javascript
// 1.4 
let array1 = ["apple", "banana", "orange"]
// array2 ["APPLE", "BANANA", "ORANGE"]

let array2 = array1.map(a => a.toUpperCase());
console.log(array2);
```  

> 📙 `answer.`     
```javascript
// 1.5 
let array1 = [
      { name: "apple", age: 14 },
      { name: "banana", age: 18 },
      { name: "watermelon", age: 32 },
    ]
// array2 ["apple", "banana", "watermelon"]

let array2 = array1.map((item,i,arr) => arr[i]['name'] );
console.log(array2);
```  

> 📙 `answer.`     
```javascript
// 1.6 
let array1 = [
      { name: "apple", age: 14 },
      { name: "banana", age: 18 },
      { name: "watermelon", age: 32 },
    ]
// array2 [14, 18, 32] 

let array2 = array1.map((item,i,arr) => arr[i]['age'] );
console.log(array2);
```  

> 📙 `answer.`     
```javascript
// 1.7 
let array1 = [
      { name: "apple", surname: "London" },
      { name: "banana", surname: "Bangkok" },
      { name: "watermelon", surname: "Singapore" },
    ]
// array2 ["apple London", "banana Bangkok", "watermelon Singapore"]

let array2 = array1.map((item,i,arr) => `${arr[i]['name']} ${arr[i]['surname']}`);
console.log(array2);
```  

> 📙 `answer.`     
```javascript
// 1.8 
let array1 = [1,3,4,5,6,7,8]
// array2 ["odd", "odd", "even", "odd", "even", "odd", "even"]

let array2 = array1.map(a => a % 2 === 0 ? 'even' : 'odd');
console.log(array2);
```  

> 📙 `answer.`     
```javascript
// 1.9 
let array1 = [1, -3, 2, 8, -4, 5]
// array2 [1, 3, 2, 8, 4, 5]

let array2 = array1.map(a => a < 0 ? a * (-1) : a );
console.log(array2);
```  

> 📙 `answer.`     
```javascript
// 1.10 
let array1 = [100, 200.25, 300.84, 400.3]
// array2 ["100.00", "200.25", "300.84", "400.30"]

let array2 = array1.map(a => a.toFixed(2) );
console.log(array2);
```  

> 📙 `answer.`     
```javascript
// 1.11 
let array1 = [
       { name: "apple", birth: "2000-01-01" },
       { name: "banana", birth: "1990-10-01" },
       { name: "watermelon", birth: "1985-12-01" },
     ]
//  array2 [
//    { name: "apple", birth: "2000-01-01", age: 19 },
//    { name: "banana", birth: "1990-10-01", age: 29 },
//    { name: "watermelon", birth: "1985-12-01", age: 33 },
//  ]

let age = [19,29,33];
let array2 = array1;
array2.map((item,i,arr) => arr[i]['age'] = age[i]);
console.log(array2);
```  

> 📙 `answer.`     
```javascript
// 1.12 
let array1 = [
       { name: "apple", birth: "2000-01-01" },
       { name: "banana", birth: "1990-10-10" },
       { name: "watermelon", birth: "1985-12-30" },
     ]
// array2 [
//     "<tr>
//     <td>apple</td> 
//     <td>01 jan 2000</td>
//     </tr>",
//     "<tr> <td>banana</td> <td>10 oct 1990</td> </tr>",
//     "<tr> <td>watermelon</td> <td>30 dec 1985</td> </tr>",
// ]

// let options = {day: 'numeric', month: 'short', year: 'numeric'};
// let array2 = array1.map((item,i,arr) => `<tr> <td>${arr[i].name}</td><td>${new Intl.DateTimeFormat('th-TH', options).format(new Date(arr[i].birth))}</td> </tr>` );

// let shortMonth = ["January","February","March","April","May","June","July","August","September","October","November","December"];
let shortMonth2 = ["jan","feb","mar","apr","may","jun","jul","aug","sep","oct","nov","dec"];
let array2 = array1.map((item,i,arr) => `<tr> <td>${arr[i].name}</td> <td>${(new Date(arr[i].birth)).getDate() < 10 ? '0'+(new Date(arr[i].birth)).getDate():(new Date(arr[i].birth)).getDate()} ${shortMonth2[(new Date(arr[i].birth)).getMonth()]} ${(new Date(arr[i].birth)).getFullYear()}</td> </tr>` );
console.log(array2); // ☺☺☺☺☺
```  

+ ให้สร้าง array2 จาก array1 ตามที่โจทย์กำหนด โดยใช้ฟังก์ชัน Array.filter()  
> 📙 `answer.`     
```javascript
// 2.1  
let array1 = [1, 2, 30, 400] ;
// array2 [30, 400] // filter เลขที่มากกว่า 10

let array2 = array1.filter(x => x > 10 );
console.log(array2);
```  

> 📙 `answer.`     
```javascript
// 2.2  
let array1 = [1, 2, 3, 4]
// array2 [1, 3] // filter เลขคี่

let array2 = array1.filter(x => x % 2 !== 0 );
console.log(array2);
```  

> 📙 `answer.`     
```javascript
// 2.3  
let array1 = [1, "1", 2, {}] 
// array2 [1, 2] // filter Number

let array2 = array1.filter(x => typeof x === 'number' );
console.log(array2);
```  

> 📙 `answer.`     
```javascript
// 2.4  
let array1 = ["apple", "banana", "orange", "pineapple", "watermeon"]
// array2 ["pineapple", "watermeon"] // filter ตัวอักษร > 6

let array2 = array1.filter(x => x.length > 6 );
console.log(array2);
```  

> 📙 `answer.`     
```javascript
// 2.5 
let array1 = [
      { name: "apple", age: 14 },
      { name: "banana", age: 18 },
      { name: "watermelon", age: 32 },
      { name: "pineapple", age: 16 },
      { name: "peach", age: 24 },
    ]
// array2 [
//     { name: "apple", age: 14 },
//     { name: "pineapple", age: 16 },
// ] // filter age < 18

let array2 = array1.filter((cur,i,arr) => arr[i]['age'] < 18 );
console.log(array2);
```  

> 📙 `answer.`     
```javascript
// 2.6 
let array1 = [
      { name: "apple", age: 14 },
      { name: "banana", age: 18 },
      { name: "watermelon", age: 32 },
      { name: "pineapple", age: 16 },
      { name: "peach", age: 24 },
    ]
// array2 [
//     { name: "apple", age: 14 },
//     { name: "banana", age: 18 },
//     { name: "pineapple", age: 16 },
//     { name: "peach", age: 24 },
// ] // filter ไม่เอาคนที่อายุ 32

let array2 = array1.filter((cur,i,arr) => arr[i]['age'] !== 32 );
console.log(array2);
``` 

> 📙 `answer.`     
```javascript
// 2.7  
let array1 = [1, -3, 2, 8, -4, 5]
// array2 [1, 2, 8, 5] // filter เลขบวก

let array2 = array1.filter(x => x > 0 );
console.log(array2);
```  

> 📙 `answer.`     
```javascript
// 2.8  
let array1 = [1,3,4,5,6,7,8]
//  array2 [3, 6] // filter เลขหาร 3 ลงตัว

let array2 = array1.filter(x => x % 3 === 0 );
console.log(array2);
```  

> 📙 `answer.`     
```javascript
// 2.9  
let array1 = ["peach", 1, -3, "2", {}, []]
//  array2 ["peach", "2"] // filter string

let array2 = array1.filter(x => typeof x === 'string' );
console.log(array2);
```  

> 📙 `answer.`     
```javascript
// 2.10 
let array1 = ["APPLE", "appLE", "PEACH", "PEach"]
//  array2 = ["APPLE", "PEACH"] // filter คำที่เป็นอักษรใหญ่ทุกตัว

let array2 = array1.filter(x => x === x.toUpperCase() );
console.log(array2);
```  

> 📙 `answer.`     
```javascript
// 2.11 
let array1 = [
       { name: "apple", birth: "2001-01-01" },
       { name: "banana", birth: "1990-10-10" },
       { name: "watermelon", birth: "1985-12-30" },
       { name: "peach", birth: "2002-10-13" },
     ]
//  array2 [
//    { name: "banana", birth: "1990-10-10" },
//      { name: "peach", birth: "2002-10-13" },
//  ] // filter คนเกิดเดือน 10

// /** In JavaScript, the first month (January) is month number 0, so December returns month number 11. */
let array2 = array1.filter((cur,i,arr) => (new Date(arr[i]['birth']).getMonth()) === (10-1));
console.log(array2);
```  

> 📙 `answer.`     
```javascript
// 2.12 
let array1 = [
       { name: "apple", birth: "2001-01-01" },
       { name: "banana", birth: "1990-10-10" },
       { name: "watermelon", birth: "1985-12-30" },
       { name: "peach", birth: "2002-10-13" },
     ]
//  array2 [
//    { name: "banana", birth: "1990-10-10" },
//    { name: "watermelon", birth: "1985-12-30" },
//  ] // filter คนเกิดก่อนปี 2000

let array2 = array1.filter((cur,i,arr) => (new Date(arr[i]['birth']).getFullYear()) < 2000);
console.log(array2);
```  

### Map และ Set ( slide 168 )  
+ 6.10. แบบฝึกหัด  
    + 1.ให้ arr เป็น Array สร้าง function ชื่อ unique(arr) ให้คืนค่าเป็น unique items ของ arr  
> 📙 `answer.`     
```javascript
function unique(arr) {
  /* your code */
    [...arr] = new Set(arr)
    return arr;
}
let values = ["Hare", "Krishna", "Hare", "Krishna", "Krishna", "Krishna", "Hare", "Hare", ":-O" ];

alert( unique(values) ); // Hare, Krishna, :-O
console.log(unique(values));
```  

### Map และ Set ( slide 169 )  
+ 6.10. แบบฝึกหัด  
    + 2.Anagram เป็นตัวอักษรที่มีจำนวนตัวอักษรแต่ละตัวที่เท่ากัน แต่เรียงไม่เหมือนกัน ( **Optional** )  
    + nap - pan  
    + ear - are - era  
    + cheaters - hectares - teachers  
> 📙 `answer.`     
```javascript
function aclean(a) {
    let arr1 = [];
    let arr2 = [];        
    for (let i=0; i < a.length; i++) {        
        let newArr = a.filter(x => x.length === a[i].length && [...(x.toLowerCase())].sort().join() === [...(a[i].toLowerCase())].sort().join());           
        if (newArr.length > 1) {            
            arr1.push(newArr[0]);
            arr2.push(newArr[1]);
        }        
    }
    [...arr1] = new Set(arr1);
    [...arr2] = new Set(arr2);
    return (`"${arr1}" or "${arr2}"`)
}
let arr = ["nap", "teachers", "cheaters", "PAN", "ear", "era", "hectares"];

alert( aclean(arr) ); // "nap,teachers,ear" or "PAN,cheaters,era"  (<--นี้คือโจทย์?[slide169])

console.log(aclean(arr));
```  

### Map และ Set ( slide 170 )  
+ 6.10. แบบฝึกหัด
    + 3.เราได้ array จาก map.keys() แต่ไม่สามารถใช้ push ได้ เราจะทำยังไงให้ keys.push สามารถทำงานได้
> 📙 `answer.`     
```javascript
let map = new Map();

map.set("name", "John");

let keys = map.keys();

// Error: keys.push is not a function 
// keys.push("more");

// แปลง object keys ให้เป็น array ถึงจะ push ได้ ...หรือไม่ก็ ตามโค้ดด้านล่าง (ไม่รู้เข้าใจถูกไหมนะครับ)
let arr = [];
for (let i of keys) {
    arr.push(i);
}
arr.push("more");

console.log(arr);
```  

### Keys, Values และ Entities ( slide 175 )  
+ 7.2. แบบฝึกหัด  
    + 1.กำหนดให้ salaries เป็น Object ให้เขียนฟังก์ชัน sumSalaries(salaries)   
    + ที่คืนค่าเป็นผลผมรวมของเงินเดือน ถ้า salaries ไม่มีสมาชิก ให้คืนค่าเป็น 0  
> 📙 `answer.`     
```javascript
let salaries = {
  "John": 100,
  "Pete": 300,
  "Mary": 250
};

function sumSalaries(salaries) {
    let arrValues = Object.values(salaries)  
    if (arrValues.length < 1) {
        return 0;
    }  
    return arrValues.reduce((a,b) => a + b);
}

alert( sumSalaries(salaries) ); // 650
console.log(sumSalaries(salaries));
```  

### Keys, Values และ Entities ( slide 176 )  
+ 7.2. แบบฝึกหัด  
    + 2.ให้เขียนฟังก์ชัน count(obj) ที่คืนค่าเป็นจำนวน properties ใน object  
> 📙 `answer.`     
```javascript
let user = {
  name: 'John',
  age: 30
};

function count(obj) {
    let arrProps = Object.keys(obj);    
    return arrProps.length;    
}

alert( count(user) ); // 2
console.log(count(user));
```  

