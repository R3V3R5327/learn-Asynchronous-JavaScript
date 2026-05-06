# 🚀 Introduction to Asynchronous JavaScript

This project contains beginner-friendly examples to understand the core concepts of **Asynchronous JavaScript**.

---

## 📚 Topics Covered

### 🔹 Synchronous JavaScript

* Executes code line by line
* Single-threaded behavior
* Blocking operations

### 🔹 Asynchronous JavaScript

* Non-blocking execution
* Handles time-consuming tasks efficiently

---

## ⚙️ Concepts Implemented

### ⏱️ setTimeout()

Executes a function after a delay.

### 🔁 setInterval()

Runs a function repeatedly at fixed intervals.

### 🤝 Promises

Handles asynchronous operations using:

* `.then()`
* `.catch()`

### ⚡ Promise Methods

* `Promise.all()`
* `Promise.race()`

### 🔗 Promise Chaining

### 🌐 Fetch API

Used to retrieve data from external APIs.

### 🔥 Async / Await

Modern and cleaner way to write asynchronous code.

---

## 🧪 Example: Random User Generator

```js
async function randomUser() {
  let urlAPI = await fetch('https://randomuser.me/api/');
  let rawData = await urlAPI.json();

  console.log(`${rawData.results[0].name.title} ${rawData.results[0].name.first} ${rawData.results[0].name.last}`);
  console.log(`${rawData.results[0].gender}`);
  console.log(`${rawData.results[0].location.country}`);
}

randomUser();
```

---

## 🎯 Learning Outcomes

* Understand synchronous vs asynchronous JavaScript
* Work with Promises effectively
* Fetch data from APIs
* Use async/await for cleaner code

---

## 🛠️ Tools Used

* JavaScript (ES6+)
* Browser Console / Node.js

---

## 📌 Author

**Sahariar Islam**

🎓 Learning JavaScript & Cybersecurity Enthusiast

---

## 📺 Learning Source

This project was built by following tutorials from the YouTube channel **Ali Hossain**.
It is created for learning and practice purposes only.

---

## ⭐ Future Improvements

* Build a simple UI to display user data
* Add button to fetch new users
* Implement proper error handling
* Use Axios instead of Fetch

---

## 📎 Notes

This project is part of my learning journey in JavaScript. More improvements and features will be added over time.

---
