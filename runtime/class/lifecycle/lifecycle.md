| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | [ILifecycle](/runtime/interface/lifecycle/ilifecycle.md) |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; batch**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public, readonly | ✘ | [IAutoProcessingQueue](/runtime/interface/lifecycle/iautoprocessingqueue.md)&lt;[IBatchable](/runtime/interface/observation/ibatchable.md)&gt; |

&nbsp;&nbsp; **&#10148; mount**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public, readonly | ✘ | [IProcessingQueue](/runtime/interface/lifecycle/iprocessingqueue.md)&lt;[IController](/runtime/interface/lifecycle/icontroller.md)&lt;INode, IViewModel&lt;INode&gt;&gt;&gt; |

&nbsp;&nbsp; **&#10148; unmount**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public, readonly | ✘ | [IProcessingQueue](/runtime/interface/lifecycle/iprocessingqueue.md)&lt;[IController](/runtime/interface/lifecycle/icontroller.md)&lt;INode, IViewModel&lt;INode&gt;&gt;&gt; |

&nbsp;&nbsp; **&#10148; afterBind**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public, readonly | ✘ | [IAutoProcessingQueue](/runtime/interface/lifecycle/iautoprocessingqueue.md)&lt;[IController](/runtime/interface/lifecycle/icontroller.md)&lt;INode, IViewModel&lt;INode&gt;&gt;&gt; |

&nbsp;&nbsp; **&#10148; afterUnbind**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public, readonly | ✘ | [IAutoProcessingQueue](/runtime/interface/lifecycle/iautoprocessingqueue.md)&lt;[IController](/runtime/interface/lifecycle/icontroller.md)&lt;INode, IViewModel&lt;INode&gt;&gt;&gt; |

&nbsp;&nbsp; **&#10148; afterAttach**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public, readonly | ✘ | [IAutoProcessingQueue](/runtime/interface/lifecycle/iautoprocessingqueue.md)&lt;[IController](/runtime/interface/lifecycle/icontroller.md)&lt;INode, IViewModel&lt;INode&gt;&gt;&gt; |

&nbsp;&nbsp; **&#10148; afterDetach**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public, readonly | ✘ | [IAutoProcessingQueue](/runtime/interface/lifecycle/iautoprocessingqueue.md)&lt;[IController](/runtime/interface/lifecycle/icontroller.md)&lt;INode, IViewModel&lt;INode&gt;&gt;&gt; |

# &#10025; Method(s)

&nbsp;&nbsp; **&#10148; register**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, static | ✘ | [IResolver](/kernel/interface/di/iresolver.md)&lt;[ILifecycle](/runtime/interface/lifecycle/ilifecycle.md)&gt; |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; container**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | [IContainer](/kernel/interface/di/icontainer.md) | ✘  | ✘ | ✘ |