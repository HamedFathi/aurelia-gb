| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

# &#10025; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; config**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IRegistry](/kernel/interface/di/iregistry.md) | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; wnd**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| Window | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; Scheduler**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| Constructable&lt;[IScheduler](/runtime/variable/scheduler/ischeduler.md)&gt; | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; UIEventType**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new (type: string, eventInitDict?: UIEventInit &#124; undefined): UIEvent; prototype: UIEvent; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; EventType**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new (type: string, eventInitDict?: EventInit &#124; undefined): Event; prototype: Event; readonly AT&#95;TARGET: number; readonly BUBBLING&#95;PHASE: number; readonly CAPTURING&#95;PHASE: number; readonly NONE: number; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; CustomEventType**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new &lt;T&gt;(typeArg: string, eventInitDict?: CustomEventInit&lt;T&gt; &#124; undefined): CustomEvent&lt;T&gt;; prototype: CustomEvent&lt;any&gt;; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; NodeType**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new (): Node; prototype: Node; readonly ATTRIBUTE&#95;NODE: number; readonly CDATA&#95;SECTION&#95;NODE: number; readonly COMMENT&#95;NODE: number; readonly DOCUMENT&#95;FRAGMENT&#95;NODE: number; readonly DOCUMENT&#95;NODE: number; readonly DOCUMENT&#95;POSITION&#95;CONTAINED&#95;BY: number; readonly DOCUMENT&#95;POSITION&#95;CONTAINS: number; readonly DOCUMENT&#95;POSITION&#95;DISCONNECTED: number; readonly DOCUMENT&#95;POSITION&#95;FOLLOWING: number; readonly DOCUMENT&#95;POSITION&#95;IMPLEMENTATION&#95;SPECIFIC: number; readonly DOCUMENT&#95;POSITION&#95;PRECEDING: number; readonly DOCUMENT&#95;TYPE&#95;NODE: number; readonly ELEMENT&#95;NODE: number; readonly ENTITY&#95;NODE: number; readonly ENTITY&#95;REFERENCE&#95;NODE: number; readonly NOTATION&#95;NODE: number; readonly PROCESSING&#95;INSTRUCTION&#95;NODE: number; readonly TEXT&#95;NODE: number; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; ElementType**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new (): Element; prototype: Element; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; HTMLElementType**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new (): HTMLElement; prototype: HTMLElement; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; HTMLDivElementType**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new (): HTMLDivElement; prototype: HTMLDivElement; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; TextType**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new (data?: string &#124; undefined): Text; prototype: Text; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; CommentType**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new (data?: string &#124; undefined): Comment; prototype: Comment; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; DOMParserType**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new (): DOMParser; prototype: DOMParser; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; CSSStyleSheetType**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new (): CSSStyleSheet; prototype: CSSStyleSheet; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; ShadowRootType**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new (): ShadowRoot; prototype: ShadowRoot; } | ✘  | ✘ | ✘ |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; wnd**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public, readonly | ✘ | Window |

&nbsp;&nbsp; **&#10148; doc**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public, readonly | ✘ | Document |

&nbsp;&nbsp; **&#10148; dom**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public, readonly | ✘ | [HTMLDOM](/runtime-html/class/dom/htmldom.md) |

&nbsp;&nbsp; **&#10148; UIEvent**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public, readonly | ✘ | { new (type: string, eventInitDict?: UIEventInit &#124; undefined): UIEvent; prototype: UIEvent; } |

&nbsp;&nbsp; **&#10148; Event**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public, readonly | ✘ | { new (type: string, eventInitDict?: EventInit &#124; undefined): Event; prototype: Event; readonly AT&#95;TARGET: number; readonly BUBBLING&#95;PHASE: number; readonly CAPTURING&#95;PHASE: number; readonly NONE: number; } |

&nbsp;&nbsp; **&#10148; CustomEvent**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public, readonly | ✘ | { new &lt;T&gt;(typeArg: string, eventInitDict?: CustomEventInit&lt;T&gt; &#124; undefined): CustomEvent&lt;T&gt;; prototype: CustomEvent&lt;any&gt;; } |

