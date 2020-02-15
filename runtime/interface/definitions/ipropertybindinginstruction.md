| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [ITargetedInstruction](/runtime/variable/definitions/itargetedinstruction.md) |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; type**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | TargetedInstructionType.propertyBinding |

&nbsp;&nbsp; **&#10148; mode**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [BindingMode](/runtime/enum/flags/bindingmode.md) |

&nbsp;&nbsp; **&#10148; from**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | string &#124; IAccessThisExpression &#124; IAccessScopeExpression &#124; IArrayLiteralExpression &#124; IObjectLiteralExpression &#124; IPrimitiveLiteralExpression&lt;StrictPrimitive&gt; &#124; ITemplateExpression &#124; ICallFunctionExpression &#124; ICallMemberExpression &#124; ICallScopeExpression &#124; IAccessMemberExpression &#124; IAccessKeyedExpression &#124; ITaggedTemplateExpression &#124; IUnaryExpression &#124; IBinaryExpression &#124; IConditionalExpression &#124; IAssignExpression &#124; IValueConverterExpression &#124; IBindingBehaviorExpression |

&nbsp;&nbsp; **&#10148; to**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | string |

&nbsp;&nbsp; **&#10148; oneTime**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | boolean &#124; undefined |