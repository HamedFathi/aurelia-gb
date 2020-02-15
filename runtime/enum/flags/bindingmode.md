# &#10025; Summary

* Note: the oneTime binding now has a non-zero value for 2 reasons:
plays nicer with bitwise operations (more consistent code, more explicit settings)
allows for potentially having something like BindingMode.oneTime | BindingMode.fromView, where an initial value is set once to the view but updates from the view also propagate back to the view model
*
* Furthermore, the "default" mode would be for simple ".bind" expressions to make it explicit for our logic that the default is being used.
* This essentially adds extra information which binding could use to do smarter things and allows bindingBehaviors that add a mode instead of simply overwriting it

| Const                        |
|------------------------------|
| ✘ |

# &#10025; Member(s)

| Name                                      | Value         |
|-------------------------------------------|---------------|
| oneTime | 1 |
| toView | 2 |
| fromView | 4 |
| twoWay | 6 |
| default | 8 |