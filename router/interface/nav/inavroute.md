| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; route**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | string &#124; Constructable&lt;{}&gt; &#124; RouteableComponentType&lt;Constructable&lt;{}&gt;&gt; &#124; IRouteableComponent&lt;INode&gt; &#124; IViewportInstruction &#124; ViewportInstruction &#124; NavigationInstruction[] &#124; undefined |

&nbsp;&nbsp; **&#10148; execute**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | ((route: [NavRoute](/router/class/nav-route/navroute.md)) =&gt; void) &#124; undefined |

&nbsp;&nbsp; **&#10148; condition**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | boolean &#124; ((route: [NavRoute](/router/class/nav-route/navroute.md)) =&gt; boolean) &#124; undefined |

&nbsp;&nbsp; **&#10148; consideredActive**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | string &#124; Constructable&lt;{}&gt; &#124; RouteableComponentType&lt;Constructable&lt;{}&gt;&gt; &#124; IRouteableComponent&lt;INode&gt; &#124; IViewportInstruction &#124; ViewportInstruction &#124; NavigationInstruction[] &#124; ((route: [NavRoute](/router/class/nav-route/navroute.md)) =&gt; boolean) &#124; undefined |

&nbsp;&nbsp; **&#10148; compareParameters**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | boolean &#124; undefined |

&nbsp;&nbsp; **&#10148; link**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | string &#124; undefined |

&nbsp;&nbsp; **&#10148; title**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | string |

&nbsp;&nbsp; **&#10148; children**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | [INavRoute](/router/interface/nav/inavroute.md)[] &#124; undefined |

&nbsp;&nbsp; **&#10148; meta**

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | Record&lt;string, unknown&gt; &#124; undefined |