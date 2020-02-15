| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [ITargetedInstruction](/runtime/variable/definitions/itargetedinstruction.md) |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; type**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | HTMLTargetedInstructionType.attributeBinding |

&nbsp;&nbsp; **&#10148; from**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | string &#124; IAccessThisExpression &#124; IAccessScopeExpression &#124; IArrayLiteralExpression &#124; IObjectLiteralExpression &#124; IPrimitiveLiteralExpression&lt;StrictPrimitive&gt; &#124; ITemplateExpression &#124; ICallFunctionExpression &#124; ICallMemberExpression &#124; ICallScopeExpression &#124; IAccessMemberExpression &#124; IAccessKeyedExpression &#124; ITaggedTemplateExpression &#124; IUnaryExpression &#124; IBinaryExpression &#124; IConditionalExpression &#124; IAssignExpression &#124; IValueConverterExpression &#124; IBindingBehaviorExpression |

&nbsp;&nbsp; **&#10148; attr**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

`attr` and `to` have the same value on a normal attribute
Will be different on `class` and `style`
on `class`: attr = `class` (from binding command), to = attribute name
on `style`: attr = `style` (from binding command), to = attribute name

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | string |

&nbsp;&nbsp; **&#10148; to**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | string |