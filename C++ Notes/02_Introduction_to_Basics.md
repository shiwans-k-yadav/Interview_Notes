<!-- ======================= BASIC STRUCTURE ======================= -->

<h2 style="color:#E91E63;">🧾 4. Basic Structure of a C++ Program</h2>

```cpp
#include <iostream>
using namespace std;

int main() {
    cout << "Hello C++";
    return 0;
}
```

---

<!-- ======================= EXPLANATION ======================= -->

<h2 style="color:#3F51B5;">🧩 5. Component Breakdown</h2>

- 🔹 `#include <iostream>` → header file for input/output  
- 🔹 `using namespace std;` → lets us use `cout` without `std::`  
- 🔹 `int main()` → program entry point  
- 🔹 `cout` → prints output  
- 🔹 `return 0;` → program ends successfully  

---

<!-- ======================= SHORTCUTS ======================= -->

<h2 style="color:#FF9800;">⚡ 6. Useful Shortcuts</h2>

### 🔹 `#include <bits/stdc++.h>`
```cpp
#include <bits/stdc++.h>
using namespace std;
```
**Pros:**  
- Includes almost all standard libs  
- Saves time in CP  

**Cons:**  
- Not part of standard C++  
- Avoid in real projects  

---

### 🔹 Fast I/O
```cpp
ios::sync_with_stdio(false);
cin.tie(NULL);
```

### 🔹 Macro for long long
```cpp
#define ll long long
```

---

<!-- ======================= COMMON MISTAKES ======================= -->

<h2 style="color:#F44336;">⚠️ 8. Common Mistakes</h2>

<p style="background:#FFEBEE; padding:12px; border-left:4px solid #F44336;">
Common errors beginners make:
</p>

- ❌ Missing semicolon  
- ❌ `Main()` instead of `main()`  
- ❌ Using `cout` without `<iostream>`  
- ❌ Forgetting `return 0;`  
- ❌ Using `std::cout` without namespace  

---

<!-- ======================= INTERVIEW ======================= -->

<h2 style="color:#4CAF50;">❓ 9. Interview Questions</h2>

<p style="background:#E8F5E9; padding:12px; border-left:4px solid #4CAF50;">

<b>Q1:</b> Why is C++ faster than Python?  
<b>➡ A:</b> C++ is compiled + gives direct memory control.

<br><br>

<b>Q2:</b> What is the entry point of a program?  
<b>➡ A:</b> `main()` function.

<br><br>

<b>Q3:</b> Why do we write `using namespace std;`?  
<b>➡ A:</b> To avoid using `std::` again and again.
</p>

---

<!-- ======================= PRACTICE ======================= -->

<h2 style="color:#2196F3;">📝 10. Practice Tasks</h2>

- 🔸 Print your name  
- 🔸 Print sum of two numbers  
- 🔸 Print “I am learning C++” 5 times  
- 🔸 Modify the basic structure to print your age  

---

<!-- ======================= SUMMARY ======================= -->

<h2 style="color:#00BCD4;">✅ Summary (1-Minute Revision)</h2>

<ul>
  <li>✔ C++ = Fast, compiled, OOP-based</li>
  <li>✔ Used in systems, games, browsers, CP</li>
  <li>✔ Each program starts from <b>main()</b></li>
  <li>✔ `#include` brings libraries</li>
  <li>✔ `cout` prints output</li>
  <li>✔ Use `<bits/stdc++.h>` only for CP</li>
</ul>

---
