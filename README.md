A simple PHP program demonstrating basic string manipulation using built-in PHP functions.

## 📌 Overview

This project performs different operations on the string:

`PHP Programming`

The program displays:

* Original String
* String Length
* Reversed String
* Substring Extraction

## 💻 Source Code

```php
<?php
$str = "PHP Programming";

echo "Original String: $str <br>";
echo "Length: " . strlen($str) . "<br>";
echo "Reverse: " . strrev($str) . "<br>";
echo "Substring: " . substr($str, 0, 3);
?>
```

## 🚀 Output

```text
Original String: PHP Programming
Length: 15
Reverse: gnimmargorP PHP
Substring: PHP
```

## 🛠 Functions Used

| Function   | Purpose                          |
| ---------- | -------------------------------- |
| `strlen()` | Returns length of the string     |
| `strrev()` | Reverses the string              |
| `substr()` | Extracts a portion of the string |

## ▶️ How to Run

1. Save the file as `string.php`
2. Place it in the `htdocs` folder (XAMPP)
3. Start Apache server
4. Open in browser:

```text
http://localhost/string.php
```

## 📚 Learning Objective

This project helps beginners understand:

* PHP syntax
* String handling
* Built-in functions in PHP

