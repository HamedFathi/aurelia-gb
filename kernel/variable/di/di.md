| Modifier(s)                            |
|----------------------------------------|
| export |

# &#9733; Variable(s)

&nbsp;&nbsp; **&#10148; DI**

| Type                        |
|-----------------------------|
| { createContainer(...params: any[]): [IContainer](/kernel/interface/di/icontainer.md); getDesignParamtypes(Type: Constructable&lt;{}&gt; &#124; Injectable&lt;{}&gt;): readonly Key[] &#124; undefined; getAnnotationParamtypes(Type: Constructable&lt;{}&gt; &#124; Injectable&lt;{}&gt;): readonly Key[] &#124; undefined; getOrCreateAnnotationParamTypes(Type: Constructable&lt;{}&gt; &#124; Injectable&lt;{}&gt;): Key[]; getDependencies(Type: Constructable&lt;{}&gt; &#124; Injectable&lt;{}&gt;): Key[]; createInterface&lt;K extends Key&gt;(friendlyName?: string &#124; undefined): [IDefaultableInterfaceSymbol](/kernel/interface/di/idefaultableinterfacesymbol.md)&lt;K&gt;; inject(...dependencies: Key[]): (target: Injectable&lt;{}&gt;, key?: string &#124; number &#124; undefined, descriptor?: number &#124; PropertyDescriptor &#124; undefined) =&gt; void; transient&lt;T extends Constructable&lt;{}&gt;&gt;(target: T & Partial&lt;RegisterSelf&lt;T&gt;&gt;): T & RegisterSelf&lt;T&gt;; singleton&lt;T&#95;1 extends Constructable&lt;{}&gt;&gt;(target: T&#95;1 & Partial&lt;RegisterSelf&lt;T&#95;1&gt;&gt;): T&#95;1 & RegisterSelf&lt;T&#95;1&gt;; } |