| Modifier(s)                            | Return Type                    | Generator                        | Overload                         | Implementation                        |
|----------------------------------------|--------------------------------|:--------------------------------:|:--------------------------------:|:-------------------------------------:|
| export | { startPromise: Promise&lt;unknown&gt;; ctx: [HTMLTestContext](/testing/class/html-test-context/htmltestcontext.md); host: Element &#124; null; container: [IContainer](/kernel/interface/di/icontainer.md); lifecycle: [ILifecycle](/runtime/interface/lifecycle/ilifecycle.md); scheduler: [IScheduler](/runtime/variable/scheduler/ischeduler.md); testHost: HTMLDivElement; appHost: HTMLElement; au: [Aurelia](/runtime/class/aurelia/aurelia.md)&lt;INode&gt;; component: ICustomElementViewModel&lt;INode&gt; & T; observerLocator: [IObserverLocator](/runtime/observation/interface/observer-locator/iobserverlocator.md); start: () =&gt; Promise&lt;void&gt;; tearDown: () =&gt; Promise&lt;void&gt;; } | ✘ | ✘  | ✔ |

# &#10025; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; template**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | string &#124; Node | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; $class**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | Constructable&lt;T&gt; &#124; undefined | ✔  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; registrations**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | any[] | ✔  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Initializer**

```ts
[]
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; autoStart**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | boolean | ✔  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Initializer**

```ts
true
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; ctx**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | [HTMLTestContext](/testing/class/html-test-context/htmltestcontext.md) | ✔  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Initializer**

```ts
TestContext.createHTMLTestContext()
```