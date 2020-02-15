# &#10025; Summary

note: string.length is the only property of any primitive that is not a function,
so we can hardwire it to that and simply return undefined for anything else
note#2: a modified primitive constructor prototype would not work (and really, it shouldn't..)

| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | [IAccessor](/runtime/interface/observation/iaccessor.md)&lt;unknown&gt;, [ISubscribable](/runtime/interface/observation/isubscribable.md) |

# &#10025; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; obj**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| Primitive | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; propertyKey**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| string &#124; number &#124; symbol | ✘  | ✘ | ✘ |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; getValue**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | () =&gt; number &#124; undefined |

&nbsp;&nbsp; **&#10148; setValue**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

removed the error reporter here because technically any primitive property that can get, can also set,
but since that never serves any purpose (e.g. setting string.length doesn't throw but doesn't change the length either),
we could best just leave this as a no-op and so don't need to store the propertyName

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | () =&gt; void |

&nbsp;&nbsp; **&#10148; subscribe**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | () =&gt; void |

&nbsp;&nbsp; **&#10148; unsubscribe**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | () =&gt; void |

&nbsp;&nbsp; **&#10148; dispose**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | () =&gt; void |

&nbsp;&nbsp; **&#10148; doNotCache**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | boolean |

&nbsp;&nbsp; **&#10148; obj**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | Primitive |

# &#10025; Method(s)

&nbsp;&nbsp; **&#10148; getStringLength**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | number |

&nbsp;&nbsp; **&#10148; returnUndefined**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | undefined |