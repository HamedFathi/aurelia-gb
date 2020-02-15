| Modifier(s)                            |
|----------------------------------------|
| export |

# &#9733; Literal(s)

&nbsp;&nbsp; **&#10148; DI**

| Type                        | Array                           |
|-----------------------------|---------------------------------|
| { createContainer(...params: any[]): [IContainer](/kernel/interface/di/icontainer.md); getDesignParamtypes(Type: Constructable&lt;{}&gt; &#124; Injectable&lt;{}&gt;): readonly Key[] &#124; undefined; getAnnotationParamtypes(Type: Constructable&lt;{}&gt; &#124; Injectable&lt;{}&gt;): readonly Key[] &#124; undefined; getOrCreateAnnotationParamTypes(Type: Constructable&lt;{}&gt; &#124; Injectable&lt;{}&gt;): Key[]; getDependencies(Type: Constructable&lt;{}&gt; &#124; Injectable&lt;{}&gt;): Key[]; createInterface&lt;K extends Key&gt;(friendlyName?: string &#124; undefined): [IDefaultableInterfaceSymbol](/kernel/interface/di/idefaultableinterfacesymbol.md)&lt;K&gt;; inject(...dependencies: Key[]): (target: Injectable&lt;{}&gt;, key?: string &#124; number &#124; undefined, descriptor?: number &#124; PropertyDescriptor &#124; undefined) =&gt; void; transient&lt;T extends Constructable&lt;{}&gt;&gt;(target: T & Partial&lt;RegisterSelf&lt;T&gt;&gt;): T & RegisterSelf&lt;T&gt;; singleton&lt;T extends Constructable&lt;{}&gt;&gt;(target: T & Partial&lt;RegisterSelf&lt;T&gt;&gt;): T & RegisterSelf&lt;T&gt;; } | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Member(s)**

| Object                        |
|:-----------------------------:|
| ✔ |

**&#9733; Method(s)**

&nbsp;&nbsp; **&#10148; createContainer**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | [IContainer](/kernel/interface/di/icontainer.md) |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; getDesignParamtypes**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | readonly Key[] &#124; undefined |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; getAnnotationParamtypes**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | readonly Key[] &#124; undefined |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; getOrCreateAnnotationParamTypes**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | Key[] |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; getDependencies**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | Key[] |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; createInterface**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | [IDefaultableInterfaceSymbol](/kernel/interface/di/idefaultableinterfacesymbol.md)&lt;K&gt; |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Type Parameter(s)**

| Type | Constraint |
| ---- | ---------- |
| K    | Key        |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; inject**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | (target: Injectable&lt;{}&gt;, key?: string &#124; number &#124; undefined, descriptor?: number &#124; PropertyDescriptor &#124; undefined) =&gt; void |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; transient**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**;
Registers the `target` class as a transient dependency; each time the dependency is resolved
a new instance will be created.

**Parameter(s)**

| Name   | Description                                                 |
| ------ | ----------------------------------------------------------- |
| target |  The class / constructor function to register as transient. |

**Returns**

The same class, with a static `register` method that takes a container and returns the appropriate resolver.

**Example**

```ts
// On an existing class
class Foo { }
DI.transient(Foo);
// Inline declaration
const Foo = DI.transient(class { });
// Foo is now strongly typed with register
Foo.register(container);
```

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | T & RegisterSelf&lt;T&gt; |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Type Parameter(s)**

| Type | Constraint              |
| ---- | ----------------------- |
| T    | Constructable&lt;{}&gt; |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; singleton**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Summary**;
Registers the `target` class as a singleton dependency; the class will only be created once. Each
consecutive time the dependency is resolved, the same instance will be returned.
  
  **Parameter(s)**

| Name   | Description                                                   |
| ------ | ------------------------------------------------------------- |
| target |  The class / constructor function to register as a singleton. |

**Returns**

The same class, with a static `register` method that takes a container and returns the appropriate resolver.
  
  **Example**

```ts
// On an existing class
class Foo { }
DI.singleton(Foo);
// Inline declaration
const Foo = DI.singleton(class { });
// Foo is now strongly typed with register
Foo.register(container);
```

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | T & RegisterSelf&lt;T&gt; |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Type Parameter(s)**

| Type | Constraint              |
| ---- | ----------------------- |
| T    | Constructable&lt;{}&gt; |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |