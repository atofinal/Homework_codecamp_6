# JavaScript (Folder)

## part1
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

## part2
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
![](/05_JavaScript/test_s/02.png?raw=false)
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








> 📙 `answer.`  
```javascript

```  