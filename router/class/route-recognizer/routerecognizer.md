# &#10025; Summary

Class that parses route patterns and matches path strings.

| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; rootState**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | [State](/router/class/route-recognizer/state.md) |

&nbsp;&nbsp; **&#10148; names**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | Record&lt;string, [RouteGenerator](/router/class/route-recognizer/routegenerator.md)&gt; |

&nbsp;&nbsp; **&#10148; routes**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | Map&lt;[RouteHandler](/router/interface/route-recognizer/routehandler.md), [RouteGenerator](/router/class/route-recognizer/routegenerator.md)&gt; |

# &#10025; Method(s)

&nbsp;&nbsp; **&#10148; add**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

Parse a route pattern and add it to the collection of recognized routes.

**Parameter(s)**

| Name  | Description        |
| ----- | ------------------ |
| route |  The route to add. |

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [State](/router/class/route-recognizer/state.md) &#124; undefined |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; route**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | [ConfigurableRoute](/router/interface/route-recognizer/configurableroute.md) &#124; ConfigurableRoute[] | ✘  | ✘ | ✘ |

&nbsp;&nbsp; **&#10148; getRoute**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

Retrieve a RouteGenerator for a route by name or RouteConfig (RouteHandler).

**Parameter(s)**

| Name        | Description                                   |
| ----------- | --------------------------------------------- |
| nameOrRoute |  The name of the route or RouteConfig object. |

**Returns**

The RouteGenerator for that route.

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [RouteGenerator](/router/class/route-recognizer/routegenerator.md) |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; nameOrRoute**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | string &#124; [RouteHandler](/router/interface/route-recognizer/routehandler.md) | ✘  | ✘ | ✘ |

&nbsp;&nbsp; **&#10148; handlersFor**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

Retrieve the handlers registered for the route by name or RouteConfig (RouteHandler).

**Parameter(s)**

| Name        | Description                                   |
| ----------- | --------------------------------------------- |
| nameOrRoute |  The name of the route or RouteConfig object. |

**Returns**

The handlers.

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [HandlerEntry](/router/class/route-recognizer/handlerentry.md)[] |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; nameOrRoute**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | string &#124; [RouteHandler](/router/interface/route-recognizer/routehandler.md) | ✘  | ✘ | ✘ |

&nbsp;&nbsp; **&#10148; hasRoute**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

Check if this RouteRecognizer recognizes a route by name or RouteConfig (RouteHandler).

**Parameter(s)**

| Name        | Description                                   |
| ----------- | --------------------------------------------- |
| nameOrRoute |  The name of the route or RouteConfig object. |

**Returns**

True if the named route is recognized.

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | boolean |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; nameOrRoute**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | string &#124; [RouteHandler](/router/interface/route-recognizer/routehandler.md) | ✘  | ✘ | ✘ |

&nbsp;&nbsp; **&#10148; generate**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

Generate a path and query string from a route name or RouteConfig (RouteHandler) and params object.

**Parameter(s)**

| Name        | Description                                                                                                                        |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| nameOrRoute |  The name of the route or RouteConfig object.                                                                                      |
| params      |  The route params to use when populating the pattern. Properties not required by the pattern will be appended to the query string. |

**Returns**

The generated absolute path and query string.

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | string |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; nameOrRoute**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | string &#124; [RouteHandler](/router/interface/route-recognizer/routehandler.md) | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; params**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | object &#124; undefined | ✔  | ✘ | ✘ |

&nbsp;&nbsp; **&#10148; recognize**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**

Match a path string against registered route patterns.

**Parameter(s)**

| Name | Description                    |
| ---- | ------------------------------ |
| path |  The path to attempt to match. |

**Returns**

Array of objects containing `handler`, `params`, and
`isDynamic` values for the matched route(s), or undefined if no match
was found.

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [RecognizeResults](/router/interface/route-recognizer/recognizeresults.md) |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; path**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | string | ✘  | ✘ | ✘ |