<h1 align="center" style="color:#4CAF50;">⭐ 03 – Variables & Data Types</h1>

<hr style="border:1px solid #ddd;">


<!-- ====================================================== -->
<h2 style="color:#2196F3;">📌 1. What is a Variable?</h2>

<p style="background:#E3F2FD; padding:12px; border-left:4px solid #2196F3;">
A variable is a named memory location used to store data.
</p>

**Key Points**
- 🔹 Name given to a memory location  
- 🔹 Value can change during program execution  
- 🔹 Must be declared before use  
- 🔹 Stores different types of data (int, float, char, etc.)  


---

<!-- ====================================================== -->
<h2 style="color:#9C27B0;">📌 2. Variable Declaration</h2>

```cpp
int age;
float salary;
char grade;
```

**Rules**
- 🔹 Must start with letter or `_`  
- 🔹 Cannot start with a number  
- 🔹 Case-sensitive (`Age` ≠ `age`)  
- 🔹 No spaces allowed  
- 🔹 Cannot use C++ keywords (int, float, if, return…)  


---

<!-- ====================================================== -->
<h2 style="color:#009688;">📌 3. Variable Initialization</h2>

```cpp
int age = 20;
float salary = 45000.5;
char grade = 'A';
```

**Types of Initialization**
- 🔹 **Direct:** `int a = 5;`  
- 🔹 **Separate:** `int a; a = 5;`  
- 🔹 **Multiple:** `int x=1, y=2, z=3;`  


---

<!-- ====================================================== -->
<h2 style="color:#E91E63;">📌 4. What is a Data Type?</h2>

<p style="background:#FCE4EC; padding:12px; border-left:4px solid #E91E63;">
A data type defines the type and size of data a variable can store.
</p>

---

<!-- ====================================================== -->
<h2 style="color:#3F51B5;">📌 5. Basic Data Types in C++</h2>

<p style="background:#E8EAF6; padding:12px; border-left:4px solid #3F51B5;">
Below are the most commonly used data types:
</p>

| Data Type | Meaning | Size (approx.) |
|----------|---------|----------------|
| `int` | integer values | 4 bytes |
| `float` | decimal values (single precision) | 4 bytes |
| `double` | decimal values (double precision) | 8 bytes |
| `char` | single character | 1 byte |
| `bool` | true/false | 1 byte |

> Note: Size may differ slightly based on compiler/system.


---

<!-- ====================================================== -->
<h2 style="color:#FF9800;">📌 6. Range of Data Types</h2>

<p style="background:#FFF3E0; padding:12px; border-left:4px solid #FF9800;">
Ranges vary by compiler, but typical values:
</p>

- 🔹 `int` → −2,147,483,648 to 2,147,483,647  
- 🔹 `char` → −128 to 127  
- 🔹 `bool` → true / false  
- 🔹 `float` → 6–7 decimal digits  
- 🔹 `double` → 15+ decimal digits  


---

<!-- ====================================================== -->
<h2 style="color:#F44336;">⚠️ 7. Common Mistakes</h2>

<p style="background:#FFEBEE; padding:12px; border-left:4px solid #F44336;">
Avoid these beginner mistakes:
</p>

- ❌ Using a variable without declaring it  
- ❌ Storing decimal value in `int`  
- ❌ Using `' '` incorrectly for multi-characters  
- ❌ Using uninitialized variables  
- ❌ Writing `char grade = "A";` → should be `'A'`  


---

<!-- ====================================================== -->
<h2 style="color:#4CAF50;">❓ 8. Interview Questions</h2>

<p style="background:#E8F5E9; padding:12px; border-left:4px solid #4CAF50;">

<b>Q1:</b> What is the difference between variable declaration and initialization?  
<b>➡ A:</b> Declaration reserves memory; initialization assigns value.

<br><br>

<b>Q2:</b> What is the size of int/float/double?</b>  
<b>➡ A:</b> int = 4B, float = 4B, double = 8B (depends on compiler).

<br><br>

<b>Q3:</b> Why does `char` take 1 byte?  
<b>➡ A:</b> It stores only 1 ASCII character.

<br><br>

<b>Q4:</b> Why should variables be initialized?  
<b>➡ A:</b> Uninitialized variables contain garbage values.
</p>

---

<!-- ====================================================== -->
<h2 style="color:#2196F3;">📝 9. Practice Tasks</h2>

- 🔸 Declare variables for name, age, salary  
- 🔸 Store any character grade  
- 🔸 Declare three integers in one line  
- 🔸 Test garbage value by printing an uninitialized variable (just for learning)  


---

<!-- ====================================================== -->
<h2 style="color:#00BCD4;">✅ Summary</h2>

<ul>
  <li>✔ Variables store data in memory</li>
  <li>✔ Data types decide the type & size of data</li>
  <li>✔ `int`, `float`, `char`, `bool` = common types</li>
  <li>✔ Declaration ≠ Initialization</li>
  <li>✔ Uninitialized variables hold garbage values</li>
</ul>

---
