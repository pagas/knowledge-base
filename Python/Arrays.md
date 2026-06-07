| 📌 Category       | Operation                                           | Example                                                              |
| ----------------- | --------------------------------------------------- | -------------------------------------------------------------------- |
| **Create**        | Create list                                         | `arr = [1, 2, 3]`<br>`arr = list(([1, 2, 3]))`                       |
|                   | Repeat values                                       | `arr = [0] * 5`                                                      |
| **Access**        | First / last element                                | `arr[0]`, `arr[-1]`                                                  |
|                   | <br>Slice elements<br>Get first two<br>Every second | `arr[start:stop:step]` <br>`arr[1:3]`, <br>`arr[:2]`, <br>`arr[::2]` |
| **Modify**        | Update value                                        | `arr[1] = 10`                                                        |
|                   | Replace slice                                       | `arr[1:3] = [20, 30]`                                                |
| **Add**           | Add one item                                        | `arr.append(4)`                                                      |
|                   | Add multiple                                        | `arr.extend([5, 6])`                                                 |
|                   | Insert at index                                     | `arr.insert(1, 99)`                                                  |
| **Remove**        | Remove by value                                     | `arr.remove(2)`                                                      |
|                   | Remove last                                         | `arr.pop()`                                                          |
|                   | Remove by index                                     | `arr.pop(1)`, `del arr[0]`                                           |
|                   | Clear list                                          | `arr.clear()`                                                        |
| **Check**         | Length                                              | `len(arr)`                                                           |
|                   | Min / Max / Sum                                     | `min(arr)`, `max(arr)`, `sum(arr)`                                   |
|                   | Membership                                          | `2 in arr`                                                           |
| **Loop**          | Simple loop                                         | `for x in arr:`                                                      |
|                   | With index                                          | `for i, x in enumerate(arr):`                                        |
| **Sort**          | Sort in-place                                       | `arr.sort()`                                                         |
|                   | Reverse sort                                        | `arr.sort(reverse=True)`                                             |
|                   | New sorted list                                     | `sorted(arr)`                                                        |
| **Copy**          | Copy list                                           | `arr.copy()`, `arr[:]`                                               |
| **Comprehension** | Transform                                           | `[x*2 for x in arr]`                                                 |
|                   | Filter                                              | `[x for x in arr if x > 2]`                                          |
| **2D List**       | Matrix access                                       | `matrix[0][1]`                                                       |