&nbsp;&nbsp; **&#10148; Node**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public, readonly | ✘ | { new (): Node; prototype: Node; readonly ATTRIBUTE&#95;NODE: number; readonly CDATA&#95;SECTION&#95;NODE: number; readonly COMMENT&#95;NODE: number; readonly DOCUMENT&#95;FRAGMENT&#95;NODE: number; readonly DOCUMENT&#95;NODE: number; readonly DOCUMENT&#95;POSITION&#95;CONTAINED&#95;BY: number; readonly DOCUMENT&#95;POSITION&#95;CONTAINS: number; readonly DOCUMENT&#95;POSITION&#95;DISCONNECTED: number; readonly DOCUMENT&#95;POSITION&#95;FOLLOWING: number; readonly DOCUMENT&#95;POSITION&#95;IMPLEMENTATION&#95;SPECIFIC: number; readonly DOCUMENT&#95;POSITION&#95;PRECEDING: number; readonly DOCUMENT&#95;TYPE&#95;NODE: number; readonly ELEMENT&#95;NODE: number; readonly ENTITY&#95;NODE: number; readonly ENTITY&#95;REFERENCE&#95;NODE: number; readonly NOTATION&#95;NODE: number; readonly PROCESSING&#95;INSTRUCTION&#95;NODE: number; readonly TEXT&#95;NODE: number; } |

&nbsp;&nbsp; **&#10148; Element**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public, readonly | ✘ | { new (): Element; prototype: Element; } |

&nbsp;&nbsp; **&#10148; HTMLElement**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public, readonly | ✘ | { new (): HTMLElement; prototype: HTMLElement; } |

&nbsp;&nbsp; **&#10148; HTMLDivElement**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public, readonly | ✘ | { new (): HTMLDivElement; prototype: HTMLDivElement; } |

&nbsp;&nbsp; **&#10148; Text**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public, readonly | ✘ | { new (data?: string &#124; undefined): Text; prototype: Text; } |

&nbsp;&nbsp; **&#10148; Comment**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public, readonly | ✘ | { new (data?: string &#124; undefined): Comment; prototype: Comment; } |

&nbsp;&nbsp; **&#10148; DOMParser**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public, readonly | ✘ | { new (): DOMParser; prototype: DOMParser; } |

&nbsp;&nbsp; **&#10148; config**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| private, readonly | ✘ | [IRegistry](/kernel/interface/di/iregistry.md) |

&nbsp;&nbsp; **&#10148; &#95;container**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| private | ✔ | [IContainer](/kernel/interface/di/icontainer.md) &#124; undefined |

&nbsp;&nbsp; **&#10148; &#95;scheduler**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| private | ✔ | [IScheduler](/runtime/variable/scheduler/ischeduler.md) &#124; undefined |

&nbsp;&nbsp; **&#10148; &#95;templateCompiler**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| private | ✔ | [ITemplateCompiler](/runtime/interface/renderer/itemplatecompiler.md) &#124; undefined |

&nbsp;&nbsp; **&#10148; &#95;observerLocator**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| private | ✔ | [IObserverLocator](/runtime/observation/interface/observer-locator/iobserverlocator.md) &#124; undefined |

&nbsp;&nbsp; **&#10148; &#95;lifecycle**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| private | ✔ | [ILifecycle](/runtime/interface/lifecycle/ilifecycle.md) &#124; undefined |

&nbsp;&nbsp; **&#10148; &#95;renderer**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| private | ✔ | [IRenderer](/runtime/interface/renderer/irenderer.md) &#124; undefined |

&nbsp;&nbsp; **&#10148; &#95;projectorLocator**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| private | ✔ | [IProjectorLocator](/runtime/resources/variable/custom-element/iprojectorlocator.md)&lt;INode&gt; &#124; undefined |

&nbsp;&nbsp; **&#10148; &#95;domParser**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| private | ✔ | HTMLDivElement &#124; undefined |

&nbsp;&nbsp; **&#10148; Scheduler**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| private, readonly | ✘ | Constructable&lt;[IScheduler](/runtime/variable/scheduler/ischeduler.md)&gt; |

# &#10025; Get Accessor(s)

&nbsp;&nbsp; **&#10148; container**

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | [IContainer](/kernel/interface/di/icontainer.md) |

&nbsp;&nbsp; **&#10148; scheduler**

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | [IScheduler](/runtime/variable/scheduler/ischeduler.md) |

