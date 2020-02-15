# &#10025; Summary

Describes a type that specifically tracks changes in an object property, or simply something that can have a getter and/or setter

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#10025; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| TObj | -          |

| Type  | Constraint |
| ----- | ---------- |
| TProp | -          |

| Type   | Constraint |
| ------ | ---------- |
| TValue | -          |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; obj**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | TObj |

&nbsp;&nbsp; **&#10148; propertyKey**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | TProp &#124; undefined |

&nbsp;&nbsp; **&#10148; currentValue**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | TValue &#124; undefined |