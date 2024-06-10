```javascript
/* direction: ltr */
// مثال 1: تعريف سترينق (String)
let greeting = "Hello, world!";
console.log(greeting); // Hello, world!

greeting = "Hi there!";
console.log(greeting); // Hi there!

// مثال 2: تعريف أرقام (Numbers)
let age = 25;
console.log(age); // 25

age = 26;
console.log(age); // 26

// مثال 3: تعريف متغيرات متعددة
let name = "John";
let height = 180;
let isStudent = true;

console.log(name);      // John
console.log(height);    // 180
console.log(isStudent); // true

// إعادة تعيين القيم
name = "Doe";
height = 175;
isStudent = false;

console.log(name);      // Doe
console.log(height);    // 175
console.log(isStudent); // false

// مثال 4: استخدام المتغيرات في عملية حسابية
let num1 = 10;
let num2 = 20;
let sum = num1 + num2;
console.log(sum); // 30

// إعادة تعيين القيم
num1 = 15;
num2 = 25;
sum = num1 + num2;
console.log(sum); // 40

// مثال 5: استخدام النصوص في دمج النصوص
let firstName = "Alice";
let lastName = "Smith";
let fullName = firstName + " " + lastName;
console.log(fullName); // Alice Smith

// إعادة تعيين القيم
firstName = "Bob";
lastName = "Johnson";
fullName = firstName + " " + lastName;
console.log(fullName); // Bob Johnson

// استخدام النصوص القالبية مع علامة الدولار

// مثال 6: دمج المتغيرات
let product = "Laptop";
let price = 1200;
let message = `The price of the ${product} is $${price}.`;

console.log(message); // The price of the Laptop is $1200.

// مثال 7: التعبيرات الرياضية
let a = 5;
let b = 10;
let sumMessage = `The sum of ${a} and ${b} is ${a + b}.`;

console.log(sumMessage); // The sum of 5 and 10 is 15.

// مثال 8: استدعاء دالة داخل النص القالبي
function greet(name) {
    return `Hello, ${name}!`;
}

let user = "Alice";
let welcomeMessage = `${greet(user)}`;

console.log(welcomeMessage); // Hello, Alice!

// مثال 9: استخدام الشرطيات
let isMember = true;
let discountMessage = `You ${isMember ? "get" : "do not get"} a discount.`;

console.log(discountMessage); // You get a discount.
// الحصول على العنصر الذي تريد تعيين نصه
let element = document.getElementById("myElement");

// تعيين نص المحتوى باستخدام خاصية textContent
element.textContent = "هذا هو النص الجديد.";


```
