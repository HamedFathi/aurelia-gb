| Modifier(s)                            |
|----------------------------------------|
| export |

# &#9733; Literal(s)

&nbsp;&nbsp; **&#10148; BindingBehavior**

| Type                        | Array                           |
|-----------------------------|---------------------------------|
| BindingBehaviorKind | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Member(s)**

| Object                        |
|:-----------------------------:|
| ✔ |

**&#9733; Assignment(s)**

**&#10148; name**

| Type                      | Shorthand                         | Spread                        |
|---------------------------|:---------------------------------:|:-----------------------------:|
| { name: string; keyFrom(name: string): string; isType&lt;T&gt;(value: T): value is T extends Constructable&lt;{}&gt; ? ResourceType&lt;T, { bind(flags: LifecycleFlags, scope: IScope, binding: IBinding, ...args: {}[]): void; unbind(flags: LifecycleFlags, scope: IScope, binding: IBinding, ...args: {}[]): void; }, {}, InstanceType&lt;T&gt;&gt; : never; define&lt;T extends Constructable&lt;{ bind(flags: LifecycleFlags, scope: IScope, binding: IBinding, ...args: {}[]): void; unbind(flags: LifecycleFlags, scope: IScope, binding: IBinding, ...args: {}[]): void; }&gt;&gt;(nameOrDef: string &#124; PartialResourceDefinition&lt;{ strategy?: BindingBehaviorStrategy &#124; undefined; }&gt;, Type: T): ResourceType&lt;T, { bind(flags: LifecycleFlags, scope: IScope, binding: IBinding, ...args: {}[]): void; unbind(flags: LifecycleFlags, scope: IScope, binding: IBinding, ...args: {}[]): void; }, {}, InstanceType&lt;T&gt;&gt;; getDefinition&lt;T extends Constructable&lt;{}&gt;&gt;(Type: T): [BindingBehaviorDefinition](/runtime/resources/class/binding-behavior/bindingbehaviordefinition.md)&lt;T&gt;; annotate&lt;K extends "name" &#124; "aliases" &#124; "strategy"&gt;(Type: Constructable&lt;{}&gt;, prop: K, value: PartialResourceDefinition&lt;{ strategy?: BindingBehaviorStrategy &#124; undefined; }&gt;[K]): void; getAnnotation&lt;K extends "name" &#124; "aliases" &#124; "strategy"&gt;(Type: Constructable&lt;{}&gt;, prop: K): PartialResourceDefinition&lt;{ strategy?: BindingBehaviorStrategy &#124; undefined; }&gt;[K]; } | ✘  | ✘ |

**&#9733; Value**

Protocol.resource.keyFor('binding-behavior')

**&#9733; Method(s)**

&nbsp;&nbsp; **&#10148; keyFrom**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | string |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; isType**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | boolean |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Type Parameter(s)**

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; define**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | ResourceType&lt;T, { bind(flags: LifecycleFlags, scope: IScope, binding: IBinding, ...args: {}[]): void; unbind(flags: LifecycleFlags, scope: IScope, binding: IBinding, ...args: {}[]): void; }, {}, InstanceType&lt;T&gt;&gt; |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Type Parameter(s)**

| Type | Constraint                                                                                                                                                                                         |
| ---- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| T    | Constructable&lt;{ bind(flags: LifecycleFlags, scope: IScope, binding: IBinding, ...args: {}[]): void; unbind(flags: LifecycleFlags, scope: IScope, binding: IBinding, ...args: {}[]): void; }&gt; |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; getDefinition**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | [BindingBehaviorDefinition](/runtime/resources/class/binding-behavior/bindingbehaviordefinition.md)&lt;T&gt; |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Type Parameter(s)**

| Type | Constraint              |
| ---- | ----------------------- |
| T    | Constructable&lt;{}&gt; |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; annotate**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | void |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Type Parameter(s)**

| Type | Constraint                                |
| ---- | ----------------------------------------- |
| K    | "name" &#124; "aliases" &#124; "strategy" |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; getAnnotation**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | PartialResourceDefinition&lt;{ strategy?: BindingBehaviorStrategy &#124; undefined; }&gt;[K] |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Type Parameter(s)**

| Type | Constraint                                |
| ---- | ----------------------------------------- |
| K    | "name" &#124; "aliases" &#124; "strategy" |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |