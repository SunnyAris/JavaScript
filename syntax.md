# Values

Fixed values are called Literals.

Variable values are called Variables.

## Literals

Numbers are written with or without decimals:
```
<script>
document.getElementById("demo").innerHTML = 10.50;
</script>
```

Strings are text, written within double or single quotes:

```
"John Doe"

'John Doe'
```

## Variables

Variables are used to store data values.

JavaScript uses the keywords var, let and const to declare variables.

```
let x;
x = 2;
```

# Operators

JavaScript uses arithmetic operators ( + - * / ) to compute values:

```
<script>
document.getElementById("demo").innerHTML = (1 + 1) * 2;
</script>
```
and assignment operator ( = ) to assign values to variables:

```
let x, y;
x = 5;
y = 6;
```

# Expressions

An expression is a combination of values, variables, and operators, which computes to a value.

```
<script>
document.getElementById("demo").innerHTML = 5 * 10;
</script>
```
Expressions can also contain variable values:

```
<script>
var x;
x = 5;
document.getElementById("demo").innerHTML = x * 10;
</script>
```
"John" + " " + "Doe", evaluates to "John Doe":



```
<script>
document.getElementById("demo").innerHTML = "John" + " "  + "Doe";
</script>
```

# Keywords

JavaScript keywords are used to identify actions to be performed

```
let x, y;
x = 1 + 1;
y = x * 2;
```

```
var x, y;
x = 1 + 1;
y = x * 2;
```

# Comments

Code after double slashes // or between /* and */ is treated as a comment.

```
let x = 1;   // I will be executed

// x = 1;   I will NOT be executed
```

# Identifiers / Names

Identifiers are used to name variables and keywords, and functions.

A letter (A-Z or a-z)

A dollar sign ($)

Or an underscore (_)

# Case Sensitive

JavaScript does not interpret LET or Let as the keyword let.

The variables lastName and lastname, are two different variables:

```
let lastname, lastName;
lastName = "Doe";
lastname = "John";
```


