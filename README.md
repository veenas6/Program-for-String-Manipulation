# 📄 PHP String Functions Program

---

## 🌟 Project Overview

This project demonstrates how to perform **basic string manipulation** using built-in **PHP string functions**.

The program uses the string:

`PHP Programming`

and performs operations such as:

* Display Original String
* Find String Length
* Reverse the String
* Extract Substring

---

## 🎯 Objective

✔ Understand string handling in PHP
✔ Learn built-in PHP string functions
✔ Perform common string operations
✔ Display dynamic output using PHP

---

## 🛠️ Technologies Used

* 🐘 **PHP**
* 💻 **XAMPP / WAMP Server**
* 🌐 **Web Browser**
* 🧾 **Text Editor / VS Code**

---

## ⚙️ Working Principle

### 🔹 Step 1 — Create a String Variable

The string is stored in a PHP variable.

```php
$str = "PHP Programming";
```

---

### 🔹 Step 2 — Find String Length

The `strlen()` function returns the total number of characters.

```php
strlen($str);
```

---

### 🔹 Step 3 — Reverse the String

The `strrev()` function reverses the text.

```php
strrev($str);
```

---

### 🔹 Step 4 — Extract Substring

The `substr()` function extracts a portion of the string.

```php
substr($str, 0, 3);
```

---

## 💻 Program Code

```php
<?php
$str = "PHP Programming";

echo "Original String: $str <br>";
echo "Length: " . strlen($str) . "<br>";
echo "Reverse: " . strrev($str) . "<br>";
echo "Substring: " . substr($str, 0, 3);
?>
```

---

## ▶️ How to Run the Program

1️⃣ Install **XAMPP/WAMP**
2️⃣ Save file as:

```text
string.php
```

3️⃣ Move file into **htdocs** folder
4️⃣ Start Apache server
5️⃣ Open browser:

```text
http://localhost/string.php
```

---

## 🖥️ Sample Output

```text
Original String: PHP Programming
Length: 15
Reverse: gnimmargorP PHP
Substring: PHP
```

---

## ✨ Features

✅ Simple and easy to understand
✅ Uses built-in PHP functions
✅ Beginner-friendly example
✅ Demonstrates string operations
✅ Dynamic output display

---

## 📚 Learning Outcomes

* Understanding PHP strings
* Using string functions in PHP
* Manipulating text data
* Writing basic PHP programs

---

## 📌 Conclusion

This project successfully demonstrates how PHP handles string operations using built-in functions like `strlen()`, `strrev()`, and `substr()`. It is a great beginner project for learning PHP basics.