&nbsp;&nbsp; **&#10148; templateCompiler**

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | [ITemplateCompiler](/runtime/interface/renderer/itemplatecompiler.md) |

&nbsp;&nbsp; **&#10148; observerLocator**

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | [IObserverLocator](/runtime/observation/interface/observer-locator/iobserverlocator.md) |

&nbsp;&nbsp; **&#10148; lifecycle**

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | [ILifecycle](/runtime/interface/lifecycle/ilifecycle.md) |

&nbsp;&nbsp; **&#10148; renderer**

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | [IRenderer](/runtime/interface/renderer/irenderer.md) |

&nbsp;&nbsp; **&#10148; projectorLocator**

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | [IProjectorLocator](/runtime/resources/variable/custom-element/iprojectorlocator.md)&lt;INode&gt; |

&nbsp;&nbsp; **&#10148; domParser**

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | HTMLDivElement |

# &#10025; Method(s)

&nbsp;&nbsp; **&#10148; create**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, static | ✘ | [HTMLTestContext](/testing/class/html-test-context/htmltestcontext.md) |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; config**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | [IRegistry](/kernel/interface/di/iregistry.md) | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; wnd**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | Window | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; Scheduler**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | Constructable&lt;[IScheduler](/runtime/variable/scheduler/ischeduler.md)&gt; | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; UIEventType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | { new (type: string, eventInitDict?: UIEventInit &#124; undefined): UIEvent; prototype: UIEvent; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; EventType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | { new (type: string, eventInitDict?: EventInit &#124; undefined): Event; prototype: Event; readonly AT&#95;TARGET: number; readonly BUBBLING&#95;PHASE: number; readonly CAPTURING&#95;PHASE: number; readonly NONE: number; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; CustomEventType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | { new &lt;T&gt;(typeArg: string, eventInitDict?: CustomEventInit&lt;T&gt; &#124; undefined): CustomEvent&lt;T&gt;; prototype: CustomEvent&lt;any&gt;; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; NodeType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | { new (): Node; prototype: Node; readonly ATTRIBUTE&#95;NODE: number; readonly CDATA&#95;SECTION&#95;NODE: number; readonly COMMENT&#95;NODE: number; readonly DOCUMENT&#95;FRAGMENT&#95;NODE: number; readonly DOCUMENT&#95;NODE: number; readonly DOCUMENT&#95;POSITION&#95;CONTAINED&#95;BY: number; readonly DOCUMENT&#95;POSITION&#95;CONTAINS: number; readonly DOCUMENT&#95;POSITION&#95;DISCONNECTED: number; readonly DOCUMENT&#95;POSITION&#95;FOLLOWING: number; readonly DOCUMENT&#95;POSITION&#95;IMPLEMENTATION&#95;SPECIFIC: number; readonly DOCUMENT&#95;POSITION&#95;PRECEDING: number; readonly DOCUMENT&#95;TYPE&#95;NODE: number; readonly ELEMENT&#95;NODE: number; readonly ENTITY&#95;NODE: number; readonly ENTITY&#95;REFERENCE&#95;NODE: number; readonly NOTATION&#95;NODE: number; readonly PROCESSING&#95;INSTRUCTION&#95;NODE: number; readonly TEXT&#95;NODE: number; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; ElementType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | { new (): Element; prototype: Element; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; HTMLElementType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | { new (): HTMLElement; prototype: HTMLElement; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; HTMLDivElementType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | { new (): HTMLDivElement; prototype: HTMLDivElement; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; TextType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | { new (data?: string &#124; undefined): Text; prototype: Text; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; CommentType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | { new (data?: string &#124; undefined): Comment; prototype: Comment; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; DOMParserType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | { new (): DOMParser; prototype: DOMParser; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; CSSStyleSheetType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | { new (): CSSStyleSheet; prototype: CSSStyleSheet; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; ShadowRootType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | { new (): ShadowRoot; prototype: ShadowRoot; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp; **&#10148; createElementFromMarkup**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | HTMLElement |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; markup**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | string | ✘  | ✘ | ✘ |

&nbsp;&nbsp; **&#10148; createElement**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | HTMLElement |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; name**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | string | ✘  | ✘ | ✘ |

&nbsp;&nbsp; **&#10148; createAttribute**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | Attr |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; name**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | string | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; value**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | string | ✘  | ✘ | ✘ |