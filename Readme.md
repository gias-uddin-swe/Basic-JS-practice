// variable
// ভেরিয়েবল বলতে এমন কিছুকে বোঝানো হয়ে থাকে যার মান সময়ের সাথে সাথে বদলানো যায়। যার মান সময়ের সাথে সাথে বিভিন্ন ভাবে প্রভাবিত হতে পারে

// ভেরিয়েবল হচ্ছে কম্পিউটার মেমোরি একটি নির্দিষ্ট জায়গা যেখানে বিভিন্ন মান সংরক্ষণ করে রাখা যায়

// ভ্যারিয়েবল লেখার জন্য যা যা ব্যবহার করতে পারবেন

// 1. Letter(A-z)
// 2. Number {0-9}
// 3. UnderScore (\_)
// 4. Doller ($)

// ভ্যারিয়েবল লেখার জন্য যা যা ব্যবহার করতে পারবেন না

// 1. কি ওয়ার্ড ব্যবহার করা যাবে না

// 2. নম্বর শুরুতেই ব্যবহার করা যাবে না
// 3. স্পেস দেওয়া যাবে না

// 4. কেস সেনসিটিভ হওয়ায় সেইম টু সেইম হতে হবে

// note : CamelCase

var name = "gias uddin";

// Key Words

// জাভাস্ক্রিপ্ট আপনার জন্য কিছু জিনিস (ফাঙ্কশন ) অলরেডি তৈরী করে রাখছে এইগুলাই রিজার্ভ ওয়ার্ড অথবা কি ওয়ার্ড

if (true) {
console.log("yesssssss");
}

// এই গুলা মুখুস্থ করার কোনো জিনিস না তাই চিন্তা করার দরকার নাই আস্তে আস্তে সব এমনেই মনের মধ্যে বসে যাবে ব্যাবহার করতে করতে

// DAta Types

// আমরা মূলত এখানে স্ট্রিং এবং নম্বর এবং বুলিয়েন ডাটা টাইপ আলোচনা করবো

// 1. string

var name1 = "hero Alom";

console.log(typeof name1);

// number data types
var roll = 71;

console.log(typeof roll);

// boolean data types
var statement = true;
console.log(typeof statement);

// \*parseFloat parseInt

var num1 = 70.78;
var num2 = 70;

var sum = num1 + num2;
console.log(parseInt(sum));
// console.log(parseFloat(sum));

// ## If else statement

if (4 > 5) {
console.log("4 is bigger than 5");
} else {
console.log("5 is bigger than 4");
}

// 2nd examaple with condition
var number = 50;
if (number % 2 == 0) {
console.log(" wow its even number");
} else if (number % 2 == 1) {
console.log("wow its Oddd number");
} else {
console.log("dont knwo whats that ");
}
