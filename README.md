
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
// ? Quotes-এর ভিতরে যা থাকবে, JavaScript সেটাকে String হিসেবে গণ্য করবে।

 এমনকি যদি সেটা সংখ্যা হয়।

অর্থাৎ:

"10"
"500"
"99999"

এগুলো সবই String।

**=======================📚 Lesson 3 (Part 2)====================**

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

🤔 তাহলে দুই ধরনের Quote কেন?

এটা খুব গুরুত্বপূর্ণ।

ধরো তুমি লিখতে চাও:

I'm learning JavaScript

যদি এভাবে লেখো:

let text = 'I'm learning JavaScript';

🚨 Error হবে।

কারণ ' (apostrophe) আর String-এর শেষের Quote একে অপরের সাথে সংঘর্ষ করবে।

তখন আমরা লিখি:

let text = "I'm learning JavaScript";

✔️ এবার ঠিক।

আবার যদি String-এর ভিতরে Double Quote দরকার হয়:

let text = 'He said "Hello"';

✔️ এটাও ঠিক।


# test
