# ContractStdlib

*Version: 0.1.0*

the offficial ObjektRT standard library

---

## Table of Contents

- **ObjektRT.Std**
  - [abs](#abs)
  - [inc](#inc)
  - [mul](#mul)
  - [negate](#negate)

---

## ObjektRT.Std

### abs

**function**

```contract
let abs = fn (x: int) -> {
```

returns the absolute value.

**Parameters:**

| Name | Type | Description |
|------|------|-------------|
| `x` | `int` |  |

---

### inc

**function**

```contract
let inc = fn (x) -> x + 1;
```

increments a value

**Parameters:**

| Name | Type | Description |
|------|------|-------------|
| `x` | `` |  |

**Returns:** `x + 1`

**Example:**

```contract
var apples = inc(5);
IO.Println("apples: " + Convert.ToString(apples)));
```

---

### mul

**function**

```contract
let mul = fun (a: int, b: int) -> a * b;
```

multiplies 2 numbers.

**Parameters:**

| Name | Type | Description |
|------|------|-------------|
| `a` | `int` |  |
| `b` | `int` |  |

**Returns:** `a * b`

---

### negate

**function**

```contract
let negate: int = fn (x: int) -> 0 - x;
```

negates the input.

**Returns:** `int = fn (x: int) -> 0 - x`

---

