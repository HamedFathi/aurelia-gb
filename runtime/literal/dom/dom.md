| Modifier(s)                            |
|----------------------------------------|
| export |

# &#9733; Literal(s)

&nbsp;&nbsp; **&#10148; DOM**

| Type                        | Array                           |
|-----------------------------|---------------------------------|
| [IDOM](/runtime/variable/dom/idom.md)&lt;INode&gt; & { readonly isInitialized: boolean; readonly scheduler: [IScheduler](/runtime/variable/scheduler/ischeduler.md); initialize(dom: IDOM&lt;INode&gt;): void; destroy(): void; } | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Member(s)**

| Object                        |
|:-----------------------------:|
| ✔ |

**&#9733; Assignment(s)**

**&#10148; niDOM**

| Type                      | Shorthand                         | Spread                        |
|---------------------------|:---------------------------------:|:-----------------------------:|
| { scheduler: never; isInitialized: boolean; initialize(dom: [IDOM](/runtime/variable/dom/idom.md)&lt;INode&gt;): void; destroy(): void; IDOM.addEventListener(eventName: string, subscriber: unknown, publisher?: unknown, options?: unknown): void; IDOM.appendChild(parent: INode, child: INode): void; IDOM.cloneNode&lt;TClone&gt;(node: TClone, deep?: boolean &#124; undefined): TClone; IDOM.convertToRenderLocation(node: INode): IRenderLocation&lt;INode&gt;; IDOM.createDocumentFragment(markupOrNode?: string &#124; INode &#124; undefined): INode; IDOM.createNodeSequence(fragment: INode &#124; null): INodeSequence&lt;INode&gt;; IDOM.createElement(name: string): INode; IDOM.createCustomEvent(eventType: string, options?: unknown): unknown; IDOM.dispatchEvent(evt: unknown): void; IDOM.createNodeObserver?(node: INode, cb: (...args: unknown[]) =&gt; void, init: unknown): unknown; IDOM.createTemplate(markup?: string &#124; undefined): INode; IDOM.createTextNode(text: string): INode; IDOM.getEffectiveParentNode(node: INode): INode &#124; null; IDOM.setEffectiveParentNode(nodeSequence: INodeSequence&lt;INode&gt;, parentNode: INode): void; IDOM.setEffectiveParentNode(childNode: INode, parentNode: INode): void; IDOM.insertBefore(nodeToInsert: INode, referenceNode: INode): void; IDOM.isMarker(node: unknown): node is INode; IDOM.isNodeInstance(potentialNode: unknown): potentialNode is INode; IDOM.isRenderLocation(node: unknown): node is IRenderLocation&lt;INode&gt;; IDOM.makeTarget(node: INode): void; IDOM.registerElementResolver(container: IContainer, resolver: IResolver&lt;any&gt;): void; IDOM.remove(node: INode): void; IDOM.removeEventListener(eventName: string, subscriber: unknown, publisher?: unknown, options?: unknown): void; IDOM.setAttribute(node: INode, name: string, value: unknown): void; } | ✘  | ✔ |

**&#9733; Value**

-

**&#10148; scheduler**

| Type                      | Shorthand                         | Spread                        |
|---------------------------|:---------------------------------:|:-----------------------------:|
| { scheduler: never; isInitialized: boolean; initialize(dom: [IDOM](/runtime/variable/dom/idom.md)&lt;INode&gt;): void; destroy(): void; IDOM.addEventListener(eventName: string, subscriber: unknown, publisher?: unknown, options?: unknown): void; IDOM.appendChild(parent: INode, child: INode): void; IDOM.cloneNode&lt;TClone&gt;(node: TClone, deep?: boolean &#124; undefined): TClone; IDOM.convertToRenderLocation(node: INode): IRenderLocation&lt;INode&gt;; IDOM.createDocumentFragment(markupOrNode?: string &#124; INode &#124; undefined): INode; IDOM.createNodeSequence(fragment: INode &#124; null): INodeSequence&lt;INode&gt;; IDOM.createElement(name: string): INode; IDOM.createCustomEvent(eventType: string, options?: unknown): unknown; IDOM.dispatchEvent(evt: unknown): void; IDOM.createNodeObserver?(node: INode, cb: (...args: unknown[]) =&gt; void, init: unknown): unknown; IDOM.createTemplate(markup?: string &#124; undefined): INode; IDOM.createTextNode(text: string): INode; IDOM.getEffectiveParentNode(node: INode): INode &#124; null; IDOM.setEffectiveParentNode(nodeSequence: INodeSequence&lt;INode&gt;, parentNode: INode): void; IDOM.setEffectiveParentNode(childNode: INode, parentNode: INode): void; IDOM.insertBefore(nodeToInsert: INode, referenceNode: INode): void; IDOM.isMarker(node: unknown): node is INode; IDOM.isNodeInstance(potentialNode: unknown): potentialNode is INode; IDOM.isRenderLocation(node: unknown): node is IRenderLocation&lt;INode&gt;; IDOM.makeTarget(node: INode): void; IDOM.registerElementResolver(container: IContainer, resolver: IResolver&lt;any&gt;): void; IDOM.remove(node: INode): void; IDOM.removeEventListener(eventName: string, subscriber: unknown, publisher?: unknown, options?: unknown): void; IDOM.setAttribute(node: INode, name: string, value: unknown): void; } | ✘  | ✘ |

**&#9733; Value**

(void 0)!

**&#9733; Get Accessor(s)**

&nbsp;&nbsp; **&#10148; isInitialized**

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| - | boolean |

**&#9733; Method(s)**

&nbsp;&nbsp; **&#10148; initialize**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | void |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; destroy**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | void |