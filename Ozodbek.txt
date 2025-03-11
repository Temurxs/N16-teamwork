1. Javascriptda qanday ma'lumot turlari mavjud?

   Primitive ma'lumot turlari:
   - Number (sonlar) -> `let x = 5;`
   - String (matn) -> `let str = "Hello";`
   - Boolean (mantiqiy) -> `let isTrue = true;`
   - Undefined -> `let a;`
   - Null -> `let b = null;`
   - Symbol -> `let sym = Symbol("id");`
   - BigInt -> `let big = 12345678901234567890n;`

   Non-primitive ma'lumot turlari:
   - Object -> `let obj = {name: "John", age: 25};`
   - Array -> `let arr = [1, 2, 3];`
   - Function -> `function foo() { return "Hello"; }`

   Null va Undefined o'rtasidagi farq:
   - `null` - qiymati yo‘qligini anglatadi.
   - `undefined` - o‘zgaruvchiga hech qanday qiymat berilmaganligini bildiradi.

2. Javascriptda qanday qilib o'zgaruvchi yaratish mumkin?
   - `var`, `let`, `const` yordamida o‘zgaruvchi yaratish mumkin.
   - `var` – eski usul, block scope'ga ega emas, hoisting mavjud.
   - `let` – block scope'ga ega, hoisting mavjud, lekin `var` dan farqli ravishda redeclare qilib bo‘lmaydi.
   - `const` – o‘zgaruvchining qiymatini o‘zgartirib bo‘lmaydi.

   Scope va Hoisting:
   - Scope - o‘zgaruvchining ko‘rinish doirasi (`global`, `local`, `block`).
   - Hoisting - `var` bilan e’lon qilingan o‘zgaruvchilar kodning yuqori qismiga ko‘tariladi.

3. while va do while o'rtasidagi farq?
   - `while` - shart bajarilsa, sikl ishlaydi.
   - `do while` - sikl avval kamida bir marta bajarilib, keyin shart tekshiriladi.

4. Object metodlari:
   - `Object.keys(obj)` – object kalitlarini qaytaradi.
   - `Object.values(obj)` – object qiymatlarini qaytaradi.
   - `Object.entries(obj)` – objectni array shaklida qaytaradi.
   - `Object.assign(target, source)` – objectni nusxalaydi.
   - `Object.freeze(obj)` – objectni o‘zgarmas qiladi.

5. Array metodlari:
   - `push()` – element qo‘shish.
   - `pop()` – oxirgi elementni o‘chirish.
   - `shift()` – birinchi elementni o‘chirish.
   - `unshift()` – boshiga element qo‘shish.
   - `map()` – har bir elementga amal bajarish.
   - `filter()` – shart bo‘yicha elementlarni tanlash.
   - `reduce()` – barcha elementlarni bitta qiymatga aylantirish.

6. Funksiya nima?
   - Kod bloklarini qayta ishlatish uchun yoziladigan blok.
   - Turlari: `Function Declaration`, `Function Expression`, `Arrow Function`, `IIFE`.

7. Pure va Impure function o'rtasidagi farq?
   - `Pure` function bir xil kiruvchi qiymat uchun har doim bir xil natijani qaytaradi.
   - `Impure` function tashqi omillarga bog‘liq bo‘lishi mumkin.

8. String metodlari:
   - `length` – uzunlikni qaytaradi.
   - `toUpperCase()` – katta harfga o‘girish.
   - `toLowerCase()` – kichik harfga o‘girish.
   - `trim()` – bo‘sh joylarni olib tashlash.
   - `slice(start, end)` – bo‘lak ajratish.
   - `split(separator)` – satrni massivga aylantirish.
   - `includes(substring)` – satr ichida so‘z borligini tekshirish.
   - `replace(old, new)` – bir so‘zni boshqasiga almashtirish.

9. call, apply, bind farqi?
   - `call` – funksiya chaqirish va argumentlarni vergul bilan berish.
   - `apply` – funksiya chaqirish va argumentlarni array sifatida berish.
   - `bind` – yangi funksiya yaratadi va kontekstni bog‘laydi.

10. Map va Object farqi?
   - `Object` - kalitlar faqat `string` yoki `symbol` bo‘lishi mumkin.
   - `Map` - har qanday turdagi kalitlarga ega bo‘lishi mumkin.

11. OOP nima?
   - Object-Oriented Programming (Obyektga yo‘naltirilgan dasturlash).

12. OOPning tamoyillari:
   - **Encapsulation** – ma’lumotlarni yashirish.
   - **Abstraction** – faqat muhim qismlarni ko‘rsatish.
   - **Inheritance** – meros olish.
   - **Polymorphism** – bir funksiya turli usullarda ishlashi.

13. typeof va instanceof farqi?
   - `typeof` - ma'lumot turini aniqlaydi.
   - `instanceof` - object qaysi classdan ekanligini tekshiradi.

14. Promise nima?
   - Asinxron kodni bajarish uchun ishlatiladi.
   - Holatlar: `pending`, `fulfilled`, `rejected`.

15. Promise metodlari:
   - `then()` – muvaffaqiyatli bajarsa ishlaydi.
   - `catch()` – xato bo‘lsa ishlaydi.
   - `finally()` – har doim ishlaydi.

16. Event Loop nima?
   - Javascript qanday qilib asinxron kodlarni boshqarishi.
   - Call Stack, Web APIs, Task Queue, Microtask Queue tushunchalarini o‘z ichiga oladi.

17. CRUD nima?
   - Create, Read, Update, Delete.
   - `fetch` va `axios` orqali ma’lumotlarni olish, o‘zgartirish va o‘chirish amallari bajariladi.

18. DOM nima? Kamida 5ta event turi?
   - Document Object Model - HTML tuzilmasini boshqarish.
   - Eventlar: `click`, `mouseover`, `keydown`, `keyup`, `change`.

