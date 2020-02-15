| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | { bindingType: [BindingType](/runtime/binding/enum/expression-parser/bindingtype.md); compile(binding: [PlainAttributeSymbol](/jit/class/semantic-model/plainattributesymbol.md) &#124; [BindingSymbol](/jit/class/semantic-model/bindingsymbol.md)): ITargetedInstruction; } |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; bindingType**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public, readonly | ✘ | BindingType.CustomCommand |

# &#10025; Method(s)

&nbsp;&nbsp; **&#10148; compile**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [TranslationBindingInstruction](/i18n/t/class/translation-renderer/translationbindinginstruction.md) |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; binding**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | [PlainAttributeSymbol](/jit/class/semantic-model/plainattributesymbol.md) &#124; [BindingSymbol](/jit/class/semantic-model/bindingsymbol.md) | ✘  | ✘ | ✘ |