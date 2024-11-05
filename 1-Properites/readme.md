Here's your updated `README.md` file with the added content at the end:

```markdown
# Properties of JavaScript

Every programming language comes with its unique set of features. JavaScript has the following:

## 1. Interpreted
JavaScript is an interpreted language, meaning it's executed line-by-line at runtime by the JavaScript engine in the browser or server environment, rather than being compiled into machine code beforehand.

![Interpreted Language Diagram](/pic-1.webp)

### Upsides
- There is one less step to do before running your code.

### Downsides
- Performance Overhead
- More prone to runtime errors

---

## 2. Dynamically Typed
Variables in JavaScript are not bound to a specific data type. Types are determined at runtime and can change as the program executes.

### Example: C++ Code (won’t compile)
```cpp
#include <iostream>

int main() { 
  int a = 1;
  a = "hello";  // Error: Type mismatch
  a = true;     // Error: Type mismatch
}
```

### Example: JavaScript Code (will execute)
```javascript
var a = 1;
a = "harkirat";
a = true;

console.log(a); // Output: true
```

---

## 3. Single-Threaded
JavaScript executes code in a single-threaded environment, meaning it processes one task at a time. We will dive deeper into this next week.

![Single Threaded Diagram](/pic-1.webp)
![Single threaded Diagram](/Screenshot_2024-08-04_at_6.13.11_PM.webp)


---

## 4. Garbage Collected
JavaScript automatically manages memory allocation and deallocation through garbage collection, which helps prevent memory leaks by automatically reclaiming memory used by objects no longer in use.

![Garbage Language Diagram](/p-3.webp)


---

## Conclusion
**Is JavaScript a good language?**
- **Yes and no.** It is beginner-friendly but has a lot of performance overhead. Tools like Bun are trying to address these performance concerns, but there’s still a long way to go before JavaScript can compete with languages like C++ or Rust.

![JavaScript Logo](logo_image_link_here)

---

