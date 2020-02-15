| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

# &#10025; Decorators(s)

| Name                                | Decorator Factory                        |
|-------------------------------------|:----------------------------------------:|
| inject | ✔  |

| Argument(s)                                           |
|-------------------------------------------------------|
| IRouter  |
| INode  |

| Name                                | Decorator Factory                        |
|-------------------------------------|:----------------------------------------:|
| customElement | ✔  |

| Argument(s)                                           |
|-------------------------------------------------------|
| {
name: 'au-nav', template:
`<template>
<nav if.bind="name" class="\${name} \${navClasses.nav}">
<au-nav routes.bind="navRoutes" classes.bind="navClasses" containerless></au-nav>
</nav>
<ul if.bind="routes" class="nav-level-\${level} \${classes.ul}">
<li repeat.for="route of routes" if.bind="route.visible" class="\${route.active ? classes.liActive : ''} \${route.hasChildren} \${classes.li}">
<a if.bind="route.link && route.link.length" goto="\${route.link}" class="\${route.active ? classes.aActive : ''} \${classes.a}" innerhtml.bind="route.title"></a>
<a if.bind="route.execute" click.trigger="route.executeAction($event)" href="" class="\${route.active ? classes.aActive : ''} \${classes.a}" innerhtml.bind="route.title"></a>
<span if.bind="(!route.link || !route.link.length) && !route.execute && !route.children" class="\${route.active ? classes.aActive : ''} \${classes.span} nav-separator" innerhtml.bind="route.title"></span>
<a if.bind="(!route.link || !route.link.length) && !route.execute && route.children" click.delegate="route.toggleActive()" href="" class="\${route.active ? classes.aActive : ''} \${classes.a}" innerhtml.bind="route.title"></a>
<au-nav if.bind="route.children" routes.bind="route.children" level.bind="level + 1" classes.bind="classes" containerless></au-nav>
</li>
</ul>
</template>` }  |

# &#10025; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; router**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IRouter](/router/interface/router/irouter.md) | ✘  | ✘ | ✔ |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; name**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | string &#124; null |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Decorators(s)**

| Name                                | Decorator Factory                        |
|-------------------------------------|:----------------------------------------:|
| bindable | ✘  |

&nbsp;&nbsp; **&#10148; routes**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | [NavRoute](/router/class/nav-route/navroute.md)[] &#124; null |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Decorators(s)**

| Name                                | Decorator Factory                        |
|-------------------------------------|:----------------------------------------:|
| bindable | ✘  |

&nbsp;&nbsp; **&#10148; level**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | number |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Decorators(s)**

| Name                                | Decorator Factory                        |
|-------------------------------------|:----------------------------------------:|
| bindable | ✘  |

&nbsp;&nbsp; **&#10148; classes**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | [INavClasses](/router/resources/interface/nav/inavclasses.md) |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Decorators(s)**

| Name                                | Decorator Factory                        |
|-------------------------------------|:----------------------------------------:|
| bindable | ✘  |

# &#10025; Get Accessor(s)

&nbsp;&nbsp; **&#10148; navRoutes**

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | [NavRoute](/router/class/nav-route/navroute.md)[] |

&nbsp;&nbsp; **&#10148; navClasses**

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | [INavClasses](/router/resources/interface/nav/inavclasses.md) |

# &#10025; Method(s)

&nbsp;&nbsp; **&#10148; active**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | string |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; route**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | [NavRoute](/router/class/nav-route/navroute.md) | ✘  | ✘ | ✘ |