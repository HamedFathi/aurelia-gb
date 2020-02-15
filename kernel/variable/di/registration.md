| Modifier(s)                            |
|----------------------------------------|
| export |

# &#9733; Variable(s)

&nbsp;&nbsp; **&#10148; Registration**

| Type                        |
|-----------------------------|
| { instance&lt;T&gt;(key: Key, value: T): [IRegistration](/kernel/interface/di/iregistration.md)&lt;T&gt;; singleton&lt;T&#95;1 extends Constructable&lt;{}&gt;&gt;(key: Key, value: T&#95;1): IRegistration&lt;InstanceType&lt;T&#95;1&gt;&gt;; transient&lt;T&#95;2 extends Constructable&lt;{}&gt;&gt;(key: Key, value: T&#95;2): IRegistration&lt;InstanceType&lt;T&#95;2&gt;&gt;; callback&lt;T&#95;3&gt;(key: Key, callback: ResolveCallback&lt;T&#95;3&gt;): IRegistration&lt;Resolved&lt;T&#95;3&gt;&gt;; alias&lt;T&#95;4&gt;(originalKey: T&#95;4, aliasKey: Key): IRegistration&lt;Resolved&lt;T&#95;4&gt;&gt;; defer(key: Key, ...params: unknown[]): [IRegistry](/kernel/interface/di/iregistry.md); } |