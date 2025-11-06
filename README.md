# Nahin Search

Nahin Search একটি ছোট সার্চ ইঞ্জিন ওয়েবসাইট যা HTML, CSS এবং JavaScript দিয়ে তৈরি।  
এখানে তুমি নিজের দেওয়া লিংক বা তথ্য সার্চ করতে পারবে।  

## 🔹 Features
- সার্চ বক্স থেকে লিংক খোঁজা  
- Category filter (Social, Movie, App, Other)  
- Responsive এবং Mobile-friendly design  
- নতুন আইটেম সহজে `scripts.js` এ যোগ করা যায়  

## 🔹 Live Demo
[Open Nahin Search](https://yourusername.github.io/nahin-search/)

## 🔹 How to Use
1. সার্চ বক্সে লিখে খুঁজে দেখো  
2. রেজাল্ট লিংক ওপেন করো  

## 🔹 How to Add New Item
1. `scripts.js` ফাইল খুলো  
2. DATA অ্যারেতে নতুন অবজেক্ট যোগ করো, যেমন:
```javascript
DATA.push({
  id: 5,
  title: "Twitter",
  url: "https://twitter.com",
  description: "Social media platform for short messages.",
  category: "social",
  tags: ["social", "chat", "tweet"]
});
