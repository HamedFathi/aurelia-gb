# &#10025; Summary

Class responsible for handling interactions that should trigger navigation.

| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

# &#10025; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; dom**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [HTMLDOM](/runtime-html/class/dom/htmldom.md) | ✘  | ✘ | ✘ |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; inject**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public, static, readonly | ✘ | readonly Key[] |

&nbsp;&nbsp; **&#10148; window**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | Window |

&nbsp;&nbsp; **&#10148; document**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | Document |

&nbsp;&nbsp; **&#10148; options**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| private | ✘ | [ILinkHandlerOptions](/router/interface/link-handler/ilinkhandleroptions.md) |

&nbsp;&nbsp; **&#10148; isActive**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| private | ✘ | boolean |

&nbsp;&nbsp; **&#10148; handler**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public, readonly | ✘ | EventListener |

# &#10025; Method(s)

&nbsp;&nbsp; **&#10148; getEventInfo**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

Gets the href and a "should handle" recommendation, given an Event.

**Parameter(s)**

| Name  | Description                                       |
| ----- | ------------------------------------------------- |
| event |  The Event to inspect for target anchor and href. |

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private, static | ✘ | [AnchorEventInfo](/router/interface/link-handler/anchoreventinfo.md) |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; event**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | MouseEvent | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; win**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | Window | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; options**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | [ILinkHandlerOptions](/router/interface/link-handler/ilinkhandleroptions.md) | ✘  | ✘ | ✘ |

&nbsp;&nbsp; **&#10148; targetIsThisWindow**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

Finds the closest ancestor that's an anchor element.
Gets a value indicating whether or not an anchor targets the current window.
private static closestAnchor(el: Element): Element | null {
while (el !== null && el !== void 0) {
if (el.tagName === 'A') {
return el;
}
el = el.parentNode as Element;
}
return null;
}
Finds the closest ancestor that's an anchor element.
Gets a value indicating whether or not an anchor targets the current window.

**Parameter(s)**

| Name   | Description                                           |
| ------ | ----------------------------------------------------- |
|        |  The element to search upward from.                   |
| target |  The anchor element whose target should be inspected. |
|        |  The element to search upward from.                   |
| target |  The anchor element whose target should be inspected. |

**Returns**

The link element that is the closest ancestor.

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private, static | ✘ | boolean |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; target**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | Element | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; win**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | Window | ✘  | ✘ | ✘ |

&nbsp;&nbsp; **&#10148; activate**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

Activate the instance.

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; options**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | [ILinkHandlerOptions](/router/interface/link-handler/ilinkhandleroptions.md) | ✘  | ✘ | ✘ |

&nbsp;&nbsp; **&#10148; deactivate**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

Deactivate the instance. Event handlers and other resources should be cleaned up here.

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |