### Temperature Converter II


---

### ✅ **C Program:**

```c
#include <stdio.h>

int main() {
    float fahrenheit = 98.3;
    printf("%f", (fahrenheit - 32) * 5 / 9);
    return 0;
}
```

---

### 🔍 **Explanation:**

To convert Fahrenheit to Celsius, we rearrange the original formula:

```
fahrenheit = (celsius * 9 / 5) + 32
```

Solving for `celsius`:

```
celsius = (fahrenheit - 32) * 5 / 9
```

So with `fahrenheit = 98.3`, we compute:

```
(98.3 - 32) * 5 / 9 = 36.83333
```

### ✅ Output:

```
36.83333
```

