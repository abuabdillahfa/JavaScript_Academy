
**=====================📚Lesson 1: Variable কী?===============**


1. Variable হলো একটি নামযুক্ত পাত্র (Container), যেখানে আমরা Data সংরক্ষণ করি।
2. ডাটাকে যে নামে ডাকা হয়, সেটাই Variable Name।
3. Variable-এর ভিতরে যে Data থাকে, সেটাই Value।
4. let হলো JavaScript-এর একটি Keyword, যা নতুন Variable তৈরি করতে ব্যবহৃত হয়।



**==============📚Lesson 2: Variable Naming Rules==================**

1. 🎯 Rule 1: Variable Name কখনো সংখ্যা দিয়ে শুরু করা যাবে না।
let name1 = "Abu";
 // ? let 1name = "Abu"; ❌ ভুল


2. 🎯 Rule 2: Variable Name-এ Space (ফাঁকা জায়গা) রাখা যাবে না।
let myName = "Abu";
 // ? let my name = "Abu"; ❌ ভুল


3. 🎯 Rule 3: Variable Name-এ শুধু কী কী ব্যবহার করা যায়?
✅ ইংরেজি অক্ষর (a-z, A-Z)
✅ সংখ্যা (0-9) — তবে শুরুতে নয়
✅ _ (underscore)
✅ $ (dollar sign)

/*
let firstName = "Abu";
let user_name = "Abu";
let _count = 10;
let $price = 500;
*/
  


  *Reserved Keyword কী?*
// ? JavaScript-এর কিছু শব্দ আগে থেকেই নিজের কাজের জন্য সংরক্ষণ করে রেখেছে। এগুলোকে বলে Reserved Keywords।

/*
let
const
if
else
for
while
function
class
return
switch  
*/ 

/*

**==============📚Lesson 3: Data Types (Part 1)==================**
JavaScript-এ Quotes ("" বা '') এর ভিতরে থাকা Text Data-কে String বলে।

// ? Quotes-এর ভিতরে যা থাকবে, JavaScript সেটাকে String হিসেবে গণ্য করবে।

 এমনকি যদি সেটা সংখ্যা হয়।

অর্থাৎ:

"10"
"500"
"99999"

এগুলো সবই String।

**=======================📚 Lesson 3.2 (String)====================**

আজ String-এর আরেকটি গুরুত্বপূর্ণ বিষয় শিখব।


Single Quote ('') এবং Double Quote ("")

দেখো:

let country = "Bangladesh";

এবং

let country = 'Bangladesh';


❓ প্রশ্ন:

দুটোর মধ্যে কোনটি String?

উত্তর হলো...

👉 দুটোই String। ✅

JavaScript-এ "" এবং ''—দুটো দিয়েই String লেখা যায়।

🎯 উদাহরণ
let firstName = "Abu";
let lastName = 'Abdullah';
let city = "Mymensingh";
let country = 'Bangladesh';

**=======================📚 Lesson 3.3 (Number)====================**
📖 Number কী?

Number হলো এমন একটি Data Type যা সংখ্যা (Numeric Value) সংরক্ষণ করে।


🌍 বাস্তব উদাহরণ

ধরো তুমি একটি দোকানে গেলে।

তুমি দেখলে:

দাম = 250 টাকা
স্টক = 40টি
বয়স = 20 বছর

এগুলো কি লেখা (Text)?

❌ না।

এগুলো সংখ্যা (Number)।

JavaScript-এ সব ধরনের সংখ্যাকে Number বলা হয়।


 // ? আরেকটি উদাহারণ
ধরো:

তোমার বয়স = 25
মোবাইলের দাম = 18500
শরীরের তাপমাত্রা = 36.5
ব্যাংক ব্যালেন্স = -500 (ধরো ঋণ)

এসবই Number।

⚠️ সবচেয়ে গুরুত্বপূর্ণ নিয়ম

দেখো:

let age = 25;

এখানে 25 হলো Number।

কিন্তু—

let age = "25";

এখানে "25" হলো String।

📌 Quotes থাকলে Number-ও String হয়ে যায়।

এটি JavaScript-এর সবচেয়ে গুরুত্বপূর্ণ নিয়মগুলোর একটি।

📒 JavaScript Mastery Program
Lesson 4: Number (Revision Note)
🎯 Number কী?

Number হলো JavaScript-এর একটি Data Type, যা সব ধরনের সংখ্যা সংরক্ষণ করতে ব্যবহৃত হয়।

📌 Number-এর ধরন
1. Integer (পূর্ণ সংখ্যা)

দশমিক (.) ছাড়া সংখ্যা।

উদাহরণ:

25
100
0
-15
2. Decimal / Float (দশমিক সংখ্যা)

যে সংখ্যায় দশমিক (.) থাকে।

উদাহরণ:

36.5
3.14
0.75
-10.25
3. Negative Number (ঋণাত্মক সংখ্যা)

যে সংখ্যার আগে - থাকে।

উদাহরণ:

-5
-100
-0.75
📌 Number vs String
25

➡️ Number

"25"

➡️ String

36.5

➡️ Number

"36.5"

➡️ String

🧠 মনে রাখার নিয়ম

Quotes ("" বা '') থাকলে → String

Quotes না থাকলে → Number

⚠️ Common Mistakes

❌ ভুল

let age = "25";

যদি বয়স সংখ্যা হিসেবে রাখতে চাও।

✅ সঠিক

let age = 25;
💡 Tips
0 একটি Number।
ঋণাত্মক সংখ্যা (-10) ও Number।
দশমিক সংখ্যা (36.5) ও Number।
JavaScript-এ Integer ও Decimal—দুটোই Number।
📦 Memory Box
25        → Number
-10       → Number
36.5      → Number
0         → Number

"25"      → String
"36.5"    → String
"Hello"   → String
📝 আজকের Lesson Summary
✅ Number কী
✅ Integer
✅ Decimal (Float)
✅ Negative Number
✅ Number ও String-এর পার্থক্য
✅ Quotes থাকলে Number-ও String হয়ে যায়


