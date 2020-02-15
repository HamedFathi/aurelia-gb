| Modifier(s)                            |
|----------------------------------------|
| export |

# &#9733; Literal(s)

&nbsp;&nbsp; **&#10148; RouterConfiguration**

| Type                        | Array                           |
|-----------------------------|---------------------------------|
| { register(container: IContainer): IContainer; createContainer(): IContainer; customize(config?: [[IRouter](/router/interface/router/irouter.md)Options](/router/interface/router/irouteroptions.md) &#124; ((router: IRouter) =&gt; void) &#124; undefined): { register(container: IContainer): IContainer; createContainer(): IContainer; }; } | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Member(s)**

| Object                        |
|:-----------------------------:|
| ✔ |

**&#9733; Assignment(s)**

**&#10148; routerConfiguration**

| Type                      | Shorthand                         | Spread                        |
|---------------------------|:---------------------------------:|:-----------------------------:|
| { register(container: IContainer): IContainer; createContainer(): IContainer; customize(config?: [[IRouter](/router/interface/router/irouter.md)Options](/router/interface/router/irouteroptions.md) &#124; ((router: IRouter) =&gt; void) &#124; undefined): { register(container: IContainer): IContainer; createContainer(): IContainer; }; } | ✘  | ✔ |

**&#9733; Value**

-

**&#9733; Method(s)**

&nbsp;&nbsp; **&#10148; customize**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**;
Make it possible to specify options to Router activation.
Parameter is either a config object that's passed to Router's activate
or a config function that's called instead of Router's activate.

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | { register(container: IContainer): IContainer; createContainer(): IContainer; } |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |