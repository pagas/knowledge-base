# ✅ What `range()` does

`range()` generates a **sequence of numbers**.

- It is commonly used in loops
- It does **not create a list** (it returns a _range object_)
- It is **memory efficient** (numbers are generated on demand)

---

## ✅ Syntax

```
range(start, stop, step)
```

- **start** → where to begin (default = 0)
- **stop** → where to end (**excluded**)
- **step** → increment (default = 1)

---

## ✅ Key Idea

👉 “Start at `start`, keep adding `step`, stop _before_ `stop`”

---

# ✅ `range()` Cheat Sheet (Table)

|Concept|Explanation|
|---|---|
|Purpose|Generates a sequence of numbers|
|Return type|`range` object (not a list)|
|Default start|0|
|Stop behavior|Stop value is **excluded**|
|Default step|1|
|Step direction|Positive → forward, Negative → backward|
|Memory usage|Efficient (doesn't store all values)|
|Common use|Loops (`for`)|

---

# ✅ Common Patterns

|Pattern|Meaning|
|---|---|
|`range(n)`|Numbers from 0 to n−1|
|`range(a, b)`|Numbers from a to b−1|
|`range(a, b, s)`|Numbers from a stepping by s until before b|

# ✅ Quick Summary Table

| Call              | Output sequence |
| ----------------- | --------------- |
| `range(3)`        | 0, 1, 2         |
| `range(2, 6)`     | 2, 3, 4, 5      |
| `range(1, 10, 3)` | 1, 4, 7         |
| `range(5, 0, -1)` | 5, 4, 3, 2, 1   |